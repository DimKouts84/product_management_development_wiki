# 🔁 08 · Retrospectives

> **We do not learn from experience. We learn from reflecting on experience.** — John Dewey

This section covers the essential practice of looking back — conducting internal retrospectives to improve team processes, and gathering external feedback to improve the product.

---

## Section Overview

```mermaid
graph TD
    RET["🔁 Retrospectives"] --> RF["Retrospectives & Feedback"]

    RF -->|"Internal learnings"| INT["Team Process Improvements"]
    RF -->|"External feedback"| EXT["Product Improvements"]

    INT -.->|"Improve"| DEV["04 · Development"]
    EXT -.->|"Feed back into"| DISC["02 · Discovery"]
    EXT -.->|"Validate"| MET["06 · Metrics"]

    style RET fill:#4f46e5,stroke:#4338ca,color:#fff
    style RF fill:#818cf8,stroke:#4f46e5,color:#fff
    style INT fill:#c7d2fe,stroke:#818cf8,color:#000
    style EXT fill:#c7d2fe,stroke:#818cf8,color:#000
    style DEV fill:#dc2626,stroke:#b91c1c,color:#fff
    style DISC fill:#059669,stroke:#047857,color:#fff
    style MET fill:#0891b2,stroke:#0e7490,color:#fff
```

---

## Pages in This Section

| Page | Status | Description |
|:-----|:------:|:------------|
| [Retrospectives & Feedback](retrospectives-feedback.md) | ⚪ | Sprint retrospectives, post-mortems, user feedback collection |

---

## Key Concepts at a Glance

- **Sprint Retrospective**: What went well, what didn't, what to improve
- **Post-Mortem**: Structured analysis after major incidents or launches
- **User Feedback Loops**: Continuous collection and integration of user sentiment
- **Continuous Improvement**: The retrospective cycle feeds back into discovery

---

## The Continuous Improvement Loop

```mermaid
graph LR
    A["Build"] --> B["Measure"]
    B --> C["Learn"]
    C --> D["Adjust"]
    D --> A

    style A fill:#dc2626,stroke:#b91c1c,color:#fff
    style B fill:#0891b2,stroke:#0e7490,color:#fff
    style C fill:#4f46e5,stroke:#4338ca,color:#fff
    style D fill:#059669,stroke:#047857,color:#fff
```

---

## Related Sections

- ← [04 · Development](../04-development/index.md) — Review development process effectiveness
- ← [06 · Metrics](../06-metrics/index.md) — Use metrics data in retrospectives
- → [02 · Discovery](../02-discovery/index.md) — Feed learnings back into the next discovery cycle

---

*[← Back to Wiki Home](../index.md)*
