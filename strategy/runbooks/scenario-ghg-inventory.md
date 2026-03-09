# Runbook: GHG Inventory Engagement

> **Scenario**: A company needs its first (or significantly improved) GHG inventory — Scope 1, 2, and material Scope 3 categories — that will serve as the baseline for SBTi target-setting, CSRD disclosure, and CDP reporting. The inventory must be methodology-documented, internally consistent, and assurance-ready within 12 weeks.

---

## When to Use This Runbook

- First-ever GHG inventory
- Prior inventory had significant methodology gaps (no Scope 3, wrong consolidation approach, undocumented EFs)
- Inventory needed as base year for SBTi target submission
- Inventory needed for CSRD first-year report (FY2024 or FY2025)
- CDP submission requiring verified Scope 1+2 and quantified Scope 3

---

## Agent Team

| Role | Agent | Phase |
|---|---|---|
| Intake & scoping | MERIDIAN Orchestrator | Week 1 |
| Organizational boundary | Sustainability Data Consolidator | Week 1–2 |
| Scope 1+2 inventory | GHG Inventory Specialist | Week 2–6 |
| Scope 3 screening + inventory | Scope 3 Analyst | Week 2–8 |
| Energy data analysis | Energy Efficiency Auditor | Week 3–5 |
| Multi-entity consolidation | Sustainability Data Consolidator | Week 6–9 |
| Data quality assessment | ESG Data Analyst | Week 6–9 |
| Assurance package prep | ESG Data Analyst + Sustainability Data Consolidator | Week 9–12 |
| Client deliverable | Client Deliverable Generator | Week 11–12 |
| Greenwashing review | Greenwashing Auditor | Week 12 |

---

## Week-by-Week Timeline

### Week 1: Intake and Scoping

**MERIDIAN Orchestrator**:
- Client briefing: company profile, regulatory triggers, timeline drivers
- Review prior work: any existing GHG data, energy data, sustainability reports
- Map regulatory requirements: CSRD? CA SB 253? CDP? SBTi base year?
- Issue data collection templates to client
- Confirm consolidation approach with client and document

**Deliverable**: Engagement scope document; data request issued to client

### Weeks 1–2: Organizational Boundary

**Sustainability Data Consolidator**:
- Obtain complete legal entity list from client finance/legal
- Map each entity to consolidation approach (operational/financial/equity control)
- Document include/exclude decision with rationale for each entity
- Identify special cases: JVs, management contracts, leased assets, franchises
- Confirm de minimis exclusions (<5% of estimated total)

**Deliverable**: Boundary map document (entity × include/exclude × rationale × estimated %)

### Weeks 2–6: Scope 1 and 2 Data Collection and Calculation

**GHG Inventory Specialist**:
- Collect Scope 1 source data: natural gas bills, fuel invoices, refrigerant records, process data
- Calculate Scope 1 by category (stationary, mobile, process, fugitive)
- Apply AR6 GWPs; document EF sources per fuel type
- Collect Scope 2 source data: electricity utility bills, district heat bills, RECs/GOs/PPAs
- Calculate Scope 2 location-based: IEA or national grid EFs
- Calculate Scope 2 market-based: supplier EFs, residual mix, or GHG Protocol fallback
- QA check: year-over-year variance analysis; production volume reconciliation

**Energy Efficiency Auditor (supporting)**:
- Review energy data for completeness and plausibility
- Identify missing sub-meters; flag facilities with unusual energy intensity
- Recommend any quick wins for energy data improvement

**Deliverable**: Scope 1 and 2 calculation workbook with all source data, EFs, and DQS scores

### Weeks 2–8: Scope 3 Screening and Inventory

**Scope 3 Analyst**:
- Screen all 15 categories for relevance to this company's value chain
- Prioritize material categories (>1% of estimated total Scope 1+2+3)
- Quantify material categories using best available method:
  - Cat 1: spend-based USEEIO or hybrid (primary supplier data where available)
  - Cat 3: calculated directly from Scope 1+2 activity data
  - Cat 6: travel data × distance × transport EF
  - Cat 7: commuting survey or headcount × commuting distance assumption
  - Cat 11: product sales data × use-phase emission model
- Document each category: method, data source, EF, DQS, gap-fill rationale (if applicable)
- Identify top 5 Scope 3 categories by emissions — these drive target-setting and supplier engagement

