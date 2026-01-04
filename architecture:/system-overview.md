# System Overview (Client AI Lead Engine)

## Components
- **Lead Source** (form / webhook / inbox)
- **Make.com** (orchestration & routing)
- **LLM (OpenAI)** (intent + scoring)
- **Airtable** (data layer / CRM)
- **Notifications** (Slack / Email / SMS)

## Flow
Lead Source → Make.com → LLM Analysis → Airtable Update → Notifications
