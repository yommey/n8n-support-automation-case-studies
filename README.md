# Support Automation — Project Case Studies

**n8n · OpenAI · APIs · webhooks · JavaScript · data validation · human escalation**

This repository describes automation and operational workflows from my CV, focused on collecting reliable inputs, routing work accurately and preserving human oversight.

> **Evidence status:** These are explanatory case studies, not exported n8n workflows or independent proof of production deployment. Sanitized exports and reproducible demonstrations may be added after ownership and security review.

## Projects

| Case study | Problem addressed | Skills |
| --- | --- | --- |
| [JANE — AI Customer Support Agent](JANE_AI_SUPPORT_CASE_STUDY.md) | Routed support conversations across Telegram and live chat | n8n, OpenAI, conversation context, safeguards, escalation |
| [Lead-to-Appointment Automation](LEAD_TO_APPOINTMENT_CASE_STUDY.md) | Manual intake, qualification and scheduling | Jotform, JavaScript, Sheets, Calendar, Gmail |
| [Manchester AI Weather Assistant](MANCHESTER_WEATHER_CASE_STUDY.md) | Grounding AI answers in validated weather data | Open-Meteo API, n8n, JavaScript, validation |

## Relevance to technical customer support

- **Triage:** classify incoming requests and route them to the right next step.
- **Data integrity:** avoid malformed records, duplicates and incomplete API responses.
- **Customer communication:** acknowledge requests and respond through the correct channel.
- **Escalation:** preserve human review for sensitive or consequential decisions.
- **Testing:** make failures understandable and reproducible.

Read the [Security and Evidence Checklist](SECURITY_AND_EVIDENCE_CHECKLIST.md) before publishing exports or screenshots.

For runnable SQL investigations, see [Billing Support SQL Lab](https://github.com/yommey/billing-support-sql-lab).
