# Feature Prioritization

> **Understand what, why, and when to create a product or feature.**

---

## Table of Contents

- [Decision Matrix](#decision-matrix)
- [RICE Methodology](#rice-methodology)
- [Cost-Value Matrix](#cost-value-matrix)
- [Problem Sense](#problem-sense)
- [Prioritization Risks](#prioritization-risks)

---

## Decision Matrix

A simple weighted scoring model for comparing features:

| Feature | Business Value (1-5) | Development Effort (1-5) | User Impact (1-5) | **Total Score** |
|:--------|:-------------------:|:------------------------:|:-----------------:|:--------------:|
| Feature A | — | — | — | — |
| Feature B | — | — | — | — |
| Feature C | — | — | — | — |

> [!TIP]
> Weight each dimension differently based on your strategic focus. For a growth-stage product, **User Impact** might be weighted 2×. For a mature product, **Business Value** may take priority.

---

## RICE Methodology

```mermaid
graph LR
    R["📣 Reach\nHow many users affected?"] --> CALC["🧮 RICE Score"]
    I["💥 Impact\nHow much per user?"] --> CALC
    C["🎯 Confidence\nHow sure are we?"] --> CALC
    E["⚡ Effort\nPerson-months needed"] --> CALC

    CALC --> RESULT["Score = R × I × C ÷ E"]

    style R fill:#2563eb,stroke:#1e40af,color:#fff
    style I fill:#dc2626,stroke:#b91c1c,color:#fff
    style C fill:#059669,stroke:#047857,color:#fff
    style E fill:#d97706,stroke:#b45309,color:#fff
    style CALC fill:#7c3aed,stroke:#6d28d9,color:#fff
    style RESULT fill:#4f46e5,stroke:#3730a3,color:#fff
```

### RICE Components

| Component | Definition | Scale |
|:----------|:-----------|:------|
| **Reach** | How many people will this affect over a specific period? | Absolute number (e.g., users/quarter) |
| **Impact** | How much will it change the user experience per user reached? | 0.25 (minimal) → 0.5 → 1.0 → 2.0 → 3.0 (massive) |
| **Confidence** | How sure are you about reach, impact, and effort estimates? | 50% (low) → 80% (medium) → 100% (high) |
| **Effort** | How many person-months will this require? | Person-months |

> **RICE Score** = (Reach × Impact × Confidence) / Effort

---

## Cost-Value Matrix

Define goals for the next 6 months and create a roadmap with high-level goals that create value and impact.

```mermaid
quadrantChart
    title Cost-Value Feature Prioritization
    x-axis "Low Cost" --> "High Cost"
    y-axis "Low Value" --> "High Value"
    quadrant-1 "Do Now (Quick Wins)"
    quadrant-2 "Plan & Invest"
    quadrant-3 "Deprioritize"
    quadrant-4 "Start with MVP"
```

### Value-Based Prioritization Questions

- Will this feature **increase our customers**?
- Is this something **needed by our customers**?
- Does it fit the **company's vision and roadmap**?
- Does the company have the **resources needed**?

> [!TIP]
> If a feature is **high value and high cost**, start with an MVP. Then iterate based on user feedback.

---

## Problem Sense

### Define Feature Type

```mermaid
graph TD
    FT["🧩 Feature Type"] --> NEW["✨ New Features"]
    FT --> IMP["🔧 Improvements"]
    FT --> URG["🚨 Urgency"]

    NEW --> N1["Improve user experience\nwith a product"]
    IMP --> I1["Address user\npain points"]
    URG --> U1["Legal, compliance,\nor technical urgency"]

    style FT fill:#d97706,stroke:#b45309,color:#fff
    style NEW fill:#fbbf24,stroke:#d97706,color:#000
    style IMP fill:#fbbf24,stroke:#d97706,color:#000
    style URG fill:#fbbf24,stroke:#d97706,color:#000
```

### How to Identify User Pain Points

| Source | Method |
|:-------|:-------|
| **Product Signals** | Funnel drop-offs, abandonment patterns (e.g., churn during onboarding) |
| **Customer Feedback** | Reviews, support tickets, NPS surveys |
| **User Research** | Interviews, usability tests (see [User Research](../02-discovery/user-research.md)) |
| **Market Research** | Competitor analysis, untapped market segments |

---

## Prioritization Risks

### Why Solve This Problem Now?

- Will we **reduce the churn rate**?
- What will be the **impact on users**, the product, or the business?
- Will this lead to **increased revenue**?

### Risk Assessment Questions

| Risk Area | Question |
|:----------|:---------|
| **Opportunity Cost** | What happens if we deprioritize other features? |
| **Resource Exhaustion** | Will this consume resources needed elsewhere? |
| **Root Cause** | Do we need root cause analysis before acting? |
| **ROI** | Have we calculated the return on investment? |
| **Market Trends** | Are we missing industry trends? |

> [!TIP]
> Perform a **SWOT analysis** or use **Risk Matrices** (see [Risk Management](../07-risk-management/risk-management.md)) to systematically assess prioritization trade-offs.

---

## Related Pages

- ← [Market Analysis](../02-discovery/market-analysis.md) — Market data informing prioritization
- → [Go-to-Market](go-to-market.md) — Launch strategy for prioritized features
- → [Roadmap Planning](roadmap-planning.md) — Sequencing prioritized features
- → [Risk Management](../07-risk-management/risk-management.md) — Formal risk assessment

---

## Sources & References

- Legacy notes: `docs/legacy_notion_files/Product Development and Strategy Wiki` (Features and Prioritization section)
- Legacy notes: `docs/legacy_notion_files/Product Planning & Roadmap` (RICE section)

---

*[← Back to Section Index](index.md) · [← Back to Wiki Home](../index.md)*
