# GraphQL Hive

GraphQL Hive is an open-source GraphQL schema registry and observability platform developed by The Guild. It provides a public GraphQL API for schema publishing, validation, usage tracking, breaking change detection, and analytics for GraphQL federation and other GraphQL APIs. Available as a managed cloud service at graphql-hive.com or as a self-hosted deployment.

**Website:** https://the-guild.dev/graphql/hive  
**Documentation:** https://the-guild.dev/graphql/hive/docs  
**GitHub Org:** https://github.com/graphql-hive  
**Status Page:** https://status.graphql-hive.com/  
**Pricing:** https://the-guild.dev/graphql/hive/pricing  

## APIs

- **Console GraphQL API** — `https://api.graphql-hive.com/graphql` — Manage schemas, access tokens, usage metrics, and analytics programmatically. Authenticates via Bearer tokens (hvo1/ prefix).

## Repository Contents

- `apis.yml` — APIs.json 0.19 provider index
- `plans/graphql-hive-plans-pricing.yml` — Hobby (free), Pro ($20/month + $10/M ops), Enterprise (custom)
- `rate-limits/graphql-hive-rate-limits.yml` — Complexity-based GraphQL API rate limits, operations quotas per plan
- `finops/graphql-hive-finops.yml` — FinOps guidance, cost drivers, optimization strategies

## Maintained by

Kin Lane — kin@apievangelist.com
