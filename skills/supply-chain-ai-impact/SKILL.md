---
name: supply-chain-ai-impact
description: Evidence-based assessment of whether AI and automation will materially disrupt a client's logistics operations within 12 months. Delivers a frank assessment with a 6-month mitigation plan.
tags: ai-impact, automation, disruption, supply-chain, logistics, future-proof, mitigation
version: 1.0.0
---

# Supply Chain AI Impact

> **Disclaimer:** This skill provides an operational assessment based on publicly available data, industry reports, and the consultant's professional experience. It is not financial, investment, or legal advice. The findings represent a snapshot in time in a rapidly evolving field. All investment decisions should be made in consultation with qualified financial and legal professionals.

## Overview

This skill helps you assess whether AI and automation will materially disrupt a client's logistics operations within the next 12 months — and what to do about it.

It works in two phases:

**Phase 1 — Research (system reasoning, not shown to client):** Targeted web search queries against the client's specific operations. Cross-references WEF Future of Jobs, McKinsey automation research, industry reports, and logistics automation case studies to identify which tasks, roles, and processes face disruption versus which are structurally resilient.

**Phase 2 — Assessment & Plan (deliverable output):** A direct, evidence-based verdict. It names what is at risk, what is resilient, and puts a timeline on the disruption. It then delivers a concrete 6-month month-by-month mitigation plan so the client leaves with agency, not just anxiety.

Two ground rules:
1. **Open with facts, not comfort.** Sugar-coating helps nobody. The client is paying for truth.
2. **End with agency and a plan.** Do not leave the client paralysed. Every risk gets a countermeasure. Every countermeasure gets a month assigned.

---

## Capabilities

### A: AI Impact Assessment

A full disruption research + mitigation plan for a logistics operation.

**Input you need from the client:**

| Piece of Information | Why It Matters |
|---|---|
| Operation type (3PL, freight forwarder, manufacturer, retailer DC) | Different operations face different disruption profiles |
| Annual shipment/order volume | Scale determines automation viability thresholds |
| Primary geographies served | Labour markets and automation adoption vary by region |
| Current tech stack (WMS, TMS, ERP, anything homegrown) | Legacy systems are often the bottleneck — or the vulnerability |
| Labour mix (FT vs temporary, skilled vs unskilled, unionised?) | Workforce composition determines transition difficulty |
| Key customer requirements (OTIF targets, EDI/API, VMI, labelling, customs documentation) | Customer demands may force automation faster than the client wants |
| Average margin per shipment or order | Thin margins leave no room to absorb disruption passively |
| Top 3 operational pain points today | Existing pain points are often where disruption lands first |

**Output:**

1. **Disruption Verdict** — A frank assessment of which tasks, roles, and processes in the client's operation are:
   - **High Risk** — Likely automated or fundamentally changed within 12 months
   - **Medium Risk** — Shifting within 12–24 months; action needed this year to stay ahead
   - **Resilient** — Human judgement, exception handling, or relationship-based work unlikely to be disrupted soon

2. **Timeline** — When the disruption will actually hit, not when the headlines say it will. Based on adoption curves in the client's specific geography and vertical.

3. **6-Month Mitigation Plan** — Month-by-month actions the client can take. Each month has one primary action, one secondary action, and a measurable milestone.

4. **Commercial Upside** — Where automation is not a threat but an opportunity for the client. A candid assessment of whether they should be the disruptor, not the disrupted.

**Quick start prompts:**

- "Will AI disrupt this 3PL's operations?"
- "Assess how automation will affect this warehouse network"
- "What's the AI risk for our cross-border operation?"
- "Help me sell an AI readiness assessment to this client"

### B: AI Readiness Conversation Guide

Use this when you are in discovery with a prospect and want to open the AI/automation conversation without sounding like a vendor pushing fear. The goal is to surface whether they are thinking about disruption — and whether they are ready to act.

**Opening questions:**

1. "If you look at your operation today, which tasks do you think could be automated in the next two years, and which ones couldn't?"
2. "Have any of your customers asked about AI, robotics, or automation capabilities in your RFPs or QBRs?"
3. "What's your current approach to technology investment — are you a fast follower, a cautious adopter, or waiting for the market to settle?"
4. "What keeps you up at night about the impact of AI on logistics?"
5. "If a competitor adopted automation that let them offer 20% lower rates, what would you do?"

**Red flags that signal urgency:**

- "We haven't really thought about it" (in a role where they should have)
- "Our customers haven't asked yet" (they will — usually without warning)
- "We tried automation once and it didn't work" (likely a specific vendor failure, not a strategy failure)
- "Our margins are too thin to invest" (the exact reason they cannot afford to wait)

---

## Two-Phase Assessment Protocol

### Phase 1: Research (system-side, not shared with client directly)

For each assessment, conduct targeted research using these queries, adapted to the client's specifics:

1. `[task/role] automation logistics [year] case study`
2. `[task/role] AI impact supply chain WEF McKinsey [year]`
3. `[geography/region] warehouse automation adoption rate [year]`
4. `[task/role] resilience to automation logistics`
5. `[operation type] technology disruption [task]`

Cross-reference findings against the sources listed in `references/disruption-research.md`. Classify each task/role/process as High Risk, Medium Risk, or Resilient using the task-level assessment framework.

### Phase 2: Assessment & Plan (client-facing deliverable)

Structure the client-facing output as follows:

1. **Executive Summary** (3–5 bullet points capturing the verdict)
2. **Disruption Assessment** by task/role/process, with risk level and supporting evidence
3. **Timeline** (short-term, medium-term, long-term disruption windows)
4. **What's Safe** (resilient tasks — where human judgement still matters)
5. **6-Month Mitigation Plan** (month-by-month, from `references/mitigation-plan.md`)
6. **Commercial Upside** (where the client can lead rather than react)
7. **Open Questions** (what else needs investigation)

---

## References

- `references/disruption-research.md` — Research methodology, source list, and task-level assessment framework
- `references/mitigation-plan.md` — 6-month mitigation plan template with specific actions, month-by-month

---

## Related Skills

- **/client-footprint** — Use before AI impact assessment to build a baseline of the client's operational and digital footprint
- **/pitch-master** — Use the AI impact assessment as the centrepiece of a proposal: "You need an AI readiness audit"
