---
name: client-footprint
description: Operational and digital footprint audit through a client's or prospect's supply chain lens. Scored dashboard (1-10) across customs compliance, carrier mix, tech stack, exception rates, TCO, and digital presence.
tags: footprint, audit, due-diligence, operations, compliance, supply-chain, logistics, 3pl, shipping, assessment
version: 1.0.0
---

# Client Footprint Analysis

Operational and digital footprint audit for logistics consulting. A deep-research swarm assessment of a client's or prospect's supply chain operations, synthesised into a scored dashboard with actionable recommendations for engagement strategy and service positioning.

## Capabilities

| # | Capability | When to Use |
|:-:|:-----------|:------------|
| 1 | Full Footprint Analysis | Complete operational + digital audit of a prospect or client |
| 2 | Operations Audit | Focused deep-dive on logistics operations indicators |
| 3 | Digital Presence Check | How the company presents itself to potential partners and customers |
| 4 | Competitor Benchmark | Compare a client's operation against peer companies |

## Quick Start

```
"Audit this 3PL before I engage them"
"What would I find if I checked XYZ Logistics?"
"Benchmark my operation against competitors"
"Run a footprint on this prospect for our next meeting"
```

---

## How It Works

This skill uses an **agentic deep-research swarm** approach:

1. **You provide** the company name, sector, key contacts, and any available operational data
2. **Parallel research agents** scan publicly available data across supply chain, financial, and digital channels simultaneously
3. **Operations lens analysis** interprets findings through logistics consulting frameworks
4. **Dashboard synthesis** produces a scored output with RED/AMBER/GREEN indicators
5. **Engagement strategy** recommends next steps for positioning, pricing, and approach

---

## Pre-Engagement Checklist

Before initiating the footprint analysis, clarify what information will be used.

### OSINT-Only Analysis
- **Required from consultant:** Company name, sector, website.
- **Process:** The analysis will be conducted using only publicly available Open-Source Intelligence (OSINT). This provides a view of the company that any competitor or customer could obtain.
- **Advantage:** Fast, no client interaction required, good for initial prospecting.
- **Limitation:** Data confidence may be low in some areas (e.g., specific cost data, internal KPIs).

### Client-Assisted Analysis
- **Required from consultant:** All of the above, plus any data the client is willing to share.
- **Process:** The OSINT analysis is augmented and verified with client-provided data.
- **Advantage:** Higher data confidence, more accurate scoring, demonstrates partnership.
- **Limitation:** Requires client trust and willingness to share potentially sensitive information.

**Recommendation:** Start with an OSINT-only analysis for initial qualification and use the findings to build a case for a deeper, client-assisted audit during the first engagement meeting.

---

## Input Gathering

Before starting any analysis, collect the following:

### Required Information

**Question 1: Company Details**
"To run the client footprint, I need some basics. What is the full company name and what sector do they operate in?"

**Question 2: Operational Context**
"What do you already know about their operations? Any details help:"
- Estimated shipment volume (per month or year)
- Primary modes (FTL, LTL, parcel, ocean, air, rail)
- Known customers or industries served
- Existing 3PL relationships (who they currently use)
- Any known pain points (service failures, cost pressure, compliance issues)

**Question 3: Data Available**
"Do you have any operational data you can share? This could be:"
- Carrier scorecards or KPI reports
- TCO or cost-per-shipment data
- Freight audit reports
- Warehouse metrics (if warehousing is in scope)
- Customer satisfaction or NPS data
- Any internal assessments already done

**Question 4: Strategic Context**
"What is the purpose of this assessment? For example:"
- New business development (qualifying a prospect)
- Account review (expanding an existing client)
- Competitive intelligence (benchmarking a competitor)
- M&A due diligence (evaluating an acquisition target)

**Question 5: Specific Concerns**
"Is there anything specific you are worried about or want me to focus on? For example: compliance risks over-reliance on a single carrier technology concerns or financial stability."

