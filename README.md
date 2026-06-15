# Groove (groove)

Groove is a customer support helpdesk and shared inbox platform for small and midsize businesses that consolidates email, live chat, social, and knowledge base content into a single agent workspace with automations, collision detection, reporting, and SLAs. Groove also provides customer- facing knowledge bases and self-service portals. Developers can integrate via the v2 GraphQL API or the legacy v1 REST API, both authenticated with an API key obtained from account settings.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/groove/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/groove/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Customer Support
- Helpdesk
- Shared Inbox
- Knowledge Base
- Conversations
- Live Chat

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-30

## APIs

### Groove GraphQL API v2

GraphQL API exposing conversations, messages, agents, contacts, mailboxes, tags, and knowledge base data through a single endpoint. Authentication uses a Bearer API key retrieved from Groove account settings. The GraphQL API is the actively developed replacement for the legacy v1 REST API.

- **Human URL:** [https://developer.groovehq.com](https://developer.groovehq.com)
- **Base URL:** `https://api.groovehq.com/graphql`

#### Tags

- GraphQL
- Conversations
- Messages
- Contacts
- Agents
- Knowledge Base

#### Properties

- [Documentation](https://developer.groovehq.com)
- [Git Hub  Documentation](https://github.com/GrooveHQ/docs)
- [Postman Collection](collections/groove.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/groove.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Groove REST API v1

Legacy REST API for managing customers, conversations, messages, mailboxes, agents, tags, and webhooks in Groove. Authentication uses a Bearer API key. The REST API is no longer actively developed; new integrations should target the GraphQL API.

- **Human URL:** [https://doc.groovehq.com](https://doc.groovehq.com)
- **Base URL:** `https://api.groovehq.com/v1`

#### Tags

- Customer Support
- Conversations
- Customers
- Mailboxes
- Webhooks

#### Properties

- [Documentation](https://doc.groovehq.com)
- [Postman Collection](collections/groove.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/groove.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Groove Webhooks

Groove's webhook surface delivered through the legacy REST API webhook subscription endpoint. Customers register destination URLs and event types via POST /v1/webhooks; Groove then POSTs JSON payloads for the fourteen documented events covering tickets, customers, agents, and messages.

- **Human URL:** [https://doc.groovehq.com/webhooks](https://doc.groovehq.com/webhooks)
- **Base URL:** `https://api.groovehq.com/v1/webhooks`

#### Tags

- Webhooks
- Events
- Tickets
- Messages
- Customers
- Agents

#### Properties

- [Documentation](https://doc.groovehq.com/webhooks)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/groove/refs/heads/main/asyncapi/groove-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/groove.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/groove.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.groovehq.com)
- [Developer  Portal](https://developer.groovehq.com)
- [Documentation](https://doc.groovehq.com)
- [Pricing](https://www.groovehq.com/pricing)
- [Sign Up](https://www.groovehq.com/signup)
- [Blog](https://www.groovehq.com/blog)
- [Git Hub](https://github.com/GrooveHQ)
- [LinkedIn](https://www.linkedin.com/company/groovehq)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
