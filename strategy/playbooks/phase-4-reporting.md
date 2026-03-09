# Phase 4: Disclosure & Reporting Playbook

> **MERIDIAN Phase 4** — Where the work becomes public. Everything built in Phases 1–3 gets translated into the outputs that regulators will review, investors will benchmark, and NGOs will scrutinize. The quality gate here is the Greenwashing Auditor — no external claim leaves without clearance. This phase is not a formatting exercise. It is where the credibility of the entire engagement is tested.

---

## Phase Overview

**Lead Agents**: ESG Report Writer, Client Deliverable Generator
**Supporting Agents**: CDP Specialist, CSRD Advisor, Materiality Facilitator, Sustainability Data Consolidator
**Review Agents**: Greenwashing Auditor (mandatory for all external deliverables)
**Duration**: 4–8 weeks
**Primary output**: CSRD/GRI/ISSB report + CDP submission + board deliverables + investor factsheet — all greenwashing-cleared

---

## Step 1: Source of Truth Lock

**Lead**: Sustainability Data Consolidator

Before any disclosure drafting begins, the master data table from Phase 1 must be locked.

### What "locked" means

- All KPIs are finalized with DQS scores
- All gap-fills are documented
- Any restatements vs. prior year are documented in the restatement log
- No number changes after this point without explicit versioning, documentation, and notification to all deliverable leads

### Consistency matrix

Create a cross-reference table before drafting begins:

```markdown
## Consistency Matrix — [Company] — FY[Year]

| Metric | Master Table Value | CDP Response | CSRD Report | Board Deck | Investor Factsheet |
|---|---|---|---|---|---|
| Scope 1 (tCO2e) | 12,400 | 12,400 | 12,400 | [confirm] | [confirm] |
| Scope 2 market (tCO2e) | 8,200 | 8,200 | 8,200 | [confirm] | [confirm] |
| Scope 3 total (tCO2e) | 342,000 | 342,000 | 342,000 | [confirm] | [confirm] |
| % renewable electricity | 68% | 68% | 68% | [confirm] | [confirm] |
| Revenue ($M) | 2,840 | 2,840 | 2,840 | [confirm] | [confirm] |
```

This matrix must be completed and signed off before any deliverable goes external.

---

## Step 2: CSRD/ESRS Report Drafting

**Lead**: ESG Report Writer + CSRD Advisor

### ESRS disclosure structure

**General disclosures (ESRS 2)** — required regardless of materiality:
- GOV-1: Governance of sustainability matters (board structure, sustainability oversight)
- GOV-2: Information provided to and sustainability matters addressed by the undertaking's administrative, management and supervisory bodies
- GOV-3: Integration of sustainability-related performance in incentive schemes
- GOV-4: Statement on due diligence
- GOV-5: Risk management and internal controls over sustainability reporting
- SBM-1: Strategy, business model and value chain
- SBM-2: Interests and views of stakeholders
- SBM-3: Material impacts, risks and opportunities and their interaction with strategy and business model
- IRO-1: Description of the processes to identify and assess material impacts, risks and opportunities
- IRO-2: Disclosure requirements in ESRS covered by the undertaking's sustainability statement

**Topical disclosures** — for each material ESRS standard (per Phase 2 application matrix):
- Policies and actions
- Targets and progress against targets
- Metrics (quantitative disclosures)
- Narrative context

### ESRS E1 (Climate) disclosure structure

- E1-1: Transition plan for climate change mitigation (if applicable)
- E1-2: Policies related to climate change mitigation and adaptation
- E1-3: Actions and resources in relation to climate change policies
- E1-4: Targets related to climate change mitigation and adaptation
- E1-5: Energy consumption and mix
- E1-6: Gross Scopes 1, 2, 3 and Total GHG emissions
- E1-7: GHG removals and GHG mitigation projects financed through carbon credits
- E1-8: Internal carbon pricing
- E1-9: Anticipated financial effects from material physical and transition risks and potential climate-related opportunities

### Drafting principles

- **Data first, narrative second**: for quantitative disclosures — lead with the number, then context
- **Accuracy over polish**: do not soften uncertainty with confident language — say "estimated" when it is estimated
- **No dead-ends**: every disclosure of a material issue connects to a policy, target, or action
- **Time horizons**: consistently apply short/medium/long-term horizons across all disclosures
- **Cross-references**: where ESRS E1 targets are the same as SBTi targets — cross-reference; do not contradict

### XBRL tagging (for CSRD submission)

- ESRS XBRL taxonomy published by EFRAG — apply tags to all mandatory quantitative disclosures
- Block tagging for narrative disclosures
- File format: Inline XBRL (iXBRL) embedded in the HTML sustainability statement
- Work with digital reporting tool (Workiva, Certent, or equivalent) from Day 1 of Phase 4 — don't XBRL-tag at the end

