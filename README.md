# Onshape

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Onshape is a cloud-native computer-aided design (CAD) and product data management (PDM) platform, part of PTC, that runs entirely in a web browser with real-time collaboration, versioning, and configurations. Its public REST API (OpenAPI 3.0.1, base https://cad.onshape.com/api/v16) exposes documents, workspaces, versions and microversions, Part Studios, parts, assemblies, drawings, metadata, translations (CAD import/export), release management, and webhooks. Authentication is via OAuth 2.0 or HMAC-signed API keys, with offset/limit pagination and per-endpoint plus annual API call limits. Onshape was surfaced as an a16z portfolio company and enriched with its real developer surface by the API Evangelist pipeline.

**Areas:** Company · CAD · PLM · Product Data Management · Engineering · Manufacturing · Design · Cloud · Developer Tools

## Onshape on APIs.io

Everything profiled for Onshape is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/onshape/](https://apis.io/providers/onshape/)** — or go straight to one of the APIs or properties below.

### APIs (42)

- [Onshape Account API](https://apis.io/apis/onshape/onshape-account-api/) — Manage user purchases, subscriptions, and consumables.
- [Onshape Alias API](https://apis.io/apis/onshape/onshape-alias-api/) — Create and manage enterprise aliases. (Enterprise admins only.)
- [Onshape AppAssociativeData API](https://apis.io/apis/onshape/onshape-appassociativedata-api/) — Manage the application-specific metadata that associates application data with Onshape data.
- [Onshape AppElement API](https://apis.io/apis/onshape/onshape-appelement-api/) — Access and modify application elements.
- [Onshape Assembly API](https://apis.io/apis/onshape/onshape-assembly-api/) — Create and manage assemblies.
- [Onshape Billing API](https://apis.io/apis/onshape/onshape-billing-api/) — Get billing plan data for applications.
- [Onshape BlobElement API](https://apis.io/apis/onshape/onshape-blobelement-api/) — Create, modify, and translate blob elements.
- [Onshape Comment API](https://apis.io/apis/onshape/onshape-comment-api/) — Create, read, update, and delete comments.
- [Onshape Company API](https://apis.io/apis/onshape/onshape-company-api/) — Access company information.
- [Onshape Document API](https://apis.io/apis/onshape/onshape-document-api/) — Create and manage documents.
- [Onshape Drawing API](https://apis.io/apis/onshape/onshape-drawing-api/) — Access, create, and translate drawings.
- [Onshape Element API](https://apis.io/apis/onshape/onshape-element-api/) — Access and manage Elements. Every Element in an Onshape document is represented by a tab.
- [Onshape ExportRule API](https://apis.io/apis/onshape/onshape-exportrule-api/) — Access valid export rules.
- [Onshape FeatureStudio API](https://apis.io/apis/onshape/onshape-featurestudio-api/) — Access and manage Feature Studio Elements.
- [Onshape Folder API](https://apis.io/apis/onshape/onshape-folder-api/) — Access and modify folder sharing permissions.
- [Onshape Insertable API](https://apis.io/apis/onshape/onshape-insertable-api/) — Access the list of things that can be inserted into a document.
- [Onshape Item API](https://apis.io/apis/onshape/onshape-item-api/) — Manage non-geometric [items](https://cad.onshape.com/help/Content/Plans/items.htm). (Professional, Educator, and Enterprise accounts only.)
- [Onshape Material API](https://apis.io/apis/onshape/onshape-material-api/) — Work with the Onshape Material Library.
- [Onshape Metadata API](https://apis.io/apis/onshape/onshape-metadata-api/) — Access and modify metadata.
- [Onshape MetadataCategory API](https://apis.io/apis/onshape/onshape-metadatacategory-api/) — Access properties associated with metadata categories.
- [Onshape NumberingScheme API](https://apis.io/apis/onshape/onshape-numberingscheme-api/) — Manage the set of valid part numbers.
- [Onshape Part API](https://apis.io/apis/onshape/onshape-part-api/) — Export Parts and access Part details.
- [Onshape PartNumber API](https://apis.io/apis/onshape/onshape-partnumber-api/) — Create valid part numbers.
- [Onshape PartStudio API](https://apis.io/apis/onshape/onshape-partstudio-api/) — Access and modify Part Studios.
- [Onshape PropertiesTableTemplate API](https://apis.io/apis/onshape/onshape-propertiestabletemplate-api/) — Create, access, and delete templates for properties tables.
- [Onshape Publication API](https://apis.io/apis/onshape/onshape-publication-api/) — Access publication information.
- [Onshape ReleasePackage API](https://apis.io/apis/onshape/onshape-releasepackage-api/) — Endpoints for creating , updating, and managing releases. See [API Guide: Release Management](https://onshape-public.github.io/docs/api-adv/relmgmt/).
- [Onshape Revision API](https://apis.io/apis/onshape/onshape-revision-api/) — Get revision information. See [API Guide: Release Management](https://onshape-public.github.io/docs/api-adv/relmgmt/)
- [Onshape Sketch API](https://apis.io/apis/onshape/onshape-sketch-api/) — Access sketch information.
- [Onshape StandardContent API](https://apis.io/apis/onshape/onshape-standardcontent-api/) — Work with Onshape standard content.
- [Onshape Task API](https://apis.io/apis/onshape/onshape-task-api/) — Create, access, and modify Tasks and Action Items.
- [Onshape Team API](https://apis.io/apis/onshape/onshape-team-api/) — Access team information.
- [Onshape Thumbnail API](https://apis.io/apis/onshape/onshape-thumbnail-api/) — Access, modify, and delete thumbnails.
- [Onshape Translation API](https://apis.io/apis/onshape/onshape-translation-api/) — Import and export Onshape surfaces, parts, Part Studios, Assemblies, and subassemblies to/from other file formats (STL, PARASOLID, etc).
- [Onshape User API](https://apis.io/apis/onshape/onshape-user-api/) — Access user information.
- [Onshape Variables API](https://apis.io/apis/onshape/onshape-variables-api/) — Create, modify, and access variables.
- [Onshape Version API](https://apis.io/apis/onshape/onshape-version-api/) — Get all versions of the Onshape REST APIs.
- [Onshape Webhook API](https://apis.io/apis/onshape/onshape-webhook-api/) — Create and manage [webhooks](https://onshape-public.github.io/docs/app-dev/webhook/).
- [Onshape Workflow API](https://apis.io/apis/onshape/onshape-workflow-api/) — Access and modify workflows.
- [Onshape API Application API](https://apis.io/apis/onshape/onshape-api-application-api/) — Manage application preferences.
- [Onshape Open API](https://apis.io/apis/onshape/onshape-open-api-api/) — Get the OpenAPI specification for the Onshape API.
- [Onshape Product structure API](https://apis.io/apis/onshape/onshape-product-structure-api/) — Access information on how entities are structured within designs and documents.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Onshape Events Webhooks](https://apis.io/asyncapis/onshape/onshape-events-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [onshape](https://apis.io/servers/onshape/onshape/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Onshape Agentic Access](https://apis.io/agentic-access/onshape/onshape-agentic-access/)

#### Collections (42)

Postman and Open Collection request collections.

- [Onshape REST Account API](https://apis.io/collections/onshape/open-onshape-account-api/)
- [Onshape REST Account Alias API](https://apis.io/collections/onshape/open-onshape-alias-api/)
- [Onshape REST Account APIApplication API](https://apis.io/collections/onshape/open-onshape-apiapplication-api/)
- [Onshape REST Account AppAssociativeData API](https://apis.io/collections/onshape/open-onshape-appassociativedata-api/)
- [Onshape REST Account AppElement API](https://apis.io/collections/onshape/open-onshape-appelement-api/)
- [Onshape REST Account Assembly API](https://apis.io/collections/onshape/open-onshape-assembly-api/)
- [Onshape REST Account Billing API](https://apis.io/collections/onshape/open-onshape-billing-api/)
- [Onshape REST Account BlobElement API](https://apis.io/collections/onshape/open-onshape-blobelement-api/)
- [Onshape REST Account Comment API](https://apis.io/collections/onshape/open-onshape-comment-api/)
- [Onshape REST Account Company API](https://apis.io/collections/onshape/open-onshape-company-api/)
- [Onshape REST Account Document API](https://apis.io/collections/onshape/open-onshape-document-api/)
- [Onshape REST Account Drawing API](https://apis.io/collections/onshape/open-onshape-drawing-api/)
- [Onshape REST Account Element API](https://apis.io/collections/onshape/open-onshape-element-api/)
- [Onshape REST Account ExportRule API](https://apis.io/collections/onshape/open-onshape-exportrule-api/)
- [Onshape REST Account FeatureStudio API](https://apis.io/collections/onshape/open-onshape-featurestudio-api/)
- [Onshape REST Account Folder API](https://apis.io/collections/onshape/open-onshape-folder-api/)
- [Onshape REST Account Insertable API](https://apis.io/collections/onshape/open-onshape-insertable-api/)
- [Onshape REST Account Item API](https://apis.io/collections/onshape/open-onshape-item-api/)
- [Onshape REST Account Material API](https://apis.io/collections/onshape/open-onshape-material-api/)
- [Onshape REST Account Metadata API](https://apis.io/collections/onshape/open-onshape-metadata-api/)
- [Onshape REST Account MetadataCategory API](https://apis.io/collections/onshape/open-onshape-metadatacategory-api/)
- [Onshape REST Account NumberingScheme API](https://apis.io/collections/onshape/open-onshape-numberingscheme-api/)
- [Onshape REST Account OpenApi API](https://apis.io/collections/onshape/open-onshape-openapi-api/)
- [Onshape REST Account Part API](https://apis.io/collections/onshape/open-onshape-part-api/)
- [Onshape REST Account PartNumber API](https://apis.io/collections/onshape/open-onshape-partnumber-api/)
- …and 17 more published on APIs.io

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Onshape Openapi Overlay](https://apis.io/overlays/onshape/onshape-openapi-overlay/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Onshape Authentication](https://apis.io/security/onshape/onshape-authentication/)
- [Onshape Domain Security](https://apis.io/security/onshape/onshape-domain-security/)
- [Onshape Trust Center](https://apis.io/security/onshape/onshape-trust-center/)
- [Onshape Vulnerability Disclosure](https://apis.io/security/onshape/onshape-vulnerability-disclosure/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Onshape Scopes](https://apis.io/scopes/onshape/onshape-scopes/)

#### Plans and pricing (2)

Published plans, tiers and prices.

- [Onshape Plans Pricing](https://apis.io/plans/onshape/onshape-plans-pricing/)
- [Onshape Price Estimates](https://apis.io/plans/onshape/onshape-price-estimates/)

#### Rate limits (1)

Published request limits.

- [Onshape Rate Limits](https://apis.io/rate-limits/onshape/onshape-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.onshape.com/)
- [Documentation](https://onshape-public.github.io/docs/)
- [Getting started](https://onshape-public.github.io/docs/api-intro/quickstart/)
- [API reference](https://cad.onshape.com/glassworks/explorer/)
- [Pricing](https://www.onshape.com/en/pricing)
- [Sign up](https://cad.onshape.com/signup)
- [Support](https://onshape-public.github.io/docs/help/)
- [Blog](https://www.onshape.com/en/blog)
- [Security](https://www.onshape.com/en/security)
- [Compliance](https://www.onshape.com/en/security)
- [Terms of service](https://www.onshape.com/en/legal/terms-of-use)
- [GitHub](https://github.com/onshape-public)
- [Status](https://status.onshape.com/)

## API Evangelist rating

**Kin Score 59.8** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 55.5 |
| Contract governance | 4.5 |
| Operational transparency | 52.6 |
| Developer ergonomics | 66.1 |
| Access clarity | 68.4 |

**Agent readiness 35.1** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | negotiable (partial credit) |
| Idempotency | — |
| Error Semantics | derived (partial credit) |
| OpenAPI Examples | partial |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | yes |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | documented (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 41.2** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/onshape/](https://apis.io/providers/onshape/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Onshape: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/onshape/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
