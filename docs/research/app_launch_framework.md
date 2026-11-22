# App Launch Framework: Systems, Preparation, and Execution

This research document analyzes the tactical software systems, marketing assets, and decision-making criteria required to launch new applications. It focuses on setting up loops for user acquisition, in-app product telemetry, direct customer feedback channels, and automated engagement systems, comparing low-key and high-impact launch strategies.

---

## 1. Executive Summary

A successful app launch is not a single promotional event. It is the culmination of structural steps designed to gauge interest, collect user data, iterate on product feedback, and maximize initial distribution. Many builders make the mistake of launching without proper telemetry or feedback loops, essentially "building on hard mode" without knowing why users churn or what features they actually desire.

This document outlines a 6-step tactical framework (Phases 0–5) to ensure a product is prepared to retain users, capture market interest, and sustain growth post-launch.

---

## 2. The App Launch Framework (Phases 0-5)

### Phase 0: Pre-Build & Waitlist
* **Objective**: Gauge market interest and compile a seed list of high-intent beta testers.
* **The System**: Set up a simple, single-page landing page featuring **one high-fidelity screenshot** and an email collection form.
* **Why it Works**: Validates demand before investing months of development time. It provides a springboard of early adopters when the product is ready.
* **Stack**: Framer (page design) + FormSpark (simple form submission capture).

### Phase 1: In-App Analytics
* **Objective**: Measure user actions and diagnose drop-off points.
* **The System**: Install in-app product analytics prior to launch (takes ~30 minutes).
* **Why it Works**: Early users provide critical data on why cohorts churn. Without analytics, developers cannot make data-driven decisions to adjust features.
* **Stack**: PostHog.

### Phase 2: User Feedback Board
* **Objective**: Gather customer requests and prioritize the product roadmap.
* **The System**: Implement an interactive, public feedback board where users can submit requests and upvote other entries.
* **Why it Works**: Builders cannot accurately predict what users want. Upvotes provide a clear signal on high-value features. Building requested features directly reduces churn.
* **Stack**: Canny (expensive but seamless web/iOS login integration) or UserJot (cost-effective indie alternative).

### Phase 3: Email Sequence System
* **Objective**: Keep users engaged during the critical first 14 days and recover inactive cohorts.
* **The System**: Programmatic email triggers sent on a specific cadence.
* **Key Sequences**:
  * *Welcome Trigger*: Sent immediately upon account creation.
  * *Activity Prime*: E.g., sending 5 emails over the course of 2 weeks explaining lesser-known features. This teaches the interface and reminds users to return.
  * *Inactivity Check-in*: Triggered automatically if a user does not open the app for 7 consecutive days, requesting direct feedback.
* **Stack**: Loops (easy-to-use email sequencer with highly responsive support).

### Phase 4: App Store Listing Optimization
* **Objective**: Maximize organic search discovery and listing conversion rate (CVR).
* **The System**: Writing optimized titles, descriptions, and tags, alongside high-converting screenshots.
* **The Apple Boost**: Apple provides new listings with an organic search visibility boost for the first few days to two weeks. A optimized listing is critical to capture this unique acquisition window.
* **ASO Focus**: Devote 3–4 days strictly to screenshots. They are the primary visual element users evaluate when deciding to download.

### Phase 5: Production Landing Page
* **Objective**: Showcase product value and direct traffic to the App Store or web sign-up.
* **The System**: A dedicated promotional page built with rich assets, descriptions, and call-to-actions (CTAs).
* **Stack**: Framer.

---

## 3. Timing and Launch Decision Criteria

Launching too early can burn initial traffic if the product fails to retain users.

* **Retention Signal**: Launch only when analytics show beta testers are sticking around for at least a few days. 
* **Gut Check**: If users drop off immediately after Day 1, focus on fixing core flows before scaling acquisition.

---

## 4. Execution Playbook: Low-Key vs. High-Impact Launches

The execution path depends on personal comfort and product type:

### A. Low-Key Launch
* **Channels**: Announcements on personal socials (YouTube video, Twitter/X threads, LinkedIn posts) and an announcement email to the Phase 0 waitlist.
* **Pros**: Simple, highly comfortable, direct link to existing audience.
* **Cons**: Limited reach beyond warm traffic.

### B. High-Impact Launch
* **Strategy**:
  * **Pre-Launch Week**: Teaser posts on socials to build anticipation.
  * **Launch Day**: Coordinate social media support from peers.
  * **Product Hunt**: Run a coordinated campaign to hit top spots.
  * **Communities**: Structured, non-spam postings on Reddit, internet forums, and developer communities.
* **Goal**: Drive maximum unique visits to the landing page and app store page to scale initial numbers.

---

## 5. Case Studies & Tool Analysis

| Tool / Case | Category | Classification | Why it Works / Fails |
| :--- | :--- | :---: | :--- |
| **Ellie App (Lists)** | Feedback Board Feature | 🟢 Success | The "list" feature on the left sidebar was not in the original product roadmap. User upvoting on Canny made it top priority; it is now a daily-use core feature for all users. |
| **Loops** | Email Sequencing | 🟢 Success | Clean UI, generous free tier, and responsive support. Simplifies drip campaigns that educate users and reduce churn. |
| **PostHog** | Analytics | 🟢 Success | Allows rapid integration. Captures critical user telemetry to identify drop-off barriers before launch. |
| **FormSpark** | Waitlist Form | 🟢 Success | Hooks directly into Framer, making waitlist email collection quick to build and maintenance-free. |
| **ASO Screenshots** | Store Optimization | 🟢 Success | Taking 3–4 days to polish screenshots prevents wasting Apple's initial organic search boost. |
| **"Ship and Pray"** | Raw launching | 🔴 Failure | Launching without feedback boards or analytics makes iterating blind and increases churn risk. |

---

## 6. Sources & References

* *Video Source*: *My Launch Checklist for New Apps* — YouTube (Chris)
* *Wiki Integration*: [App Launch Checklist](../../wiki/03-strategy/app-launch-checklist.md)
