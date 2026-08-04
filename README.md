# Marqo (marqo)

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

Marqo is an open-source, multimodal vector search engine that lets developers index text and images, generate embeddings on the fly, and run tensor, lexical, and hybrid search through a single REST API. Built on Vespa for storage and retrieval and FastAPI for the HTTP surface, Marqo bundles model inference (Sentence Transformers, OpenCLIP, ONNX) inside the engine so a single `docker run` produces a working semantic search stack. The Apache 2.0 open-source engine has been marked deprecated by the maintainers as Marqo pivots to a hosted ecommerce search product, but the project remains widely forked, downloaded, and self-hosted, with active sibling repositories for the Python client, Terraform provider, InstantSearch client, ecommerce embedding models, and Generalised Contrastive Learning research.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/marqo/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/marqo/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Vector Database
- Vector Search
- Multimodal
- Semantic Search
- Embeddings
- AI
- Machine Learning
- Open Source
- Ecommerce Search

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-25

## APIs

### Marqo REST API

The Marqo REST API is the HTTP surface exposed by the open-source engine (default `http://localhost:8882`). It provides index lifecycle management, document add/update/get/delete, lexical/tensor/hybrid search, recommendations, embedding generation, model lifecycle, telemetry, and health endpoints. The same surface is served by Marqo Cloud at `https://api.marqo.ai`, and the live OpenAPI schema is published by the running engine at `/openapi.json` with Swagger UI at `/docs`.

- **Human URL:** [https://docs.marqo.ai/](https://docs.marqo.ai/)
- **Base URL:** `http://localhost:8882`

#### Tags

- REST
- Indexes
- Documents
- Search
- Embeddings
- Models
- Multimodal

#### Properties

- [Documentation](https://docs.marqo.ai/)
- [OpenAPI](openapi/marqo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/marqo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/marqo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [API Reference](https://docs.marqo.ai/latest/)
- [Getting Started](https://github.com/marqo-ai/marqo#getting-started)
- [Source Code](https://github.com/marqo-ai/marqo)
- [Deprecation](https://github.com/marqo-ai/marqo)

## Common Properties

- [Website](https://www.marqo.ai/)
- [GitHub Organization](https://github.com/marqo-ai)
- [GitHub Repository](https://github.com/marqo-ai/marqo)
- [LinkedIn](https://www.linkedin.com/company/marqo-ai)
- [Documentation](https://docs.marqo.ai/)
- [Getting Started](https://github.com/marqo-ai/marqo#getting-started)
- [License](https://github.com/marqo-ai/marqo/blob/mainline/LICENSE)
- [Blog](https://www.marqo.ai/blog/)
- [Pricing](https://www.marqo.ai/pricing)
- [Plans](plans/marqo-plans-pricing.yml)
- [Rate Limits](rate-limits/marqo-rate-limits.yml)
- [Fin Ops](finops/marqo-finops.yml)
- [SDK](https://github.com/marqo-ai/py-marqo)
- [SDK](https://github.com/marqo-ai/marqo-instantsearch-client)
- [Tools](https://github.com/marqo-ai/terraform-provider-marqo)
- [Tools](https://github.com/marqo-ai/marqo-base)
- [Tools](https://github.com/marqo-ai/ingrain_server)
- [Models](https://github.com/marqo-ai/marqo-ecommerce-embeddings)
- [Models](https://github.com/marqo-ai/marqo-FashionCLIP)
- [Research](https://github.com/marqo-ai/GCL)
- [Examples](https://github.com/marqo-ai/local-image-search-demo)
- [Course](https://github.com/marqo-ai/fine-tuning-embedding-models-course)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
