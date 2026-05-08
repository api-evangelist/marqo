# Marqo (marqo)

Marqo is an AI-native ecommerce search and discovery platform with managed cloud. Note: the original Apache 2.0 open-source vector engine (github.com/marqo-ai/marqo) is now marked deprecated and no longer receives updates; Marqo's current product is the Marqo Cloud SaaS focused on ecommerce search.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/marqo/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=marqo-api-evangelist&utm_content=repo)

## Type
- **x-type:** company

## APIs
- **Marqo Cloud API** - REST. Indexes, document add/update, lexical and tensor/vector search, merchandising controls.
- **Marqo Open Source (Deprecated)** - Default port 8882. Same REST surface; project is no longer maintained.

## Tags
- Vector Database, Ecommerce Search, AI, Embeddings, Recommendations

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Common Properties
- [Website](https://www.marqo.ai/)
- [Marqo Cloud](https://cloud.marqo.ai/)
- [Documentation](https://docs.marqo.ai/)
- [Source (Apache 2.0, deprecated)](https://github.com/marqo-ai/marqo)
- [Plans](plans/marqo-plans-pricing.yml)
- [RateLimits](rate-limits/marqo-rate-limits.yml)
- [FinOps](finops/marqo-finops.yml)

## Notes
- Pricing partial — Marqo Cloud uses tiered storage shards (Marqo Balanced ~16M vectors per shard / Marqo Performance) and inference pods (CPU Large / GPU). Specific hourly rates not published on a flat pricing page; billing starts when first index is created.
- Major change: the open-source GitHub project is now marked **deprecated** as Marqo pivots to managed ecommerce search.
- API parity between cloud and open source is preserved for legacy users.

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