---

## 1. Full Footprint Analysis

**What you need:** Company name + sector + available data + strategic context
**Load:** @references/digital-footprint-audit.md
**Template:** @references/dashboard-template.md

Agentic parallel research covering eight dimensions simultaneously.

### Research Swarm Architecture

Launch parallel research agents for each dimension simultaneously:

```
                                CLIENT FOOTPRINT RESEARCH SWARM
                                                   
   Agent 1          Agent 2          Agent 3          Agent 4
   Customs &        Carrier Mix      Tech Stack       Exception
   Compliance       Analysis         Audit            Rate Analysis
                                                   
   Agent 5          Agent 6          Agent 7          Agent 8
   Total Cost       Digital          Financial        News &
   to Serve         Visibility       Health           Sentiment
                                                   
         SYNTHESIS & DASHBOARD ENGINE
    Score each dimension (1-10)
    Flag strengths and risks
    Map to service opportunity
    Generate engagement strategy
```

### Dimensions Assessed

| Dimension | What We Check | Agent |
|:----------|:-------------|:------|
| **Customs Compliance** | Regulatory filings, customs broker use, duty management, compliance record, denied party screening, recent penalties | Agent 1 |
| **Carrier Diversification** | Number of carriers used, concentration risk, mode coverage, rate competitiveness, contract structure | Agent 2 |
| **Technology Maturity** | TMS/WMS usage, integration capabilities, API readiness, tracking visibility, EDI status, automation level | Agent 3 |
| **Exception Rate** | On-time performance, claims rate, damage ratio, misshipments, accessorial charges trend, root cause data | Agent 4 |
| **Total Cost to Serve** | Freight cost as % of revenue, average cost per shipment, cost trend vs market, cost allocation granularity | Agent 5 |
| **Digital Visibility** | Company website, digital marketing, online reviews, social media presence, thought leadership, brand positioning | Agent 6 |
| **Financial Health** | Revenue trend, margin indicators, credit rating, ownership structure, payment history, D&B rating | Agent 7 |
| **Market Reputation** | Industry mentions, customer reviews, news coverage, awards, complaints, partner relationships | Agent 8 |

### Scoring Dimensions

Each dimension scored 1-10 with text-label rating (GREEN/AMBER/RED):

| Dimension | What It Measures |
|:----------|:----------------|
| **Customs Compliance** | Regulatory rigour, penalty history, broker quality, denied party exposure |
| **Carrier Diversification** | Concentration risk, mode coverage, rate competitiveness, contract health |
| **Technology Maturity** | TMS/WMS capability, integration posture, automation, visibility tools |
| **Exception Rate** | Service reliability, claims experience, root cause capability |
| **Total Cost to Serve** | Cost competitiveness, trend analysis, allocation granularity |
| **Digital Visibility** | Online brand strength, website quality, market positioning |
| **Financial Stability** | Revenue health, margin quality, ownership stability, creditworthiness |
| **Market Reputation** | Industry standing, customer sentiment, partnerships, awards |

**Output:** `{company-slug}-footprint-dashboard.md`

---

## 2. Operations Audit

**What you need:** Company name + sector + operational data (as available)
**Load:** @references/digital-footprint-audit.md (operations sections)
**Template:** @references/dashboard-template.md

Focused deep-dive on operational indicators only:

- Customs and trade compliance posture
- Carrier mix and concentration analysis
- Technology stack assessment
- Exception rate and service quality trends
- Total cost to serve modelling
- Root cause analysis capability

**Output:** `{company-slug}-operations-audit.md`

---

## 3. Digital Presence Check

**What you need:** Company name + website URL + competitors (optional)

Focused assessment of digital footprint and market positioning:

- Website quality and messaging
- SEO and online findability
- Social media presence (LinkedIn, Twitter/X, YouTube)
- Google Maps and directory listings
- Customer reviews and ratings
- Thought leadership content
- Digital marketing effectiveness
- Competitor comparison of digital presence

