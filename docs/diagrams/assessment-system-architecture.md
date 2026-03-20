# Assessment System Architecture

> **License:** CC BY-SA 4.0  
> https://creativecommons.org/licenses/by-sa/4.0/

This diagram shows how the assessment framework combines capability, operating mode, and safety constraints into a final maturity determination.

```mermaid
flowchart TB

P["Capability Pillars<br/><br/>7 dimensions scored 0-4<br/>• Intent & Specification Fidelity<br/>• Evaluation & Scenario Architecture<br/>• Agent Operating Model & Autonomy Control<br/>• Delivery Guardrails & Auditability<br/>• Codebase Readiness & Brownfield Extractability<br/>• Infrastructure & Tooling Readiness<br/>• Organizational Design & Governance"]:::box

L["Maturity Levels<br/><br/>Observed dominant operating mode<br/>Level 1 → Level 5"]:::box

G["Stage Gates<br/><br/>Binary readiness constraints<br/>• Evaluation adequacy<br/>• Guardrails & controls<br/>• Accountability & governance<br/>• Recoverability & resilience<br/>• Domain suitability"]:::box

U["Unified Scoring System<br/><br/>Final assessment logic:<br/>effective maturity = constrained by<br/>levels + pillars + gates"]:::core

R["Assessment Result<br/><br/>• Effective maturity level<br/>• Identified bottlenecks<br/>• Risk exposure<br/>• Recommended next moves"]:::result

P --> U
L --> U
G --> U
U --> R

classDef box fill:#f8f9fa,stroke:#4b5563,stroke-width:1px,color:#111827;
classDef core fill:#e0f2fe,stroke:#0284c7,stroke-width:2px,color:#0f172a,font-weight:bold;
classDef result fill:#ecfccb,stroke:#65a30d,stroke-width:2px,color:#1f2937,font-weight:bold;
