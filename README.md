# 🧠 Cognitive-Economic Operating System (CRM + AI Intelligence Platform)

> **An enterprise-grade, AI-first CRM and business intelligence platform** built with ethical data practices,
> predictive analytics, and multi-agent AI orchestration — designed to replace fragmented toolchains
> with a single cognitive operating layer for revenue intelligence.

---

## 🎯 Built For Recruiters: Key Competency Signal Map

> This project demonstrates **production-level mastery** across the most in-demand roles at AI-forward companies.

| Competency | Demonstrated Skills |
|---|---|
| 🤖 **Prompt Engineering** | Structured JSON schema prompts, role-based personas, chain-of-thought decomposition, multi-constraint output generation |
| 📊 **Business Intelligence** | Predictive modeling, cohort analysis, SARIMAX forecasting, KPI dashboards, churn scoring |
| 🧩 **Systems Thinking** | Consent-first architecture, event-driven billing, multi-tenant identity, audit trail design |
| 🔗 **AI Integration** | LLM orchestration, agent toolchaining, web-augmented reasoning, vision model support |
| 🏗️ **Data Architecture** | JSON Schema entity modeling, real-time subscriptions, service role patterns, usage metering |
| 💳 **Payments & Monetization** | Stripe webhooks, usage-based billing, tiered subscriptions, add-on marketplace |
| 🔒 **Privacy & Compliance** | Consent management, GDPR-aligned audit trails, anonymized benchmarking, data filtering |
| 🤝 **CRM & Revenue Ops** | Lifecycle tracking, interaction analytics, LTV modeling, source attribution |

---

## 🚀 What Makes This Unlike Any Competing Platform

> Most CRMs track contacts. Most BI tools show charts. Most AI tools generate text.
> **This system does all three — coherently, ethically, and in real time.**

- ✅ **Consent-gated collective intelligence** — benchmarks only include clients who explicitly opted in, unlike Salesforce or HubSpot which have no such distinction

- ✅ **Actuarial-grade equation engine** — users define custom mathematical formulas; AI resolves variable values from live client data and solves them with confidence scores

- ✅ **AI agents with WhatsApp integration** — conversational AI that has live read/write access to your CRM entities, deployable over WhatsApp without custom infrastructure

- ✅ **Charge triggers tied to cognitive events** — billing isn't time-based, it's event-driven: exports, automation runs, history depth exceeded, execution variant unlocked

- ✅ **Built-in social impact accounting** — 30% of profits are auto-tracked and split across cancer research, open technology, and hunger relief; displayed in real time to all users

- ✅ **SARIMAX forecasting inside a CRM** — statistical time-series modeling (typically reserved for data science environments) is embedded directly into the client workflow

- ✅ **Multi-agent orchestration** — `clientCommunicator` and `quantAnalyst` agents operate independently with scoped entity access and tool-calling capabilities

- ✅ **Identity architecture separate from authentication** — `CustomerIdentity` entity provides immutable customer IDs decoupled from login sessions, enabling cross-channel tracking

---

## 🧠 Prompt Engineering: Techniques & Patterns

### 1. Role-Based Expert Persona Prompting

