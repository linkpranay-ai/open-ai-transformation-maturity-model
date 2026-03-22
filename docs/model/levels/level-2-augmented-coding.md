<a id="top"></a>

[Home](../../../README.md) · [Getting Started](../../GETTING_STARTED.md) · [Model](../5-level-maturity-model.md) · [Assessment Hub](../assessment/README.md) · [Roadmap](../../ROADMAP.md) · [References](../../REFERENCES.md)

---
# Level 2 — Augmented Coding

> **License:** CC BY-SA 4.0  
> https://creativecommons.org/licenses/by-sa/4.0/

## AI as a Junior Contributor

At this level, AI systems perform bounded implementation tasks that may span multiple files, such as test generation, refactoring, scaffolding, and documentation.

Developers still control task decomposition, architectural decisions, and acceptance. Work remains largely ticket-driven, and AI output is reviewed line by line before integration.

AI begins to function as a junior contributor rather than a mere assistant.

---

## Core Characteristics

- Significant increase in code production
- AI performs multi-file but well-bounded tasks
- Review and integration become primary bottlenecks
- Delivery speed improves modestly, not proportionally to output
- Legacy system comprehension accelerates through AI assistance

---

## Organizational Signals

Organizations at this stage often exhibit:

- Standardization of tools by task class (coding, testing, documentation)
- AI-assisted workflows becoming routine across teams
- Significant increase in automated test generation
- Escalating review load as more code is produced
- Continued reliance on traditional ticket-driven development

Organizations frequently plateau here because they equate faster coding with faster engineering.

---

## Primary Bottleneck

**Human verification capacity**

Although AI produces more implementation artifacts, humans remain responsible for validating correctness, safety, and integration, creating a growing review bottleneck.

---

## Common Failure Mode

### PR Flood

Organizations experience a surge in pull requests and development activity without corresponding improvements in delivery speed.

Symptoms include:

- Large increases in code volume and commit frequency
- Review queues are growing faster than they can be processed
- Integration friction rising
- Cycle time remains largely unchanged
- Leadership perceiving high productivity despite stagnant outcomes

---

## Transition Requirements to Level 3

Moving beyond this stage typically requires:

- Shifting review from line-level to outcome-level evaluation
- Establishing trust boundaries for AI-generated changes
- Improving automated testing and validation infrastructure
- Redesigning workflows to manage AI-raised contributions
- Recognizing that verification, not generation, is the scaling constraint

---

[↑ Back to top](#top) · [Home](../../../README.md)
