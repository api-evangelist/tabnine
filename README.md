# Tabnine (tabnine)

Tabnine provides AI code completion, chat, and agentic workflows across IDEs and CLI, with strong support for SaaS, VPC, and air-gapped on-prem deployments. The Enterprise Context Engine indexes a customer's codebase, dependencies, and architecture.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/tabnine/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=tabnine-api-evangelist&utm_content=repo)

## Type
- **x-type:** company

## Tags
- AI, Developer Tools, Code Completion, Self-Hosted, Enterprise, Privacy

## APIs
- **Tabnine IDE Plugins** — VS Code, JetBrains (IntelliJ, PhpStorm, etc.), Eclipse. Autocomplete, chat, agentic workflows over a proprietary protocol.
- **Tabnine Enterprise (Admin Suite + Context Engine)** — Admin console (analytics, model provisioning, context permissions, SSO), Enterprise Context Engine (codebase indexing), flexible deployment (SaaS / VPC / Local / Air-Gapped).

### Plans (May 2026)
- **Free** — Basic completions.
- **Pro** — Advanced features (consumer/individual).
- **Enterprise** — $39/user/month list. SaaS, VPC, on-prem, or air-gapped; admin suite; IP indemnification; custom enterprise contracts available.

## Plans, Rate Limits, FinOps
- [Plans](plans/tabnine-plans-pricing.yml)
- [RateLimits](rate-limits/tabnine-rate-limits.yml)
- [FinOps](finops/tabnine-finops.yml)

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Common Properties
- [Website](https://www.tabnine.com/)
- [Documentation](https://docs.tabnine.com/)

## Notes
- Tabnine does not expose a general-purpose public REST inference API for end-developers. Consumption is via IDE plugins and the Tabnine CLI talking to Tabnine's hosted or self-hosted backend over a proprietary protocol.
- No public OpenAPI spec discovered.

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
