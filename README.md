# Feign

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

Feign (OpenFeign) is a declarative Java HTTP client binder inspired by Retrofit, JAX-RS, and WebSocket. It turns annotated interfaces into templated HTTP requests with pluggable encoders, decoders, error handlers, and HTTP transports. The OpenFeign organization maintains a large set of modules covering serialization (Jackson, Gson, Moshi, FastJSON2, JAXB, SAX, SOAP), HTTP transports (OkHttp, Apache HttpClient, Java 11 client, Ribbon), JAX-RS contracts, resilience (Hystrix), logging (SLF4J), form encoding, GraphQL, and metrics.

**Areas:** HTTP Client · Java · JVM · Open Source · REST · SDK

## Feign on APIs.io

Everything profiled for Feign is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/feign/](https://apis.io/providers/feign/)** — or go straight to one of the APIs or properties below.

### APIs (12)

- [Feign Core](https://apis.io/apis/feign/feign-core/) — Feign Core is the base library that processes annotated Java interfaces into templated HTTP requests. It defines the contract, encoder, decoder, and client…
- [Feign Jackson](https://apis.io/apis/feign/feign-jackson/) — Feign Jackson module provides Jackson-based JSON encoding and decoding for Feign-annotated client interfaces, the most common serialization choice in JVM…
- [Feign Gson](https://apis.io/apis/feign/feign-gson/) — Feign Gson module provides Google Gson-based JSON encoding and decoding for Feign clients, useful in projects already standardized on Gson.
- [Feign OkHttp](https://apis.io/apis/feign/feign-okhttp/) — Feign OkHttp module replaces the default JDK HTTP transport with Square's OkHttp client, adding HTTP/2, connection pooling, and modern transport features.
- [Feign Apache HttpClient](https://apis.io/apis/feign/feign-httpclient/) — Feign Apache HttpClient module integrates Apache HttpComponents (HC5) as the underlying HTTP transport for Feign clients.
- [Feign Java 11 HTTP](https://apis.io/apis/feign/feign-java11/) — Feign Java 11 HTTP module uses the JDK 11+ standard HttpClient as the transport, supporting HTTP/2 and asynchronous calls without external dependencies.
- [Feign Ribbon](https://apis.io/apis/feign/feign-ribbon/) — Feign Ribbon module integrates Netflix Ribbon for client-side load balancing across a list of HTTP servers.
- [Feign Hystrix](https://apis.io/apis/feign/feign-hystrix/) — Feign Hystrix module wraps Feign client calls in Netflix Hystrix commands, adding circuit breaking, fallbacks, and bulkhead isolation.
- [Feign JAX-RS](https://apis.io/apis/feign/feign-jaxrs/) — Feign JAX-RS modules let developers reuse JAX-RS 1.x, 2.x, 3.x, and 4.x annotations on Feign client interfaces instead of Feign's native annotation set.
- [Feign SLF4J](https://apis.io/apis/feign/feign-slf4j/) — Feign SLF4J module routes Feign request and response logging through the SLF4J facade, integrating with the host application's logging backend.
- [Feign Form](https://apis.io/apis/feign/feign-form/) — Feign Form module adds support for application/x-www-form-urlencoded and multipart/form-data request bodies, including file uploads.
- [Feign Micrometer](https://apis.io/apis/feign/feign-micrometer/) — Feign Micrometer module exposes Feign client metrics (timings, counts, errors) through Micrometer for shipment to Prometheus, Datadog, and other monitoring…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### GraphQL (1)

GraphQL schemas.

- [Moved to /providers/feign/](https://apis.io/graphqls/feign/feign-graphql/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Feign Plans Pricing](https://apis.io/plans/feign/feign-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Feign Rate Limits](https://apis.io/rate-limits/feign/feign-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Feign Finops](https://apis.io/finops/feign/feign-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://github.com/OpenFeign/feign)
- [Documentation](https://github.com/OpenFeign/feign#readme)
- [GitHub](https://github.com/OpenFeign)

## API Evangelist rating

**Kin Score 13.3** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 62.5 |
| Contract quality | 0.0 |
| Contract governance | 0.0 |
| Operational transparency | 26.3 |
| Developer ergonomics | 21.4 |
| Access clarity | 7.9 |

**Agent readiness 0.6** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
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

**Regulatory alignment 0.0** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/feign/](https://apis.io/providers/feign/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Feign: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/feign/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
