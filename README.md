# Tabnine

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

Tabnine provides AI code completion, chat, and agentic workflows across IDEs and CLI, with strong support for SaaS, VPC, and air-gapped on-prem deployments. The Enterprise Context Engine indexes a customer's codebase, dependencies, and architecture. Tabnine's consumer surface is via IDE plugins (VS Code, JetBrains, Eclipse) and the Tabnine CLI; there is no general-purpose public REST inference API for end-developers.

**Areas:** Artificial Intelligence · Developer Tools · Code Completion · Self-Hosted · Enterprise · Privacy

## Tabnine on APIs.io

Everything profiled for Tabnine is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/tabnine/](https://apis.io/providers/tabnine/)** — or go straight to one of the APIs or properties below.

### APIs (6)

- [Tabnine IDE Plugins](https://apis.io/apis/tabnine/plugins/) — VS Code, JetBrains (IntelliJ, PhpStorm, etc.), and Eclipse plugins surfacing autocomplete, chat, and agentic workflows. Communicates with Tabnine's hosted…
- [Tabnine Enterprise (Admin Suite + Context Engine)](https://apis.io/apis/tabnine/enterprise/) — Enterprise SKU with admin console (data analytics, model provisioning, context permissions, SSO), Enterprise Context Engine (codebase indexing), and…
- [Tabnine Groups API](https://apis.io/apis/tabnine/tabnine-groups-api/) — The Groups API from Tabnine — 2 operation(s) for groups.
- [Tabnine Main API](https://apis.io/apis/tabnine/tabnine-main-api/) — The Main API from Tabnine — 12 operation(s) for main.
- [Tabnine Schemas API](https://apis.io/apis/tabnine/tabnine-schemas-api/) — The Schemas API from Tabnine — 1 operation(s) for schemas.
- [Tabnine Users API](https://apis.io/apis/tabnine/tabnine-users-api/) — The Users API from Tabnine — 2 operation(s) for users.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Tabnine Webhooks](https://apis.io/asyncapis/tabnine/tabnine-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [tabnine-mcp.yml](https://apis.io/servers/tabnine/tabnine-mcp-yml/)

#### JSON Schema (6)

The data models the API reads and writes.

- [GetGroupsIdResponse](https://apis.io/schemas/tabnine/tabnine-get-groups-id-response/)
- [GetGroupsResponse](https://apis.io/schemas/tabnine/tabnine-get-groups-response/)
- [GetUsersIdResponse](https://apis.io/schemas/tabnine/tabnine-get-users-id-response/)
- [GetUsersResponse](https://apis.io/schemas/tabnine/tabnine-get-users-response/)
- [PostGroupsResponse](https://apis.io/schemas/tabnine/tabnine-post-groups-response/)
- [PostUsersResponse](https://apis.io/schemas/tabnine/tabnine-post-users-response/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Tabnine Context](https://apis.io/jsonld/tabnine/tabnine-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Tabnine API Rules](https://apis.io/rules/tabnine/tabnine-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Tabnine Authentication](https://apis.io/security/tabnine/tabnine-authentication/)
- [Tabnine Domain Security](https://apis.io/security/tabnine/tabnine-domain-security/)
- [Tabnine Trust Center](https://apis.io/security/tabnine/tabnine-trust-center/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Tabnine Plans Pricing](https://apis.io/plans/tabnine/tabnine-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Tabnine Rate Limits](https://apis.io/rate-limits/tabnine/tabnine-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Tabnine Finops](https://apis.io/finops/tabnine/tabnine-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.tabnine.com/)
- [Documentation](https://docs.tabnine.com/)
- [Getting started](https://docs.tabnine.com/main/getting-started/install)
- [Support](https://support.tabnine.com/hc/en-us)
- [Changelog](https://docs.tabnine.com/main/administering-tabnine/release-notes)
- [Blog](https://www.tabnine.com/blog/feed/)
- [Compliance](https://trust.tabnine.com/)
- [Terms of service](https://www.tricentis.com/resources/tosca-cloud-ata-demo)
- [Privacy policy](https://docs.tabnine.com/main/welcome/readme/privacy)
- [GitHub](https://github.com/codota)
- [Status](https://status.tabnine.com/)

## API Evangelist rating

**Kin Score 42.6** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 30.0 |
| Contract governance | 22.0 |
| Operational transparency | 57.9 |
| Developer ergonomics | 40.5 |
| Access clarity | 42.1 |

**Agent readiness 25.6** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | yes |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 27.3** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/tabnine/](https://apis.io/providers/tabnine/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Tabnine: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/tabnine/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
