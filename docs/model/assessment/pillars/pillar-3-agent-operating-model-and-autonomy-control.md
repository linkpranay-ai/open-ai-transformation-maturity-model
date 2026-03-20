# Pillar 3 — Agent Operating Model & Autonomy Control

> **License:** CC BY-SA 4.0  
> https://creativecommons.org/licenses/by-sa/4.0/

This pillar assesses whether an organization has a structured operating model for deploying, supervising, and governing AI agents performing software development tasks.

👉 [Back to Assessment Framework](../README.md)  
👉 [Back to Unified Scoring System](../scoring-model.md)

---

## Why This Pillar Matters

As organizations move beyond assistive AI toward agentic systems, the key challenge shifts from generating outputs to controlling autonomous behavior safely and predictably.

Without a defined operating model, agents may produce large volumes of work with unclear accountability, inconsistent quality, or unintended side effects.

A mature operating model ensures that autonomy increases productivity without compromising reliability or safety.

---

## What This Pillar Evaluates

This pillar evaluates whether the organization can:

- deploy agents to perform bounded tasks safely
- define levels of autonomy appropriate to context
- supervise agent activity effectively
- manage intervention and escalation mechanisms
- maintain accountability for agent-generated outcomes

---

## Typical Assessment Questions

Examples of criteria within this pillar include:

- Are agents assigned clearly defined scopes of responsibility?
- Are autonomy levels calibrated to domain risk and evaluation capability?
- Can humans intervene or override agent actions when necessary?
- Are agent activities monitored and logged systematically?
- Is there a defined process for handling agent failures or unexpected behavior?

---

## Evidence to Look For

Useful evidence may include:

- documented agent workflows or orchestration patterns
- policies defining safe-to-automate tasks
- intervention metrics (e.g., human corrections required)
- monitoring dashboards for agent performance
- governance guidelines for agent deployment
- escalation procedures for anomalies

---

## Low-Maturity Pattern

At low maturity, organizations tend to rely on:

- ad hoc agent usage by individuals
- unclear boundaries of responsibility
- inconsistent supervision practices
- manual cleanup of agent errors
- reactive responses to failures

Agents behave more like experimental tools than managed production components.

---

## High-Maturity Pattern

At high maturity, organizations tend to exhibit:

- clearly defined agent roles and scopes
- calibrated autonomy aligned with risk
- proactive monitoring and supervision
- measurable performance indicators
- structured intervention mechanisms
- accountability for outcomes rather than outputs

Agents function as controlled contributors within the delivery system.

---

## Common Failure Modes

### Autonomy Without Control
Agents are granted broad authority without sufficient monitoring or safeguards.

### Intervention Overload
Humans must constantly correct agent outputs, negating productivity gains.

### Accountability Ambiguity
Unclear ownership for decisions made by agents.

---

## Relationship to Other Pillars

This pillar strongly influences:

- **Pillar 2 — Evaluation & Scenario Architecture**, because autonomy depends on reliable validation
- **Pillar 4 — Delivery System Guardrails & Auditability**, because safe operation requires enforceable controls
- **Pillar 7 — Organizational Design & Governance**, because leadership must define acceptable risk boundaries

---

## Scoring Interpretation

### Score 0
Agent usage is informal and largely unmanaged.

### Score 1
Some structured usage exists, but boundaries and controls are weak.

### Score 2
Agents operate within defined scopes in selected contexts.

### Score 3
A consistent operating model governs agent deployment across major areas.

### Score 4
Autonomy is systematically managed, monitored, and aligned with organizational risk tolerance.

---

## Relevance by Level

- **Level 1 — AI Initiated:** Minimal relevance  
- **Level 2 — Augmented Coding:** Increasing importance  
- **Level 3 — Managed Agents:** Foundational  
- **Level 4 — Spec-Driven Development:** Critical  
- **Level 5 — Autonomous Delivery:** Essential
