# Lytics

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

Lytics is a customer data platform (CDP) that provides two concurrent REST APIs for managing unified user profiles, behavioral audiences, content affinity scoring, campaign flows, and real-time personalization. The v2 API (886 paths / 1,331 operations) covers accounts, authorizations, connections, schema and identity configuration, data models, streams, jobs and ML models; the v1 API still owns data collection, personalization, entity lookup and content classification. Lytics ingests data from 100+ sources, builds predictive audiences, and activates them across advertising networks, email providers, data warehouses and on-site personalization. Lytics joined Contentstack in January 2025.

**Areas:** Customer Data Platform · CDP · Personalization · Segmentation · User Profiles · Behavioral Analytics · Content Affinity · Real-Time Data · Marketing Automation · Audience Activation

## Lytics on APIs.io

Everything profiled for Lytics is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/lytics/](https://apis.io/providers/lytics/)** — or go straight to one of the APIs or properties below.

### APIs (34)

- [Lytics Account API](https://apis.io/apis/lytics/lytics-account-api/) — Account related resources of the *Lytics API*. The Account resource describes an account. An account can be a *Master* account, which means that it is a…
- [Lytics Account Settings API](https://apis.io/apis/lytics/lytics-account-settings-api/) — Account Settings describe features/settings for a Lytics account.
- [Lytics Auth API](https://apis.io/apis/lytics/lytics-auth-api/) — API for creation or storage of auth tokens. Most of these tokens are created from the Integrations/Imports setup for Lytics integrations. Additionally, api…
- [Lytics Auths API](https://apis.io/apis/lytics/lytics-auths-api/) — Create and manage credentials and access to external systems.
- [Lytics Catalog API](https://apis.io/apis/lytics/lytics-catalog-api/) — Catalog exposes info about the schema of the data in Lytics. * **Entities** are Object Types, the primary one being a *User* although most accounts also…
- [Lytics Connections API](https://apis.io/apis/lytics/lytics-connections-api/) — Create and manage connections to external data sources.
- [Lytics Content API](https://apis.io/apis/lytics/lytics-content-api/) — Content APIs for Lytics Content Affinity Engine, allow for adding content into lytics, getting lists of content, and understanding the content and…
- [Lytics Experience API](https://apis.io/apis/lytics/lytics-experience-api/) — API for creating and managing Experiences as well as all related and/or dependent models such as but not limited to Groups, Templates, Candidates, etc.
- [Lytics Flows API](https://apis.io/apis/lytics/lytics-flows-api/) — Create and manage flows that orchestrate multi-step audience journeys.
- [Lytics Jobs API](https://apis.io/apis/lytics/lytics-jobs-api/) — Create and manage data import and export jobs.
- [Lytics Metric API](https://apis.io/apis/lytics/lytics-metric-api/) — The Metric API provides access to a variety of metrics that are recorded in the Lytics platform. With this API, you can access segment-size metrics, events…
- [Lytics Metrics API](https://apis.io/apis/lytics/lytics-metrics-api/) — Query time series metrics for segments, streams, experiences, and other Lytics resources.
- [Lytics ML Models API](https://apis.io/apis/lytics/lytics-ml-models-api/) — The ML Models API from Lytics — 3 operation(s) for ml models.
- [Lytics Personalization API](https://apis.io/apis/lytics/lytics-personalization-api/) — Entity API, ie Personalization or Profile API. Retrieve attributes and segments an entity (most likely a user) is a member of. The *Entity* is a *User* most…
- [Lytics Profiles API](https://apis.io/apis/lytics/lytics-profiles-api/) — Get and delete user profiles.
- [Lytics Provider API](https://apis.io/apis/lytics/lytics-provider-api/) — Provider is a 3rd party Lytics Integrates with (Mailchimp, Optimizely, Mixpanel, Facebook etc)
- [Lytics Query API](https://apis.io/apis/lytics/lytics-query-api/) — Schema management api to add/edit queries and user-fields. Lytics Query Language ============================= The Lytics Query Language is used to define…
- [Lytics Reports API](https://apis.io/apis/lytics/lytics-reports-api/) — Create and manage reports.
- [Lytics Schema API](https://apis.io/apis/lytics/lytics-schema-api/) — Manage how data sources populate profile fields.
- [Lytics Segment API](https://apis.io/apis/lytics/lytics-segment-api/) — Segments are named, logical expressions of users. These segments may logically be built using other segments as well. The segment api provides a list of…
- [Lytics Segment Collection API](https://apis.io/apis/lytics/lytics-segmentcollection-api/) — Segment Collections are grouped/named lists of segments. Segments that participate in a collection such as **Goals** are related. The Lytics App ui has one…
- [Lytics Segment ML API](https://apis.io/apis/lytics/lytics-segmentml-api/) — SegmentML provides a framework for building custom machine learning models directly in Lytics. Lytics SegmentML models are self-training,…
- [Lytics Segments API](https://apis.io/apis/lytics/lytics-segments-api/) — Create and manage audience segments.
- [Lytics Stream API](https://apis.io/apis/lytics/lytics-stream-api/) — API for creating stream models. A stream is the same as a [data…
- [Lytics Streams API](https://apis.io/apis/lytics/lytics-streams-api/) — Get metrics and events for data streams in your Lytics account.
- [Lytics Subscription API](https://apis.io/apis/lytics/lytics-subscription-api/) — **BETA API** Subscriptions are queries into real-time events in Lytics, most commonly listening to a list of users entering/leaving segments ie _triggers_.…
- [Lytics System API](https://apis.io/apis/lytics/lytics-system-api/) — Manage Lytics system users and their access to data and resources.
- [Lytics System Events API](https://apis.io/apis/lytics/lytics-system-events-api/) — Get internal Lytics system events. These events are generally related to internal changes to state of an account. Common changes are CRUD Operations…
- [Lytics Templates API](https://apis.io/apis/lytics/lytics-templates-api/) — Create, manage, and test templates.
- [Lytics User API](https://apis.io/apis/lytics/lytics-user-api/) — Info about Administrative Lytics account users * Lytics users are unique across accounts * They get *invited* to have access to your account
- [Lytics Work API](https://apis.io/apis/lytics/lytics-work-api/) — Work is an *integration* unit, typically for imports and exports. Most run continually, while some run to completion. You generally would only use it…
- [Lytics Workflow API](https://apis.io/apis/lytics/lytics-workflow-api/) — Workflow is a specification for a work unit
- [Lytics Data models API](https://apis.io/apis/lytics/lytics-data-models-api/) — Create and manage data models and their record stores.
- [Lytics Data Upload API](https://apis.io/apis/lytics/lytics-data-upload-api/) — APIs for collecting or uploading data.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Lytics Webhooks](https://apis.io/asyncapis/lytics/lytics-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [lytics](https://apis.io/servers/lytics/lytics/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Lytics Agentic Access](https://apis.io/agentic-access/lytics/lytics-agentic-access/)

#### JSON Schema (3)

The data models the API reads and writes.

- [Lytics Collect Event](https://apis.io/schemas/lytics/lytics-collect-event/)
- [Lytics Segment](https://apis.io/schemas/lytics/lytics-segment/)
- [Lytics User Profile](https://apis.io/schemas/lytics/lytics-user-profile/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Lytics Context](https://apis.io/jsonld/lytics/lytics-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Lytics API Vocabulary](https://apis.io/vocabularies/lytics/lytics-vocabulary/)

#### Examples (4)

Example requests and responses.

- [Lytics Collect Event Example](https://apis.io/examples/lytics/lytics-collect-event-example/)
- [Lytics Segment Scan Request Example](https://apis.io/examples/lytics/lytics-segment-scan-request-example/)
- [Lytics Segment Scan Response Example](https://apis.io/examples/lytics/lytics-segment-scan-response-example/)
- [Lytics User Profile Example](https://apis.io/examples/lytics/lytics-user-profile-example/)

#### Collections (2)

Postman and Open Collection request collections.

- [V1 Lytics API](https://apis.io/collections/lytics/open-lytics-api-v1/)
- [Lytics API](https://apis.io/collections/lytics/open-lytics-api-v2/)

#### Overlays (36)

OpenAPI overlays, including conversational phrasing for each operation.

- [Lytics Account Api Phrasing Overlay](https://apis.io/overlays/lytics/lytics-account-api-phrasing-overlay/)
- [Lytics Account Settings Api Phrasing Overlay](https://apis.io/overlays/lytics/lytics-account-settings-api-phrasing-overlay/)
- [Lytics Api V1 Overlay](https://apis.io/overlays/lytics/lytics-api-v1-overlay/)
- [Lytics Api V2 Overlay](https://apis.io/overlays/lytics/lytics-api-v2-overlay/)
- [Lytics Auth Api Phrasing Overlay](https://apis.io/overlays/lytics/lytics-auth-api-phrasing-overlay/)
- [Lytics Auths Api Phrasing Overlay](https://apis.io/overlays/lytics/lytics-auths-api-phrasing-overlay/)
- [Lytics Catalog Api Phrasing Overlay](https://apis.io/overlays/lytics/lytics-catalog-api-phrasing-overlay/)
- [Lytics Connections Api Phrasing Overlay](https://apis.io/overlays/lytics/lytics-connections-api-phrasing-overlay/)
- [Lytics Content Api Phrasing Overlay](https://apis.io/overlays/lytics/lytics-content-api-phrasing-overlay/)
- [Lytics Data Models Api Phrasing Overlay](https://apis.io/overlays/lytics/lytics-data-models-api-phrasing-overlay/)
- [Lytics Data Upload Api Phrasing Overlay](https://apis.io/overlays/lytics/lytics-data-upload-api-phrasing-overlay/)
- [Lytics Experience Api Phrasing Overlay](https://apis.io/overlays/lytics/lytics-experience-api-phrasing-overlay/)
- [Lytics Flows Api Phrasing Overlay](https://apis.io/overlays/lytics/lytics-flows-api-phrasing-overlay/)
- [Lytics Jobs Api Phrasing Overlay](https://apis.io/overlays/lytics/lytics-jobs-api-phrasing-overlay/)
- [Lytics Metric Api Phrasing Overlay](https://apis.io/overlays/lytics/lytics-metric-api-phrasing-overlay/)
- [Lytics Metrics Api Phrasing Overlay](https://apis.io/overlays/lytics/lytics-metrics-api-phrasing-overlay/)
- [Lytics Ml Models Api Phrasing Overlay](https://apis.io/overlays/lytics/lytics-ml-models-api-phrasing-overlay/)
- [Lytics Personalization Api Phrasing Overlay](https://apis.io/overlays/lytics/lytics-personalization-api-phrasing-overlay/)
- [Lytics Profiles Api Phrasing Overlay](https://apis.io/overlays/lytics/lytics-profiles-api-phrasing-overlay/)
- [Lytics Provider Api Phrasing Overlay](https://apis.io/overlays/lytics/lytics-provider-api-phrasing-overlay/)
- [Lytics Query Api Phrasing Overlay](https://apis.io/overlays/lytics/lytics-query-api-phrasing-overlay/)
- [Lytics Reports Api Phrasing Overlay](https://apis.io/overlays/lytics/lytics-reports-api-phrasing-overlay/)
- [Lytics Schema Api Phrasing Overlay](https://apis.io/overlays/lytics/lytics-schema-api-phrasing-overlay/)
- [Lytics Segment Api Phrasing Overlay](https://apis.io/overlays/lytics/lytics-segment-api-phrasing-overlay/)
- [Lytics Segmentcollection Api Phrasing Overlay](https://apis.io/overlays/lytics/lytics-segmentcollection-api-phrasing-overlay/)
- …and 11 more published on APIs.io

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Lytics — jsonschema rules](https://apis.io/rules/lytics/lytics-jsonschema-spectral-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Lytics Authentication](https://apis.io/security/lytics/lytics-authentication/)
- [Lytics Domain Security](https://apis.io/security/lytics/lytics-domain-security/)
- [Lytics Trust Center](https://apis.io/security/lytics/lytics-trust-center/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Lytics Plans Pricing](https://apis.io/plans/lytics/lytics-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Lytics Rate Limits](https://apis.io/rate-limits/lytics/lytics-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Lytics Finops](https://apis.io/finops/lytics/lytics-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.lytics.com/)
- [Documentation](https://docs.lytics.com/)
- [Getting started](https://docs.lytics.com/reference/getting-started)
- [API reference](https://docs.lytics.com/reference)
- [Pricing](https://www.lytics.com/pricing/)
- [Sign up](https://app.lytics.com/register)
- [Support](https://support.lytics.com/hc/en-us)
- [Changelog](https://docs.lytics.com/changelog)
- [Blog](https://www.lytics.com/blog/)
- [Compliance](https://docs.lytics.com/docs/compliance)
- [Terms of service](https://www.lytics.com/terms-of-service/)
- [Privacy policy](https://www.lytics.com/privacy-policy/)
- [GitHub](https://github.com/lytics)
- [Status](https://lytics.statuspage.io/)

## API Evangelist rating

**Kin Score 65.8** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 65.4 |
| Contract governance | 28.0 |
| Operational transparency | 34.2 |
| Developer ergonomics | 67.9 |
| Access clarity | 81.6 |

**Agent readiness 40.1** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | yes |
| Agent Skills | yes |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | yes |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | mostly |

**Regulatory alignment 27.0** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/lytics/](https://apis.io/providers/lytics/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Lytics: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/lytics/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
