# Help Scout (helpscout)

Help Scout is an email-first help desk platform with shared inboxes, live chat, knowledge bases, and a customer portal. The Help Scout APIs expose conversations, customers, inboxes, users, workflows, ratings, reports, Docs (knowledge base), Beacon (in-app messaging), and webhooks.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/helpscout/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=helpscout-api-evangelist&utm_content=repo)

## Type

- **x-type:** company

## Tags

Customer Support, Help Desk, Email, Live Chat, Knowledge Base, SaaS

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

| API | Tags |
|---|---|
| Help Scout Conversations API | Conversations, Threads, Tickets |
| Help Scout Threads API | Threads, Replies |
| Help Scout Customers API | Customers, Contacts |
| Help Scout Mailboxes API | Mailboxes, Inboxes |
| Help Scout Users API | Users, Agents |
| Help Scout Teams API | Teams |
| Help Scout Tags API | Tags, Categorization |
| Help Scout Workflows API | Workflows, Automation |
| Help Scout Custom Fields API | Custom Fields, Metadata |
| Help Scout Attachments API | Attachments, Files |
| Help Scout Ratings API | Ratings, Happiness, CSAT |
| Help Scout Reports API | Reports, Analytics |
| Help Scout Webhooks API | Webhooks, Events |
| Help Scout Docs API | Docs, Knowledge Base, Articles |
| Help Scout Beacon API | Beacon, Live Chat, Embed |
| Help Scout Chat API | Chat, Live Chat |
| Help Scout Apps API | Apps, Sidebar, Marketplace |

## Plans

- **Free:** up to 5 users, 1 inbox, 1 Docs site
- **Standard:** $25/user/month
- **Plus:** $45/user/month (popular)
- **Pro:** $75/user/month
- **AI Answers:** $0.75 per resolution
- **Add-ons:** additional inbox $10/mo, additional Docs site $20/mo
- 16% off annual billing

## Rate Limits

- **Account-shared per-minute** sliding window
- **Write multiplier:** POST/PUT/PATCH/DELETE count as 2 requests
- Headers: `X-RateLimit-Limit-Minute`, `X-RateLimit-Remaining-Minute`, `X-RateLimit-Retry-After`

## Common Properties

- [Website](https://www.helpscout.com/)
- [Documentation](https://developer.helpscout.com/)
- [API Reference](https://developer.helpscout.com/mailbox-api/)
- [Pricing](https://www.helpscout.com/pricing/)
- [Status](https://status.helpscout.com/)
- [Plans](plans/helpscout-plans-pricing.yml) — API Commons Plans 0.1
- [Rate Limits](rate-limits/helpscout-rate-limits.yml) — API Commons Rate Limits 0.1
- [FinOps](finops/helpscout-finops.yml) — FOCUS-aligned FinOps Framework 1.0

## Artifacts

| Artifact | Path |
|---|---|
| Plans | `plans/helpscout-plans-pricing.yml` |
| Rate Limits | `rate-limits/helpscout-rate-limits.yml` |
| FinOps | `finops/helpscout-finops.yml` |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
