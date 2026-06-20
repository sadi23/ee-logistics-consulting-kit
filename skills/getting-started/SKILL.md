---
name: getting-started
description: Orientation, workflow planning, session setup, and power user strategies for the EE Logistics Consulting Kit. First skill to load when starting a new engagement or session.
tags: onboarding, getting-started, setup, workflow, ee-logistics-consulting-kit
version: 1.0.0
---

# Getting Started — Logistics Consultant Kit

## Capabilities

| # | Capability | When to Use |
|---|------------|-------------|
| 1 | Session Setup | First time using LC-Kit or starting a new engagement |
| 2 | Skill Navigator | Not sure which skill to start with |
| 3 | Workflow Planner | Building a multi-session engagement plan |
| 4 | Quick Reference | Need a reminder of available skills and commands |

## Quick Start Prompts

```
"What can this kit do?"
"Help me get set up for a new client engagement"
"I'm not sure where to start — walk me through my options"
"Set up my workspace for [client name]"
"Show me all available skills"
"I need a 90-day engagement plan"
```

## Entry Flow

### First Session

1. **Check for** `ee-logistics-consulting-kit-preferences.md` in the working directory. If found, read YAML frontmatter.
2. **If no preferences exist**, ask 2 questions (one at a time):
   - "What's your current situation? New client engagement, building pipeline, or refining your positioning?"
   - "Any accessibility preferences I should know about? (e.g., dyslexia-friendly formatting, colour-blind safe outputs)"
3. If user has accessibility needs, save to `ee-logistics-consulting-kit-preferences.md`.

### Returning Session

1. Load `ee-logistics-consulting-kit-preferences.md` if present.
2. Check for a workspace directory structure under `engagements/{client-slug}/`.
3. Ask: "Picking up where we left off, or starting something new?"

## Available Skills

| Skill | Command | Purpose |
|-------|---------|---------|
| **Personal Brand** | `/personal-brand` | Positioning, audience map, bio library |
| **Client Footprint** | `/client-footprint` | Operational + digital audit dashboard |
| **Pitch Master** | `/pitch-master` | Proposal prep, mock pitch, post-pitch analysis |
| **Engagement Navigator** | `/engagement-navigator` | Lead gen, rate negotiation, pipeline, win-loss |
| **Supply Chain AI Impact** | `/supply-chain-ai-impact` | AI disruption assessment + mitigation plan |
| **LinkedIn Coach** | `/linkedin-coach` | Profile audit, content strategy, headline |

## Workspace Structure

```
engagements/
  {client-slug}/
    footprint-audit.md
    pitch-prep.md
    negotiation-strategy.md
    pipeline.md
    win-loss-analysis.md
```

Output files are saved into `engagements/{client-slug}/` when tied to a specific client, or workspace root for general work.

## Related Skills

- `/consultant-coach` — Guided orchestration across all skills
- `/personal-brand` — Positioning before you pitch new clients
- `/client-footprint` — Audit before you quote

## Save This

When asked to save session state, create `ee-logistics-consulting-kit-session-state.md` with:
- Current client(s)
- Last skill used
- Pending next actions
- Any incomplete workflows
