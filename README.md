# Marqo

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

Marqo is an open-source, multimodal vector search engine that lets developers index text and images, generate embeddings on the fly, and run tensor, lexical, and hybrid search through a single REST API. Built on Vespa for storage and retrieval and FastAPI for the HTTP surface, Marqo bundles model inference (Sentence Transformers, OpenCLIP, ONNX) inside the engine so a single `docker run` produces a working semantic search stack. The Apache 2.0 open-source engine has been marked deprecated by the maintainers as Marqo pivots to a hosted ecommerce search product, but the project remains widely forked, downloaded, and self-hosted, with active sibling repositories for the Python client, Terraform provider, InstantSearch client, ecommerce embedding models, and Generalised Contrastive Learning research.

**Areas:** Vector Search · Multi-Modal · Semantic Search · Embeddings · Artificial Intelligence · Machine Learning · Open Source · Ecommerce Search

## Marqo on APIs.io

Everything profiled for Marqo is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/marqo/](https://apis.io/providers/marqo/)** — or go straight to one of the APIs or properties below.

### APIs (7)

- [Marqo Documents API](https://apis.io/apis/marqo/marqo-documents-api/) — Add, update, get, and delete documents in an index.
- [Marqo Embeddings API](https://apis.io/apis/marqo/marqo-embeddings-api/) — Generate embedding vectors using engine-loaded models.
- [Marqo Indexes API](https://apis.io/apis/marqo/marqo-indexes-api/) — Create, list, inspect, and delete tensor / lexical indexes.
- [Marqo Models API](https://apis.io/apis/marqo/marqo-models-api/) — Inspect, load, and eject embedding models from the engine.
- [Marqo Recommendations API](https://apis.io/apis/marqo/marqo-recommendations-api/) — Return documents similar to one or more reference documents.
- [Marqo Search API](https://apis.io/apis/marqo/marqo-search-api/) — Tensor, lexical, and hybrid search across an index.
- [Marqo Telemetry API](https://apis.io/apis/marqo/marqo-telemetry-api/) — Health, readiness, and engine-level metadata.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Marqo Agentic Access](https://apis.io/agentic-access/marqo/marqo-agentic-access/)

#### Collections (8)

Postman and Open Collection request collections.

- [Marqo REST API](https://apis.io/collections/marqo/open-marqo/)
- [Marqo REST Documents API](https://apis.io/collections/marqo/open-marqo-documents-api/)
- [Marqo REST Documents Embeddings API](https://apis.io/collections/marqo/open-marqo-embeddings-api/)
- [Marqo REST Documents Indexes API](https://apis.io/collections/marqo/open-marqo-indexes-api/)
- [Marqo REST Documents Models API](https://apis.io/collections/marqo/open-marqo-models-api/)
- [Marqo REST Documents Recommendations API](https://apis.io/collections/marqo/open-marqo-recommendations-api/)
- [Marqo REST Documents Search API](https://apis.io/collections/marqo/open-marqo-search-api/)
- [Marqo REST Documents Telemetry API](https://apis.io/collections/marqo/open-marqo-telemetry-api/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Marqo Authentication](https://apis.io/security/marqo/marqo-authentication/)
- [Marqo Domain Security](https://apis.io/security/marqo/marqo-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Marqo Plans Pricing](https://apis.io/plans/marqo/marqo-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Marqo Rate Limits](https://apis.io/rate-limits/marqo/marqo-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Marqo Finops](https://apis.io/finops/marqo/marqo-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.marqo.ai/)
- [Documentation](https://docs.marqo.ai/)
- [Getting started](https://github.com/marqo-ai/marqo#getting-started)
- [Pricing](https://www.marqo.ai/pricing)
- [Blog](https://www.marqo.ai/blog/)
- [GitHub](https://github.com/marqo-ai)

## API Evangelist rating

**Kin Score 41.2** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 45.0 |
| Contract governance | 0.0 |
| Operational transparency | 42.1 |
| Developer ergonomics | 42.9 |
| Access clarity | 15.8 |

**Agent readiness 20.9** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 10.9** — AI & Biometrics

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/marqo/](https://apis.io/providers/marqo/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Marqo: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/marqo/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
