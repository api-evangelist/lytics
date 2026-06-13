# Lytics

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
