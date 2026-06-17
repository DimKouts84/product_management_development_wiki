# 📘 Product Management, Development & Strategy Wiki

> **Right Product · Done Right · Managed Right**

Welcome to the Product Management Wiki — a structured knowledge base covering the full product lifecycle from initial discovery through launch, measurement, and continuous improvement.

---

## How to Navigate This Wiki

This wiki is organized into **8 progressive sections** that mirror the product development lifecycle. Each section builds upon the previous, though they can be read independently.

```mermaid
graph TD
    A["🔤 01 · Foundations"] --> B["🔍 02 · Discovery"]
    B --> C["🎯 03 · Strategy"]
    C --> D["⚙️ 04 · Development"]
    D --> E["🎨 05 · Design"]
    E --> F["📊 06 · Metrics"]
    F --> G["⚠️ 07 · Risk Management"]
    G --> H["🔁 08 · Retrospectives"]
    H -.->|"Continuous\nImprovement"| B

    style A fill:#7c3aed,stroke:#6d28d9,color:#fff
    style B fill:#059669,stroke:#047857,color:#fff
    style C fill:#d97706,stroke:#b45309,color:#fff
    style D fill:#dc2626,stroke:#b91c1c,color:#fff
    style E fill:#ec4899,stroke:#db2777,color:#fff
    style F fill:#0891b2,stroke:#0e7490,color:#fff
    style G fill:#ea580c,stroke:#c2410c,color:#fff
    style H fill:#4f46e5,stroke:#4338ca,color:#fff
```

---

## Sections

### 🔤 [01 · Foundations](01-foundations/index.md)
Core terminology, glossary, and PRD document standards. Start here to establish a common language.

| Page | Status | Description |
|:-----|:------:|:------------|
| [Basic Terminology](01-foundations/basic-terminology.md) | 🟢 | Glossary of product management terms |
| [Product Document Essentials](01-foundations/product-document-essentials.md) | 🟢 | PRD structure and cheatsheet |

---

### 🔍 [02 · Discovery](02-discovery/index.md)
Understanding users, markets, and requirements before building anything.

| Page | Status | Description |
|:-----|:------:|:------------|
| [User Research](02-discovery/user-research.md) | 🟢 | Personas, segmentation, and research methods |
| [Market Analysis](02-discovery/market-analysis.md) | 🟢 | TAM/SAM/SOM, competition, and market trends |
| [Requirements Solicitation](02-discovery/requirements-solicitation.md) | 🟢 | Elicitation techniques, backlogs, and storymaps |

---

### 🎯 [03 · Strategy](03-strategy/index.md)
Deciding what to build, when, and how to bring it to market.

| Page | Status | Description |
|:-----|:------:|:------------|
| [Feature Prioritization](03-strategy/feature-prioritization.md) | 🟢 | RICE, decision matrices, cost-value analysis |
| [Go-to-Market](03-strategy/go-to-market.md) | 🟢 | GTM strategy, A/B testing, launch planning |
| [App Store Optimization](03-strategy/app-store-optimization.md) | 🟢 | Keyword metadata, screenshot CVR, review loops |
| [Roadmap Planning](03-strategy/roadmap-planning.md) | 🟢 | Roadmaps, WBS, dependencies, Gantt charts |
| [App Launch Checklist](03-strategy/app-launch-checklist.md) | 🟢 | Tactical launch checklist: analytics, waitlists, feedback boards, and emails |

---

### ⚙️ [04 · Development](04-development/index.md)
Translating strategy into actionable development work.

| Page | Status | Description |
|:-----|:------:|:------------|
| [Requirements & User Stories](04-development/requirements-user-stories.md) | 🟢 | Requirements types, user stories, INVEST |
| [Estimations & Velocity](04-development/estimations-velocity.md) | 🟢 | Story points, velocity, Fibonacci estimation |
| [Acceptance Criteria](04-development/acceptance-criteria.md) | 🟢 | Given-When-Then templates, verification lists |

---

### 🎨 [05 · Design](05-design/index.md)
User experience, interaction design, and product design patterns.

| Page | Status | Description |
|:-----|:------:|:------------|
| [UI Design Foundations](05-design/ui-design-foundations.md) | 🟢 | Affordances, hierarchy, typography, color, shadows, states, and overlays |
| [User Interaction & Design](05-design/user-interaction-design.md) | 🟢 | Use cases, wireframes, storyboards |
| [Mobile UI Design Foundations](05-design/mobile-ui-design-foundations.md) | 🟢 | Layout constraints, navigation architectures, and gestural interactions |
| [Onboarding Patterns](05-design/onboarding-patterns.md) | 🟢 | Onboarding UX strategies and case studies |
| [Gamification Patterns](05-design/gamification-patterns.md) | 🟢 | Sustainable gamification design patterns |

---

### 📊 [06 · Metrics](06-metrics/index.md)
Measuring success and understanding user retention.

| Page | Status | Description |
|:-----|:------:|:------------|
| [Success Metrics](06-metrics/success-metrics.md) | 🟢 | AARRR framework, KPIs, measurement |
| [Retention Psychology](06-metrics/retention-psychology.md) | 🟢 | Three pillars of retention architecture |

---

### ⚠️ [07 · Risk Management](07-risk-management/index.md)
Identifying, assessing, and mitigating project risks.

| Page | Status | Description |
|:-----|:------:|:------------|
| [Risk Management](07-risk-management/risk-management.md) | 🟢 | Risk matrices and risk plans |
| [Anti-Patterns](07-risk-management/anti-patterns.md) | 🟢 | Common PM anti-patterns to avoid |

---

### 🔁 [08 · Retrospectives](08-retrospectives/index.md)
Learning from outcomes and closing the feedback loop.

| Page | Status | Description |
|:-----|:------:|:------------|
| [Retrospectives & Feedback](08-retrospectives/retrospectives-feedback.md) | 🟢 | Internal retrospectives and external feedback |

---

## Cross-Cutting Themes

```mermaid
graph LR
    subgraph "User-Centric"
        UR["User Research"] --> UID["Interaction Design"]
        UID --> OB["Onboarding"]
        OB --> GM["Gamification"]
        GM --> RP["Retention"]
    end

    subgraph "Process-Centric"
        REQ["Requirements"] --> EST["Estimations"]
        EST --> AC["Acceptance Criteria"]
        AC --> RETRO["Retrospectives"]
    end

    subgraph "Strategy-Centric"
        MA["Market Analysis"] --> FP["Feature Prioritization"]
        FP --> GTM["Go-to-Market"]
        GTM --> SM["Success Metrics"]
    end

    style UR fill:#059669,stroke:#047857,color:#fff
    style MA fill:#059669,stroke:#047857,color:#fff
    style REQ fill:#dc2626,stroke:#b91c1c,color:#fff
```

---

*Navigate to any section above to begin exploring. Each page contains detailed frameworks, examples, mermaid diagrams, and cross-references to related content.*
