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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Lytics is a customer data platform (CDP) that provides a REST API for managing unified user profiles, behavioral segments, content affinity scoring, campaigns, and real-time personalization integrations. The platform enables marketers to ingest data from 100+ sources, build predictive audiences, and activate them across advertising networks, email providers, data warehouses, and on-site personalization tools.

**Website:** https://www.lytics.com/  
**API Documentation:** https://docs.lytics.com/reference  
**GitHub:** https://github.com/lytics  
**Status:** https://lytics.statuspage.io/  
**Blog:** https://www.lytics.com/blog/  
**Pricing:** https://www.lytics.com/pricing/  

## APIs

- **Lytics REST API** — User profile management, behavioral segment queries, content affinity scores, audience activation, data stream ingestion, Cloud Connect warehouse integrations, and job orchestration. Base URL: `https://api.lytics.io`

## Authentication

API tokens are created in the Lytics admin portal under **Account > Security > Authorizations**. Tokens carry role-based scopes. Pass the token as an HTTP `Authorization` header or as an `access_token` query parameter.

## Plans

| Plan | Monthly Credits | Price |
|------|----------------|-------|
| Developer | 2M | Free |
| Growth | 5M | $500/mo |
| Enterprise | 10M+ (custom) | Custom |

See [plans/lytics-plans-pricing.yml](plans/lytics-plans-pricing.yml) for full details.

## Rate Limits

Key platform limits (all tiers unless noted):

- Max event record size: 4 KB
- Max batch record size: 16 KB
- Max batch total: 1 GB
- Max profile size: 1 MB
- Max audiences per account: 500
- Max active imports: 100
- Max active exports: 200
- Max URLs enriched: 20,000/month

Event ingress/egress rates, aggregate sizes, and re-evaluation rates are quota-based and vary by plan. See [rate-limits/lytics-rate-limits.yml](rate-limits/lytics-rate-limits.yml) for full details.

## FinOps

Lytics uses a credit-based consumption model. Inbound data events consume 1 credit each; Cloud Connect warehouse sync rows consume 0.5 credits. See [finops/lytics-finops.yml](finops/lytics-finops.yml) for optimization guidance.

---

Maintained by [Kin Lane](mailto:kin@apievangelist.com) as part of the [APIs.json](https://apisjson.org) catalog.
