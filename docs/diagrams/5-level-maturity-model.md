# 5-Level AI Transformation Maturity Model

> **License:** CC BY-SA 4.0  
> https://creativecommons.org/licenses/by-sa/4.0/

This diagram presents the model as an ascending staircase from Level 1 to Level 5.

```mermaid
flowchart LR

%% Step 1
subgraph STEP1[" "]
direction TB
L1["Level 1<br/><b>AI Initiated</b>"]:::level
N1["Assistive AI use<br/>No structural workflow change<br/>Local productivity gains"]:::note
L1 --- N1
end

%% Step 2
subgraph STEP2[" "]
direction TB
L2["Level 2<br/><b>Augmented Coding</b>"]:::level
N2["AI as junior contributor<br/>Multi-file bounded tasks<br/>Human line-by-line review"]:::note
L2 --- N2
end

%% Step 3
subgraph STEP3[" "]
direction TB
L3["Level 3<br/><b>Managed Agents</b>"]:::level
N3["Agents execute task bundles<br/>Outcome-based supervision<br/>Safe-to-automate domains emerge"]:::note
L3 --- N3
end

%% Step 4
subgraph STEP4[" "]
direction TB
L4["Level 4<br/><b>Spec-Driven Development</b>"]:::level
N4["Intent becomes primary artifact<br/>Specs drive implementation<br/>Scenario suites validate outcomes"]:::note
L4 --- N4
end

%% Step 5
subgraph STEP5[" "]
direction TB
L5["Level 5<br/><b>Autonomous Delivery</b>"]:::level
N5["Spec → task graph → execution<br/>Minimal routine human coding<br/>Strong gates, auditability, recovery"]:::note
L5 --- N5
end

%% Stair progression
L1 --> L2 --> L3 --> L4 --> L5

%% Visual styling
classDef level fill:#f8f9fa,stroke:#4b5563,stroke-width:1px,color:#111827,font-weight:bold;
classDef note fill:none,stroke:none,color:#111827;
