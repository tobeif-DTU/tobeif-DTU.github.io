
---
title: Design Intelligence
ShowToc: true
tocopen: false
draft: false
tags:
  - Research
  - Design Intelligence
  - Artifical Intelligence
---

## Design Intelligence

We are interested in how intelligent methods — optimization, knowledge representation, generative models, and human-AI collaboration — can be embedded directly into the engineering design process. Across our projects, one question recurs: how do we build systems that don't just automate design tasks, but genuinely improve the quality, transparency, and trustworthiness of design decisions, all while contributing to efficient development processes? The four research threads below outline our current focus.

---

### 1. In Search of the Ideal Design — Intelligent Processes

Optimal design synthesis promises to find the "best" design automatically, but real engineering problems are full of competing objectives, hidden trade-offs, and constraints that shift as a design matures. Our work focuses on intelligent processes to systematically use this knowledge for **trade-off mitigation and constraint management** within optimal design synthesis — treating the search for an ideal design not as a single optimization run, but as an intelligent, adaptive process that reasons about which trade-offs matter and when.

Also have a look at out paper in _Design Science_: [In Search of the Ideal Design: Systematic Trade-off Mitigation and Constraint Management in Optimal Design Synthesis](https://www.cambridge.org/core/journals/design-science/article/in-search-of-the-ideal-design-systematic-tradeoff-mitigation-and-constraint-management-in-optimal-design-synthesis/626E64258BEB729C7676ECC184871B73).

---

### 2. Design Knowledge — Knowledge Graphs in Engineering Processes

Engineering knowledge is rarely written down in one place — it lives across requirements documents, CAD models, simulation results, and the heads of experienced engineers. We're  i) exploring how **knowledge graphs** can capture and connect this design knowledge across the design process (so it becomes queryable, reusable, and machine-actionable, rather than siloed in individual tools or people's heads); and ii) work on tools to intuitively integrate these approaches into the design process (enabling designers to systematically build/use this knowledge  and provide AI agents with structured access to a project's design knowledge rather than relying on unstructured text search).

---

### 3. Design Automation — Beyond Statistical Similarity

Many current generative design tools either produce solutions that merely _look_ plausible because they statistically resemble their training data, or rely heavily on trial-and-error search of a multidimensional design process. Or in other words, when we go away from pcitures and text, why are the typical examples for automated systems design still the same gearboxes that have been an example for design grammars since decades.

We therefore work on engineering solutions that are not developed based on statistical similarity, but by whether they satisfy the trade-offs that actually define a good design. Building on our trade-off and constraint-management concept, we develop neuro-symbolic tools — combining LLMs with symbolic descriptions of the design problem — to reason explicitly about engineering trade-offs and automatically implement targeted design changes. The goal is automation that can justify _why_ a design is good, not just that it resembles something that once was.

---

### 4. Intelligence augmentation - Designing Human-AI Collaboration

As AI takes on more of the design process, the critical questions shift from _what can the system do_ to _who benefits, and how should humans stay in control_. Our research investigates:

- **Who benefits** from AI-assisted design — and who might be disadvantaged if it is adopted without care.
- **Where to place human decision points** in an AI-supported design workflow, so that judgment, accountability, and domain expertise remain where they matter most.
- **Bias for and against AI systems** — both algorithmic bias embedded in the tools themselves, and human bias (over-trust or unwarranted skepticism) toward new AI-driven design systems.

The aim is not to maximize automation for its own sake, but to design human-AI collaborations that are transparent, fair, and genuinely improve engineering outcomes.

