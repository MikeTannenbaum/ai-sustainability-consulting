# MERIDIAN Handoff Templates

> **Structured context transfer between agents.** No agent starts cold. Every handoff includes: what was done, what was decided, what data is being transferred, and what the receiving agent should NOT reopen without authorization.

---

## Standard Handoff Template

```markdown
## Handoff: [FROM AGENT] → [TO AGENT]
**Date**: [Date]
**Engagement**: [Company] — [Engagement type]
**Phase transition**: Phase [X] → Phase [Y]
**Prepared by**: [Agent name]

---

### Work Completed in This Phase

[3–5 bullet points: what was done, what outputs were produced, what decisions were made]

### Key Findings for Receiving Agent

[The 3–5 most important things the receiving agent needs to know to do their job well]

### Data Transferred

| Metric | Value | DQS | Source | Caveats / Limitations |
|---|---|---|---|---|
| [Metric name] | [Value + units] | [1–5] | [Source document] | [Any limitations, estimates, or improvement notes] |

### Decisions That Are Locked

The following decisions were made with the client and are not to be reopened:
- [Decision 1: e.g., Consolidation approach = Operational Control — rationale documented in boundary map]
- [Decision 2: e.g., Base year = FY2019 — pre-COVID; recalculation policy agreed in writing]
- [Decision 3]

### Open Items for Receiving Agent

[Anything unresolved that the receiving agent needs to address — be specific]

### Deliverables Transferred

| Document | Version | Location | Status |
|---|---|---|---|
| [Document name] | [v1.0] | [File path] | [Draft / Reviewed / Final] |

### Quality Gate Status

[Gate X: PASSED / PASSED WITH CONDITIONS (list conditions) / FAILED (do not advance)]

---
*Master data table location*: [File path]
*Engagement project folder*: [Location]
```

---

## Phase-Specific Handoff Templates

### Phase 0 → Phase 1: Intake to Baseline

```markdown
## Handoff: MERIDIAN Orchestrator → GHG Inventory Specialist + ESG Data Analyst
**Phase transition**: Phase 0 (Intake) → Phase 1 (Baseline Assessment)

### Work Completed
- Client briefing complete: [Company] context, triggers, timeline documented
- Regulatory trigger map: [List applicable frameworks and deadlines]
- Consolidation approach confirmed: [Operational / Financial / Equity control]
- Data request issued to client: [Date issued; due date from client]
- Agent activation plan confirmed: [List Phase 1 agents and their assignments]

### Critical Inputs for Phase 1

| Item | Detail | Source |
|---|---|---|
| Consolidation approach | [Approach + rationale] | Engagement scope document |
| Base year | [Year or TBD] | [Agreement or TBD in Phase 1] |
| Regulatory deadline | [Earliest relevant deadline] | Regulatory trigger map |
| Client data owner | [Name, email] | Client briefing |
| Data submission date | [Date] | Data collection plan |

### Locked Decisions
- Consolidation approach: [LOCKED — do not change without client re-authorization and restatement]
- Reporting period: [Calendar year / Fiscal year ending [date]]

### Open Items for Phase 1
- [ ] Data collection from client — due [date]
- [ ] Confirm base year once data quality is assessed
- [ ] Scope 3 screening — Scope 3 Analyst to begin by Week 2

### Gate 0 Status: PASSED
```

---

### Phase 1 → Phase 2: Baseline to Materiality

```markdown
## Handoff: GHG Inventory Specialist + ESG Data Analyst → Materiality Facilitator
**Phase transition**: Phase 1 (Baseline) → Phase 2 (Materiality)

### Work Completed
- GHG inventory complete: Scope 1, 2 (location + market), Scope 3 material categories
- ESG baseline dataset: [List key metrics collected]
- Master data table: created and version-controlled at [file path]
- Data quality scores: [X]% of Scope 1+2 at DQS ≥4; Scope 3 [X]% at DQS ≥3
- Gap-fill documentation: [X] metrics gap-filled; documented at [file path]

### Key Data for Materiality Assessment

| Metric | Value | DQS | Key Note |
|---|---|---|---|
| Scope 1 | [X tCO2e] | [4] | AR6 GWPs; stationary + mobile + fugitive |
| Scope 2 location | [X tCO2e] | [5] | IEA grid EF |
| Scope 2 market | [X tCO2e] | [4] | PPA + residual mix |
| Scope 3 total | [X tCO2e] | [2–4] | [X] of 15 categories quantified |
| Top Scope 3 category | Cat [X]: [X tCO2e] | [2] | Spend-based; improvement needed |
| GHG intensity | [X tCO2e/$M revenue] | [4] | |
| Carbon cost exposure | $[X]M by 2030 | [3] | EU ETS €80/tCO2e assumption |

### Implications for Materiality
- Climate (ESRS E1) is material on both impact and financial dimensions
- [Other topics suggested by baseline data]

### Master Data Table: LOCKED at Version 1.0
Location: [file path] | Locked: [date]
All Phase 2+ deliverables must use these numbers.

### Gate 1 Status: PASSED
```

