# Disruption Research Reference

## Research Methodology

### Purpose

This reference supports Phase 1 of the AI Impact Assessment — the research phase that identifies which tasks, roles, and processes in a client's logistics operation face disruption from AI and automation within a 12-month horizon.

### Approach

The assessment uses a **task-level decomposition** method. Rather than asking "will this job be automated?" (which is too broad to answer usefully), it asks "which specific tasks within this operation are vulnerable to current or near-term AI/automation capability?"

**Five-step process:**

1. **Decompose the operation** into discrete tasks, roles, and processes
2. **Source evidence** for each task from authoritative reports, case studies, and adoption data
3. **Classify** each task as High Risk, Medium Risk, or Resilient
4. **Cross-reference** against adoption curves in the client's geography and vertical
5. **Synthesise** into a verdict with timeline and action plan

---

## Authoritative Source List

### Primary Sources (checked first, most relevant)

| Source | What It Covers | Why It Is Authoritative |
|---|---|---|
| WEF Future of Jobs Report (annual) | Job displacement and creation estimates by sector; reskilling needs | World Economic Forum — cross-industry panel of CHROs and strategists |
| McKinsey Global Institute — Jobs Lost, Jobs Gained (2017, updated 2023) | Automation potential by occupation; midpoint adoption scenarios | Most widely cited automation research; conservative modelling |
| McKinsey — The Last Yard (2023) | Last-mile delivery automation; autonomous vehicles, drones, droids | Dedicated logistics automation analysis from MGI |
| OECD Employment Outlook (annual) | Automation risk by task; routine vs non-routine task analysis | Government-backed; methodology used by national labour ministries |
| DHL Logistics Trend Radar (biennial) | Logistics-specific technology trends; maturity curves | Leading logistics operator's internal research, publicly shared |
| Gartner Hype Cycle for Supply Chain Strategy (annual) | Technology maturity; time to plateau; adoption phases | Widely used by supply chain technology buyers |
| WEF — Supply Chain & Transport in the Fourth Industrial Revolution | Autonomous trucks, warehouse robotics, port automation | Focused on logistics-specific disruption scenarios |
| World Economic Forum / Accenture — Human Capital in the Age of AI | Reskilling frameworks and labour transition strategies | Actionable advice for workforce transition |
| IFR (International Federation of Robotics) — World Robotics Report (annual) | Worldwide robot installations by industry and country | Hard adoption data, not projections |
| Bureau of Labor Statistics (US) / ONS (UK) / Eurostat — Employment by Occupation | Occupational employment data; wage distributions | Used for reality-checking: expensive labour gets automated first |

### Secondary Sources (used for depth and case studies)

| Source | What It Covers |
|---|---|
| MIT Technology Review — AI in Logistics | Technology breakthroughs and real-world deployments |
| Supply Chain Dive, FreightWaves, The Loadstar | Industry news with concrete company examples |
| Company case studies (Amazon Robotics, Dexory, GreyOrange, Locus Robotics, Covariant, Nuro, Waymo Via, Schäfer, Knapp) | Vendor-specific examples; useful but weight against bias |
| Academic papers (Transportation Research, EJOR, JBL) | Rigorous but often lagging practice by 2-3 years |
| LinkedIn supply chain community discussions | Ground truth from practitioners; useful for timing and sentiment |

### How to Weigh Sources

| Weight | Source Type | When to Use |
|---|---|---|
| High | Primary sources + direct case studies | For the verdict and timeline |
| Medium | Secondary sources + academic papers | For colour, nuance, and edge cases |
| Low | Vendor marketing materials | For examples only — always verify independently |
| Context | Industry news from trade publications | For timing and adoption sentiment |

---

## Task-Level Assessment Framework

### Classification Criteria

| Classification | Definition | What You Should See | Action Required |
|---|---|---|---|
| **High Risk** | Task is likely automated or fundamentally changed within 12 months | Widely deployed automation exists today; cost of automation is falling; labour supply for this task is tightening; regulation is enabling automation; competitors are adopting en masse | Immediate action needed. Identify replacement, transition plan, or exit strategy |
| **Medium Risk** | Task will shift significantly within 12–24 months | Proven automation exists but adoption is not yet widespread in the client's geography/vertical; cost-benefit is close but not yet compelling; early adopters are gaining advantage | Plan and pilot within 6 months. Be ready to scale in months 9–12 |
| **Resilient** | Task is unlikely to be disrupted within 24+ months | Requires adaptive human judgement, exception handling, relationship management, creative problem-solving, or physical dexterity that automation cannot yet replicate cost-effectively | Monitor but do not over-invest. Use these tasks as strategic differentiation |

