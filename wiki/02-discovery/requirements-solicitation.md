# Requirements Solicitation

> **Effective products start with the right questions, not the right answers.**

---

## Table of Contents

- [Elicitation Techniques](#elicitation-techniques)
- [Product Backlog](#product-backlog)
- [Story Maps](#story-maps)
- [Quality Assessments](#quality-assessments)

---

## Elicitation Techniques

Requirements elicitation is the process of gathering needs from users, stakeholders, and existing systems. The key challenge is bridging the gap between what users **say** they want and what they **actually need**.

### User Limitation Awareness

When gathering requirements, account for user limitations:

```mermaid
graph TD
    UL["⚠️ User Limitations"] --> PER["👁️ Perceptual"]
    UL --> PHY["💪 Physical"]
    UL --> COG["🧠 Cognitive"]
    UL --> CUL["🌍 Cultural"]

    PER --> P1["Visual, auditory,\nhaptic constraints"]
    PHY --> P2["Motor skills,\nmobility, dexterity"]
    COG --> P3["Memory limits,\nattention span, literacy"]
    CUL --> P4["Language, conventions,\nexpectations"]

    style UL fill:#059669,stroke:#047857,color:#fff
    style PER fill:#34d399,stroke:#059669,color:#000
    style PHY fill:#34d399,stroke:#059669,color:#000
    style COG fill:#34d399,stroke:#059669,color:#000
    style CUL fill:#34d399,stroke:#059669,color:#000
```

### Involving Clients

> [!NOTE]
> This section will be expanded in future iterations to cover specific client involvement techniques: workshops, JAD sessions, observation studies, and document analysis.

---

## Product Backlog

The product backlog is a prioritized list of features, enhancements, and fixes that define the product roadmap at the tactical level.

### Backlog Prioritization

> [!NOTE]
> This section will be expanded to cover prioritization methods including MoSCoW, Kano Model, and weighted scoring. See also [Feature Prioritization](../03-strategy/feature-prioritization.md).

---

## Story Maps

Story maps organize requirements into a visual hierarchy that shows the complete user experience.

```mermaid
graph TD
    SM["🗺️ Story Map"] --> A["Activities\n(User Goals)"]
    A --> T["Tasks\n(Steps to achieve goals)"]
    T --> US["User Stories\n(Detailed requirements)"]

    US --> P1["Priority 1 — MVP"]
    US --> P2["Priority 2 — Release 2"]
    US --> P3["Priority 3 — Future"]

    style SM fill:#059669,stroke:#047857,color:#fff
    style A fill:#34d399,stroke:#059669,color:#000
    style T fill:#6ee7b7,stroke:#34d399,color:#000
    style US fill:#a7f3d0,stroke:#6ee7b7,color:#000
    style P1 fill:#dc2626,stroke:#b91c1c,color:#fff
    style P2 fill:#d97706,stroke:#b45309,color:#fff
    style P3 fill:#6b7280,stroke:#4b5563,color:#fff
```

> [!NOTE]
> This section will be expanded with practical story mapping templates and workshop facilitation guides.

---

## Quality Assessments

> [!NOTE]
> This section will be expanded to cover requirements quality checks, traceability matrices, and validation techniques.

---

## Related Pages

- → [User Research](user-research.md) — Research methods that feed into requirements
- → [Requirements & User Stories](../04-development/requirements-user-stories.md) — Writing and structuring requirements
- → [Feature Prioritization](../03-strategy/feature-prioritization.md) — Prioritizing the backlog
- → [Acceptance Criteria](../04-development/acceptance-criteria.md) — Verifying requirements are met

---

## Sources & References

- Software Product Management Specialization — Coursera
- Legacy notes: `docs/legacy_notion_files/Requirements Solicitation`

---

*[← Back to Section Index](index.md) · [← Back to Wiki Home](../index.md)*
