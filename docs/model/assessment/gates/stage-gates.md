# Stage Gates — Readiness Constraints for Advancement

> **License:** CC BY-SA 4.0  
> https://creativecommons.org/licenses/by-sa/4.0/

Stage gates define mandatory conditions that must be satisfied before an organization can safely operate at higher maturity levels.

👉 [Back to Assessment Framework](README.md)  
👉 [Back to Unified Scoring System](scoring-model.md)

---

## Why Stage Gates Exist

Capability alone does not guarantee safe transformation.

Organizations may possess advanced tools or skills but lack the controls required to prevent catastrophic failure.

Stage gates act as safety constraints that prevent premature adoption of higher autonomy levels.

Failure to satisfy a required gate blocks advancement regardless of pillar scores.

---

## How Stage Gates Differ from Pillars

- **Pillars** measure capability maturity  
- **Levels** describe operating mode  
- **Gates** enforce safety and readiness  

Gates are binary conditions: satisfied or not satisfied.

---

## Gate Categories

Stage gates typically address the following risk areas:

- Evaluation adequacy
- Governance and accountability
- Operational safeguards
- Domain suitability
- Recoverability

---

## Gate 1 — Reliable Evaluation Capability

The organization must be able to validate system behavior automatically and detect regressions with high confidence.

Indicators include:

- comprehensive automated testing
- scenario-based validation
- production-representative environments
- measurable success criteria
- low dependence on manual QA for correctness

Without this capability, increased autonomy creates unacceptable risk.

---

## Gate 2 — Enforceable Guardrails and Controls

Automated systems must operate within technically enforced boundaries.

Indicators include:

- policy-based access controls
- protected deployment pathways
- prevention of unsafe actions
- monitoring and alerting mechanisms
- controlled permissions for automated actors

Procedural safeguards alone are insufficient.

---

## Gate 3 — Accountability and Governance

Clear responsibility must exist for outcomes produced by automated systems.

Indicators include:

- defined ownership of AI-driven processes
- governance policies for acceptable risk
- escalation mechanisms for anomalies
- leadership alignment on transformation goals

Ambiguous accountability leads to operational paralysis during incidents.

---

## Gate 4 — Recoverability and Resilience

The organization must be able to recover from failures quickly and reliably.

Indicators include:

- tested rollback procedures
- disaster recovery capabilities
- change traceability
- incident response processes
- ability to halt automated activity if necessary

Higher autonomy amplifies the importance of recovery mechanisms.

---

## Gate 5 — Domain Suitability for Autonomy

Not all domains are equally safe for autonomous operation.

Indicators include:

- well-defined system boundaries
- manageable risk impact
- predictable behavior patterns
- regulatory considerations
- tolerance for errors or delays

Organizations often operate multiple domains at different maturity levels.

---

## Interpreting Gate Results

### All Required Gates Satisfied
Advancement may proceed if pillar capability supports it.

### Some Gates Not Satisfied
Advancement is blocked or limited to lower-risk contexts.

### Major Gate Failures
Higher autonomy should not be attempted.

---

## Relationship to Maturity Levels

Gate requirements increase with maturity level:

- Lower levels require minimal gating
- Mid-level autonomy requires strong evaluation and control
- Highest levels require comprehensive safeguards across all categories

Organizations may operate different systems at different gated levels simultaneously.

---

## Use in Assessments

Stage gates should be evaluated through evidence-based review involving:

- engineering leadership
- platform teams
- risk and governance stakeholders
- operations teams

Gates represent organizational readiness, not technical ambition.
