# Level 4 — Spec-Driven Development  

> License: CC BY-SA 4.0  
> https://creativecommons.org/licenses/by-sa/4.0/

## Intent Becomes the Control Plane

Around this point, the team stops treating code as the “source of truth.”  
What matters more is a clear description of what the system is supposed to do — behavior, limits, performance expectations, weird edge cases, all that.

People spend a lot more time getting that description right. The actual code can be generated, thrown away, regenerated, tweaked… whatever. It’s no longer sacred.

Many groups use structured flows (for example: constitution → spec → plan → tasks → implementation), but in practice it’s rarely that tidy.

---

## Core Characteristics

- Work usually starts from a written intent, not a repo branch  
- Specs get versioned and reviewed seriously (even more than code)  
- Code becomes a derived artifact of intent rather than the primary asset: so it starts to feel disposable, which is unsettling at first  
- Scenario tests become the real proof that things behave correctly  
- Spec evolve - implementation regenerated: updating the spec can cascade into a fresh implementation  
- Teams argue a lot about wording because small ambiguities matter 

---

## Organizational Signals

Things you tend to notice:

- Product + engineering boundaries blur a bit: Convergence of roles around intent definition 
- Non-functional stuff (latency, reliability, security) finally gets spelled out  
- Reverse specification of brownfield systems to extract actual behavior 
- Architectural constitutions: Architecture rules are written down instead of living in people’s heads  
- More focus on invariants — the things that must not break, and system-level guarantees 

---

## Primary Bottleneck

**Specification fidelity: how precise the specification actually is**

Writing code used to be the hard part. Now it’s writing something precise enough that a machine won’t misunderstand it.

Vague specs = unpredictable results. Every time.

---

## Common Failure Mode

### Spec Theater

Lots of documents, not much clarity.

Typical signs:

- Improved documentation without enforceable intent: huge specs that still require someone to “interpret” them  
- Requirements that can’t be validated automatically  
- Different teams reading the same spec and building different things  
- Generated outputs all over the place  
- Leadership assuming “we’re ready” when… not really  

---

## Critical Insight

Agents pull signals from everywhere — existing code, docs, tests, examples.  
If those sources disagree, the system can amplify the mess very quickly.

So these need to stay roughly aligned:

- Documentation  
- Architecture  
- Implementation  
- Actual runtime behavior  

Keeping them in sync is ongoing work, not a one-time cleanup.

---

## Transition Requirements to Level 5

Moving forward usually means trusting the system to operate with minimal hand-holding.

That tends to involve:

- Fully automated pipelines driven by specs  
- Strong scenario-based validation  
- Safe environments (digital twins, staging replicas, etc.)  
- Governance that can handle higher autonomy  
- Confidence that constraints will be respected without constant human checking or in other words, intent can be enforced without continuous human supervision 

If the specs aren’t solid, this step gets scary fast.