**Deliverable**: Scope 3 calculation workbook; category screening table; DQS summary

### Weeks 6–9: Multi-Entity Consolidation and QA

**Sustainability Data Consolidator**:
- Validate each entity submission: units correct, no math errors, year-over-year changes explained
- Flag anomalies: >20% change vs. prior year requires investigation
- Handle intercompany energy transfers (exclude from total or document gross + netting)
- Consolidate to group level per boundary map
- Calculate group-level intensity metrics: per revenue, per employee, per production unit
- Prepare gap-fill documentation for all estimated figures
- Assess restatement requirements vs. any prior inventory

**ESG Data Analyst (QA)**:
- Assign final DQS scores to all metrics
- Assess % of inventory at DQS ≥3 (target: ≥80% of Scope 1+2 at DQS ≥4)
- Flag metrics at DQS ≤2 with improvement plan for next year
- Create master data table (single source of truth for all subsequent engagement work)

**Deliverable**: Consolidated group inventory; data quality report; master data table

### Weeks 9–12: Assurance Package and Deliverables

**ESG Data Analyst + Sustainability Data Consolidator**:
- Compile evidence package: utility bills, fuel invoices, EF citations, calculation workbooks, entity rollup
- Index all evidence with reference from group total → entity → site → source document
- Prepare management assertion letter draft
- Create verifier briefing document: boundary, methodology, key data sources, DQS summary

**Client Deliverable Generator**:
- GHG Inventory Report: technical summary; methodology documentation; entity-level breakdown; DQS assessment; base year recommendation; improvement plan
- Executive Summary (for CSO + CFO): key findings; scope totals; intensity; data quality; next steps
- Board brief (if requested): financial framing; carbon cost exposure; regulatory implications

**Greenwashing Auditor**:
- Review any public-facing GHG claims in deliverables
- Check: Scope definition; methodology disclosure; hedging language for estimates
- Issue PASS/CONDITIONAL PASS/FAIL per claim

**Deliverable**: Complete GHG inventory report package; assurance-ready evidence package; executive summary; any additional deliverables per scope

---

## Key Decisions to Document

1. **Consolidation approach**: operational control / financial control / equity share — rationale
2. **Base year**: which year and why (must have reliable data; pre-COVID for many companies means 2018–2019)
3. **Recalculation policy**: significance threshold for restatements (typically ≥5% change in base year)
4. **GWP version**: AR6 or AR5 — note for CDP: CDP accepts both but requires consistency with prior years
5. **Scope 3 materiality threshold**: which categories are included and why others are excluded
6. **Gap-fill decisions**: each gap-fill is a documented decision with its own DQS impact

---

## Common Pitfalls

| Pitfall | Prevention |
|---|---|
| Using different EF vintages in same inventory | Lock EF sources in Week 1; apply consistently |
| Missing refrigerant emissions | Always include in scope; request refrigerant service records |
| Including PPAs/RECs in location-based (incorrect) | Strictly separate location-based and market-based calculations |
| Scope 3 Cat 3 omitted | Always include — calculated directly from Scope 1+2 fuel and energy data |
| Base year chosen without recalculation policy | Set recalculation policy in writing before choosing base year |
| Intercompany energy transfers double-counted | Identify all in-scope entities that trade energy; net before consolidation |

---

## Activation Prompt

```
Activate MERIDIAN Orchestrator for GHG Inventory engagement.

Client: [COMPANY NAME]
Sector: [INDUSTRY]
Scope: [Scope 1+2 only / Scope 1+2+3 / Full with assurance]
Consolidation approach: [Operational control / Financial control / to be determined]
Base year: [Year / to be determined]
Drivers: [CSRD base year / SBTi base year / CDP reporting / First inventory]
Available data: [Utility bills available / Partial / TBD]
Timeline: [X weeks]

Activate team:
- Sustainability Data Consolidator: boundary mapping (Week 1)
- GHG Inventory Specialist: Scope 1+2 (Weeks 2–6)
- Scope 3 Analyst: screening + material categories (Weeks 2–8)
- Sustainability Data Consolidator: consolidation + QA (Weeks 6–9)
- ESG Data Analyst: DQS assessment + assurance package (Weeks 6–12)
- Client Deliverable Generator: inventory report + executive summary (Weeks 11–12)
- Greenwashing Auditor: public-facing claims review (Week 12)
```
