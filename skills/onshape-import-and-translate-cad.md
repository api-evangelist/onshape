---
name: Import and translate a CAD file into Onshape
description: Upload a foreign CAD file into an Onshape document and poll the async translation to completion.
api: openapi/onshape-openapi-original.json
operations: [createDocument, createTranslation, getTranslation]
---

# Import and translate a CAD file into Onshape

Use this skill to bring an external CAD file (STEP, IGES, SolidWorks, etc.) into Onshape as parts/assemblies.

## Auth
Authenticate with OAuth 2.0 (`OAuth2Read` + `OAuth2Write` scopes) or with API-key HMAC-signed Basic auth. See `authentication/onshape-authentication.yml`.

## Steps
1. **Create (or pick) a target document** — `createDocument` (`POST /documents`). Capture the returned `did` (document id) and its default `wid` (workspace id).
2. **Start the translation** — `createTranslation` (`POST /translations/d/{did}/w/{wid}`). Supply the source file and target format. This returns a translation id (`tid`); translation is asynchronous.
3. **Poll for completion** — `getTranslation` (`GET /translations/{tid}`) until the status reports completed or failed. Prefer subscribing to the `onshape.model.translation.complete` webhook over tight polling (see `asyncapi/onshape-events-webhooks.yml`).

## Rules
- Translation is async — never assume the result is ready on the create call.
- No idempotency key exists; re-issuing `createTranslation` starts a new job (see `conventions/onshape-conventions.yml`).
- Handle `429` (per-endpoint rate limit) and `402` (annual quota exhausted); every 2xx/3xx call counts against the annual limit.