```text
"As an actuarial scientist with expertise in financial risk modeling,
analyze the following client data and generate a predictive equation..."
Assigns a domain-specific expert role to the LLM, dramatically improving the precision and vocabulary of outputs — a foundational prompt engineering technique for professional-grade AI outputs.

2. Structured JSON Schema Output Enforcement
response_json_schema: {
  type: "object",
  properties: {
    variables:           { type: "object" },
    steps:               { type: "array", items: { type: "string" } },
    result:              { type: "number" },
    confidence_score:    { type: "number", minimum: 0, maximum: 100 },
    insights:            { type: "string" },
    recommendations:     { type: "array", items: { type: "string" } },
    visualization_data:  { type: "object" }
  }
}
Forces deterministic, parseable AI outputs — eliminates hallucinated structure and enables direct database persistence without post-processing.

3. Chain-of-Thought Decomposition
Please perform the following steps in order:
  1. Identify variable values from the client data provided
  2. Solve the equation with full step-by-step reasoning
  3. Assign a confidence score from 0–100 with justification
  4. Generate 6 visualization data points across a time horizon
  5. Provide exactly 3 actionable business recommendations
Breaks complex tasks into ordered subtasks, improving accuracy and making AI reasoning auditable and explainable — critical for enterprise AI deployments.

4. Context-Injected Grounding
Client interaction history, outcomes, lifetime value, submission data, and custom fields are dynamically injected into prompts — grounding LLM outputs in actual business reality rather than generic responses.

5. Web-Augmented Reasoning
add_context_from_internet: true
Extends LLM knowledge beyond training cutoff by attaching live search results, enabling real-time market context and current industry benchmarks.

6. Multi-Modal AI (Vision + Web + Reasoning)
File URLs, uploaded images, and internet search can be combined in a single prompt — enabling compound intelligence tasks like analyzing uploaded financial statements alongside current market data.

📊 Business Intelligence & Advanced Analytics
1. Predictive Modeling
Churn Risk Score:
Risk = (1 - RecentInteractions/30) × (1 - PositiveOutcomes/TotalInteractions) × 100
Lifetime Value Projection:
LTV = CurrentLTV × (1 + AvgMonthlyGrowth × ProjectedMonths)
Revenue Forecast:
Forecast = BaseRevenue × (1 + GrowthRate)^Periods × SeasonalFactor
2. SARIMAX Time-Series Forecasting
Seasonal AutoRegressive Integrated Moving Average with eXogenous inputs — a statistical forecasting method typically used in data science pipelines, embedded directly inside the CRM workflow.

3. Cohort & Segmentation Analysis
Client lifecycle stage segmentation (lead → churned)

Acquisition source attribution (website, referral, advertising, events, cold outreach)

Interaction pattern clustering by type, direction, and outcome

Consent cohort separation (benchmark contributors vs. non-contributors)

4. Real-Time KPI Dashboards
Total revenue with period-over-period trend indicators

Active client count with growth rate

Average lifetime value across consented cohort

AI insight generation count and confidence distribution

5. Integration Intelligence & Sync Health
Salesforce and HubSpot coverage percentages (clients synced vs. total)

Staleness detection — flags records not synced within 48 hours

Health scoring: good / moderate / needs_attention

Automated sync recommendations surfaced in the UI

6. Consent-Filtered Benchmarking
Aggregate analytics only process data from clients with consent_benchmarks: true — ensuring collective intelligence is built on ethically sourced, explicitly consented data.

7. Interaction Outcome Intelligence
Sentiment distribution across all client touchpoints (positive/neutral/negative)

Outcome trends over time (7 / 30 / 90 day windows)

AI confidence scoring per insight (0–100)

Interaction-to-value attribution (monetary outcomes logged per interaction)

🏗️ Technical Architecture
Frontend Stack
React 18 with TypeScript — component-based UI architecture

Tailwind CSS + shadcn/ui — utility-first, accessible design system

React Query (@tanstack/react-query) — server state management with automatic cache invalidation

Recharts — composable chart library for all analytics visualizations

Framer Motion — production-quality animation and transition system

Backend Stack
Base44 BaaS — backend-as-a-service with entity management, auth, and integrations

Deno Runtime — secure, modern JavaScript/TypeScript serverless functions

Stripe API — checkout sessions, webhooks, subscription lifecycle management

Salesforce + HubSpot APIs — bidirectional CRM sync with OAuth connectors

Google Calendar API — event synchronization via OAuth app connector

Data Architecture
JSON Schema entity modeling — strict typed schemas for all domain objects

Real-time subscriptions — live entity change streams for reactive UI updates

Service role pattern — elevated admin operations separated from user-scoped access

Usage metering system — per-customer limits tracked across 8 dimensions

Immutable identity layer — CustomerIdentity entity decoupled from auth sessions

AI & Agent Architecture
InvokeLLM — structured LLM queries with JSON schema response enforcement

Web search augmentation — internet-grounded prompts via add_context_from_internet

Vision model support — file/image URLs passed directly to multimodal LLMs

clientCommunicator agent — conversational CRM agent with entity read/write access

quantAnalyst agent — data analysis agent for quantitative queries

WhatsApp integration — agents deployable over WhatsApp without custom infrastructure

🔒 Data Governance & Ethical AI
Consent Architecture
consent_insights — permission to run AI analysis on individual client data

consent_benchmarks — permission to include anonymized data in collective analytics

consent_communications — permission to send marketing and transactional emails

Audit Infrastructure
ConsentAudit entity logs every consent change with: previous value, new value, changed_by, reason, IP address, and timestamp

Immutable audit trail — records are append-only

Admin-only access to consent history

Privacy-Preserving Analytics
Benchmark analytics silently filter to consent_benchmarks: true clients only

No PII is exposed in collective reports

Each AI insight is scoped to the requesting user's data context

💳 Monetization & Event-Driven Billing
Subscription Tiers
Feature	Free	Pro ($19.99/mo)
Clients	Limited	Unlimited
AI Insights	Capped	Unlimited
Predictive Analytics	❌	✅
Integrations	❌	✅
Export	❌	✅
Automations	❌	✅
Charge Trigger Events
limit_reached — user hits a usage ceiling

export_requested — data export initiated

automation_enabled — scheduled task activated

execution_variant_unlocked — advanced AI mode accessed

history_depth_exceeded — client history beyond free tier window

time_threshold_reached — tenure-based charge event

Add-On Marketplace Categories
integration — connect additional external services

automation — scheduled workflows and triggers

storage — expanded data retention

collaboration — multi-user team access

intelligence — advanced AI model access

🌍 Social Impact Accounting
30% of platform profits are automatically tracked and allocated in real time:

🎗️ 10% → Cancer research initiatives

💻 10% → Open technology and public infrastructure

🌾 10% → Global hunger relief programs

Displayed live in the application header for full transparency to every user.

📐 Key Architectural Patterns
Consent-First Design — all collective analysis enforces consent_benchmarks before aggregating any data

Service Role Pattern — admin functions use elevated asServiceRole access, separated from user token scope

Mutation-Based State — React Query mutations invalidate caches automatically on write operations

Event-Driven Billing — ChargeTrigger entity decouples billing logic from business logic

Immutable Customer Identity — CustomerIdentity.customer_id is permanent and survives auth changes

Append-Only Audit Trails — ConsentAudit records are never modified, only appended

Webhook Signature Verification — Stripe webhooks verified with constructEventAsync before processing

Agent Tool Scoping — AI agents receive only the minimum entity permissions required for their function

🧩 Systems Thinking: Design Decisions That Scale
Why separate CustomerIdentity from User? Enables cross-channel identity resolution without coupling to authentication provider

Why filter benchmarks at the query level, not the display level? Ensures no accidentally exposed data even if UI logic fails

Why use JSON Schema for entities? Enables runtime validation, AI schema introspection, and auto-generated forms from a single source of truth

Why SARIMAX in a CRM? Revenue forecasting requires seasonal adjustment — simple linear regression produces misleading projections for businesses with cyclical patterns

Why event-driven billing over time-based? Aligns revenue capture with actual value delivery, not arbitrary time periods

https://benevolent-crm-98bd0543.base44.app

Built with Base44 · React 18 · Deno · Stripe · Tailwind CSS · shadcn/ui · Recharts · Framer Motion
