# Neoll Labs AI — Enterprise Autonomous Platform Documentation

Welcome to the central documentation hub for **Neoll Labs AI**, an autonomous software factory and multi-agent operations platform built on **Hermes Agent**, **Paperclip AI**, **Vercel Infrastructure**, and **Telegram Community Governance**.

---

## Architecture Overview

```text
┌─────────────────────────────────────────────────────────────┐
│                 NEOLL LABS TECH HOLDINGS                    │
│                 Founder & Group CTO: Nelson Lourenço        │
└──────────────┬──────────────────────────────┬───────────────┘
               │                              │
               ▼                              ▼
    ┌────────────────────┐         ┌────────────────────┐
    │  HERMES MULTI-BOT  │         │  PAPERCLIP CONTROL │
    │  OPERATIONS ENGINE │         │  PLANE & RUNNER    │
    │  • Marco (Sales)   │         │  • 5 Companies     │
    │  • Elena (PO)      │         │  • Embedded PG DB  │
    │  • Sofia (Legal)   │         │  • Spend & Budgets │
    │  • Pedro (Ops)     │         │  • Issue Ingestion │
    └──────────┬─────────┘         └──────────┬─────────┘
               │                              │
               └──────────────┬───────────────┘
                              │
                              ▼
    ┌─────────────────────────────────────────────────────────┐
    │            TELEGRAM COMMUNITY (Neoll-Labs.tlg)          │
    │  • Topic #1:  Geral / HQ (@PedroAlmeidaBot)             │
    │  • Topic #53: Globex Corp (@globexcorp_bot)             │
    │  • Topic #55: Eco Swimming Pool (@LuisLusoBot)          │
    │  • Topic #58: Tertul-IA (@jaime_botas_bot)              │
    │  • Topic #62: Chat2App (@BrozisBot)                     │
    └─────────────────────────┬───────────────────────────────┘
                              │
                              ▼
    ┌─────────────────────────────────────────────────────────┐
    │         VERCEL DUAL-TIER INFRASTRUCTURE                 │
    │  • Staging Preview: Floating feedback & chat banner     │
    │  • Approval Gate: Client/Sales button sign-off required │
    │  • Production: Clean, high-performance web applications│
    └─────────────────────────────────────────────────────────┘
```

---

## Core Platform Components

### 1. Paperclip Control Plane
- **Location**: `C:\Users\ai\ao\paperclip\`
- **Database**: Embedded PostgreSQL on port `54329` with automated hourly/daily backups.
- **REST API**: Running on `http://127.0.0.1:3100` (`/api/companies`, `/api/companies/<id>/issues`).
- **Companies**:
  - `neoll-labs-tech`: Parent holding company aggregating all IT & AI ventures.
  - `chat2app`: Chat-driven autonomous app factory.
  - `globex-corp`: Autonomous cloud migration architecture.
  - `eco-swimming-pool`: Sustainable pool tech e-commerce (software provided by neoll-labs.com).
  - `tertul-ia`: AI intellectual salons and community hub (software provided by neoll-labs.com).

### 2. Hermes Multi-Agent Squad
- **Marco Silva (`sales-lead` / `@BrozisBot`)**: Client partner, qualification, commercial terms, and staging review sign-offs.
- **Elena Rostova (`pool-pm`)**: Product Owner, feature tickets, user stories, and staging review gates.
- **Sofia Sterling (`legal-counsel`)**: General legal counsel, Mutual NDAs, SOWs, IP governance, and GDPR compliance.
- **Pedro Almeida (`it-lead` / `@PedroAlmeidaBot`)**: VP Operations & Infrastructure, Vercel deployment hooks, Paperclip governance.
- **Luís Luso (`pool-salesops` / `@LuisLusoBot`)**: Product & commercial partner for Eco Swimming Pool.
- **Jaime Botas (`aicom-online` / `@jaime_botas_bot`)**: Community host & AI evangelist for Tertul-IA.

### 3. Boston / Specialized Skills Catalog
- `multi-channel-sales-factory`: Inverted channel-first workflow, staging preview deployments, and 45-second hot-fix micro-loops.
- `collabsquad-product-spec`: Specification for autonomous multi-agent software factory squads.
- `legal-adviser`: Contract reviews, IP assignment clauses, and compliance.
- `paperclip-orchestrator`: Management and background supervision of local Paperclip runners.
- `telegram-forum-management`: Automated supergroup topic creation and bridge routing.

### 4. Vercel Staging-First Pipeline
1. Pushes to `staging` auto-deploy to **Vercel Staging preview** with active feedback banner.
2. In chat, the bot delivers the preview link with inline decision buttons:
   - `[ ✅ Approve & Ship to Prod ]`
   - `[ ✏️ Request Feature Fix ]`
   - `[ ⚡ Tweak Numbers & Copy ]`
3. Clicks trigger a 45-second hot-fix loop or promote to **Vercel Production** (`*.neoll-labs.com`).

### 5. Automated Disaster Recovery
- Daily cron job runs at 03:00 UTC via `backup_hermes.py`.
- Permanently captures all Hermes databases (`state.db`, `memory_store.db`, `kanban.db`), Paperclip company YAMLs, and PostgreSQL database dumps (`*.sql.gz`) into versioned ZIP archives.