---

## Step 3: CDP Submission

**Lead**: CDP Specialist

### CDP Climate questionnaire (C0–C15)

Priority modules for A-list scoring:
- **C0**: Introduction — verify prior year response consistency
- **C1**: Governance — board oversight of climate; management-level accountability
- **C2**: Risks and opportunities — physical and transition risks with financial quantification; aligned with TCFD
- **C3**: Business strategy — scenario analysis; climate integration into strategy
- **C4**: Targets and performance — absolute Scope 1+2 target; Scope 3 target; SBTi status; progress
- **C6**: Emissions data — Scope 1 (by country, activity); Scope 2 location and market; methodology
- **C7**: Emissions breakdown — by activity, region, subsidiary
- **C8**: Energy — absolute energy consumption; renewable % (location and market)
- **C9**: Additional metrics — optional additional disclosures
- **C11**: Carbon pricing — internal carbon price; exposure to carbon pricing regulations (EU ETS, etc.)
- **C12**: Engagement — engagement with value chain; SBTi engagement target for suppliers

### A-list scoring factors

CDP publishes the methodology annually. Consistent A-list drivers:
- Complete and detailed responses — no "not applicable" without clear rationale
- Quantified financial risks (not just "high" qualitative)
- Scope 3 completeness — all 15 categories at minimum screened; material ones quantified
- SBTi validated target — required for A in recent years
- Independently verified Scope 1+2 data
- Internal carbon price in use
- Science-aligned strategy with near-term milestones

### Consistency with other disclosures

CDP responses are cross-referenced against:
- Annual report / sustainability report
- SEC filings (for US-listed companies)
- CSRD sustainability statement
- Prior CDP responses

Inconsistencies = CDP reviewer flags = potential score reduction and investor questions.

### CDP Water and Forests (if in scope)

CDP Water: W0–W13; focus on water risk assessment using WRI Aqueduct; high water-stress facility disclosure; water targets

CDP Forests: F0–F18; supply chain deforestation risk; EUDR alignment; commodity-specific (timber, palm, soy, beef, cocoa, leather, rubber); NDPE policy

---

## Step 4: Audience-Specific Deliverables

**Lead**: Client Deliverable Generator

### Board Briefing Deck (10–15 slides)

Opening frame: financial exposure and business risk — not GHG figures
Structure:
1. Why now (regulatory deadline, investor pressure, competitive risk — specific)
2. Where we stand (current performance vs. prior year vs. peers vs. requirements)
3. What we found (key materiality findings; top risks and opportunities)
4. The strategy (net zero roadmap summary; SBTi target; key levers)
5. Financial summary (investment required; risk reduction; NPV; cost of inaction)
6. Roadmap (milestones 2025–2030–2040–2050)
7. Ask (board approval for investment budget; endorsement of SBTi commitment; note and feedback)
8. Appendix (GHG data; methodology; peer benchmarks; regulatory detail)

### Executive Summary (2 pages)

- Lead with the single most important finding for this audience
- Business implications (second paragraph): risk, cost, competitive position, obligation
- Recommended actions (third paragraph): numbered; owner named; timeline given
- Key data in call-out boxes
- Technical detail in linked appendix

### CFO / Finance Annex

- Quantified risk table: carbon pricing exposure, regulatory compliance costs, stranded asset risk
- Cost-benefit analysis: investment required vs. risk reduction value
- NPV analysis by lever: which investments make financial sense
- Accounting treatment guidance: capex vs. opex; carbon credit accounting; TCFD-aligned financial statement notes

### Investor ESG Factsheet

- ISSB IFRS S1/S2 aligned: financial materiality framing
- Year-over-year trend data: Scope 1+2+3 trajectory; intensity metrics
- Target status: near-term (SBTi); long-term (net zero); progress markers
- Methodology transparency: consolidation approach; EF sources; assurance level
- Cross-reference to CDP and regulatory disclosures

### Legal Disclosure Language Review

- All sustainability claims in SEC filings, annual report, and proxy: reviewed for material misrepresentation risk
- Forward-looking statement hedging: "subject to [conditions]," "based on current plans and assumptions"
- Consistency with SEC filings: no sustainability claims in investor materials that contradict 10-K disclosures
- Greenwashing audit findings incorporated into approved disclosure language

---

## Step 5: Greenwashing Audit

**Lead**: Greenwashing Auditor
**This step is non-negotiable for all external deliverables.**

### Claim audit process

