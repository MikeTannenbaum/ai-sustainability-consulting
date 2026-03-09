# Phase 1: Baseline Assessment Playbook

> **MERIDIAN Phase 1** — Where the real work begins. Every claim, every target, every board presentation in this engagement will trace back to the numbers established here. Get this right, with documented methodology and defensible data quality, and the rest of the engagement is on solid ground.

---

## Phase Overview

**Lead Agents**: GHG Inventory Specialist, ESG Data Analyst
**Supporting Agents**: Scope 3 Analyst, Energy Efficiency Auditor, Sustainability Data Consolidator
**Duration**: 4–8 weeks (data-intensive — timeline depends on client data quality)
**Primary output**: Verified GHG inventory + ESG baseline dataset + master data table

---

## Step 1: Organizational Boundary Setting

**Lead**: Sustainability Data Consolidator

### Consolidation approach selection

Choose one approach and apply it consistently across all years:

| Approach | When to Use | Coverage |
|---|---|---|
| **Operational control** | Company operates most assets; want to capture all operations | 100% of emissions from operations where company has authority to set operating policies |
| **Financial control** | Want alignment with IFRS financial consolidation | 100% of emissions from operations where company has financial control |
| **Equity share** | Significant JV or minority investment portfolio | Emissions proportional to equity ownership % |

Decision factors:
- Which approach best reflects actual influence over emissions?
- Which is consistent with any existing SBTi commitment or prior inventory?
- Which aligns with regulatory requirements (some mandates specify approach)?
- CSRD boundary note: ESRS uses accounting directive boundary — document any differences from GHG Protocol choice

### Boundary map

Create the boundary map before beginning any calculations:

```markdown
| Entity | Country | Ownership % | Control Type | Included? | Rationale |
|---|---|---|---|---|---|
| [Parent Co] | US | 100% | Operational | Yes | Operating entity |
| [Sub A] | Germany | 100% | Operational | Yes | Wholly controlled |
| [JV B] | Brazil | 50% | Operational | Yes | Company operates JV |
| [Associate C] | India | 25% | Financial only | No | No operational control |
```

Document all exclusions and estimate their % of total emissions to confirm de minimis (typically <5%).

---

## Step 2: Scope 1 Inventory

**Lead**: GHG Inventory Specialist

### Emission categories to quantify

- **Stationary combustion**: natural gas, fuel oil, LPG, coal at owned/controlled facilities
- **Mobile combustion**: company-owned or leased vehicles (cars, trucks, fork lifts, ships, aircraft)
- **Process emissions**: industrial process releases (cement, steel, chemicals — sector-specific)
- **Fugitive emissions**: refrigerant releases (F-gases), methane from coal/oil/gas operations if applicable

### Calculation approach

Activity-based calculation is preferred (DQS 4–5):
```
GHG emission = Activity data × Emission factor
(e.g., kWh of gas burned × kg CO2e per kWh)
```

**Emission factors**: use AR6 100-year GWPs from IPCC (CO2: 1, CH4: 29.8, N2O: 273, HFCs/PFCs/SF6 per AR6 Table 7.SM.7)

**Fuel combustion EFs**: use IPCC 2006 Guidelines Tier 1 EFs or national inventory EFs where available (higher quality)

**Refrigerants**: GWP values from AR6 Table 7.SM.7; report as tCO2e per refrigerant type

### Data quality scoring (DQS 1–5)

| DQS | Description | Example |
|---|---|---|
| 5 | Verified primary data, third-party assured | Utility bills + ISO 14064-3 verification |
| 4 | Primary data, internally reviewed | Metered data with QA sign-off |
| 3 | Calculated from primary activity data | Fuel purchases × EF |
| 2 | Estimated or extrapolated | Prior year × growth factor |
| 1 | Rough proxy or default | Industry average |

---

## Step 3: Scope 2 Inventory

**Lead**: GHG Inventory Specialist

