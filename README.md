# AI Sustainability Consulting Firm

> **A complete AI sustainability consulting firm at your fingertips** — from Scope 3 data detectives to EPR compliance architects, net zero roadmap builders to greenwashing auditors. 38 specialist agents across 8 practice areas. Each one knows the GHG Protocol cold, cites the right regulation, and won't let a claim go unsubstantiated.

[![GitHub stars](https://img.shields.io/github/stars/MikeTannenbaum/ai-sustainability-consulting?style=social)](https://github.com/MikeTannenbaum/ai-sustainability-consulting)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://makeapullrequest.com)
[![Forked from](https://img.shields.io/badge/Forked%20from-msitarzewski%2Fagency--agents-blue)](https://github.com/msitarzewski/agency-agents)

---

## What Is This?

**AI Sustainability Consulting** is a complete collection of AI agent personas for sustainability, ESG, and climate work — built on the same agent architecture as [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents), adapted from a digital agency into a sustainability consulting firm of the caliber of Anthesis, ERM, BSR, Quantis, and Ramboll.

Each agent is:

- **Technically grounded**: Real frameworks — GHG Protocol, ESRS, SBTi, TCFD, TNFD, ISO 14040, FTC Green Guides
- **Regulation-specific**: Cites the right law, provision, and version — not vague references to "ESG frameworks"
- **Deliverable-focused**: Produces actual outputs — GHG inventories, CDP responses, CSRD disclosures, supplier codes of conduct, board briefings
- **Greenwashing-resistant**: Every external claim goes through the Greenwashing Auditor before it leaves the building
- **Orchestrated**: MERIDIAN coordinates the full consulting engagement — from intake through final disclosure

**Think of it as**: A sustainability consulting team that never sleeps, cites its sources, and refuses to let unsubstantiated claims go public.

---

## Quick Start

### Option 1: Claude Code (Recommended)

```bash
# Clone the repo
git clone https://github.com/MikeTannenbaum/ai-sustainability-consulting.git

# Install all agents to Claude Code
cd ai-sustainability-consulting
./scripts/install.sh --tool claude-code
```

Then in Claude Code:

```
/agents
```

Select any specialist agent to begin. For a full consulting engagement, start with MERIDIAN Orchestrator.

### Option 2: Manual Installation

Copy any agent `.md` file from the division directories into `~/.claude/agents/`. Each file is a self-contained agent persona — no dependencies.

### Option 3: Other AI Tools

```bash
# Convert for your preferred tool
./scripts/convert.sh --tool cursor    # Cursor rules
./scripts/convert.sh --tool windsurf  # Windsurf rules
./scripts/convert.sh --tool gemini-cli # Gemini CLI
./scripts/convert.sh --tool aider     # Aider CONVENTIONS.md
./scripts/convert.sh --tool all       # All tools
```

---

## The Agent Roster

### 🌡️ Climate Division (`climate/`)

| Agent | What They Do |
|---|---|
| **GHG Inventory Specialist** | Scope 1/2/3 accounting per GHG Protocol; activity data collection; emission factor selection; verification prep |
| **Science-Based Targets Advisor** | SBTi near-term (1.5°C) and net zero targets; FLAG, SBTN, SBTi validation pathway |
| **Net Zero Strategist** | Decarbonization roadmap design; MACC analysis; residual emissions strategy; interim milestones |
| **Carbon Markets Analyst** | VCM and compliance market navigation; credit quality (ICVCM CCPs); VCMI claims code; carbon pricing exposure |
| **Climate Risk Analyst** | TCFD 4-pillar disclosure; NGFS/IEA scenario analysis; physical and transition risk quantification; ISSB S2 |

### ⚖️ Compliance Division (`compliance/`)

| Agent | What They Do |
|---|---|
| **EPR Specialist** | CA SB 54, OR HB 2592, EU PPWR, PRO registration, eco-modulation fee calculation, How2Recycle |
| **CSRD Advisor** | All 12 ESRS standards, double materiality methodology, IRO identification, XBRL tagging, assurance |
| **EU Taxonomy Analyst** | Technical screening criteria, DNSH assessment, MSS verification, Article 8 KPIs (turnover/capex/opex) |
| **SEC Climate Expert** | CA SB 253/261, SEC Rule 33-11275, filer category thresholds, Scope 3 safe harbor, comment letter patterns |
| **Permit Navigator** | NEPA/EIS/EA/CE, Clean Air Act Title V/PSD/NSR, Section 404, RCRA, EJScreen, climate permitting |

### 📊 Reporting Division (`reporting/`)

| Agent | What They Do |
|---|---|
| **ESG Report Writer** | GRI Standards, ISSB IFRS S1/S2, SASB industry standards, integrated reporting (IIRC <IR> Framework) |
| **CDP Specialist** | CDP Climate/Water/Forests questionnaire completion; A-list scoring strategy; year-over-year score improvement |
| **Materiality Facilitator** | Financial, impact, and double materiality; IRO identification; stakeholder surveys; ESRS DMA methodology |
| **ESG Data Analyst** | Data collection architecture, DQS scoring, assurance readiness (ISAE 3000), XBRL, ESG platform selection |

### ⚡ Energy & Resources Division (`energy-resources/`)

| Agent | What They Do |
|---|---|
| **Energy Efficiency Auditor** | ASHRAE Level 1/2/3 audits, ISO 50001, EnergyPlus/eQUEST modeling, ECMs, EUI benchmarking, ENERGY STAR |
| **Renewable Energy Advisor** | Physical/virtual PPAs, RECs/GOs, GHG Protocol Scope 2 guidance, 24/7 CFE, RE100 pathway |
| **Circular Economy Strategist** | 10-R hierarchy, Ellen MacArthur principles, design for circularity, MFA, circular business model design |
| **Water & Waste Specialist** | WRI Aqueduct, AWS Standard, CDP Water, GRI 303/306, RCRA, zero waste strategy, TRUE certification |

### 🚚 Supply Chain Division (`supply-chain/`)

| Agent | What They Do |
|---|---|
| **Scope 3 Analyst** | All 15 GHG Protocol Scope 3 categories; spend-based, hybrid, and activity-based methodologies; EEIO |
| **LCA Specialist** | ISO 14040/44 full LCA, ISO 14067 PCF, ReCiPe/CML impact methods, SimaPro/OpenLCA, EPD development |
| **Supplier Engagement Specialist** | EcoVadis, CDP Supply Chain, SBTi supplier engagement targets, supplier questionnaire design, capacity building |
| **Human Rights Advisor** | UNGPs, OECD 6-step due diligence, CSDDD Directive 2024/1760, LkSG, UFLPA, ILO core conventions |

### 🌿 Nature & Biodiversity Division (`nature-biodiversity/`)

| Agent | What They Do |
|---|---|
| **TNFD Strategist** | TNFD v1.0 LEAP approach, 14 recommended disclosures, 8 core metrics, SBTN 5-step, GBF Target 15, IBAT |
| **Nature-Based Solutions Advisor** | IUCN Global Standard, REDD+/IFM/ARR methodologies, blue carbon, soil carbon, Oxford Principles, ISO 14068 |
| **Land Use Analyst** | EUDR (Regulation 2023/1115), HCS/HCV methodology, NDPE, high-risk commodity sourcing, Satelligence, Trase |

### 🎯 Strategy & Engagement Division (`strategy-engagement/`)

| Agent | What They Do |
|---|---|
| **Sustainability Strategy Advisor** | Materiality-to-strategy bridge, board governance, ESG integration, sustainability KPI design, ESG rating improvement |
| **Stakeholder Specialist** | Stakeholder mapping and prioritization, FPIC methodology, AA1000 SES, UNGPs Pillar 3, grievance mechanisms |
| **Impact Analyst** | Theory of change, IRIS+ metrics, SROI methodology, SDG mapping, BVCM distinction from compliance offsetting |
| **Greenwashing Auditor** | FTC Green Guides, EU Green Claims Directive, ISO 14021, VCMI Claims Code, SEC enforcement — the last line of defense |

### 🔧 Specialized Division (`specialized/`)

| Agent | What They Do |
|---|---|
| **MERIDIAN Orchestrator** | Full engagement coordination across all phases — Intake → Baseline → Materiality → Strategy → Disclosure |
| **Sustainability Data Consolidator** | Multi-entity consolidation, GHG Protocol boundary approaches, M&A handling, restatements, assurance package prep |
| **Client Deliverable Generator** | Audience-specific outputs for Board/CFO/CSO/Legal/Investors/Comms — without losing technical accuracy |

---

## MERIDIAN — The Engagement Operating System

**MERIDIAN** (Multi-domain Expert Routing for Integrated Disclosure, Analysis, and Net-zero Impact) coordinates the full sustainability consulting engagement. It is not just an orchestration prompt — it is a **deployment doctrine** that defines:

- **5-phase engagement model**: Intake → Baseline Assessment → Materiality → Strategy & Roadmap → Disclosure & Reporting
- **Quality gates** between every phase — no phase advances without documented evidence
- **Agent spawning logic** — which agents activate in which sequence based on engagement type
- **Handoff protocols** — structured context transfer so no agent starts cold
- **Greenwashing firewall** — Greenwashing Auditor clearance required before any external deliverable

### MERIDIAN Engagement Modes

| Mode | Use Case | Phases | Agents |
|---|---|---|---|
| **MERIDIAN-Full** | Complete sustainability engagement (GHG inventory → CSRD disclosure) | All 5 | 20–32 |
| **MERIDIAN-Sprint** | Single-focus engagement (e.g., SBTi target setting, CDP submission) | 2–3 | 8–15 |
| **MERIDIAN-Micro** | Specific deliverable (e.g., board briefing, greenwashing audit) | 1 | 2–5 |

### Activate MERIDIAN-Full

```
Activate MERIDIAN Orchestrator in Full Engagement mode.

Client: [COMPANY NAME]
Sector: [INDUSTRY / GICS SECTOR]
Regulatory jurisdiction: [EU / US / UK / Global]
Trigger: [CSRD in scope / SBTi commitment / Investor request / Proactive]
Known priorities: [e.g., GHG inventory + SBTi target + CDP A-list]

Execute complete MERIDIAN engagement:
- Phase 0: Intake & scoping (MERIDIAN Orchestrator)
- Phase 1: Baseline assessment (GHG Inventory Specialist, ESG Data Analyst, Scope 3 Analyst)
- Phase 2: Materiality (Materiality Facilitator, CSRD Advisor, Climate Risk Analyst)
- Phase 3: Strategy & roadmap (Net Zero Strategist, Science-Based Targets Advisor, Sustainability Strategy Advisor)
- Phase 4: Disclosure & reporting (ESG Report Writer, CDP Specialist, Client Deliverable Generator, Greenwashing Auditor)

Quality gates between every phase. Greenwashing Auditor clearance required for all external deliverables.
```

---

## The Strategy Layer

| Document | Purpose | Location |
|---|---|---|
| **MERIDIAN Master Doctrine** | Complete engagement playbook | `strategy/meridian-strategy.md` |
| **Phase 0: Intake & Scoping** | Client intake, regulatory trigger assessment | `strategy/playbooks/phase-0-intake.md` |
| **Phase 1: Baseline Assessment** | GHG inventory, data collection, ESG baseline | `strategy/playbooks/phase-1-baseline.md` |
| **Phase 2: Materiality** | Double materiality, IRO identification, stakeholder engagement | `strategy/playbooks/phase-2-materiality.md` |
| **Phase 3: Strategy & Roadmap** | Net zero strategy, target-setting, implementation planning | `strategy/playbooks/phase-3-roadmap.md` |
| **Phase 4: Disclosure & Reporting** | CSRD/CDP/GRI reporting, board deliverables, greenwashing audit | `strategy/playbooks/phase-4-reporting.md` |
| **Runbook: GHG Inventory** | End-to-end GHG inventory engagement | `strategy/runbooks/scenario-ghg-inventory.md` |
| **Runbook: Net Zero Roadmap** | Net zero commitment through SBTi target | `strategy/runbooks/scenario-net-zero-roadmap.md` |
| **Runbook: CSRD Disclosure** | CSRD first-time reporting engagement | `strategy/runbooks/scenario-csrd-disclosure.md` |
| **Runbook: EPR Compliance** | Extended producer responsibility compliance | `strategy/runbooks/scenario-epr-compliance.md` |

---

## Attribution

This repository is forked from and inspired by [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents) — a brilliant collection of AI agent personas for digital agencies. The agent architecture, YAML frontmatter format, orchestration doctrine model, and install/convert tooling are all derived from that original work.

What changed: the domain. Digital agency → sustainability consulting firm. Frontend developers → GHG inventory specialists. Reality checkers → Greenwashing auditors. NEXUS → MERIDIAN.

Credit where it's due: the original format made this possible.

---

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on adding new agents or improving existing ones.

**Quality bar**: every agent must cite real frameworks and regulations with correct version numbers, include a "No Greenwashing — Ever" commitment in Critical Rules, and produce deliverables that would pass peer review from a senior Anthesis or ERM consultant.

---

## License

MIT — see [LICENSE](LICENSE).

*Built on the architecture of [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents). Sustainability consulting domain expertise added by [MikeTannenbaum](https://github.com/MikeTannenbaum).*
