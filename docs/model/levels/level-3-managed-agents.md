# Level 3 — Managed Agents  
## Developer as Orchestrator

This is where AI stops feeling like a helper and starts acting more like a teammate that occasionally needs supervision.

Agent-style tools can pick up a task, modify multiple parts of the codebase, run tests, and open a PR on their own. Developers aren’t reading every line anymore — they’re mostly sanity-checking the outcome and jumping in when something smells wrong.

For a lot of orgs, this is the first stage where the development process actually changes, not just speeds up a bit. In other words, this is the first true transformation stage towards an AI-native organization.

---

## Core Characteristics

- Agents taking on full tasks instead of tiny edits  
- PRs showing up that nobody directly typed  
- Reviews focused on “does this work?” rather than “how was this written?”  
- Much more parallel activity happening at once  
- CI/CD pipelines getting noticeably busier  
- Supplying the right context to agents becoming a constant struggle  

---

## Organizational Signals

What tends to happen around this point:

- Some kind of planner/executor pattern emerging  
- Teams tracking how often humans have to intervene  
- Parts of the system labeled as safe (or unsafe) for automation  
- Rules being written about what agents are allowed to touch  
- Governance discussions getting less theoretical and more urgent  

---

## Primary Bottleneck

**Confidence in the results**

Producing solutions is cheap now. Knowing they’re correct is not.

You can generate tons of changes quickly, but validating them still takes time — especially when failures are subtle.

---

## Common Failure Mode

### Autonomy Cosplay

On paper, everything looks autonomous. In practice… not so much.

Typical warning signs:

- Changes that look reasonable but break edge cases  
- Reliability varying wildly depending on the task  
- Humans quietly fixing things behind the scenes  
- Leadership assuming capability is higher than reality  
- Risk issues surfacing after rollout  

Basically: impressive surface, fragile underneath.

---

## Transition Requirements to Level 4

To move forward, organizations usually have to rethink how work is defined.

Instead of focusing on implementation details, the emphasis shifts to describing the problem clearly enough that machines can solve it correctly.

That often involves:

- Moving toward spec-driven ways of working  
- Learning to express constraints and intent precisely  
- Building stronger automated validation  
- Defining governance for higher autonomy  
- Accepting that unclear requirements become the main blocker  

At this stage, bad specs hurt more than bad code.
