---
name: Create a release package and revision in Onshape
description: Drive an item through the Onshape release workflow to produce a revision.
api: openapi/onshape-openapi-original.json
operations: [createReleasePackage, getReleasePackage, updateReleasePackage, enumerateRevisions]
---

# Create a release package (revision) in Onshape

Use this skill to submit parts/assemblies/drawings through a release workflow and track the resulting revision.

## Auth
OAuth 2.0 (`OAuth2Read` + `OAuth2Write`) or API-key Basic auth. Release management may require appropriate company/enterprise permissions. See `authentication/onshape-authentication.yml`.

## Steps
1. **Create the release candidate** — `createReleasePackage` (`POST /releasepackages/release/{wfid}`) referencing the workflow id and the items to release. Capture the release package id (`rpid`).
2. **Inspect / advance it** — `getReleasePackage` (`GET /releasepackages/{rpid}`) to read state; `updateReleasePackage` (`POST /releasepackages/{rpid}`) to set properties and advance the workflow.
3. **Confirm the revision** — `enumerateRevisions` (`GET`) to find the released revision. Subscribe to `onshape.workflow.transition` and `onshape.revision.created` webhooks to observe state changes (see `asyncapi/onshape-events-webhooks.yml`).

## Rules
- Release workflows are stateful; drive transitions in order rather than assuming instant approval.
- Handle `403` (insufficient release permission), `429`, and `402` per `errors/onshape-problem-types.yml`.
