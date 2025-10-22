# 📄 Product Requirement Document (PRD)

---

## 🔍 What is a PRD?

A **Product Requirement Document (PRD)** is a document that outlines the **problem you're solving**, the **user needs**, and the **requirements for building the solution**. It acts as the **source of truth** between cross-functional teams like Product, Engineering, Design, Sales, and Marketing.

---

## ❗ Common Mistake PMs Make

> ⚠️ **Mistake**: PMs often wait until they have complete clarity before writing the PRD.

- In reality, PRDs are **not static**. They are **living documents**.
- You **don't wait for perfect clarity**. You write based on what you currently know, then:
  - **Talk to stakeholders**
  - **Validate assumptions**
  - **Iterate the PRD** as clarity improves

**Think of the PRD as a tool to *achieve* clarity, not just document it.**

---

## 🧠 Purpose of a PRD

- To align the team on:
  - What are we building?
  - Why are we building it?
  - For whom are we building it?
  - When should it be done?
  - What does success look like?
- To maintain consistency and visibility across departments (Engg, Design, Sales, Support)

---

## 📘 Structure of a Good PRD

> You can customize the PRD, but these are typical core components:

### 1. **Overview / Problem Statement**
- What problem are we solving?
- Who is affected and how?

### 2. **Goals / Objectives**
- Link to OKRs or strategic goals

### 3. **User Persona(s)**
- Define target users with relevant context:
  - Demographics, motivations, behaviors

### 4. **User Journey Map**
- Visual or narrative flow of how users interact with the product/feature

### 5. **Requirements**
- **Functional**: What should the product do?
- **Non-Functional**: Performance, scalability, compliance

### 6. **User Stories / Use Cases**
- As a [user], I want to [goal], so that I can [benefit]

### 7. **Out of Scope**
- Clearly define what will **not** be done in this phase

### 8. **Design / Wireframes / Mockups**
- Attach or link to design prototypes

### 9. **Success Metrics**
- Define what success looks like and how it will be measured

### 10. **Risks / Assumptions**
- Known blockers or risks
- What are we assuming to be true?

---

## 🧩 How to Use the PRD to Drive Clarity

### ✅ 1. Maintain Core Docs:
- **User Persona** → Understand who you're building for
- **User Journey Map** → Understand how they will use it
- These feed into the **PRD**, which gives the team context and direction

### ✅ 2. Active Information Flow
- Schedule **sync-ups** with stakeholders (Engg, Design, Sales, CX)
- Use tools like:
  - Slack/Teams for async updates
  - Notion/Confluence for documentation
  - Figma for live design references
- Keep the PRD **linked to the Roadmap**, and **update as clarity evolves**

---

## 🧪 Real-Life Example

> **Scenario**: You're building a **"Referral Program"** feature for a SaaS platform

- You start with an initial problem: "Growth has slowed. Users aren't referring others."
- You write a **first draft PRD** with assumptions
- Then, you talk to:
  - **Users** → to understand why they’re not referring
  - **Marketing** → to align incentives with campaigns
  - **Design** → to sketch quick mockups
- You update the PRD based on insights
- The PRD evolves 3–4 times before final dev work starts

---

## 🏁 Summary

- A **PRD is not a one-time doc** — it's a **living blueprint**.
- Write early, refine often.
- Use it as a **collaboration tool** to align stakeholders and avoid confusion.
- Your goal as a PM is to **bring clarity**, not wait for it.

> “Clarity is not something you find, it’s something you build — one conversation and one iteration at a time.”

---
Great question! The idea that **“PRDs are dead”** has been floating around, especially with the rise of AI and fast-paced product cycles. But let’s unpack this carefully.

---

## Why Some People Say PRDs Are Dead (Especially in AI)

1. **Speed & Agility**
   AI products often evolve quickly, sometimes daily or weekly. Traditional, detailed PRDs feel too slow or heavyweight to keep up with rapid iteration.

2. **Uncertainty & Experimentation**
   AI development is highly experimental—models, data, and user behavior can be unpredictable. Writing fixed, detailed specs upfront can be seen as limiting or futile.

3. **Cross-Functional Communication Tools Have Evolved**
   Teams now use more collaborative, real-time tools like Slack, Figma, Jira, and Confluence. These can sometimes replace the need for long-form PRDs.

4. **AI-specific Complexity**
   The success of AI features often depends on data quality, model training, and tuning. These are hard to fully capture in a static document.

---

## Why PRDs Will **Never** Die, Even in AI

### 1. **PRD is About Alignment, Not Just Documentation**

* PRD is a **high-level, shared reference** that aligns stakeholders—Product, Engineering, Data Science, Design, Marketing, Sales—on what is being built and why.
* Without this alignment, AI teams risk building isolated solutions that don’t solve user needs or meet business goals.

### 2. **AI Products Still Need Clear Problem Definitions**

* AI solutions are complex but must solve **clear user or business problems**.
* PRDs help define:

  * The **user personas** (who benefits)
  * The **problem scope** (what the AI is expected to do)
  * The **success criteria** (how we measure AI performance beyond accuracy—impact on user behavior, business KPIs)

### 3. **PRDs Provide a Foundation for Experimentation**

* In AI, you don’t know the perfect solution upfront. The PRD doesn’t lock you in—it sets a **starting point**.
* Iterations and learnings from AI experiments can be documented as **updates to the PRD**, keeping everyone on the same page about what changed and why.

### 4. **Complex AI Projects Require Cross-Discipline Collaboration**

* AI development involves engineers, data scientists, researchers, product managers, UX designers, legal/compliance teams, and business stakeholders.
* A PRD brings all those perspectives together by consolidating goals, constraints, assumptions, and requirements.

### 5. **Regulatory & Ethical Compliance**

* AI products often face regulatory scrutiny (e.g., data privacy, bias, explainability).
* PRDs document these constraints and ensure that teams **design ethically and compliantly** from the start.

---

## Real-Life AI Example

Imagine you're building a **smart assistant for customer support** that uses AI to auto-respond to user queries:

* The PRD clarifies:

  * **Who** the users are: support agents and end customers
  * **What** problems it solves: reduce agent load, improve response times
  * **Functional requirements**: auto-classify ticket types, suggest answers
  * **Non-functional requirements**: system latency under 2 seconds, 95% accuracy target
  * **Ethical considerations**: no biased or offensive responses
  * **Success metrics**: % reduction in average handling time, CSAT score improvements

Even as you iterate on the AI model, the PRD stays your North Star, updated with experiment results, new constraints, and roadmap changes.

---

## Summary

| **Why PRDs might seem “dead”**    | **Why PRDs remain essential**                             |
| --------------------------------- | --------------------------------------------------------- |
| Slow for fast-paced AI iterations | Provide clear alignment on goals and scope                |
| Hard to specify AI upfront        | Foundation for documenting assumptions and evolving ideas |
| Collaborative tools reduce docs   | Consolidate cross-disciplinary knowledge                  |
| Experimentation is fluid          | Help track experiments, updates, and success metrics      |
| AI complexity is high             | Ensure ethical and regulatory compliance                  |

---

### Final thought

> **PRDs are evolving, not dying.**
> In AI, they become **more lightweight, collaborative, and iterative**—but the core purpose remains: **align teams around clear user problems, goals, and requirements** to build impactful products.





