# Help Scout (helpscout)

Help Scout is an email-first help desk platform with shared inboxes, live chat, knowledge bases, and a customer portal. The Help Scout APIs expose conversations, customers, inboxes, users, workflows, ratings, reports, Docs (knowledge base), Beacon (in-app messaging), and webhooks.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/helpscout/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/helpscout/refs/heads/main/apis.yml)

## Tags

- Customer Support
- Help Desk
- Email
- Live Chat
- Knowledge Base
- SaaS

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-30

## APIs

### Help Scout Conversations API

Create, retrieve, list, update, and delete conversations including threads, attachments, custom fields, tags, and snooze states. Core Mailbox API resource for ticket-style customer interactions.

#### Tags

- Conversations
- Threads
- Tickets

#### Properties

- [Documentation](https://developer.helpscout.com/mailbox-api/)
- [API Reference](https://developer.helpscout.com/mailbox-api/endpoints/conversations/list/)
- [OpenAPI](openapi/helpscout-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/helpscout.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/helpscout.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Help Scout Threads API

Append customer replies, agent replies, internal notes, phone, chat, and forwards to an existing conversation as new threads.

#### Tags

- Threads
- Replies

#### Properties

- [Documentation](https://developer.helpscout.com/mailbox-api/endpoints/conversations/threads/)
- [Postman Collection](collections/helpscout.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/helpscout.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Help Scout Customers API

Manage customer profiles including addresses, emails, phone numbers, chat handles, social profiles, websites, and properties.

#### Tags

- Customers
- Contacts

#### Properties

- [Documentation](https://developer.helpscout.com/mailbox-api/endpoints/customers/list/)
- [Postman Collection](collections/helpscout.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/helpscout.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Help Scout Mailboxes API

Read mailbox / inbox configuration including routing settings, saved replies, custom fields, and folders.

#### Tags

- Mailboxes
- Inboxes

#### Properties

- [Documentation](https://developer.helpscout.com/mailbox-api/endpoints/mailboxes/list/)
- [Postman Collection](collections/helpscout.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/helpscout.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Help Scout Users API

Retrieve Help Scout user accounts (agents) including roles, permissions, and online/offline status.

#### Tags

- Users
- Agents

#### Properties

- [Documentation](https://developer.helpscout.com/mailbox-api/endpoints/users/list/)
- [Postman Collection](collections/helpscout.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/helpscout.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Help Scout Teams API

Manage teams that group users for routing and assignment within shared inboxes.

#### Tags

- Teams

#### Properties

- [Documentation](https://developer.helpscout.com/mailbox-api/endpoints/teams/list/)
- [Postman Collection](collections/helpscout.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/helpscout.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Help Scout Tags API

List, create, and apply tags to conversations for categorization, automation, and reporting.

#### Tags

- Tags
- Categorization

#### Properties

- [Documentation](https://developer.helpscout.com/mailbox-api/endpoints/tags/list/)
- [Postman Collection](collections/helpscout.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/helpscout.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Help Scout Workflows API

List automation workflows and trigger them manually against a conversation.

#### Tags

- Workflows
- Automation

#### Properties

- [Documentation](https://developer.helpscout.com/mailbox-api/endpoints/workflows/list/)
- [Postman Collection](collections/helpscout.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/helpscout.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Help Scout Custom Fields API

Read custom field definitions on inboxes and read / update custom field values on conversations.

#### Tags

- Custom Fields
- Metadata

#### Properties

- [Documentation](https://developer.helpscout.com/mailbox-api/endpoints/conversations/custom_fields/)
- [Postman Collection](collections/helpscout.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/helpscout.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Help Scout Attachments API

Upload and download attachment data for conversation threads.

#### Tags

- Attachments
- Files

#### Properties

- [Documentation](https://developer.helpscout.com/mailbox-api/endpoints/conversations/attachments/data/)
- [Postman Collection](collections/helpscout.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/helpscout.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Help Scout Ratings API

Read customer satisfaction ratings (great / okay / not good) attached to conversation threads.

#### Tags

- Ratings
- Happiness
- CSAT

#### Properties

- [Documentation](https://developer.helpscout.com/mailbox-api/endpoints/reports/happiness/)
- [Postman Collection](collections/helpscout.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/helpscout.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Help Scout Reports API

Aggregated reports across company performance, conversations, happiness ratings, productivity, and user/team statistics.

#### Tags

- Reports
- Analytics

#### Properties

- [Documentation](https://developer.helpscout.com/mailbox-api/endpoints/reports/)
- [Postman Collection](collections/helpscout.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/helpscout.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Help Scout Webhooks API

Subscribe to Help Scout events (convo.created, convo.assigned, convo.tag, customer.created, rating.received) for downstream automation. Webhooks include HMAC signatures for verification.

#### Tags

- Webhooks
- Events

#### Properties

- [Documentation](https://developer.helpscout.com/webhooks/)
- [AsyncAPI](asyncapi/helpscout-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/helpscout.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/helpscout.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Help Scout Docs API

Manage knowledge-base sites, collections, categories, articles, and search/related content for Help Scout Docs.

#### Tags

- Docs
- Knowledge Base
- Articles

#### Properties

- [Documentation](https://developer.helpscout.com/docs-api/)
- [Postman Collection](collections/helpscout.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/helpscout.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Help Scout Beacon API

Embed Beacon (live chat, help docs, customer portal) into web and mobile applications and pre-fill or update Beacon context via the Beacon JS API.

#### Tags

- Beacon
- Live Chat
- Embed

#### Properties

- [Documentation](https://developer.helpscout.com/beacon-2/)
- [Postman Collection](collections/helpscout.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/helpscout.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Help Scout Chat API

Read and write live chat conversations and messages alongside the email Mailbox API for unified ticketing.

#### Tags

- Chat
- Live Chat

#### Properties

- [Documentation](https://developer.helpscout.com/)
- [Postman Collection](collections/helpscout.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/helpscout.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Help Scout Apps API

Build sidebar applications that render custom content within the Help Scout Inbox UI for partner integrations.

#### Tags

- Apps
- Sidebar
- Marketplace

#### Properties

- [Documentation](https://developer.helpscout.com/apps/)
- [Postman Collection](collections/helpscout.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/helpscout.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/help-scout)
- [Website](https://www.helpscout.com/)
- [Documentation](https://developer.helpscout.com/)
- [API Reference](https://developer.helpscout.com/mailbox-api/)
- [Pricing](https://www.helpscout.com/pricing/)
- [Login](https://secure.helpscout.net/login/)
- [Status Page](https://status.helpscout.com/)
- [Blog](https://www.helpscout.com/blog/)
- [Support](https://support.helpscout.com/)
- [GitHub Organization](https://github.com/helpscout)
- [Privacy Policy](https://www.helpscout.com/company/legal/privacy/)
- [Terms of Service](https://www.helpscout.com/company/legal/terms-of-service/)
- [Authentication](https://developer.helpscout.com/mailbox-api/overview/authentication/)
- [Rate Limits](https://developer.helpscout.com/mailbox-api/overview/rate-limiting/)
- [Webhooks](https://developer.helpscout.com/webhooks/)
- [Plans](plans/helpscout-plans-pricing.yml)
- [Rate Limits](rate-limits/helpscout-rate-limits.yml)
- [Fin Ops](finops/helpscout-finops.yml)
- [Features](undefined)
- [L L Ms Txt](https://developer.helpscout.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
