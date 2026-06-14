# Help Scout GraphQL Schema

## Overview

This conceptual GraphQL schema models the Help Scout customer support and help desk platform. It covers the full surface of the Help Scout Mailbox API v2, Docs API, Beacon API, and webhooks. The schema is derived from the REST API at `https://api.helpscout.net/v2` and the developer documentation at `https://developer.helpscout.com/mailbox-api/`.

Help Scout is an email-first help desk platform with shared inboxes, live chat, knowledge bases, and a customer portal. The GraphQL schema below provides a unified type graph over all resources: mailboxes, conversations, threads, customers, users, teams, tags, workflows, ratings, reports, Docs knowledge-base content, Beacon configurations, webhooks, and API credentials.

## Schema File

`helpscout-schema.graphql`

## Type Summary

| Domain | Types |
|---|---|
| Mailboxes | Mailbox, MailboxDetails, MailboxEmail, MailboxSettings, MailboxFolder, MailboxCustomField |
| Conversations | Conversation, ConversationDetails, ConversationStatus, ConversationType, ConversationSource, ConversationCustomField |
| Folders | Folder, FolderType |
| Threads | Thread, ThreadType, EmailThread, NoteThread, PhoneThread, ChatThread, ForwardThread, ThreadCustomer, ThreadAction, Attachment |
| Tasks | Task, TaskStatus |
| Customers | Customer, CustomerDetails, CustomerEmail, CustomerPhone, CustomerAddress, CustomerSocial, CustomerNotes, CustomerProperty |
| Tags | Tag, TagDetails |
| Users | User, UserDetails, UserRole |
| Teams | Team, TeamDetails, TeamMember |
| Ratings | Rating, RatingStar |
| Reports | ReportType, ConversationReport, HappinessReport, UserReport, ProductivityReport, TeamReport |
| Workflows | Workflow, WorkflowDetails, WorkflowCondition, WorkflowAction, WorkflowStatus |
| Reply Templates | ReplyTemplate, ReplyTemplateCategory |
| Saved Searches | SavedSearch |
| Custom Properties | CustomProperty, CustomPropertyType, CustomPropertyOption |
| Docs | DocsSite, DocsCollection, DocsCategory, DocsArticle, DocsAuthor, DocsSearchResult |
| Beacon | Beacon, BeaconDetails, BeaconConfig, BeaconMode |
| Webhooks | Webhook, WebhookEvent, WebhookEventType, WebhookSecret |
| Auth | APIKey, Token, OAuthApp |
| Pagination | PageInfo, ConversationConnection, CustomerConnection, UserConnection |
| Mutations | (see Query and Mutation types) |

Total named types: 65

## Authentication

The Help Scout API uses OAuth 2.0 Client Credentials flow. A token is obtained by posting client credentials to `https://api.helpscout.net/v2/oauth2/token`. All subsequent requests use a Bearer token in the Authorization header.

Reference: `https://developer.helpscout.com/mailbox-api/overview/authentication/`

## Rate Limits

Help Scout applies an account-shared rate limit. Write requests count double. Rate limit state is communicated via `X-RateLimit-Limit-Minute`, `X-RateLimit-Remaining-Minute`, and `Retry-After` headers.

Reference: `https://developer.helpscout.com/mailbox-api/overview/rate-limiting/`

## Resources

- Mailbox API Docs: https://developer.helpscout.com/mailbox-api/
- Docs API: https://developer.helpscout.com/docs-api/
- Beacon API: https://developer.helpscout.com/beacon-2/
- Webhooks: https://developer.helpscout.com/webhooks/
- GitHub: https://github.com/helpscout