For every external document:
1. Extract all claims with an environmental or sustainability dimension
2. Categorize: product claim, process claim, corporate claim, forward commitment, comparative claim
3. Assess evidence available for each claim
4. Apply applicable standards by market:
   - FTC Green Guides (US)
   - EU Green Claims Directive + Empowering Consumers Directive (EU)
   - UK CMA Green Claims Code (UK)
   - ISO 14021 (product claims)
   - VCMI Claims Code + ISO 14068 (carbon/climate claims)
5. Rate each claim: PASS / CONDITIONAL PASS / FAIL
6. Provide revised language for all fails and conditional passes

### Zero tolerance claims

These cannot be published without remediation — escalate immediately if found:
- "Carbon neutral" without ISO 14068 scope, measurement, reduction demonstration, and third-party verification
- "Net zero" without SBTi-aligned Scope 1+2+3 targets (or credible equivalent)
- "100% renewable electricity" without GHG Protocol-compliant market instruments (vintage-matched, same market)
- "Sustainable [material]" without recognized certification or specific quantified attribute
- Forward commitments without credible plans, interim targets, and governance accountability

### Greenwashing audit output

```markdown
## Greenwashing Audit — [Document] — [Date]

Total claims reviewed: [X]
Passed: [X] ([Y]%)
Conditional Pass (revision required): [X]
Failed (must be removed or substantially revised): [X]
Critical risks: [X]

### High-Risk Finding 1
Claim: "[exact claim text]"
Location: [Document section / page]
Issue: [Precise problem — which standard, why it fails]
Applicable standard: [FTC §260.X / ISO 14068 / VCMI / EU ECD Art. X]
Risk level: CRITICAL / HIGH / MEDIUM
Required action: [Specific change]
Approved alternative: "[Revised claim text]"
```

---

## Step 6: Assurance Preparation

**Lead**: ESG Data Analyst + Sustainability Data Consolidator

### Assurance levels

| Level | Standard | What Is Assured | Typical Requirement |
|---|---|---|---|
| Limited assurance | ISAE 3000 | "Nothing came to our attention" — negative conclusion | CSRD Year 1; most voluntary frameworks |
| Reasonable assurance | ISAE 3000 or ISO 14064-3 | "In our opinion" — positive conclusion | CSRD from ~2028; best-in-class voluntary |
| Verification | ISO 14064-3 | GHG-specific; SBTi validation may require | CDP-linked; high-credibility claims |

### Evidence package structure

```markdown
## Assurance Evidence Package — [Company] — FY[Year]

### By Metric
| Metric | Value | Evidence Type | Evidence Location | DQS | Verifier Notes |
|---|---|---|---|---|---|
| Scope 1 — Natural gas | 8,400 tCO2e | Utility bills + calculation | [File path] | 4 | Utility bills attached; EF per IPCC 2006 |
| Scope 2 market-based | 8,200 tCO2e | REGO certs + calculation | [File path] | 4 | REGO certs: [provider], vintage 2024 |
| Scope 3 Cat 1 | 156,000 tCO2e | USEEIO calculation | [File path] | 2 | Spend data from ERP; USEEIO v2.0 |

### Management Assertion Letter
[Draft: company management asserts that GHG data has been prepared in accordance with GHG Protocol Corporate Standard; organizational boundary is operational control; all figures are as of December 31, [Year]]
```

---

## Phase 4 Quality Gate

**Gate 4 — Disclosure Ready**

☐ Master data table locked — version 1.0 final; all deliverables use consistent numbers
☐ Consistency matrix complete — all deliverables cross-referenced; no conflicting figures
☐ CSRD/ESRS sustainability statement complete — all material ESRS disclosure requirements addressed
☐ CDP submission complete — all applicable modules; evidence attached
☐ XBRL tagging complete (for CSRD) — taxonomy-compliant; file submitted to digital reporting tool
☐ Board briefing deck complete — financial framing; decision and ask; greenwashing cleared
☐ Investor ESG factsheet complete — ISSB-aligned; methodology disclosed
☐ Greenwashing audit complete — PASS or CONDITIONAL PASS (revisions applied) for ALL external claims
☐ Greenwashing audit finding documentation filed — creates evidence trail of due diligence
☐ Legal and communications teams have approved all external-facing language
☐ Assurance evidence package complete (if assurance in scope) — verifier engaged
☐ Internal consistency confirmed — no version drift across deliverables

**Engagement complete when all boxes checked.**

---

*The Greenwashing Auditor's sign-off is the final quality gate. If any claim cannot pass the audit, it is removed or replaced — never softened to a barely-passing version. The evidence trail of what was reviewed and what was changed is part of the engagement documentation and may be needed if a claim is later challenged.*
