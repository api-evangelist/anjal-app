# Anjal

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

Anjal provides email infrastructure designed for AI agents, allowing users to connect their preferred AI (Claude, ChatGPT, Codex, etc.) to manage inboxes on custom domains. It offers multi‑tenant workspaces, secure mail protection with prompt‑injection scanning, and a REST API plus TypeScript SDK for developers to integrate email handling into autonomous agents.

**Areas:** Email · AI · Agents · SaaS · EmailAPI

## Anjal on APIs.io

Everything profiled for Anjal is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/anjal-app/](https://apis.io/providers/anjal-app/)** — or go straight to one of the APIs or properties below.

### APIs (17)

- [Anjal Addresses API](https://apis.io/apis/anjal-app/anjal-app-addresses-api/) — Multiple accepted addresses per inbox. Add a custom-domain alias to change the outbound From without losing thread history.
- [Anjal Cadences API](https://apis.io/apis/anjal-app/anjal-app-cadences-api/) — The Cadences API from Anjal — 7 operation(s) for cadences.
- [Anjal Domains API](https://apis.io/apis/anjal-app/anjal-app-domains-api/) — Bring your own sending domain. Returns DNS records, verification state, and a BIND zone file export.
- [Anjal Drafts API](https://apis.io/apis/anjal-app/anjal-app-drafts-api/) — Compose messages across multiple agent turns and send atomically.
- [Anjal Inboxes API](https://apis.io/apis/anjal-app/anjal-app-inboxes-api/) — Email mailboxes that can send, receive, and store threads.
- [Anjal LinkedIn — Outreach API](https://apis.io/apis/anjal-app/anjal-app-linkedin-outreach-api/) — Profile lookup, connection requests, keyword post search. Each call is logged and counted against a per-session daily quota (LinkedIn rate-limits per…
- [Anjal LinkedIn — Posts API](https://apis.io/apis/anjal-app/anjal-app-linkedin-posts-api/) — The LinkedIn — Posts API from Anjal — 4 operation(s) for linkedin — posts.
- [Anjal LinkedIn — Searches API](https://apis.io/apis/anjal-app/anjal-app-linkedin-searches-api/) — Deterministic historical search across past-24h | past-week | past-month. Synchronous — returns the full hit list inline with the same structured output…
- [Anjal LinkedIn — Sessions API](https://apis.io/apis/anjal-app/anjal-app-linkedin-sessions-api/) — Login on behalf of the customer (email + password, with PIN or mobile-app verification challenge support), or import existing cookies. Cookies are…
- [Anjal LinkedIn — Signals API](https://apis.io/apis/anjal-app/anjal-app-linkedin-signals-api/) — Deterministic real-time intent watchers. Every signal is a keyword plus a plain-English firing rule (e.g. "Flag as ready when the author is a founder…
- [Anjal Lists API](https://apis.io/apis/anjal-app/anjal-app-lists-api/) — Named groups of recipient addresses per inbox.
- [Anjal Messages API](https://apis.io/apis/anjal-app/anjal-app-messages-api/) — Send, reply, forward, list, and download messages.
- [Anjal Metrics API](https://apis.io/apis/anjal-app/anjal-app-metrics-api/) — Programmatic counters scoped by workspace or inbox.
- [Anjal Tenants API](https://apis.io/apis/anjal-app/anjal-app-tenants-api/) — Super-admin only — platform operator endpoints.
- [Anjal Webhooks API](https://apis.io/apis/anjal-app/anjal-app-webhooks-api/) — HTTP callbacks fired on every inbox event.
- [Anjal WebSocket API](https://apis.io/apis/anjal-app/anjal-app-websocket-api/) — Real-time event stream. The agentmail.to spec-compatible wire protocol.
- [Anjal Workspaces API](https://apis.io/apis/anjal-app/anjal-app-workspaces-api/) — Isolated containers under a tenant. Hand scoped keys to your resellers so their customers cannot see each other.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Anjal App Webhooks](https://apis.io/asyncapis/anjal-app/anjal-app-webhooks/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Anjal App Agentic Access](https://apis.io/agentic-access/anjal-app/anjal-app-agentic-access/)

#### JSON Schema (6)

The data models the API reads and writes.

- [CadenceStepInput](https://apis.io/schemas/anjal-app/anjal-app-cadence-step-input/)
- [DraftInput](https://apis.io/schemas/anjal-app/anjal-app-draft-input/)
- [LinkedInSignal](https://apis.io/schemas/anjal-app/anjal-app-linked-in-signal/)
- [LinkedInSignalMatch](https://apis.io/schemas/anjal-app/anjal-app-linked-in-signal-match/)
- [Message](https://apis.io/schemas/anjal-app/anjal-app-message/)
- [WebhookEvent](https://apis.io/schemas/anjal-app/anjal-app-webhook-event/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Anjal App Context](https://apis.io/jsonld/anjal-app/anjal-app-context/)

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Anjal App Openapi Overlay](https://apis.io/overlays/anjal-app/anjal-app-openapi-overlay/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Anjal API Rules](https://apis.io/rules/anjal-app/anjal-app-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Anjal App Authentication](https://apis.io/security/anjal-app/anjal-app-authentication/)
- [Anjal App Domain Security](https://apis.io/security/anjal-app/anjal-app-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Anjal App Scopes](https://apis.io/scopes/anjal-app/anjal-app-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Anjal App Plans Pricing](https://apis.io/plans/anjal-app/anjal-app-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Anjal App Rate Limits](https://apis.io/rate-limits/anjal-app/anjal-app-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://anjal.app/)
- [Documentation](https://anjal.app/docs)
- [Getting started](https://anjal.app/download)
- [API reference](https://anjal.app/docs)
- [Pricing](https://anjal.app/pricing)
- [Sign up](https://anjal.app/login)
- [Blog](https://anjal.app/blog)
- [Terms of service](https://anjal.app/terms)
- [Privacy policy](https://anjal.app/privacy)
- [GitHub](https://github.com/kamskans)

## API Evangelist rating

**Kin Score 66.1** — strong · rubric 0.26.0 · scored 2026-11-01

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 63.9 |
| Contract governance | 79.1 |
| Operational transparency | 32.1 |
| Developer ergonomics | 63.6 |
| Access clarity | 73.2 |

**Agent readiness 48.8** — agent-native

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | unknown |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | verified |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | unknown |
| Agent Skills | unknown |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |
| MCP Tool Quality | na |

**Regulatory alignment 31.8** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/anjal-app/](https://apis.io/providers/anjal-app/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Anjal: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/anjal-app/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
