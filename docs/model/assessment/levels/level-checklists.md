<a id="top"></a>

[Home](../../../../README.md) · [Getting Started](../../../GETTING_STARTED.md) · [Model](../../5-level-maturity-model.md) · [Assessment Hub](../README.md) · [Roadmap](../../../ROADMAP.md) · [References](../../../REFERENCES.md)

---
# Maturity Level Checklists — Observable Operating Patterns

> **License:** CC BY-SA 4.0  
> https://creativecommons.org/licenses/by-sa/4.0/

# Level Checklists

<p align="center">
  <img src="../../../diagrams/assets/oaitmm-self-assessment-ladder.png"
       alt="OAITMM Self Assessment Ladder"
       width="70%">
</p>

These checklists describe the dominant mode of software delivery at each maturity level based on observable practices rather than stated intentions.

👉 [Back to Assessment Framework](README.md)  
👉 [Back to Unified Scoring System](scoring-model.md)

---

## Why Level Checklists Matter

Organizations often adopt advanced tools without changing how work is actually performed.

Maturity levels are determined by the primary delivery workflow for new work, not by pilot projects or isolated teams.

---

## Level 1 — AI Initiated

AI acts as an assistive layer without structural change to the development process.

Typical indicators:

- Developers use AI for completion, snippets, or explanations
- Humans perform all design, implementation decisions, and validation
- Planning, review, and release processes remain unchanged
- Adoption varies widely across teams
- Productivity gains are localized

This level improves efficiency but does not transform delivery capability.

---

## Level 2 — Augmented Coding

AI performs bounded implementation tasks, but humans remain responsible for detailed review and integration.

Typical indicators:

- AI generates code across files for specific tasks
- Developers review outputs line-by-line
- Work remains ticket-driven
- Code production increases significantly
- Integration and review become bottlenecks

Organizations often plateau here due to human verification limits.

---

## Level 3 — Managed Agents

Agents execute multi-step tasks under human supervision.

Typical indicators:

- Agents produce pull requests or change sets
- Humans review outcomes rather than every line
- Planner–executor workflows emerge
- Safe-to-automate domains are defined
- Intervention metrics are tracked
- Parallel work scales significantly

This level marks the first true transition toward AI-native development.

---

## Level 4 — Spec-Driven Development

Specifications become the primary artifact controlling implementation.

Typical indicators:

- Work begins with structured intent artifacts
- Agents implement features based on specifications
- Scenario suites validate outcomes
- Code review shifts toward specification review
- Product and engineering roles converge
- Non-functional requirements are explicit and measurable

Code becomes a derived artifact rather than the primary focus.

---

## Level 5 — Autonomous Delivery

Software is produced through largely autonomous processes within defined constraints.

Typical indicators:

- Specification → task graph → agent execution → validated outcome
- Autonomous build–test–revise cycles
- Minimal human involvement in routine implementation
- Continuous improvement within defined boundaries
- Industrial-grade auditability and rollback mechanisms
- Small teams maintain large systems

Autonomy is domain-specific and constrained by risk tolerance.

---

## Determining the Dominant Level

Organizations should assess:

- How most new work is delivered
- Which workflow governs production changes
- Where decision authority resides
- How validation is performed

Pilot projects and isolated teams should not determine the overall maturity classification.

---

## Mixed-Level Operation

Most organizations operate across multiple levels simultaneously:

- Legacy systems at lower levels
- New initiatives at higher levels
- Experimental teams ahead of the organization
- Critical systems with stricter controls

Assessment should identify the dominant level for core delivery activities.

---

## Relationship to Pillars and Gates

Levels describe how work happens, but sustainable operation at a given level requires:

- Pillar capability to support it
- Gate conditions to ensure safety

Higher levels without supporting capability or safeguards represent elevated risk.

---

[↑ Back to top](#top) · [Home](../../../../README.md)
