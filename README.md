# Marqo (marqo)

Marqo is an open-source, multimodal vector search engine that lets developers index text and images, generate embeddings on the fly, and run tensor, lexical, and hybrid search through a single REST API. Built on Vespa for storage and retrieval and FastAPI for the HTTP surface, Marqo bundles model inference (Sentence Transformers, OpenCLIP, ONNX) inside the engine so a single `docker run` produces a working semantic search stack. The Apache 2.0 open-source engine has been marked deprecated by the maintainers as Marqo pivots to a hosted ecommerce search product, but the project remains widely forked, downloaded, and self-hosted, with active sibling repositories for the Python client, Terraform provider, InstantSearch client, ecommerce embedding models, and Generalised Contrastive Learning research.

**APIs.yml:** [apis.yml](apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=marqo-api-evangelist&utm_content=repo)

## Type

- **x-type:** opensource
- **License:** Apache 2.0
- **Core Repo:** [github.com/marqo-ai/marqo](https://github.com/marqo-ai/marqo) (5,000+ stars, marked deprecated, still public and Apache 2.0)

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

**Human URL:** [https://docs.marqo.ai/](https://docs.marqo.ai/)

**Base URL:** `http://localhost:8882` (open source) / `https://api.marqo.ai` (cloud)

#### Properties

- [Documentation](https://docs.marqo.ai/)
- [OpenAPI](openapi/marqo-openapi.yml)
- [API Reference](https://docs.marqo.ai/latest/)
- [Getting Started](https://github.com/marqo-ai/marqo#getting-started)
- [Source Code](https://github.com/marqo-ai/marqo)
- [Deprecation Notice](https://github.com/marqo-ai/marqo)

## Common Properties

- [Website](https://www.marqo.ai/)
- [GitHub Organization](https://github.com/marqo-ai)
- [GitHub Repository](https://github.com/marqo-ai/marqo)
- [LinkedIn](https://www.linkedin.com/company/marqo-ai)
- [Documentation](https://docs.marqo.ai/)
- [License (Apache 2.0)](https://github.com/marqo-ai/marqo/blob/mainline/LICENSE)
- [Blog](https://www.marqo.ai/blog/)
- [Pricing (hosted product)](https://www.marqo.ai/pricing)
- [Plans](plans/marqo-plans-pricing.yml)
- [Rate Limits](rate-limits/marqo-rate-limits.yml)
- [FinOps](finops/marqo-finops.yml)

## SDKs, Tools, and Models

- **py-marqo** — Official Python client. [github.com/marqo-ai/py-marqo](https://github.com/marqo-ai/py-marqo)
- **marqo-instantsearch-client** — TypeScript client compatible with InstantSearch.js. [github.com/marqo-ai/marqo-instantsearch-client](https://github.com/marqo-ai/marqo-instantsearch-client)
- **terraform-provider-marqo** — Terraform provider for Marqo Cloud indexes. [github.com/marqo-ai/terraform-provider-marqo](https://github.com/marqo-ai/terraform-provider-marqo)
- **marqo-base** — Dockerfile and dependencies for the Marqo base image. [github.com/marqo-ai/marqo-base](https://github.com/marqo-ai/marqo-base)
- **ingrain_server** — Wrapper for serving Sentence Transformer and OpenCLIP models via Triton. [github.com/marqo-ai/ingrain_server](https://github.com/marqo-ai/ingrain_server)
- **marqo-ecommerce-embeddings** — Open-weight ecommerce embedding models. [github.com/marqo-ai/marqo-ecommerce-embeddings](https://github.com/marqo-ai/marqo-ecommerce-embeddings)
- **marqo-FashionCLIP** — Open-weight CLIP / SigLIP models finetuned for the fashion domain. [github.com/marqo-ai/marqo-FashionCLIP](https://github.com/marqo-ai/marqo-FashionCLIP)
- **GCL** — Generalised Contrastive Learning research framework + Google Shopping benchmark. [github.com/marqo-ai/GCL](https://github.com/marqo-ai/GCL)
- **local-image-search-demo** — Reference ecommerce image search demo. [github.com/marqo-ai/local-image-search-demo](https://github.com/marqo-ai/local-image-search-demo)
- **fine-tuning-embedding-models-course** — Notebook-based course on embedding model fine-tuning. [github.com/marqo-ai/fine-tuning-embedding-models-course](https://github.com/marqo-ai/fine-tuning-embedding-models-course)

## Notes

- The `marqo-ai/marqo` repository carries a deprecation notice ("Marqo's Open Source project is deprecated and will no longer receive updates") but remains public, Apache 2.0, and at 5,000+ stars / 232 forks. The most recent tag is 2.26.0 (April 2026).
- The runtime engine is FastAPI; the live OpenAPI schema is always available at `GET /openapi.json` with Swagger UI at `GET /docs` on the running container.
- Marqo Cloud (`https://api.marqo.ai`) preserves API parity with the open-source engine and adds bearer-token authentication.
- Sibling repos — py-marqo, marqo-instantsearch-client, terraform-provider-marqo, marqo-base, ingrain_server, GCL, marqo-FashionCLIP, marqo-ecommerce-embeddings — remained active through 2025-2026.

## Reference Providers

- [Anthropic](https://www.anthropic.com/) — Claude is the LLM commonly paired with Marqo retrieval for RAG.

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