### Logistics Task Library (Common Tasks by Operation Type)

#### 3PL / Warehouse Operations

| Task | Risk Level | Evidence / Reasoning |
|---|---|---|
| Order picking — case/tote (single-item) | High | Goods-to-person robots (Locus, GreyOrange, Geek+) deployed at scale; ROI under 2 years for >500 picks/day facilities. |
| Order picking — mixed pallet build | Medium | Reliable depalletising + mixed pallet building exists (e.g. Covariant, Boston Dynamics Stretch) but unit economics vary by SKU profile. Computer vision for item recognition is mature. |
| Cycle counting / inventory reconciliation | High | Drones (e.g., FlytBase, Verity) + computer vision + RFID can count a DC in hours instead of days. WMS-native cycle counting is already standard. |
| Container Damage Inspection | Medium | Computer vision platforms (e.g., VIZION, ClearMetal) can auto-detect and classify container damage from photos/videos, reducing manual inspection time. |
| Loading / unloading trailers | Medium | Autonomous unloading exists (e.g. DHL + Boston Dynamics) but adoption is slow due to trailer variability and non-standardised dunnage. |
| Putaway / replenishment | Medium | Good systems exist for pallet-level; case-level putaway less mature. AI can optimize putaway locations based on predicted demand. |
| Manual data entry (BOL, PODs) | High | OCR + RPA for freight documentation is a mature technology. Structured data extraction is largely solved. |
| Parcel manifesting / labelling | High | Automated dimensioning + print-and-apply systems are mature and cheap. |
| Returns processing / reverse logistics | Medium | Computer-vision-based grading exists but exception handling and complex refurbishment still need humans. |
| Forklift operation | High | Autonomous forklifts (e.g. Toyota, Hyster-Yale, Raymond) proven in controlled environments; retrofits cost-competitive for new builds, especially for VNA (Very Narrow Aisle). |
| Pallet wrapping / stretch hooding | High | Fully automated wrapping lines are standard. |
| Slotting / layout planning | Medium | AI-optimised slotting (e.g., Optricity) exists but most 3PLs still use rule-based or manual methods—not yet widely adopted. |
| Customer exception resolution | Resilient | Requires cross-system investigation, judgement, and relationship management. |
| Client QBR preparation | Resilient | Narrative construction, data interpretation, strategic recommendations. |
| New business implementation | Resilient | Requires project management, change management, and client-specific adaptation. |
| Safety / compliance inspection | Resilient | Checklists can be automated but judgement calls, floor observation, and incident investigation remain human. |
| Training new hires | Low-Medium | Standardised training can be automated (AR/VR, LMS); adaptive coaching remains human. |

#### Freight Forwarding / Customs Brokerage

| Task | Risk Level | Evidence / Reasoning |
|---|---|---|
| Customs documentation preparation | High | E2E digital customs platforms (e.g. Descartes, WiseTech, Bolero) — 80%+ of standard filings can be automated using RPA and structured data. |
| Rate lookups / quoting | High | API-based digital freight marketplaces (Freightos, Xeneta) — spot quoting is near-real-time. AI can predict spot rate volatility. |
| Demand Forecasting | Medium | AI/ML for demand forecasting is mature in retail/CPG and is being adopted by forwarders to predict lane volume and allocate capacity. |
| Track-and-trace / proactive exception alerts | High | IoT + carrier APIs + AI (e.g., project44, FourKites) — most tracking will be automated within 12 months. Predictive ETAs are becoming standard. |
| Invoice audit / payment reconciliation | High | Automated freight audit & pay has been standard in large forwarders for years; spreading to mid-market via RPA. |
| Routing optimisation | High | AI routing engines are standard in TMS platforms; the manual equivalent cannot compete on multi-factor optimisation (cost, carbon, transit time, risk). |
| Carrier procurement (RFP / tender) | Medium | Digital procurement platforms (e.g. Transporeon, Keelvar) — data-driven awards replacing relationship-based sourcing for commoditised lanes. |
| Regulatory classification (HS codes) | Medium | AI classification tools exist (e.g. Zonos, TariffTel) but complex rulings, new products, or ambiguous cases still need human judgement. |
| Customer service — standard inquiries ("Where is my shipment?") | High | Chatbots + self-serve tracking portals handle 70%+ of standard inquiries. |
| Customer service — complex exception handling (delayed cargo, customs holds) | Resilient | Requires proactive communication, relationship management, creative problem-solving across multiple parties. |
| Trade compliance advisory | Resilient | Requires legal interpretation, regulatory expertise, and judgement on novel situations. |
| Supplier / carrier relationship management | Resilient | Trust, negotiation, and long-term strategic relationship building remain human-intensive. |
| Air/ocean charter procurement | Medium | Digital charter platforms exist but complex, high-stakes, or sensitive charters still need broker expertise. |

