# Ruan Grobler

**Automation engineer in Cape Town.** I learn how a business process really runs, automate it with AI, and put a number on the impact in hours saved.

- **Daily stack:** Claude Code, Claude API, MCP, n8n, Python, TypeScript, Power Automate, SharePoint, Dataverse
- **Building:** multi-agent systems with human checkpoints, AI voice agents, document automation
- **Founder of [Receva](https://receva.co.za):** an AI voice receptionist for South African businesses
- **Portfolio:** [portfolio.receva.co.za](https://portfolio.receva.co.za)

## Selected work

| Project | What it does | Stack |
| --- | --- | --- |
| **Receva** | AI receptionist that answers calls, takes bookings and orders, and logs each one to a dashboard. Live demo desks on [receva.co.za](https://receva.co.za) | Retell, Twilio, n8n, Supabase |
| **Agent Pipeline** | Document triage on LangGraph. Classifier and extractor agents plus rule-based validator and router, under a supervisor that owns retry, escalation and graceful degradation. 267 tests. 26 of 26 routing decisions matched on a live Claude run over synthetic documents (code private, walkthrough on request) | Python, LangGraph, Claude API, pytest |
| **[DealFlow SQL](https://github.com/ruan-grobler/dealflow-sql)** | PostgreSQL deals database with 14 analysis queries, from joins to window functions. Reproducible in Docker with one command | PostgreSQL, Docker, Python |
| **AI engineering rig** | Custom subagents, MCP servers, hooks and scheduled agents that work overnight, with a separate agent that verifies the others | Claude Code, MCP |
| **In-house AI automations** | AI email intake, ticket logging and scanned document classification, live in production at a property group | Power Automate, AI Builder, SharePoint |

## How I work

1. Sit with the people who do the work and map what really happens
2. Measure it: how often, how long, where it breaks
3. Ship a small working version with a human approval step
4. Widen it once it is trusted, with failure alerts and a runbook so anyone can run it

**Contact:** [ruan@receva.co.za](mailto:ruan@receva.co.za)
