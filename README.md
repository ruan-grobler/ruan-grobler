# Ruan Grobler

**I automate business processes and prove the impact.**

AI automation engineer in Cape Town, South Africa. I sit with the people who do the work, map what really happens, automate it end to end and measure what changed before anyone calls it done.

[Portfolio](https://portfolio.receva.co.za) · [Receva](https://receva.co.za) · [LinkedIn](https://www.linkedin.com/in/ruangrobler) · [ruan@receva.co.za](mailto:ruan@receva.co.za)

**Latest (21 Oct 2026):** v1.0 releases of the seven open source projects below, plus a [live eval report](https://ruan-grobler.github.io/voice-agent-evals/) for voice agent evals.

## What I build

- **Power Platform.** Power Automate flows with approvals, error handling and custom connectors. Dataverse data models with security roles. Model driven and canvas apps, Power Pages sites and PCF controls.
- **n8n.** Workflows on webhooks and APIs for follow ups, reminders, escalations and daily reports.
- **AI agents.** Claude API with structured outputs, MCP tool servers, and multi agent pipelines with a checker, a human approval step and evals that try to break them.
- **Voice AI.** Retell AI voice agents on Twilio numbers that answer calls, capture bookings and hand off to a person.

## Featured projects

| Project | What it automates | Result |
| --- | --- | --- |
| [**Lead to deal copilot**](https://github.com/ruan-grobler/lead-to-deal-copilot) | Leads from a web form, email or Slack become clean, deduplicated HubSpot deals that a person approves in Slack with one click. Slack, HubSpot and Claude, with fallbacks, retries and a dead letter replay | 25 synthetic leads through a HubSpot rate limit storm: 0 duplicate deals, 0 lost leads. 160 tests pass |
| [**n8n missed call recovery**](https://github.com/ruan-grobler/n8n-missed-call-recovery) | A free n8n kit that texts every missed caller a booking link, respects opt outs and quiet hours, and sends a daily report | A synthetic day of 40 missed calls: 32 links sent, 0 double texts, 0 texts after an opt out. 15 of 15 checks pass in real n8n in Docker |
| [**Voice agent evals**](https://github.com/ruan-grobler/voice-agent-evals) | Regression tests for AI receptionists: 15 caller scenarios, code checks plus an LLM judge, and a CI gate | On 15 scripted calls the weak prompt passes 0 and the fixed prompt passes 15, and the gate blocks the regression. 172 tests pass |
| [**Grounded answers**](https://github.com/ruan-grobler/grounded-answers) | A policy and SOP assistant over a fictional dental practice's documents: hybrid search with a vector store, a citation for every claim, and a refusal when the answer is not there | On a 50 question eval vs naive retrieval: personal data leaks 4 to 0 and must refuse questions 73% to 100%, every citation quote verified. Model answers are scripted for now, see the README |
| [**Campaign brief agent**](https://github.com/ruan-grobler/campaign-brief-agent) | Claude agents turn a marketing brief into an Asana ready launch plan. A checker attacks the plan and a person approves by exception | 5 of 5 synthetic briefs pass all 28 rubric checks, and a planted prompt injection is caught |
| [**Parallel browser MCP**](https://github.com/ruan-grobler/parallel-browser-mcp) | Gives AI agents many isolated browser sessions at once, so web tasks run side by side instead of one tab at a time | 8 slow pages: 22.9 s one at a time, 6.4 s with 4 sessions in parallel |
| [**Power Platform proof**](https://github.com/ruan-grobler/power-platform-proof) | A PCF control that turns a due date into a live SLA countdown, and a Power Pages site for a fictional clinic where patients request appointments with POPIA consent | 114 automated tests pass and both projects build clean |
| [**Receva**](https://receva.co.za) | AI voice receptionist for small hospitality and healthcare businesses, on Retell AI and Twilio | Live on a demo line. Product code is private |

## Stack

![Power Automate](https://img.shields.io/badge/Power%20Automate-0066FF?style=flat-square) ![Power Apps](https://img.shields.io/badge/Power%20Apps-742774?style=flat-square) ![Dataverse](https://img.shields.io/badge/Dataverse-107C10?style=flat-square) ![Power Pages](https://img.shields.io/badge/Power%20Pages-5C2D91?style=flat-square) ![Copilot Studio](https://img.shields.io/badge/Copilot%20Studio-0F6CBD?style=flat-square) ![SharePoint](https://img.shields.io/badge/SharePoint-038387?style=flat-square)

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white) ![Claude API](https://img.shields.io/badge/Claude%20API-D97757?style=flat-square&logo=claude&logoColor=white) ![MCP](https://img.shields.io/badge/MCP-1F2937?style=flat-square&logo=modelcontextprotocol&logoColor=white) ![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white) ![Retell AI](https://img.shields.io/badge/Retell%20AI-111827?style=flat-square) ![Twilio](https://img.shields.io/badge/Twilio-F22F46?style=flat-square)

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

## Credentials

- Microsoft Certified: Power Platform Fundamentals (PL-900)
- Microsoft Applied Skills: Power Automate, Canvas Apps and Copilot Studio
- Oracle Certified Agentic AI Foundations Associate ([badge](https://catalog-education.oracle.com/ords/certview/sharebadge?id=8FDCDFB116591E7F731F5A3AA1D814B0F74AC46920F5DBA8293C68CF6DFEED12))
- Oracle Cloud Infrastructure AI Foundations Associate
- AWS Agentic AI Demonstrated ([Credly](https://www.credly.com/badges/8bd5ef28-e5a1-4080-bd15-7b07cfc6e8f8/public_url))
- n8n Foundations ([badge](https://badges.n8n.io/f82106ec-b15b-4d07-ad75-3ced658be66b))

Microsoft credentials: [Microsoft Learn profile](https://learn.microsoft.com/en-us/users/ruangrobler-2295/)
