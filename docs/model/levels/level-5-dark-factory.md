# Level 5 — Autonomous Delivery  

> **License:** CC BY-SA 4.0  
> https://creativecommons.org/licenses/by-sa/4.0/

## Dark Factory

At this level, software production operates as a largely autonomous system.

Agents generate implementations, validate them against real-world behavior in digital-twin environments, and iterate until convergence — without human code writing or line-by-line review.

Confidence derives from a rigorous evaluation infrastructure rather than artifact inspection.

Harnesses, simulations, scenario-based validation, and real-world feedback loops collectively assure that outcomes meet intent.

---

## Core Characteristics

- Spec → task graph → agent execution → validated outcome
- Fully automated build–test–revise cycles
- Continuous improvement within defined constraints
- Code treated as disposable implementation, not the primary asset
- Small human teams capable of maintaining very large systems
- Regeneration of subsystems is feasible as specifications evolve

---

## Organizational Signals

Organizations at this stage often exhibit:

- Minimal human coordination for routine development work
- Industrial-grade auditability, traceability, and rollback capabilities
- Clearly defined domain boundaries where autonomy is permitted
- Explicit documentation of safe operating envelopes
- Outcome governance replacing implementation oversight
- Strategic focus on system-level risk management

---

## Primary Bottleneck

**Evaluation completeness and risk management**

As autonomy increases, the central challenge becomes ensuring that evaluation mechanisms cover the full spectrum of realistic scenarios, failure modes, and unintended consequences.

---

## Common Failure Mode

### Dark Factory Mythology

Organizations claim full autonomy while significant hidden human labor continues to perform safety, verification, or corrective work.

Symptoms include:

- Undocumented manual interventions
- Reliance on expert operators to maintain stability
- Incomplete audit trails
- Overstated autonomy in external messaging
- Fragile systems that degrade without continuous human oversight

---

## Critical Insight

Autonomy is domain-specific.

Different domains — due to technical complexity, regulatory requirements, safety considerations, and environmental variability — will achieve different levels of autonomy.

Most organizations will operate across multiple levels simultaneously:

- Legacy cores remain human-curated
- Peripheral or well-bounded systems become autonomous
- Migration occurs unevenly over time

---

## Optimizing at Level 5

At this stage, the focus shifts from increasing autonomy to sustaining it safely.

Key ongoing concerns include:

- Governance of autonomous decision-making
- Long-term system evolution
- Ethical and regulatory compliance
- Monitoring for drift from intended behavior
- Maintaining alignment between specifications and real-world outcomes
