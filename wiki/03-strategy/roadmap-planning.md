# Roadmap Planning

> **"Give me six hours to chop down a tree and I will spend the first four sharpening the axe."** — Abraham Lincoln

---

## Table of Contents

- [Product Roadmap](#product-roadmap)
- [Task Dependencies](#task-dependencies)
- [Work Breakdown Structure (WBS)](#work-breakdown-structure-wbs)
- [CPM Chart](#cpm-chart)
- [PERT Chart](#pert-chart)
- [Gantt Chart](#gantt-chart)

---

## Product Roadmap

The Product Roadmap is the **key strategic document** that defines the vision for the product and the company.

### Roadmap Best Practices

- Focus on the first 3 months — accuracy decreases further out
- Keep everything visible and communicate frequently
- Stay flexible — change the roadmap based on feedback and data
- Each team has its priorities — listen to key stakeholders

### Stakeholder Alignment

| Method | When |
|:-------|:-----|
| **One-on-one meetings** | During roadmap creation with key stakeholders |
| **Groupthink sessions** | When roadmap is nearly completed for final alignment |

> [!TIP]
> Stick to the goal, keep everything visible, and communicate changes proactively.

---

## Task Dependencies

Dependencies among tasks define their relationships so the project can be planned accordingly.

```mermaid
graph LR
    subgraph "Dependency Types"
        SS["Start-Start\nA starts before B starts"]
        SF["Start-Finish\nA starts before B finishes"]
        FS["Finish-Start\nA finishes before B starts"]
        FF["Finish-Finish\nA finishes before B finishes"]
    end

    A1["Task A"] -->|"FS"| B1["Task B"]
    A2["Task A"] -->|"SS"| B2["Task B"]
    A3["Task A"] -->|"FF"| B3["Task B"]
    A4["Task A"] -->|"SF"| B4["Task B"]

    style SS fill:#2563eb,stroke:#1e40af,color:#fff
    style SF fill:#059669,stroke:#047857,color:#fff
    style FS fill:#dc2626,stroke:#b91c1c,color:#fff
    style FF fill:#d97706,stroke:#b45309,color:#fff
```

| Type | Notation | Meaning |
|:-----|:---------|:--------|
| **Start-Start** | SS | Task A must start before Task B can start |
| **Start-Finish** | SF | Task A must start before Task B finishes |
| **Finish-Start** | FS | Task A must finish before Task B can start (most common) |
| **Finish-Finish** | FF | Task A must finish before Task B finishes |

---

## Work Breakdown Structure (WBS)

A **WBS** organizes a project into smaller, manageable tasks or components. It breaks down the project into hierarchical levels.

```mermaid
graph TD
    P["📦 Project"] --> D1["Deliverable 1"]
    P --> D2["Deliverable 2"]
    P --> D3["Deliverable 3"]

    D1 --> WP1["Work Package 1.1"]
    D1 --> WP2["Work Package 1.2"]
    D2 --> WP3["Work Package 2.1"]
    D2 --> WP4["Work Package 2.2"]
    D3 --> WP5["Work Package 3.1"]

    WP1 --> T1["Task 1.1.1"]
    WP1 --> T2["Task 1.1.2"]
    WP3 --> T3["Task 2.1.1"]

    style P fill:#d97706,stroke:#b45309,color:#fff
    style D1 fill:#fbbf24,stroke:#d97706,color:#000
    style D2 fill:#fbbf24,stroke:#d97706,color:#000
    style D3 fill:#fbbf24,stroke:#d97706,color:#000
    style WP1 fill:#fde68a,stroke:#fbbf24,color:#000
    style WP2 fill:#fde68a,stroke:#fbbf24,color:#000
    style WP3 fill:#fde68a,stroke:#fbbf24,color:#000
    style WP4 fill:#fde68a,stroke:#fbbf24,color:#000
    style WP5 fill:#fde68a,stroke:#fbbf24,color:#000
```

---

## CPM Chart

### Critical Path Method

The **CPM** identifies the **longest sequence of dependent tasks** and determines the shortest time needed to complete a project. Tasks on the critical path have zero float — any delay directly impacts the project deadline.

```mermaid
graph LR
    S["Start"] --> A["Task A\n3 days"]
    S --> B["Task B\n2 days"]
    A --> C["Task C\n4 days"]
    B --> D["Task D\n3 days"]
    C --> E["Task E\n2 days"]
    D --> E
    E --> F["End"]

    linkStyle 0 stroke:#dc2626,stroke-width:3px
    linkStyle 2 stroke:#dc2626,stroke-width:3px
    linkStyle 4 stroke:#dc2626,stroke-width:3px

    style S fill:#059669,stroke:#047857,color:#fff
    style F fill:#dc2626,stroke:#b91c1c,color:#fff
    style A fill:#dc2626,stroke:#b91c1c,color:#fff
    style C fill:#dc2626,stroke:#b91c1c,color:#fff
    style E fill:#dc2626,stroke:#b91c1c,color:#fff
```

> The **critical path** (highlighted in red) is: Start → A → C → E → End = **9 days**

---

## PERT Chart

### Program Evaluation and Review Technique

**PERT** visualizes tasks and dependencies with probabilistic time estimates. Unlike CPM where each task has a fixed estimate, PERT uses three estimates:

| Estimate | Description |
|:---------|:-----------|
| **Optimistic (O)** | Best-case completion time |
| **Most Likely (M)** | Most probable completion time |
| **Pessimistic (P)** | Worst-case completion time |

> **Expected Time** = (O + 4M + P) / 6

### CPM vs. PERT

| Feature | CPM | PERT |
|:--------|:----|:-----|
| **Time Estimates** | Fixed (deterministic) | Probabilistic (O, M, P) |
| **Visual Focus** | Arrows = paths, Nodes = tasks | Nodes = dependencies, Arrows = tasks |
| **Best For** | Repetitive projects with known durations | Novel projects with uncertainty |

---

## Gantt Chart

A **Gantt chart** displays tasks, dates, and dependencies in a single horizontal timeline view.

```mermaid
gantt
    title Example Product Roadmap
    dateFormat  YYYY-MM-DD
    section Discovery
        User Research       :a1, 2026-01-06, 14d
        Market Analysis     :a2, after a1, 10d
    section Strategy
        Feature Prioritization  :b1, after a2, 7d
        Roadmap Planning        :b2, after b1, 7d
    section Development
        Sprint 1            :c1, after b2, 14d
        Sprint 2            :c2, after c1, 14d
    section Launch
        Beta Testing        :d1, after c2, 7d
        Go-to-Market        :d2, after d1, 7d
```

### Gantt Chart Components

- **Tasks** listed vertically on the left
- **Dates** running horizontally along the top
- **Bars** representing task duration from start to end date
- **Dependencies** shown as relationships between bars

---

## Related Pages

- ← [Feature Prioritization](feature-prioritization.md) — What goes into the roadmap
- ← [Go-to-Market](go-to-market.md) — Launch timeline alignment
- → [Estimations & Velocity](../04-development/estimations-velocity.md) — How to estimate task durations
- → [Risk Management](../07-risk-management/risk-management.md) — Identifying schedule risks

---

## Sources & References

- Software Product Management Specialization — Coursera
- Legacy notes: `docs/legacy_notion_files/Product Planning & Roadmap`

---

*[← Back to Section Index](index.md) · [← Back to Wiki Home](../index.md)*
