# Personio

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

Personio is a European HR management and recruiting platform serving small and mid-sized businesses with a unified HRIS covering employee records, absence management, time tracking, payroll preparation, performance, and applicant tracking. The platform is headquartered in Munich and is widely adopted across Germany, Austria, Switzerland, the UK, the Netherlands, and Spain. Personio exposes a Public API at api.personio.de that supports Bearer token authentication via Client ID/Secret (v1 token endpoint and v2 OAuth 2.0 client credentials flow), with webhooks now available for Person entity events.

**Areas:** Human Resources · HRIS · Recruiting · Applicant Tracking · Absence Management · Time Tracking · Europe HR

## Personio on APIs.io

Everything profiled for Personio is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/personio/](https://apis.io/providers/personio/)** — or go straight to one of the APIs or properties below.

### APIs (6)

- [Personio Public API v2](https://apis.io/apis/personio/public-api-v2/) — Next-generation REST API with OAuth 2.0 Client Credentials Grant authentication. Token endpoint POST /v2/auth/token returns access tokens used as Bearer…
- [Personio Absence Periods API](https://apis.io/apis/personio/personio-absence-periods-api/) — Manage absence periods.
- [Personio Auth API](https://apis.io/apis/personio/personio-auth-api/) — OAuth 2.0 token exchange.
- [Personio Persons API](https://apis.io/apis/personio/personio-persons-api/) — Manage person (employee) records.
- [Personio Projects API](https://apis.io/apis/personio/personio-projects-api/) — Read project definitions.
- [Personio Webhooks API](https://apis.io/apis/personio/personio-webhooks-api/) — Manage event webhook subscriptions.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [personio](https://apis.io/servers/personio/personio/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Personio Agentic Access](https://apis.io/agentic-access/personio/personio-agentic-access/)

#### Collections (6)

Postman and Open Collection request collections.

- [Personio Public API v2](https://apis.io/collections/personio/open-personio/)
- [Personio Public API v2 Absence Periods API](https://apis.io/collections/personio/open-personio-absence-periods-api/)
- [Personio Public API v2 Absence Periods Auth API](https://apis.io/collections/personio/open-personio-auth-api/)
- [Personio Public API v2 Absence Periods Persons API](https://apis.io/collections/personio/open-personio-persons-api/)
- [Personio Public API v2 Absence Periods Projects API](https://apis.io/collections/personio/open-personio-projects-api/)
- [Personio Public API v2 Absence Periods Webhooks API](https://apis.io/collections/personio/open-personio-webhooks-api/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Personio Authentication](https://apis.io/security/personio/personio-authentication/)
- [Personio Domain Security](https://apis.io/security/personio/personio-domain-security/)
- [Personio Trust Center](https://apis.io/security/personio/personio-trust-center/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.personio.com)
- [Documentation](https://developer.personio.de/)
- [Pricing](https://www.personio.com/pricing/)
- [GitHub](https://github.com/personio)

## API Evangelist rating

**Kin Score 27.7** — thin · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 75.0 |
| Contract quality | 49.0 |
| Contract governance | 0.0 |
| Operational transparency | 2.6 |
| Developer ergonomics | 16.7 |
| Access clarity | 26.3 |

**Agent readiness 41.8** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | verified |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | partial |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | partial |
| Operation Distinctiveness | distinct |

**Regulatory alignment 16.7** — Employment & Payroll

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/personio/](https://apis.io/providers/personio/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Personio: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/personio/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
