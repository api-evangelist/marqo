# Marqo (marqo)

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
