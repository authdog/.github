<p align="center">
  <img width="420" alt="Authdog" src="./logo-light.svg#gh-light-mode-only" />
  <img width="420" alt="Authdog" src="./logo-dark.svg#gh-dark-mode-only" />
</p>

<p align="center">
<b>Agentic Identity, Access Control, Observability.</b>
</p>

<p align="center">
<a href="https://www.authdog.com">Website</a> ·
<a href="https://www.authdog.com/docs">Docs</a> ·
<a href="https://www.authdog.com/pricing">Pricing</a> ·
<a href="https://console.authdog.com">Console</a> ·
<a href="https://status.authdog.com">Status</a>
</p>

Welcome to [Authdog](https://www.authdog.com) — identity for agents and workloads. Issue scoped credentials, decide what they can do, and investigate abuse with Observability.

Agents are not users. Authdog gives every workload its own identity, one authorization model per environment, and Lidar as the identity SIEM. Humans still get a full CIAM stack: passwordless, passkeys, SSO, and SCIM. The platform runs on Cloudflare’s global edge across 330+ cities, with a median authentication latency of ~24ms.

## Products

### [Agentic Identity](https://www.authdog.com/product/ai)

Issue a scoped credential to the workload. Put OAuth in front of MCP tools. Keep every call attributable.

- **Machine identity** — confidential OIDC clients on `client_credentials`; short-lived access tokens, no refresh tokens
- **MCP servers** — register the server, mint a short-lived bearer, scope the tools; playground in the console
- **Agents & Trust Store** — register, verify, and revoke named agent identities; environment isolation
- **Vault** — delegated secrets and user-consented API access for agents acting on someone’s behalf

### [Access Control](https://www.authdog.com/product/access-control)

One environment, one model. Start with roles. Move to attributes or relationships when the product needs it. The check from your app stays the same.

- **RBAC** — roles, groups, and SCIM-mapped directory permissions
- **ABAC** — versioned Rego policies over user, resource, and environment attributes
- **FGA** — Zanzibar-style relationship tuples and AuthZEN `ListObjects`
- **AuthZEN** — the same allow/deny decision API and SDK helpers at the edge

### [Observability](https://www.authdog.com/product/siem)

Lidar is Authdog’s identity SIEM — search events, correlate detections, and triage Signals in one place.

- **Threat detection** — brute force, credential stuffing, signup abuse, impossible travel, MFA fatigue
- **Signals** — per-environment findings with severity, user, IP, and rule
- **Investigate here** — Signals, scan logs, scan runs, and posture on the same event stream
- **Optional export** — copy the trail to Datadog, Splunk, a webhook, or OpenTelemetry if you already run another SIEM

## Also in the platform

Every module ships on every plan. Plans differ by team seats, support, and service levels — not product access.

- **Authentication** — passwordless, social login, passkeys/WebAuthn, MFA, hosted UI, and bot protection
- **Enterprise SSO & provisioning** — SAML & OIDC SSO, SCIM, and HRIS directory sync
- **Console & CLI** — tenants, projects, environments, users, and policies without code
- **20 official SDKs** — Next.js, React, Vue, SvelteKit, Angular, Remix, Expo, Astro, TanStack Start, Express, Fastify, Python, Go, Rust, and more

Built on open standards: OAuth 2.0, OpenID Connect, SAML, SCIM, WebAuthn/passkeys, and AuthZEN.

## Open source

| Repo | What it is |
| --- | --- |
| [web-sdk](https://github.com/authdog/web-sdk) | Framework SDKs for web, mobile, and backends |
| [sdk](https://github.com/authdog/sdk) | Language SDKs for Authdog APIs |
| [cli](https://github.com/authdog/cli) | Official CLI for management and identity services |
| [keylab](https://github.com/authdog/keylab) | JWT create/verify without rolling your own crypto |
| [agent-skills](https://github.com/authdog/agent-skills) | Skills for agentic onboarding onto Authdog |

Point an agent at [`/llms.txt`](https://www.authdog.com/llms.txt) — every guide is also available as Markdown.

## Pricing

Your first **1 million monthly active users** are free. Sign-ins are unlimited. Usage above 1M MAU is **$1,000 per additional million MAU / month** (proportional); above 5M MAU, contact sales for committed-volume pricing.

| Plan | Price | Includes |
| --- | --- | --- |
| **Free** | $0 forever | 1M MAU · every module · community support |
| **Team** | from $19/mo | 3 seats included ($11/seat after) · 1M MAU · standard support |
| **Pro** | $199/mo | 20 seats · 1M MAU · priority support · 99.9% uptime SLA |
| **Enterprise** | Custom | Unlimited MAU · 99.99% SLA · on-prem · dedicated CSM · SOC 2 Type 2 & HIPAA BAA |

Yearly billing is **20% off**. No modules are locked behind higher tiers.

[See full pricing →](https://www.authdog.com/pricing) · [Start free →](https://identity.authdog.com/signup)

## Why teams choose Authdog

Internal identity systems burn engineering time and still miss the SSO, SCIM, and agent controls that close enterprise deals. Authdog ships the full platform from day one — identities for humans and agents, access decisions in the same API, and Lidar on the identity stream — with a free million MAU so you can ship, then scale through Team, Pro, or Enterprise.

Try [Authdog](https://www.authdog.com) today.
