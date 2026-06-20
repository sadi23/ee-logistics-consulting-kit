# ee-logistics-consulting-kit

**AI-powered skillset for independent cross-border logistics consultants.**

Adapted from the career-helper agentic plugin pattern by Prosper AI Consulting.  
Repurposed for supply chain operations professionals who sell expertise, not hours.

---

## What This Is

A structured collection of agentic skills designed for an independent logistics consultant. Each skill is a self-contained module that can be loaded by an agent orchestrator (Hermes, Claude Code, or compatible system) to help you:

- **Position yourself** as the go‑to expert in your lane
- **Audit a prospect's operation** before you pitch
- **Win proposals** with structured, evidence-based responses
- **Manage engagements** from lead gen through contract negotiation to win-loss analysis
- **Assess AI/automation disruption** in a client's supply chain and sell mitigation
- **Build a credible LinkedIn presence** that attracts supply chain decision-makers

---

## Skills (6 + 1 Getting Started)

| Skill | Purpose |
|-------|---------|
| **Personal Brand** | Why You / Why Them / Why Now positioning. Audience & channel map for supply chain. Bio library (LinkedIn, speaker, proposals, podcast). |
| **Client Footprint** | Audit a prospect's or client's operational + digital footprint. Scored dashboard (1–10) across customs, carrier mix, tech stack, exceptions, TCO. |
| **Pitch Master** | RFP & proposal preparation. Mock client Q&A (procurement panel persona). Post-pitch gap analysis and rejection recovery. |
| **Engagement Navigator** | Lead gen strategy, rate/contract negotiation (UK/US/EU/APAC), pipeline tracker, win-loss analysis loop. |
| **Supply Chain AI Impact** | Research whether AI/automation will disrupt a client's logistics operation in 12 months. Evidence-based assessment + 6-month mitigation plan. |
| **LinkedIn Coach** | Profile audit, headline optimisation, content strategy calibrated for supply chain audiences. |
| **Getting Started** | Orientation, workflow planning, session setup. |

**Orchestrator Agent:** `consultant-coach` sequences and routes — like having a practice manager that keeps context across sessions.

---

## Architecture

```
lc-kit/
ee-logistics-consulting-kit/
├── agents/            # Orchestrator agent (consultant-coach)
├── commands/          # Entry points (getting-started, help, quick-start)
├── skills/            # 7 skills, each with SKILL.md + references/ + templates/
└── .claude-plugin/    # Plugin manifest
├── README.md
├── LICENSE
├── CHANGELOG.md
└── .gitignore
```

---

## Use With

- **Hermes Agent** – Load skills via `skill_view()`, orchestrate with the consultant-coach agent
- **Claude Code / Desktop** – Install as a plugin from this repo
- **Any agent framework** – The SKILL.md structure is human-readable and framework-agnostic

---

## License

CC BY-NC 4.0 – Free to adapt for personal/consulting use. Commercial redistribution requires permission.
