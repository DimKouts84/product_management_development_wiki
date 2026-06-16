# ⚠️ 07 · Risk Management

> **Risk comes from not knowing what you're doing.** — Warren Buffett

This section covers the frameworks for identifying, assessing, and mitigating project risks, along with a catalog of common anti-patterns that sabotage product teams.

---

## Section Overview

```mermaid
graph TD
    R["⚠️ Risk Management"] --> RM["Risk Management"]
    R --> AP["Anti-Patterns"]

    RM -->|"Anti-patterns are risks"| AP
    AP -->|"Inform mitigation in"| RM

    RM -.->|"Feeds into"| RETRO["08 · Retrospectives"]
    AP -.->|"Lessons from"| STRAT["03 · Strategy"]
    RM -.->|"Protects"| DEV["04 · Development"]

    style R fill:#ea580c,stroke:#c2410c,color:#fff
    style RM fill:#fb923c,stroke:#ea580c,color:#000
    style AP fill:#fb923c,stroke:#ea580c,color:#000
    style RETRO fill:#4f46e5,stroke:#4338ca,color:#fff
    style STRAT fill:#d97706,stroke:#b45309,color:#fff
    style DEV fill:#dc2626,stroke:#b91c1c,color:#fff
```

---

## Pages in This Section

| Page | Status | Description |
|:-----|:------:|:------------|
| [Risk Management](risk-management.md) | 🟢 | Risk matrices, likelihood vs. impact, risk management plans |
| [Anti-Patterns](anti-patterns.md) | 🟢 | Feature Factory, HIPPO, Scope Creep, and 7 more anti-patterns |

---

## Key Concepts at a Glance

- **Risk Matrix**: Plotting likelihood × impact to categorize risks
- **Risk Management Plan**: Structured documentation of risks with indicators and action plans
- **Anti-Pattern**: A commonly occurring situation with negative consequences
- **Root Cause Analysis**: Going beyond symptoms to identify underlying problems

---

## Related Sections

- ← [04 · Development](../04-development/index.md) — Development risks and estimation pitfalls
- ← [03 · Strategy](../03-strategy/index.md) — Strategic risks in prioritization
- → [08 · Retrospectives](../08-retrospectives/index.md) — Learn from risks that materialized

---

*[← Back to Wiki Home](../index.md)*
