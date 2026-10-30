# Groove

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

Groove is a customer support helpdesk and shared inbox platform for small and midsize businesses that consolidates email, live chat, social, and knowledge base content into a single agent workspace with automations, collision detection, reporting, and SLAs. Groove also provides customer- facing knowledge bases and self-service portals. Developers can integrate via the v2 GraphQL API or the legacy v1 REST API, both authenticated with an API key obtained from account settings.

**Areas:** Customer Service · Help Desk · Shared Inbox · Knowledge Base · Conversations · Live Chat

## Groove on APIs.io

Everything profiled for Groove is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/groove/](https://apis.io/providers/groove/)** — or go straight to one of the APIs or properties below.

### APIs (12)

- [Groove GraphQL API v2](https://apis.io/apis/groove/graphql-api/) — GraphQL API exposing conversations, messages, agents, contacts, mailboxes, tags, and knowledge base data through a single endpoint. Authentication uses a…
- [Groove REST API v1](https://apis.io/apis/groove/rest-api-v1/) — Legacy REST API for managing customers, conversations, messages, mailboxes, agents, tags, and webhooks in Groove. Authentication uses a Bearer API key. The…
- [Groove Webhooks](https://apis.io/apis/groove/webhooks/) — Groove's webhook surface delivered through the legacy REST API webhook subscription endpoint. Customers register destination URLs and event types via POST…
- [Groove Agents API](https://apis.io/apis/groove/groove-agents-api/) — The Agents API from Groove — 2 operation(s) for agents.
- [Groove Attachments API](https://apis.io/apis/groove/groove-attachments-api/) — The Attachments API from Groove — 1 operation(s) for attachments.
- [Groove Customers API](https://apis.io/apis/groove/groove-customers-api/) — The Customers API from Groove — 2 operation(s) for customers.
- [Groove Folders API](https://apis.io/apis/groove/groove-folders-api/) — The Folders API from Groove — 1 operation(s) for folders.
- [Groove Groups API](https://apis.io/apis/groove/groove-groups-api/) — The Groups API from Groove — 2 operation(s) for groups.
- [Groove Mailboxes API](https://apis.io/apis/groove/groove-mailboxes-api/) — The Mailboxes API from Groove — 1 operation(s) for mailboxes.
- [Groove Messages API](https://apis.io/apis/groove/groove-messages-api/) — The Messages API from Groove — 2 operation(s) for messages.
- [Groove Tickets API](https://apis.io/apis/groove/groove-tickets-api/) — The Tickets API from Groove — 4 operation(s) for tickets.
- [Groove Webhooks API](https://apis.io/apis/groove/groove-webhooks-api/) — The Webhooks API from Groove — 2 operation(s) for webhooks.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Groove Webhooks](https://apis.io/asyncapis/groove/groove-webhooks-asyncapi/)

#### Event channels (14)

Individual events and webhooks the provider emits.

- [agent_archived](https://apis.io/channels/groove/agent-archived/)
- [agent_invited](https://apis.io/channels/groove/agent-invited/)
- [agent_replied](https://apis.io/channels/groove/agent-replied/)
- [customer_added](https://apis.io/channels/groove/customer-added/)
- [customer_replied](https://apis.io/channels/groove/customer-replied/)
- [note_added](https://apis.io/channels/groove/note-added/)
- [ticket_assigned](https://apis.io/channels/groove/ticket-assigned/)
- [ticket_closed](https://apis.io/channels/groove/ticket-closed/)
- [ticket_deleted](https://apis.io/channels/groove/ticket-deleted/)
- [ticket_moved](https://apis.io/channels/groove/ticket-moved/)
- [ticket_opened](https://apis.io/channels/groove/ticket-opened/)
- [ticket_priority_changed](https://apis.io/channels/groove/ticket-priority-changed/)
- [ticket_started](https://apis.io/channels/groove/ticket-started/)
- [ticket_tagged](https://apis.io/channels/groove/ticket-tagged/)

#### GraphQL (1)

GraphQL schemas.

- [Groove GraphQL API](https://apis.io/graphqls/groove/groove-graphql/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [groove](https://apis.io/servers/groove/groove/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Groove Agentic Access](https://apis.io/agentic-access/groove/groove-agentic-access/)

#### Collections (10)

Postman and Open Collection request collections.

- [Groove REST API v1](https://apis.io/collections/groove/open-groove/)
- [Groove REST API v1 Agents API](https://apis.io/collections/groove/open-groove-agents-api/)
- [Groove REST API v1 Agents Attachments API](https://apis.io/collections/groove/open-groove-attachments-api/)
- [Groove REST API v1 Agents Customers API](https://apis.io/collections/groove/open-groove-customers-api/)
- [Groove REST API v1 Agents Folders API](https://apis.io/collections/groove/open-groove-folders-api/)
- [Groove REST API v1 Agents Groups API](https://apis.io/collections/groove/open-groove-groups-api/)
- [Groove REST API v1 Agents Mailboxes API](https://apis.io/collections/groove/open-groove-mailboxes-api/)
- [Groove REST API v1 Agents Messages API](https://apis.io/collections/groove/open-groove-messages-api/)
- [Groove REST API v1 Agents Tickets API](https://apis.io/collections/groove/open-groove-tickets-api/)
- [Groove REST API v1 Agents Webhooks API](https://apis.io/collections/groove/open-groove-webhooks-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Groove — asyncapi rules](https://apis.io/rules/groove/groove-asyncapi-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Groove Authentication](https://apis.io/security/groove/groove-authentication/)
- [Groove Domain Security](https://apis.io/security/groove/groove-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.groovehq.com)
- [Documentation](https://doc.groovehq.com)
- [Pricing](https://www.groovehq.com/pricing)
- [Blog](https://www.groovehq.com/blog)

## API Evangelist rating

**Kin Score 32.2** — thin · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 68.3 |
| Contract quality | 52.3 |
| Contract governance | 11.4 |
| Operational transparency | 5.3 |
| Developer ergonomics | 33.3 |
| Access clarity | 23.7 |

**Agent readiness 40.1** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | verified |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
| Event Surface Described | derived (partial credit) |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 11.8** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/groove/](https://apis.io/providers/groove/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Groove: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/groove/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
