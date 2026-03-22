<a id="top"></a>

[Home](../../../../README.md) · [Getting Started](../../../GETTING_STARTED.md) · [Model](../../5-level-maturity-model.md) · [Assessment Hub](../README.md) · [Roadmap](../../../ROADMAP.md) · [References](../../../REFERENCES.md)

---
# Pillar 5 — Codebase Readiness & Brownfield Extractability

> **License:** CC BY-SA 4.0  
> https://creativecommons.org/licenses/by-sa/4.0/

This pillar assesses whether existing systems can be understood, modified, and evolved reliably, including the ability to extract behavioral knowledge from legacy codebases.

👉 [Back to Assessment Framework](../README.md)  
👉 [Back to Unified Scoring System](../scoring-model.md)

---

## Why This Pillar Matters

Most organizations operate complex legacy systems whose behavior is only partially documented or understood.

AI-driven transformation requires the ability to interpret existing code, derive specifications from observed behavior, and safely modify systems without introducing regressions.

Without sufficient codebase readiness, transformation efforts stall at surface-level productivity improvements.

---

## What This Pillar Evaluates

This pillar evaluates whether the organization can:

- understand the structure and behavior of legacy systems
- trace functionality across components and dependencies
- modify systems safely without unintended consequences
- extract specifications from existing implementations
- support automated analysis of codebases

---

## Typical Assessment Questions

Examples of criteria within this pillar include:

- Is the architecture of major systems documented and current?
- Can engineers reliably predict the impact of changes?
- Are dependencies and interfaces well understood?
- Can production behavior be analyzed to infer system requirements?
- Are tools available for code analysis and comprehension?

---

## Evidence to Look For

Useful evidence may include:

- architecture documentation
- dependency maps and service catalogs
- code ownership information
- observability data revealing runtime behavior
- static and dynamic analysis tools
- historical change records
- documentation of system boundaries and interfaces

---

## Low-Maturity Pattern

At low maturity, organizations tend to rely on:

- tribal knowledge concentrated in a few individuals
- outdated or missing documentation
- fragile systems where changes cause unexpected failures
- long debugging cycles
- reluctance to modify legacy components

Such systems resist both manual and AI-assisted evolution.

---

## High-Maturity Pattern

At high maturity, organizations tend to exhibit:

- well-understood architectures
- clear system boundaries and interfaces
- strong observability of runtime behavior
- reliable change impact analysis
- ability to derive requirements from system behavior
- tools that assist in comprehension and refactoring

Legacy systems become assets rather than constraints.

---

## Common Failure Modes

### Knowledge Silos
Critical system understanding is limited to a few individuals.

### Architectural Erosion
System structure has drifted from original design without updated documentation.

### Change Aversion
Teams avoid modifying legacy components due to unpredictable risk.

---

## Relationship to Other Pillars

This pillar strongly influences:

- **Pillar 1 — Intent & Specification Fidelity**, because accurate specifications depend on understanding real behavior
- **Pillar 2 — Evaluation & Scenario Architecture**, because tests must reflect actual system functionality
- **Pillar 6 — Infrastructure & Tooling Readiness**, because analysis and observability depend on platform capabilities

---

## Scoring Interpretation

### Score 0
Legacy systems are poorly understood and difficult to modify safely.

### Score 1
Partial understanding exists but is inconsistent and fragile.

### Score 2
Key systems can be analyzed and modified with moderate confidence.

### Score 3
Architecture and behavior are well understood across major systems.

### Score 4
Systems are highly transparent, analyzable, and amenable to automated reasoning and evolution.

---

## Relevance by Level

- **Level 1 — AI Initiated:** Limited relevance  
- **Level 2 — Augmented Coding:** Increasing importance  
- **Level 3 — Managed Agents:** Critical for safe modification  
- **Level 4 — Spec-Driven Development:** Essential for brownfield transformation  
- **Level 5 — Autonomous Delivery:** Foundational for legacy integration

---

[↑ Back to top](#top) · [Home](../../../../README.md)
