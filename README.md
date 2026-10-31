# Paramark

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

Paramark is a marketing measurement and forecasting platform that helps growth and finance teams understand the true incremental impact of their marketing spend. Founded in 2022 by Pranav Piyush and Pete Belknap and backed by Greylock, Paramark combines incrementality testing, marketing mix modeling (MMM), and scenario planning in one place, augmented by human growth advisors and AI agents. Rather than relying on last-touch attribution, the platform uses statistics and machine learning to quantify each channel's incremental contribution across search, social, TV, and out-of-home, giving marketers defensible ROI numbers to bring to their finance teams. Paramark maintains an open-source Marketing Mix Modeling workbench and forks of the major MMM libraries under its paramark-inc GitHub organization. Paramark runs a production API at api.paramark.com, but publishes no developer portal and no public contract: its FastAPI-generated OpenAPI, /docs and /redoc all answer HTTP 401 behind an HTTP Basic challenge, and API access is sold as a feature of the Advanced ($150k/yr) and Enterprise ($220k/yr) tiers, where MCP servers are listed as coming soon. What Paramark does publish anonymously and machine-readably is its identity layer: full OpenID Connect and OAuth 2.0 authorization server metadata at signin.paramark.com, with PKCE, device code and dynamic client registration.

**Areas:** Company · Application · Marketing · Analytics · Measurements · Marketing Mix Modeling · Incrementality · Advertising · Artificial Intelligence

## Paramark on APIs.io

Everything profiled for Paramark is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/paramark/](https://apis.io/providers/paramark/)** — or go straight to one of the APIs or properties below.

### APIs (1)

- [Paramark API](https://apis.io/apis/paramark/paramark-api/) — Paramark's production API, offered as a feature of the Advanced and Enterprise tiers. The service is live and answers anonymously at GET /healthz (HTTP 200…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Paramark Authentication](https://apis.io/security/paramark/paramark-authentication/)
- [Paramark Domain Security](https://apis.io/security/paramark/paramark-domain-security/)
- [Paramark Trust Center](https://apis.io/security/paramark/paramark-trust-center/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Paramark Scopes](https://apis.io/scopes/paramark/paramark-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Paramark Plans Pricing](https://apis.io/plans/paramark/paramark-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Paramark Rate Limits](https://apis.io/rate-limits/paramark/paramark-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://paramark.com/)
- [Pricing](https://paramark.com/pricing)
- [Blog](https://paramark.com/blog)
- [Privacy policy](https://paramark.com/privacy-policy)
- [GitHub](https://github.com/paramark-inc)

## API Evangelist rating

**Kin Score 28.8** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 0.0 |
| Contract governance | 18.2 |
| Operational transparency | 2.6 |
| Developer ergonomics | 14.3 |
| Access clarity | 67.1 |

**Agent readiness 5.0** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
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

**Regulatory alignment 32.7** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/paramark/](https://apis.io/providers/paramark/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Paramark: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/paramark/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
