---
name: Subscribe to Onshape model change webhooks
description: Register, verify, and manage a webhook so an agent is notified of Onshape document/model events.
api: openapi/onshape-openapi-original.json
operations: [createWebhook, getWebhooks, getWebhook, pingWebhook, unregisterWebhook]
---

# Subscribe to Onshape model change webhooks

Use this skill to receive event notifications (model changes, translations complete, workflow transitions) instead of polling.

## Auth
OAuth 2.0 with the `webhook.create`/`webhook.read`/`webhook.delete` scopes (or API-key Basic auth). See `authentication/onshape-authentication.yml`.

## Steps
1. **Register the webhook** — `createWebhook` (`POST /webhooks`) with your HTTPS callback `url`, the `events` you want (e.g. `onshape.model.lifecycle.changed`, `onshape.model.translation.complete`), and the document/company scope. Capture the returned webhook id. Onshape sends a trial `webhook.register` notification to confirm reachability.
2. **Confirm it is live** — `getWebhooks` (`GET /webhooks`) / `getWebhook` (`GET /webhooks/{webhookid}`) to verify registration; `pingWebhook` (`POST /webhooks/{webhookid}/ping`) to test delivery.
3. **Clean up** — `unregisterWebhook` (`DELETE /webhooks/{webhookid}`) when done. Set `isTransient=false` to keep long-lived webhooks from being auto-cleaned.

## Rules
- Callback URLs must present CA-signed TLS certificates; self-signed certs are rejected.
- Registration is NOT deduplicated — each `createWebhook` call yields a new id; list before re-registering.
- Event catalog and payload shape are in `asyncapi/onshape-events-webhooks.yml`.
