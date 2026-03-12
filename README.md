<div align="center">

# 🧠 BenevolentCRM
### Cognitive Economic Operating System — AI-Native CRM + Business Intelligence Platform

[![Built With React](https://img.shields.io/badge/Built%20With-React%2018-61DAFB?style=for-the-badge&logo=react)](https://react.dev)
[![AI Powered](https://img.shields.io/badge/AI-Multi--Agent%20LLM-8B5CF6?style=for-the-badge&logo=openai)](/)
[![Business Intelligence](https://img.shields.io/badge/BI-Predictive%20Analytics-059669?style=for-the-badge&logo=chartdotjs)](/)
[![Spreadsheet Engine](https://img.shields.io/badge/Exports-Excel%20%2B%20Formulas-1D6F42?style=for-the-badge&logo=microsoftexcel)](/)
[![Stripe](https://img.shields.io/badge/Billing-Stripe%20Integrated-635BFF?style=for-the-badge&logo=stripe)](/)
[![License](https://img.shields.io/badge/License-MIT-F59E0B?style=for-the-badge)](/)

<br/>

> **BenevolentCRM is not a standard CRM.**
> It is a self-generating, AI-native cognitive operating system that converts raw relationship data into
> predictive intelligence, professional business assets, and revenue-grade spreadsheet products —
> automatically, at every layer of the stack.

</div>

---

## 🔑 Why This Project Is Unlike Any Other CRM

<br/>

Most CRMs store contacts. BenevolentCRM **thinks, forecasts, generates, and self-heals.**

<br/>

| Dimension | Traditional CRM | BenevolentCRM |
|---|---|---|
| 🧩 Architecture | CRUD data store | Cognitive Operating System with identity, consent, and billing layers |
| 🤖 AI Role | Chatbot or tag suggestion | Multi-agent orchestration (clientCommunicator + quantAnalyst) with structured LLM output |
| 📊 Analytics | Pre-built dashboards | Custom equation engine, LTV modeling, churn scoring, SARIMAX forecasting |
| 📁 Exports | CSV download | Excel workbooks with live formulas, named input variables, and 4 structured sheets |
| 🏢 Data | One user's clients | 15 synthetic practice companies with full financial datasets auto-generated |
| 🔐 Identity | Auth login = identity | Immutable `CustomerIdentity` layer separate from authentication |
| 🩺 Health | Manual checks | Self-healing 8-layer diagnostic system with 10-minute auto-refresh and repair history |
| ♻️ Revenue Ethics | No donation model | 30% of profits auto-routed to cancer research, open technology, and ending hunger |

---

## 🎯 Recruiter-Facing Skills Index

> **Target Roles:** Prompt Engineer · AI Product Manager · BI Analyst · Data Scientist · AI Solutions Architect · LLM Applications Developer · Revenue Intelligence Analyst

<br/>

### 🟣 Prompt Engineering & LLM Architecture

<br/>

- **Structured prompt design** — every AI agent call uses `response_json_schema` to force typed, parseable LLM output rather than free-form text

- **Multi-agent orchestration** — `clientCommunicator` handles relationship intelligence; `quantAnalyst` handles quantitative modeling; both are independently deployable and subscribable in real time

- **Context injection** — entity data (client profiles, interaction history, business metrics) is passed directly into LLM prompts to generate grounded, non-hallucinated insights

- **Confidence scoring** — every AI-generated insight includes an `ai_confidence` field (0–100) stored in the `Interaction` entity for auditability

- **System-level prompt architecture** — agents operate on a persistent `conversation` object model with streaming subscription (`subscribeToConversation`) for live token delivery to the UI

- **Schema-constrained output** — all LLM calls enforce a root `object` JSON schema, preventing malformed responses from breaking downstream business logic

- **Grounded web retrieval** — `add_context_from_internet: true` enables real-time Google Search + Maps context injection into analytical prompts

<br/>

---

### 🔵 Business Intelligence & Advanced Data Analytics

<br/>

- **Predictive analytics engine** — `AnalyticsReport` entity supports `ltv_prediction`, `churn_risk`, `revenue_forecast`, and `custom_equation` report types with stored results and visualization data

- **Custom equation solver** — users compose mathematical formulas using named variables; the system evaluates them and returns computed results with confidence scores and AI-generated narrative insights

- **SARIMAX forecasting reference architecture** — system health monitor validates the availability of the SARIMAX forecasting model layer, designed for seasonal time-series revenue forecasting

- **KPI dashboard design system** — executive-grade dashboards built to a strict professional spec: Navy `#1e3a5f` primary, Teal `#2a7c6f` accent, green for positive variance, red for negative variance, no 3D or pie charts

- **Stacked bar composition charts** — revenue composition by quarter (Product / Services / Recurring) and pipeline composition by stage (Lead → Negotiation) over 6-month rolling windows

- **Variance indicators** — every KPI plate shows `▲ +n%` in green or `▼ -n%` in red against prior period, computed dynamically

- **Multi-company synthetic dataset** — 15 practice companies spanning SaaS, Manufacturing, Retail, Healthcare, Finance, EdTech, Logistics, Energy, Real Estate, Analytics, Legal, Hospitality, and E-commerce — each with 12-month revenue arrays, expense ratios, pipeline distributions, NPS, churn, and revenue breakdowns

- **Deterministic data generation** — monthly revenue computed via a seasonal multiplier model (`[0.86 → 1.16]`) combined with a deterministic noise function seeded per company, producing repeatable but realistic financial trajectories

- **Sellability scoring engine** — templates are evaluated against a design quality rubric (visual hierarchy, typography, color consistency, chart appropriateness) and scored 0–100 before export

<br/>

---

### 🟢 Excel Automation & Spreadsheet Intelligence

<br/>

- **Formula workbooks** — every Excel export includes live formulas: `=SUM(B5:M5)`, `=AVERAGE(B5:M5)`, `=(M5-B5)/B5` (YOY Growth), `=D4*(E4/100)` (Weighted Pipeline Value)

- **Input Variables sheet** — each workbook has a dedicated `INPUTS` sheet with named cells for Company Name, Growth Target, Margin Target, Discount Rate, Tax Rate, and Working Capital Days — all other sheets reference these cells

- **4-sheet workbook architecture:**
  - `INPUTS` — editable assumption variables
  - `REVENUE DATA` — 12-month actuals with formula row totals and YOY growth
  - `KPI SUMMARY` — dashboard with `%` share formulas and status indicators
  - `PIPELINE` — deal table with `=Value × (Probability/100)` weighted value column

- **Template types:** Executive KPI Dashboard · Sales Pipeline Tracker · Project Tracker · Financial Summary Sheet

- **Template Packs:** Startup Founder · Sales Growth · Agency Operations · Small Business Finance · Creator Business

<br/>

---

### ⚙️ Systems Thinking & Architecture

<br/>

- **Cognitive OS layering** — the system is explicitly designed as a 10-level paradigm engine with distinct layers for identity, consent, data, analytics, agents, billing, and export

- **Immutable identity architecture** — `CustomerIdentity` is decoupled from authentication, supporting identity levels: `anonymous → verified → authenticated → validated`

- **Consent-based analytics** — `consent_benchmarks: true` is a hard gate on all anonymized benchmark queries; `ConsentAudit` logs every consent change with IP, timestamp, actor, and reason

- **Event-driven billing** — `ChargeTrigger` entity fires on business facts: `limit_reached`, `export_requested`, `automation_enabled`, `execution_variant_unlocked`, `history_depth_exceeded`

- **Self-healing diagnostics** — `SystemHealth` page runs 8 parallel module checks on load, every 10 minutes automatically, and on demand; persists each run as a `SystemDiagnostic` record with status, issues, repairs, duration, and trigger type

- **Real-time subscriptions** — entity changes are streamed via `base44.entities.X.subscribe()` for live UI updates without polling

- **Modular backend functions** — Deno-deployed serverless handlers for: Stripe webhooks, CSV import/export, Google Calendar sync, HubSpot sync, Salesforce sync, predictive analytics, time-series analysis, equation solving, and Excel generation

<br/>

---

## 🏗️ Full Feature Map

<br/>

### 👥 CRM Core

<br/>

- `ClientProfile` — full lifecycle tracking: `lead → prospect → active → inactive → churned`

- `Interaction` — logs calls, emails, meetings, purchases, support, tasks with direction, outcome, value, duration, and AI insight

- `AdvancedSearch` — combines text search with dynamic entity-specific filters; active filter badges for interactive refinement

- Bulk actions — multi-select client operations with status updates and export

- Custom fields — `OrganizationSettings.custom_schema` allows admin-defined field schemas per deployment

<br/>

---

### 🤖 AI Agents

<br/>

- **clientCommunicator** — conversational agent with access to `ClientProfile` (CRUD) and `Interaction` (read); deployable via WhatsApp for async client management

- **quantAnalyst** — analytical agent with `AnalyticsReport` (CRUD) and `ClientDataSubmission` (read); solves equations, generates forecasts, produces narrative summaries

- **AgentChat UI** — full streaming chat interface with tool-call visualization, expandable function result panels, Markdown rendering, and code block copy

<br/>

---

### 📊 Analytics & Intelligence

<br/>

- Revenue trend area charts with gradient fill

- Client status donut charts (lead / prospect / active / inactive / churned)

- Data Mirror — raw entity explorer with visual schema inspection

- Integration Insights — cross-platform data health and sync status visualization

- Quantitative Analysis — equation builder with variable inputs, result visualization, and LLM-generated interpretation

- LTV prediction, churn risk, revenue forecast report types stored as structured entity records

<br/>

---

### 🩺 System Health Monitor

<br/>

- 8 parallel module checks: Entity Schema · AI Agents · Consent Architecture · Analytics Pipeline · Stripe Billing · CRM Identity Layer · Forecasting Engine · Spreadsheet Factory

- Auto-refresh every 10 minutes with countdown progress bar

- Per-module drilldown with individual issue lists

- Aggregated issues summary panel with red/amber/green status banners

- Full diagnostic history log with run time, duration, trigger type, and issue count

<br/>

---

### 💳 Billing & Monetization

<br/>

- Stripe Checkout integration with `free` and `pro` tiers

- `Subscription` entity tracks `stripe_customer_id`, `stripe_subscription_id`, status, period end, and add-ons

- `AddOn` marketplace: integration · automation · storage · collaboration · intelligence categories

- `UpgradeIntent` captures failed conversions with email, intended tier, desired add-ons, and potential MRR for win-back campaigns

- Stripe webhook handler with `constructEventAsync` for Deno async crypto compatibility

<br/>

---

## 🛠️ Tech Stack

<br/>

| Layer | Technology |
|---|---|
| Frontend | React 18, Tailwind CSS, Framer Motion, shadcn/ui |
| Charts | Recharts (Line, Bar, Stacked Bar, Area, Pie) |
| AI / LLM | Base44 InvokeLLM (multi-model: GPT-4o, Claude Sonnet, Gemini Pro) |
| Agents | Base44 Agents SDK with real-time streaming |
| Backend | Deno serverless functions (deployed via Base44) |
| Database | Base44 entity layer (NoSQL with JSON schema enforcement) |
| Billing | Stripe (Checkout, Webhooks, Subscriptions, Products) |
| Export | xlsx library — formula workbooks, multi-sheet |
| Auth | Base44 platform auth with role-based access control |
| Integrations | Salesforce, HubSpot, Google Calendar (OAuth app connectors) |

<br/>

---

## 🚀 Getting Started

<br/>

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/benevolent-crm.git

# Install dependencies
npm install

# Set required environment variables
# STRIPE_SECRET_KEY
# STRIPE_PUBLISHABLE_KEY
# STRIPE_WEBHOOK_SECRET

# Start development server
npm run dev
<br/>
📁 Project Structure
<br/>
├── pages/                   # Route-level React components (flat, no nesting)
│   ├── Dashboard.jsx        # CRM overview with KPIs and charts
│   ├── Clients.jsx          # Client management with advanced search
│   ├── DataStudio.jsx       # Synthetic data generation pipeline
│   ├── TemplateStudio.jsx   # Spreadsheet template preview + export
│   ├── CompanyTemplates.jsx # 15-company Excel workbook generator
│   ├── SystemHealth.jsx     # 8-layer self-healing diagnostic monitor
│   ├── QuantitativeAnalysis.jsx  # Equation solver + forecasting
│   └── AgentChat.jsx        # Multi-agent AI conversation UI
│
├── components/
│   ├── templates/previews/  # KPIDashboard, SalesPipeline, FinancialSummary, ProjectTracker
│   ├── studio/              # companyData.js (15 synthetic companies), seedData.js
│   └── layout/              # Sidebar, DonationBanner
│
├── entities/                # JSON schema definitions (25+ entities)
├── functions/               # Deno serverless handlers
├── agents/                  # AI agent configuration files
└── Layout.js                # App shell with nav, user menu, donation banner
<br/>
🌍 Charitable Architecture
<br/>
BenevolentCRM is built on an ethical revenue model: 30% of net profits are automatically routed to three causes.

<br/>
🎗️ 10% → Cancer research

💻 10% → Open technology & digital equity

🌾 10% → Ending world hunger

<br/>
These are not optional features — they are embedded directly in OrganizationSettings as tracked fields (donation_cancer_research, donation_open_tech, donation_hunger) and surfaced in the donation banner on every page.

<br/>
📌 ATS Keyword Index
<br/>
Prompt Engineering · Large Language Models · LLM · Generative AI · Multi-Agent Systems · AI Orchestration · Business Intelligence · Predictive Analytics · Customer Lifetime Value · Churn Prediction · Revenue Forecasting · Time Series Analysis · SARIMAX · KPI Dashboards · Data Visualization · Synthetic Data Generation · ETL · Excel Automation · Spreadsheet Design · CRM · Event-Driven Architecture · Consent Management · GDPR · Stripe API · Webhook Integration · Salesforce · HubSpot · React · TypeScript · REST APIs · Serverless Functions · Deno · SaaS · Product Development · System Architecture · Cognitive Computing · NLP · AI Insights · Confidence Scoring · Data Modeling · Identity Architecture

<br/>
<div align="center">
Built with intention. Powered by AI. Designed for impact.

BenevolentCRM — Where cognitive architecture meets commercial intelligence.

https://benevolent-crm-98bd0543.base44.app/

</div> ```
