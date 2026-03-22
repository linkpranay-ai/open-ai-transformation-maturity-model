<a id="top"></a>

[Home](../../../../README.md) · [Getting Started](../../../GETTING_STARTED.md) · [Model](../../5-level-maturity-model.md) · [Assessment Hub](../README.md) · [Roadmap](../../../ROADMAP.md) · [References](../../../REFERENCES.md)

---
# Pillar 1 — Intent & Specification Fidelity

> **License:** CC BY-SA 4.0  
> https://creativecommons.org/licenses/by-sa/4.0/

This pillar assesses whether an organization can express desired system behavior, constraints, and expected outcomes with sufficient precision for AI systems to implement safely and reliably.

👉 [Back to Assessment Framework](../README.md)  
👉 [Back to Unified Scoring System](../scoring-model.md)

---

## Why This Pillar Matters

As organizations move toward higher levels of AI transformation maturity, the limiting factor shifts away from code generation and toward the quality of intent expression.

At higher maturity levels, specifications become the control plane for software delivery. If intent is ambiguous, incomplete, or inconsistent, agentic systems amplify those weaknesses at scale.

---

## What This Pillar Evaluates

This pillar evaluates whether the organization can:

- express behavior clearly and unambiguously
- define constraints and invariants explicitly
- specify success criteria in a testable form
- represent non-functional requirements in measurable ways
- maintain alignment between documentation, architecture, and implementation

---

## Typical Assessment Questions

Examples of criteria within this pillar include:

- Are requirements expressed as behavioral contracts rather than informal tickets?
- Are specifications versioned and reviewed like code?
- Do specifications define edge cases, invariants, and non-functional expectations?
- Are architectural constraints explicit and available to implementors and agents?
- Can intent be consumed consistently across teams and systems?

---

## Evidence to Look For

Useful evidence may include:

- version-controlled specifications
- architecture decision records
- explicit acceptance criteria
- design constitutions or engineering principles
- documented non-functional requirements
- traceability between requirements and implementation

---

## Low-Maturity Pattern

At low maturity, organizations tend to rely on:

- informal tickets
- tribal knowledge
- human interpretation
- undocumented constraints
- inconsistent requirement quality across teams

In such environments, AI can generate output, but not with consistently reliable alignment to intent.

---

## High-Maturity Pattern

At high maturity, organizations tend to exhibit:

- structured, reusable intent artifacts
- explicit behavioral specifications
- measurable success criteria
- well-defined architectural rules
- strong alignment between docs, code, and runtime expectations

These characteristics are essential for safe progression toward spec-driven development and autonomous delivery.

---

## Common Failure Modes

### Ambiguous Intent
Specifications are present but too vague to support reliable implementation.

### Specification Drift
Documentation, architecture, and actual system behavior diverge over time.

### Documentation Theater
Organizations produce large volumes of documentation without making intent enforceable or machine-consumable.

---

## Relationship to Other Pillars

This pillar strongly influences:

- **Pillar 2 — Evaluation & Scenario Architecture**, because evaluation depends on clear success criteria
- **Pillar 3 — Agent Operating Model & Autonomy Control**, because autonomy requires precise boundaries
- **Pillar 5 — Codebase Readiness & Brownfield Extractability**, because reverse-specification depends on understanding true system behavior

---

## Scoring Interpretation

### Score 0
Intent is mostly implicit, informal, or absent.

### Score 1
Some specifications exist, but they are inconsistent, incomplete, or weakly enforced.

### Score 2
Teams can define intent repeatably in some contexts, but quality varies significantly.

### Score 3
Intent is structured, reviewed, and sufficiently precise across meaningful parts of the organization.

### Score 4
Intent is explicit, machine-consumable where appropriate, consistently governed, and continuously improved.

---

## Relevance by Level

- **Level 1 — AI Initiated:** Helpful but not foundational  
- **Level 2 — Augmented Coding:** Increasingly important for consistency  
- **Level 3 — Managed Agents:** Critical for bounded autonomy  
- **Level 4 — Spec-Driven Development:** Foundational  
- **Level 5 — Autonomous Delivery:** Essential

---

[↑ Back to top](#top) · [Home](../../../../README.md)