#### Retail / Ecommerce DC Operations

| Task | Risk Level | Evidence / Reasoning |
|---|---|---|
| Single-item order picking | High | Robotic pick walls and AMRs are proven at scale (Amazon, Ocado, Walmart) |
| Parcel packing (right-sized box, dunnage) | Medium | Automated packaging machines (e.g. Packsize, CMC) are proven but capital-intensive |
| Carton sealing / labelling | High | Fully automated sealers and label applicators are standard |
| Returns induction / sorting | High | Automated returns processing lines (e.g. Optoro) are proven |
| Multi-line order consolidation | Medium | Goods-to-person makes consolidation easier but full automation of multi-SKU orders is still maturing |
| Quality inspection | Medium | Computer vision for visual defects works well; sensory checks (textile feel, food freshness) still need humans |
| Value-added services (kitting, ticketing, gift wrapping) | Low-Medium | Highly variable — some aspects automatable, others require human dexterity |

#### Cross-Border / International Logistics

| Task | Risk Level | Evidence / Reasoning |
|---|---|---|
| Export/import documentation | High | Digital platforms with template-based filings |
| Duty and tax calculation | High | Automated duty calculators are mature |
| Restricted party screening | High | Automated sanctions screening in all TMS/ERP platforms |
| Free trade agreement qualification | Medium | AI-driven FTA qualification exists but complex supply chains still need analysis |
| DDP/DAP process management | Medium | Digital customs brokerage handles standard DDP — exceptions still need humans |
| Multi-modal routing decision | Medium | TMS optimisation engines handle standard lanes — complex multi-modal with multiple handoffs still needs human oversight |

---

## Adoption Curve Guidance

The verdict is not just whether automation *exists* but whether it will *reach the client* within 12 months. Use these adoption curve indicators:

| Indicator | Early (Not Yet Relevant) | Mainstream (Plan Now) | Late (Too Late to React — Disruption Already Here) |
|---|---|---|---|
| Amazon deployment | No public deployment | Beta or limited deployment | At scale in multiple DCs |
| 3PL peer adoption | <10% of similar operations | 10-40% | >40% |
| VC funding in the space | Nascent | Growing rapidly | Peak funding (market is moving to execution) |
| Cost of technology | >3x labour cost equivalent | 1-3x labour cost | Below labour cost |
| Integration difficulty | Custom build required | Off-the-shelf with moderate configuration | Plug-and-play |
| Lab our availability for the role | Ample | Tightening | Critical shortage |

---

## Red Flags That Accelerate Disruption

These factors mean the disruption timeline is *shorter* than the baseline:

- **Client has >10 FTEs doing a single repetitive task** (data entry, order processing, customs documentation)
- **Client's largest customers are Amazon, Walmart, or a major retailer** (they will demand automation compatibility)
- **Client operates in a high-labour-cost market** (US, Western Europe, Australia)
- **Client's contracts have auto-renewal at risk** from more automated competitors
- **Client is manually re-keying data between systems** (high vulnerability — easy automation target)
- **Client's margins are below 5%** (no buffer to absorb disruption — must act faster)
- **Client serves ecommerce or fast-fashion** (high volatility, low tolerance for manual processing)

---

## What This Framework Does Not Cover

- **General AI / LLM workplace disruption** (e.g. knowledge work automation in corporate functions) — this is outside logistics operations scope
- **Autonomous long-haul trucking** — the 12-month horizon is too short for regulatory and infrastructure hurdles in most markets; revisit annually
- **Humanoid general-purpose robots** — fundamentally not ready within the assessment horizon despite media hype
- **Geo-political disruption** (tariffs, trade wars, sanctions) — outside scope of automation assessment; the client needs trade strategy advice, not AI impact
