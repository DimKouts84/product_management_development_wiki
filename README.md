# 📘 Product Management, Development & Strategy Wiki

> **A personal knowledge base for product management best practices, development methodologies, and strategic frameworks.**

---

## About This Wiki

This repository is my **Everything Product** Knowledge Base. It includes research, development, product management and strategy. It consolidates best practices, how-to's, ideas, lessons, tips and tricks learned from hands-on experience, industry research, and various certifications and courses.

The wiki is structured as a progressive journey — from foundational terminology through discovery, strategy, development, design, metrics, risk management, and retrospectives.

---

## Wiki Structure

```mermaid
graph LR
    HOME["📘 Wiki Home"] --> F["01 · Foundations"]
    HOME --> D["02 · Discovery"]
    HOME --> S["03 · Strategy"]
    HOME --> DEV["04 · Development"]
    HOME --> DES["05 · Design"]
    HOME --> M["06 · Metrics"]
    HOME --> R["07 · Risk Management"]
    HOME --> RET["08 · Retrospectives"]

    F --> F1["Basic Terminology"]
    F --> F2["PRD Essentials"]

    D --> D1["User Research"]
    D --> D2["Market Analysis"]
    D --> D3["Requirements Solicitation"]

    S --> S1["Feature Prioritization"]
    S --> S2["Go-to-Market"]
    S --> S3["Roadmap Planning"]

    DEV --> DEV1["Requirements & User Stories"]
    DEV --> DEV2["Estimations & Velocity"]
    DEV --> DEV3["Acceptance Criteria"]

    DES --> DES1["User Interaction & Design"]
    DES --> DES2["Onboarding Patterns"]
    DES --> DES3["Gamification Patterns"]

    M --> M1["Success Metrics"]
    M --> M2["Retention Psychology"]

    R --> R1["Risk Management"]
    R --> R2["Anti-Patterns"]

    RET --> RET1["Retrospectives & Feedback"]

    style HOME fill:#2563eb,stroke:#1e40af,color:#fff
    style F fill:#7c3aed,stroke:#6d28d9,color:#fff
    style D fill:#059669,stroke:#047857,color:#fff
    style S fill:#d97706,stroke:#b45309,color:#fff
    style DEV fill:#dc2626,stroke:#b91c1c,color:#fff
    style DES fill:#ec4899,stroke:#db2777,color:#fff
    style M fill:#0891b2,stroke:#0e7490,color:#fff
    style R fill:#ea580c,stroke:#c2410c,color:#fff
    style RET fill:#4f46e5,stroke:#4338ca,color:#fff
```

---

## Quick Navigation

|   #   | Section                                                 | Description                                    | Pages |
| :---: | :------------------------------------------------------ | :--------------------------------------------- | :---- |
|  01   | [**Foundations**](wiki/01-foundations/index.md)         | Core terminology and document standards        | 2     |
|  02   | [**Discovery**](wiki/02-discovery/index.md)             | User research, market analysis, requirements   | 3     |
|  03   | [**Strategy**](wiki/03-strategy/index.md)               | Prioritization, GTM, roadmaps                  | 3     |
|  04   | [**Development**](wiki/04-development/index.md)         | Requirements, estimations, acceptance criteria | 3     |
|  05   | [**Design**](wiki/05-design/index.md)                   | UX/UI, onboarding, gamification patterns       | 3     |
|  06   | [**Metrics**](wiki/06-metrics/index.md)                 | Success metrics, retention psychology          | 2     |
|  07   | [**Risk Management**](wiki/07-risk-management/index.md) | Risk frameworks and anti-patterns              | 2     |
|  08   | [**Retrospectives**](wiki/08-retrospectives/index.md)   | Feedback loops and retrospectives              | 1     |

---

## Repository Structure

```
product_management_development_wiki/
├── README.md                    # This file
├── wiki/                        # 📘 Primary wiki content (8 sections, 19 pages)
├── docs/                        # 📂 Source materials (gitignored)
│   ├── legacy_notion_files/     #    Original Notion exports
│   └── research/                #    Deep research documents
├── agents.md                    # 🤖 Agent configuration for wiki maintenance
└── skills.md                    # 🛠️ Skills reference for wiki tasks
```

---

## Content Maturity Legend

| Icon  | Status          | Description                           |
| :---: | :-------------- | :------------------------------------ |
|   🟢   | **Complete**    | Fully written and reviewed            |
|   🟡   | **In Progress** | Content present but needs enhancement |
|   ⚪   | **Scaffold**    | Structure created, content pending    |

---

## Sources & Inspiration

- [Software Product Management Specialization](https://www.coursera.org/specializations/product-management) — Coursera
- Industry research and case studies (see individual pages)
- Personal experience and professional practice

---
  
Curated with love for building stuff - DimKouts ;)