### Two methods — both required for material reporters

**Location-based**: uses grid average emission factor for the country/region where electricity is consumed
- Source: IEA Emission Factors (preferred), AIB European Residual Mix, national grid operator published EFs
- Report as: tCO2e using location-based method

**Market-based**: uses supplier-specific emission factors from contractual instruments
- Priority of EFs: (1) supplier-specific EF from contract; (2) REGOs/GOs with residual mix; (3) regional residual mix; (4) location-based as fallback
- Contractual instruments accepted: Power Purchase Agreements (PPAs), renewable energy certificates (RECs/GOs), supplier contracts with disclosed EFs
- GHG Protocol requirement: instruments must be (a) from the same market as consumption, (b) match reporting period vintage, (c) not double-counted

### District heating/cooling and steam

- Include in Scope 2 (not Scope 1)
- Location-based: country/regional EF for heat/steam
- Market-based: supplier-specific EF if available; residual mix otherwise

### Key validation check

If market-based < location-based: verify that market instruments are GHG Protocol-compliant (vintage-matched, same market). If the gap is large, scrutinize carefully — this is where greenwashing risk concentrates.

---

## Step 4: Scope 3 Screening and Inventory

**Lead**: Scope 3 Analyst
**All 15 categories assessed**:

| Category | Typical Method | DQS Range |
|---|---|---|
| Cat 1: Purchased goods & services | Spend-based (EEIO) or hybrid | 2–4 |
| Cat 2: Capital goods | Spend-based or asset-specific | 2–3 |
| Cat 3: Fuel & energy activities | Calculated from S1+S2 activity data | 4 |
| Cat 4: Upstream transportation | Spend-based or distance × weight | 2–4 |
| Cat 5: Waste in operations | Waste mass × disposal EF | 3–4 |
| Cat 6: Business travel | Distance × transport mode EF | 3–4 |
| Cat 7: Employee commuting | Commuting survey × EF | 2–3 |
| Cat 8: Upstream leased assets | Energy use × EF if available | 2–3 |
| Cat 9: Downstream transport | Distance × weight EF | 2–3 |
| Cat 10: Processing of sold products | Downstream activity data | 1–2 |
| Cat 11: Use of sold products | Product lifetime × use-phase EF | 2–4 |
| Cat 12: End-of-life treatment | Sales volume × EoL fraction × EF | 2–3 |
| Cat 13: Downstream leased assets | Lessee energy data | 2 |
| Cat 14: Franchises | Franchisee energy data | 1–2 |
| Cat 15: Investments | PCAF methodology by asset class | 1–3 |

### Screening protocol

For each category:
1. Assess relevance: is the category applicable to this company's value chain?
2. If applicable: estimate emissions magnitude (can be rough for screening)
3. Apply materiality threshold: categories >1% of total Scope 3 are typically material
4. Prioritize categories >40 tCO2e per $1M revenue for detailed calculation

### Gap-fill documentation

For every estimated or proxied figure:
```markdown
| Category | Entity/Scope | Period | Gap Type | Gap-fill Method | Estimated Volume | DQS | Next Year Improvement |
|---|---|---|---|---|---|---|---|
| Cat 1 | Global supply chain | FY2024 | Missing primary supplier data | USEEIO spend-based | 45,200 tCO2e | 2 | Engage top 10 suppliers for primary data |
```

---

## Step 5: ESG Baseline Dataset

**Lead**: ESG Data Analyst

### Priority metrics to establish

**Energy**
- Total energy consumption (MWh) — direct (Scope 1 fuels) + indirect (electricity/heat)
- Energy intensity (MWh per revenue / per production unit)
- % renewable energy (market-based)
- ENERGY STAR score where applicable (US facilities)

**Water**
- Total water withdrawal by source (municipal, surface, groundwater)
- Total water consumption
- Water intensity (m³ per revenue)
- High water-risk facilities (WRI Aqueduct screening)