---

### Phase 2 → Phase 3: Materiality to Strategy

```markdown
## Handoff: Materiality Facilitator → Net Zero Strategist + Sustainability Strategy Advisor
**Phase transition**: Phase 2 (Materiality) → Phase 3 (Strategy)

### Work Completed
- Double materiality assessment complete: IRO register finalized
- Material topics confirmed: [List material ESRS standards]
- DMA documentation drafted per ESRS 1
- Climate risk assessment: physical and transition risks quantified/qualified per TCFD
- Stakeholder consultation: [X] stakeholder groups engaged
- ESRS application matrix: [X] material standards; [Y] non-material with rationale

### Material Topics for Strategy Phase

| ESRS Standard | Topic | Why Material | Strategy Priority |
|---|---|---|---|
| E1 | Climate change | High financial impact; high emissions | HIGH |
| E5 | Circular economy | Packaging waste material | HIGH |
| S1 | Own workforce | H&S material; fair wage gap | MEDIUM |
| G1 | Business conduct | Anti-corruption gap | MEDIUM |

### Climate Risk Findings for Strategy

| Risk Type | Risk | Time Horizon | Magnitude |
|---|---|---|---|
| Transition — Policy | EU ETS carbon cost exposure | Short-medium | $[X]M/yr by 2030 |
| Physical — Acute | Flood risk to [facility] | Medium-long | $[X]M asset exposure |

### Constraints for Strategy Phase
- SBTi timeline: committed [date] — target due by [date]
- Budget: [constraint or no constraint known]
- Locked: base year [FY20XX], consolidation approach [method], target scope categories [list]

### Gate 2 Status: PASSED
```

---

### Phase 3 → Phase 4: Strategy to Disclosure

```markdown
## Handoff: Net Zero Strategist + Sustainability Strategy Advisor → ESG Report Writer + Client Deliverable Generator
**Phase transition**: Phase 3 (Strategy) → Phase 4 (Disclosure)

### Work Completed
- SBTi target: S1+2: [X]% by [year]; S3: [X]% by [year]
- MACC: [X] levers; [Y tCO2e/yr] abatement potential by 2030
- Decarbonization roadmap: [milestone summary]
- Renewable energy strategy: [X]% by [year]; instrument type
- Carbon market strategy: [role of credits; VCMI pathway if any]
- Financial case: $[X]M capex; NPV $[Y]M; risk reduction $[Z]M/yr

### Strategy Outputs for Disclosure

| Deliverable | Status | Disclosure Destination |
|---|---|---|
| SBTi target formulation | Final | CDP C4; CSRD E1-4; investor comms |
| MACC analysis | Final | CSRD E1-3; roadmap document |
| Net zero roadmap | Draft | CSRD E1-1 (transition plan); board deck |
| Financial risk summary | Final | CSRD E1-9; TCFD; CFO annex |

### Claims Requiring Greenwashing Audit
All of the following require Greenwashing Auditor clearance before publication:
- "Science-aligned targets" — SBTi committed, not yet validated
- "Net zero by [year]" — forward commitment requiring hedging
- "100% renewable electricity by [year]" — target, not yet contracted
- Any percentage reduction claim that is a target (not achieved)

### Gate 3 Status: PASSED
```

---

### Engagement Completion Handoff to Client

```markdown
## Engagement Completion: MERIDIAN → Client
**Engagement**: [Company] — [Engagement type]
**Completed**: [Date]

### Deliverables Produced

| Deliverable | Audience | Version | Status | File |
|---|---|---|---|---|
| GHG Inventory Report FY[year] | CSO / Verifier | Final 1.0 | Greenwashing cleared | [file] |
| CSRD Sustainability Statement | Board / Assurance | Final 1.0 | Assurance complete | [file] |
| CDP Climate Response | CDP / Investors | Final | Submitted [date] | [file] |
| Board Strategy Deck | Board | Final 1.0 | Board approved [date] | [file] |
| Net Zero Roadmap | CSO + Finance | Final 1.0 | Approved [date] | [file] |

### Greenwashing Audit Summary
- Claims audited: [X] | Passed: [X] | Revised: [X] | Removed: [X]
- All external deliverables: CLEARED | Audit report: [file]

### Recommended Next Steps (Year 2)

1. Data quality improvement: [Top 3 DQS improvements]
2. SBTi validation follow-up: expected [date]
3. CDP score improvement: [specific areas]
4. CSRD assurance upgrade: plan for reasonable assurance in Year [X]
5. Base year restatement: recalculation policy in writing at [file] — apply if M&A occurs

### Engagement Archive
Documentation: [Location] | Master data table: [File] | Audit records: [File] | Evidence package: [File]
```
