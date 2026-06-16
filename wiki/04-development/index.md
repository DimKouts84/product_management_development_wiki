# ⚙️ 04 · Development

> **Translate strategy into actionable, estimable, and testable work.**

This section covers the mechanics of turning product decisions into development work — writing requirements, estimating effort, and defining acceptance criteria that ensure quality delivery.

---

## Section Overview

```mermaid
graph TD
    DEV["⚙️ Development"] --> RUS["Requirements & User Stories"]
    DEV --> EV["Estimations & Velocity"]
    DEV --> AC["Acceptance Criteria"]

    RUS -->|"Stories are estimated by"| EV
    EV -->|"Sprint capacity drives"| AC
    AC -->|"Validates delivery for"| RETRO["08 · Retrospectives"]

    RUS -.->|"Sourced from"| DISC["02 · Discovery"]
    AC -.->|"Tested against"| RISK["07 · Risk Management"]

    style DEV fill:#dc2626,stroke:#b91c1c,color:#fff
    style RUS fill:#f87171,stroke:#dc2626,color:#fff
    style EV fill:#f87171,stroke:#dc2626,color:#fff
    style AC fill:#f87171,stroke:#dc2626,color:#fff
    style RETRO fill:#4f46e5,stroke:#4338ca,color:#fff
    style DISC fill:#059669,stroke:#047857,color:#fff
    style RISK fill:#ea580c,stroke:#c2410c,color:#fff
```

---

## Pages in This Section

| Page | Status | Description |
|:-----|:------:|:------------|
| [Requirements & User Stories](requirements-user-stories.md) | ⚪ | Business, functional, non-functional requirements; user story format; INVEST criteria |
| [Estimations & Velocity](estimations-velocity.md) | ⚪ | Story points, Fibonacci estimation, velocity tracking |
| [Acceptance Criteria](acceptance-criteria.md) | ⚪ | Given-When-Then templates, verification lists |

---

## Key Concepts at a Glance

- **User Story Format**: *"As a ____, I want ____, so that ____"*
- **INVEST Criteria**: Independent, Negotiable, Valuable, Estimatable, Small, Testable
- **Story Points**: Relative effort estimation using Fibonacci sequence
- **Velocity**: Work Accomplished ÷ Time
- **Given-When-Then**: Structured acceptance criteria template

---

## Related Sections

- ← [03 · Strategy](../03-strategy/index.md) — Roadmap items become development stories
- ← [02 · Discovery](../02-discovery/index.md) — Requirements sourced from discovery
- → [07 · Risk Management](../07-risk-management/index.md) — Identify risks in development
- → [08 · Retrospectives](../08-retrospectives/index.md) — Review delivery quality

---

*[← Back to Wiki Home](../index.md)*