**Output:** `{company-slug}-digital-presence.md`

---

## 4. Competitor Benchmark

**What you need:** Company name + 2-4 competitor names
**Template:** @references/dashboard-template.md

Side-by-side comparison across all eight dimensions:

- Dimension-by-dimension scoring
- Relative strengths and weaknesses
- Market positioning map
- Service opportunity identification
- Gaps in competitor coverage that the client could exploit
- Recommended consulting angle

**Output:** `{company-slug}-competitor-benchmark.md`

---

## Output Standards

- **UK English** throughout
- **No emojis** - professional consulting tone
- **Cited sources** - All findings include URLs and access dates where available
- **Text-label ratings** -- GREEN/AMBER/RED as text, never colour alone
- **Evidence-based** - Every flag backed by specific findings
- **Never invent data** - Mark missing info as `[NOT FOUND]` or `[NOT PUBLICLY AVAILABLE]`
- **Confidence indicators** - Distinguish between confirmed facts and reasonable inference

### Tone of Voice

- Address the user as "you" -- direct and peer-level
- Numbers and outcomes first in every section
- Avoid hyperbole (not "game-changing" or "revolutionary")
- Use the **Oxford comma** (serial comma: "carrier mix, tech stack, and exception rates")
- Never use em dashes. Use commas, semicolons, colons, or full stops instead.

### Template Usage

When a capability specifies a template, you must:
1. Load the template first
2. Follow the template structure exactly
3. Preserve template footers

### Working with Blocked Content

When direct access is blocked (company financials, restricted data):
- Use alternative public sources (Companies House, D&B, industry reports)
- Ask the user for internal data they can share
- Only request sensitive data if it is essential for the engagement decision
- Mark restricted items as `[NOT PUBLICLY AVAILABLE]`

---

## Parallel Execution Strategy

**Use parallel Task tool calls for maximum speed and depth.**

```
Wave 1 (Parallel):
- Task Agent: Customs compliance research (company, parent, subsidiaries)
- Task Agent: Carrier mix analysis (public filings, case studies, press releases)
- Task Agent: Tech stack discovery (job postings, integration listings, case studies)
- WebSearch: Exception rate indicators (reviews, forums, case studies)
- WebSearch: Financial health (Companies House, D&B, credit reports)

Wave 2 (After Wave 1 results):
- Task Agent: Deep-dive on flagged compliance or financial risks
- Task Agent: Cross-reference digital presence against operational claims
- WebSearch: Fill identified gaps
- WebSearch: Customer and partner sentiment analysis

Wave 3 (Synthesis):
- Score all eight dimensions
- Generate dashboard
- Map to service opportunities
- Generate engagement strategy
```

---

## Engagement Strategy Output

After completing the footprint analysis, provide a clear consulting recommendation:

| Scenario | Recommended Approach |
|:---------|:--------------------|
| Strong across all dimensions | Premium consulting -- strategic advisory, optimisation, growth |
| Operations strong, tech weak | Technology assessment and TMS/WMS implementation consulting |
| Compliance weak, other strong | Urgent compliance remediation before operational engagement |
| Carrier concentration high | Procurement and carrier diversification consulting |
| Financial concerns | Payment terms restructuring, cash flow optimisation |
| Weak digital presence | Marketing and brand positioning consulting |
| Multiple RED scores | Caution -- limited scope engagement or pass |

---

## Related Skills and Tools

- **/supply-chain-ai-impact** - Assess client's readiness for AI/automation disruption.
- **/pitch-master** - Use the footprint audit data to build a compelling, evidence-based proposal.
- **/engagement-navigator** - The audit results can inform your negotiation strategy and terms.


---

*Client Footprint Analysis v1.0.0 | Logistics Consulting Toolkit | Prosper AI Consulting, UK*
