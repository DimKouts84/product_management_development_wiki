# 🎯 03 · Strategy

> **Decide what to build, when to build it, and how to bring it to market.**

Product strategy bridges the gap between discovery insights and development execution. This section covers prioritization frameworks, go-to-market planning, and roadmap creation.

---

## Section Overview

```mermaid
graph TD
    S["🎯 Strategy"] --> FP["Feature Prioritization"]
    S --> GTM["Go-to-Market"]
    S --> RP["Roadmap Planning"]
    S --> ASO["App Store Optimization"]

    FP -->|"Ranked features feed"| RP
    RP -->|"Timeline drives"| GTM
    GTM -.->|"Informed by"| ASO
    GTM -->|"Launch validates"| MET["06 · Metrics"]

    FP -.->|"Uses data from"| DISC["02 · Discovery"]
    RP -.->|"Produces work for"| DEV["04 · Development"]
    ASO -.->|"Acquisition feeds"| ONB["05 · Design"]

    style S fill:#d97706,stroke:#b45309,color:#fff
    style FP fill:#fbbf24,stroke:#d97706,color:#000
    style GTM fill:#fbbf24,stroke:#d97706,color:#000
    style RP fill:#fbbf24,stroke:#d97706,color:#000
    style ASO fill:#fbbf24,stroke:#d97706,color:#000
    style MET fill:#0891b2,stroke:#0e7490,color:#fff
    style DISC fill:#059669,stroke:#047857,color:#fff
    style DEV fill:#dc2626,stroke:#b91c1c,color:#fff
    style ONB fill:#ec4899,stroke:#db2777,color:#fff
```

---

## Pages in This Section

| Page | Status | Description |
|:-----|:------:|:------------|
| [Feature Prioritization](feature-prioritization.md) | 🟢 | RICE methodology, decision matrices, cost-value analysis |
| [Go-to-Market](go-to-market.md) | 🟢 | GTM strategy, A/B testing, launch planning |
| [App Store Optimization](app-store-optimization.md) | 🟢 | Keyword strategy, screenshot conversion, review loops |
| [Roadmap Planning](roadmap-planning.md) | 🟢 | Product roadmaps, WBS, task dependencies, Gantt/PERT/CPM charts |

---

## Key Concepts at a Glance

- **RICE Scoring**: Reach × Impact × Confidence ÷ Effort
- **Cost-Value Matrix**: Plotting features by development cost vs. business value
- **Go-to-Market**: Who, how, where, and when to launch
- **ASO Pillars**: Keyword optimization, CVR screenshot hooks, and review prompts
- **Work Breakdown Structure**: Hierarchical decomposition of deliverables
- **Critical Path Method**: Identifying the longest dependency chain

---

## Related Sections

- ← [02 · Discovery](../02-discovery/index.md) — Research insights that inform strategy
- → [04 · Development](../04-development/index.md) — Execute the strategic roadmap
- → [06 · Metrics](../06-metrics/index.md) — Measure strategic outcomes

---

*[← Back to Wiki Home](../index.md)*