**Waste**
- Total waste generated (tonnes) by type and hazardous/non-hazardous
- Waste diversion rate (% diverted from landfill)
- % recycled, composted, incinerated with energy recovery

**Social**
- Total headcount (FTE and part-time) by gender and geography
- Turnover rate
- Safety: TRIR (Total Recordable Incident Rate) and LTIR (Lost Time Incident Rate) per 200,000 hours
- Training hours per employee
- Gender pay gap (if in scope)

### Data quality assessment

Assign DQS for each metric. Flag any metric at DQS ≤2 as a priority for improvement.

```markdown
## ESG Baseline Data Quality Summary — FY[Year]

| Metric | Value | DQS | Source | Gap-fill Used? | Next Year Improvement |
|---|---|---|---|---|---|
| Scope 1 (tCO2e) | 12,400 | 4 | Fuel invoices + EF | No | — |
| Scope 2 market-based (tCO2e) | 8,200 | 4 | PPA + residual mix EF | No | — |
| Scope 3 Cat 1 (tCO2e) | 156,000 | 2 | USEEIO spend-based | Yes — full cat | Engage top 20 suppliers |
| Energy intensity (MWh/M revenue) | 42.3 | 4 | Energy bills + revenue | No | — |
| Water withdrawal (m³) | 89,400 | 3 | Utility bills (partial) | Yes — 2 sites | Install sub-meters at remaining sites |
| Waste diversion rate (%) | 67% | 3 | Waste hauler reports | No | — |
| TRIR | 1.2 | 5 | OSHA 300 log | No | — |
```

---

## Step 6: Master Data Table

**Lead**: Sustainability Data Consolidator
**This is the single source of truth for the entire engagement.**

```markdown
## Master Data Table — [Company] — FY[Year]
**Created**: [Date] | **Version**: 1.0 | **Locked**: [Date after Phase 1 gate]
**Do not modify without versioning and documentation of change.**

### GHG Emissions
| Metric | Value (tCO2e) | DQS | Methodology | EF Source | Notes |
|---|---|---|---|---|---|
| Scope 1 | 12,400 | 4 | Activity-based | IPCC 2006 AR6 | Includes CH4 from gas combustion |
| Scope 2 — location | 14,200 | 5 | Location-based | IEA 2023 | Grid average EF |
| Scope 2 — market | 8,200 | 4 | Market-based | PPA EF + residual mix | REGO-backed PPA from FY2023 |
| Scope 3 total | 342,000 | 2–4 | Category detail below | — | See Cat breakdown |
| Scope 3 Cat 1 | 156,000 | 2 | Spend-based USEEIO | USEEIO v2.0 | FY2024 procurement spend |
| [Continue per category] | | | | | |

### Base Year Reference
| Metric | Base Year | Base Year Value | Restated? | Restated Value |
|---|---|---|---|---|
| Scope 1+2 (market) | FY2019 | 32,400 tCO2e | No | — |

### ESG Metrics
[Full table of all ESG metrics with DQS scores]
```

---

## Phase 1 Quality Gate

**Gate 1 — Baseline Complete**

☐ GHG inventory complete for all Scope 1 and 2 emission sources with DQS ≥3
☐ Both location-based and market-based Scope 2 quantified
☐ Scope 3 screening complete — all 15 categories assessed; material categories quantified
☐ Organizational boundary documented with entity-level breakdown
☐ Data quality scores assigned for all reported metrics
☐ Gap-fill methodology documented for all estimated data — improvement plan included
☐ Base year established with recalculation policy in writing
☐ Master data table created and version-controlled
☐ No undisclosed intercompany energy transfers
☐ AR6 GWPs applied (or AR5 with disclosure if required by applicable framework)

**Advance to Phase 2 when all boxes checked.**

---

*The master data table created in Phase 1 does not change without explicit versioning and client approval. All downstream deliverables draw from this table. Version drift is not acceptable.*
