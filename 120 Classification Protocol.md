# Classification Protocol

## Status

Draft v0.2

## Purpose

This document defines the practical protocol for classifying observed allocations, interventions, behaviors, or system activities across the three core contours:

* **Survival**
* **Reproduction**
* **Evolution**

Its purpose is to make application of the core model more disciplined, more repeatable, and less vulnerable to interpretive drift.

The protocol does not redefine the contours. It defines how they should be used in analysis.

This document is a companion to **Core Model Definition v0.2.1**. It assumes that:

* the three-contour core remains structurally valid,
* mediators may shape contour behavior,
* state description is often qualitative unless supported by explicit proxies,
* failure-related judgments belong to a separate failure document,
* intervention selection belongs to a separate intervention document,
* and serious application should leave behind structured artifacts rather than free-form interpretation alone.

This draft maintains the core logic of the prior version while updating its documentation context after the introduction of the broader companion set. It should now be read alongside:

* **Metrics and Proxies**
* **Failure and Breakdown Definition**
* **Intervention Logic**
* **Use Constraints and Discipline**
* **Application Artifact Suite**
* **Comparability Rules**
* **Model Assumptions Test Plan**

---

## 1. Why a Classification Protocol Is Needed

The core model treats Survival, Reproduction, and Evolution as analytically distinct **primary functional intents**. In real systems, however, the same action often has multiple effects.

For example:

* a stabilizing action may also enable later change,
* a scaling action may strengthen near-term continuity,
* an innovation investment may improve long-term survivability,
* a governance intervention may alter all three indirectly.

Without a classification protocol, the model risks becoming too elastic. Different observers may assign the same action to different contours without stating why. The result is interpretive inconsistency rather than disciplined analysis.

The purpose of this protocol is therefore not to remove judgment, but to structure it.

---

## 2. Classification Object

A **classification object** is the unit being classified.

Depending on context, this may be:

* a resource allocation,
* a decision,
* a policy,
* an intervention,
* a recurring activity,
* a capability investment,
* a component,
* or a detected system behavior.

The protocol works best when the classification object is explicit and narrow enough to be analyzed meaningfully.

Poor classification often begins when the object is too vague, too broad, or mixes multiple decisions into one statement.

---

## 3. Core Classification Principle

Classification should be based on **primary functional intent under a stated time horizon**, not on every possible downstream consequence.

This leads to two required rules.

### 3.1 Primary Intent Rule

Ask first:

**What is the main function this allocation or action is intended to serve?**

Primary intent is not the same as rhetorical justification. It refers to the dominant system function the action is actually designed to support.

### 3.2 Time Horizon Rule

Ask next:

**Over what time horizon is the primary function being interpreted?**

At minimum, every classification should identify whether the primary contour is being assigned in the:

* short term,
* medium term,
* or long term.

This rule is required because contour effects often diverge across time.

---

## 4. Canonical Contour Tests

The following tests should be applied in order.

### 4.1 Survival Test

Classify toward **Survival** when the primary function is to preserve current viability, continuity, integrity, or operational stability.

Guiding questions:

* Is the main purpose to keep the system functioning?
* Is the action primarily defensive, protective, stabilizing, or reliability-oriented?
* Would the action still be justified even if it did not increase growth or adaptation?
* Is the main concern continuity under threat, stress, or uncertainty?

Typical indicators:

* maintenance,
* protection,
* controls,
* resilience,
* repair,
* continuity,
* reliability,
* risk reduction.

### 4.2 Reproduction Test

Classify toward **Reproduction** when the primary function is to copy, scale, extend, replicate, or propagate the current form, output, reach, or throughput of the system.

Guiding questions:

* Is the main purpose to increase quantity, reach, replication, or throughput?
* Is the action primarily about expansion rather than redesign?
* Would the action still be justified if it scaled the current form without materially improving it?
* Is the main concern extension of what already exists?

Typical indicators:

* growth,
* scaling,
* duplication,
* rollout,
* propagation,
* replication,
* throughput,
* market expansion.

### 4.3 Evolution Test

Classify toward **Evolution** when the primary function is to change the form, capability, structure, or adaptive potential of the system.

Guiding questions:

* Is the main purpose to improve adaptability, discover new states, or alter how the system works?
* Is the action primarily exploratory, developmental, innovative, or redesign-oriented?
* Would the action still be justified even if it did not increase immediate scale or immediate stability?
* Is the main concern future fit rather than current continuity?

Typical indicators:

* experimentation,
* R&D,
* redesign,
* learning,
* innovation,
* adaptation,
* capability building,
* structural change.

---

## 5. Secondary Effects Discipline

A classification object may legitimately affect more than one contour.

However, the protocol requires analysts to distinguish between:

* **primary contour**, and
* **secondary contour effects**.

This is necessary because almost any meaningful intervention in a complex system has cross-contour consequences.

### 5.1 Recording Rule

When secondary effects matter, record them separately using a simple structure:

* **Primary contour:** one contour only
* **Secondary effects:** optional, one or more
* **Time horizon:** stated explicitly

### 5.2 Interpretation Rule

Secondary effects do not overrule primary contour assignment. They refine interpretation.

For example:

* short-term Survival action with long-term Evolution support,
* medium-term Evolution action with short-term Survival cost,
* short-term Reproduction action with long-term Survival erosion.

---

## 6. Mediator Handling Rule

Some objects are best understood not as contour allocations themselves, but as **mediators** that alter allocation, constraint, signaling, coordination, or feedback across contours.

Examples may include:

* governance mechanisms,
* incentive structures,
* coordination routines,
* meaning frameworks,
* legitimacy rules,
* trust architecture,
* power distribution.

When the main function of the object is to shape how contour behavior is organized rather than to directly allocate into one contour, it should be classified as:

* **Mediator-first**, then
* optionally interpreted by contour consequences.

### 6.1 Mediator-First Rule

Do not force every object into Survival, Reproduction, or Evolution if its primary function is cross-cutting structural mediation.

### 6.2 Contour Consequence Rule

After identifying an object as mediator-first, record its likely contour consequences separately.

Example structure:

* **Type:** Mediator
* **Primary role:** governance / coordination / meaning / power / etc.
* **Likely contour effects:** Survival+, Reproduction−, Evolution constrained
* **Time horizon:** stated explicitly

This preserves the core model while avoiding classification distortion.

---

## 7. Boundary Declaration Requirement

Every real application of the protocol should begin by declaring the analysis boundary.

At minimum, this should state:

* the focal system,
* the nesting level,
* the main excluded externalities,
* and the intended time horizon.

Classification quality often breaks down not because the contours fail, but because analysts shift boundaries silently.

The same action may classify differently depending on whether the focal system is:

* a team,
* a company,
* a market,
* a state,
* or a civilization.

That is not a flaw in the model. It is a boundary problem and must be handled explicitly.

---

## 8. Recommended Classification Sequence

Use the following sequence for every classification object.

### Step 1 — Define the object

What exactly is being classified?

### Step 2 — Declare the boundary

What system is being analyzed, at what level, and with what excluded externalities?

### Step 3 — Declare the time horizon

Is the primary interpretation short-term, medium-term, or long-term?

### Step 4 — Test for mediator-first status

Is the object primarily shaping allocation or coordination rather than directly serving a contour?

### Step 5 — Assign primary contour

Which contour best captures the object’s primary functional intent?

### Step 6 — Record secondary effects

What meaningful cross-contour consequences follow?

### Step 7 — State uncertainty

If ambiguity remains, describe it explicitly rather than forcing false precision.

---

## 9. Ambiguity Handling

Ambiguity should not be hidden.

If a classification object cannot be assigned confidently, the analyst should state why. Common reasons include:

* mixed intent,
* unclear boundary,
* conflicting time horizons,
* insufficient evidence,
* or mediator dominance.

### 9.1 Acceptable Ambiguity Labels

The following labels may be used:

* **mixed-primary** — two contours remain inseparable at current resolution,
* **boundary-sensitive** — classification changes depending on system boundary,
* **time-sensitive** — classification changes across time horizons,
* **mediator-dominant** — the object is primarily cross-cutting,
* **low-confidence** — insufficient evidence.

The protocol prefers explicit ambiguity over forced certainty.

---

## 10. Proxy Support

Where possible, classification should be supported by observable proxies.

Typical proxy classes include:

* budget share,
* time allocation,
* headcount allocation,
* reliability load,
* throughput orientation,
* experimentation share,
* investment category,
* policy focus,
* and decision criteria.

Proxy use does not eliminate judgment. It makes judgment more disciplined.

### 10.1 Proxy Use Rule

If proxies are available, use them to support, challenge, or refine intuitive classification.

### 10.2 Proxy Limitation Rule

If proxies are weak, noisy, or unavailable, the classification should remain qualitative and state its uncertainty.

### 10.3 Comparison Caution Rule

Classification records should not be treated as comparable across cases unless boundary, horizon, and classification discipline are sufficiently aligned.

Detailed validity conditions for comparison belong to **Comparability Rules**, not to this document alone.

---

## 11. Common Misclassification Patterns

### 11.1 Outcome-Only Classification

Mistaking visible outcome for primary intent.

Example: classifying a reliability investment as Reproduction only because it later enabled growth.

### 11.2 Rhetoric-Driven Classification

Using how an action is described rather than what it functionally serves.

Example: calling a control policy “innovation support” when its operational effect is constraint and stabilization.

### 11.3 Boundary Drift

Silently shifting the focal system during analysis.

Example: classifying from the perspective of a team in one sentence and from the perspective of the company in the next.

### 11.4 Horizon Collapse

Ignoring time horizon and compressing all effects into one moment.

Example: treating a short-term stabilizer as non-Evolutionary even when its long-term function is capability transformation.

### 11.5 Mediator Forcing

Forcing cross-cutting structures into a contour when they are better handled as mediators.

Example: treating governance itself as a contour instead of a mediator shaping all three.

### 11.6 Artifact-Free Classification

Producing contour assignments without leaving behind enough structured context to review the claim later.

This weakens repeatability, comparability, and intervention traceability.

---

## 12. Minimal Classification Template

The following template should be used in real applications.

### Classification Record

* **Object:**
* **System boundary:**
* **Nesting level:**
* **Excluded externalities:**
* **Time horizon:**
* **Mediator-first?** yes / no
* **Primary contour:** Survival / Reproduction / Evolution / Mediator
* **Secondary effects:**
* **Proxy support:**
* **Confidence level:** high / medium / low
* **Notes:**

This template should be treated as part of the broader **Application Artifact Suite** rather than as a standalone note pattern.

---

## 13. Example Forms

### 13.1 Example A — Reliability Patch

* Object: production hardening patch
* System boundary: software service
* Time horizon: short-term
* Primary contour: Survival
* Secondary effects: may support later Reproduction by reducing service instability
* Confidence: high

### 13.2 Example B — Market Rollout

* Object: rollout to five new regions
* System boundary: product business
* Time horizon: medium-term
* Primary contour: Reproduction
* Secondary effects: may stress Survival if support capacity is weak
* Confidence: high

### 13.3 Example C — Architecture Experiment

* Object: prototyping new system architecture
* System boundary: engineering organization
* Time horizon: medium-to-long term
* Primary contour: Evolution
* Secondary effects: short-term Survival cost due to disruption
* Confidence: medium

### 13.4 Example D — Governance Rule Change

* Object: approval policy for major changes
* System boundary: organization
* Time horizon: medium-term
* Mediator-first: yes
* Primary role: governance
* Likely contour effects: Survival+, Evolution−, Reproduction delayed
* Confidence: medium

---

## 14. What Good Classification Looks Like

Good classification is:

* explicit about boundary,
* explicit about time horizon,
* explicit about primary intent,
* honest about secondary effects,
* honest about uncertainty,
* and structured enough to support later review.

The protocol is working well when different analysts can reproduce similar classifications for the same object and explain disagreements using boundary, horizon, mediator, evidence, or proxy differences rather than intuition alone.

---

## 15. Relationship to Other Documents

This protocol should be used together with the other companion documents rather than as a complete application method by itself.

In particular:

* **Metrics and Proxies** supports evidence-backed classification,
* **Failure and Breakdown Definition** defines how classification findings should and should not escalate into failure claims,
* **Intervention Logic** defines how classification and diagnosis connect to action,
* **Use Constraints and Discipline** defines the minimum rules that make classification trustworthy,
* **Application Artifact Suite** defines how classification records fit into repeatable application,
* and **Comparability Rules** defines when classifications can be validly compared across cases or over time.

---

## 16. Working Summary

This protocol defines how to classify real-world objects into the model without collapsing into ambiguity.

It does so by requiring:

* a clear object,
* an explicit system boundary,
* an explicit time horizon,
* a primary-intent assignment,
* mediator handling where appropriate,
* secondary-effect recording,
* proxy support where available,
* and uncertainty discipline.

Its central claim is practical rather than theoretical:

**the core model becomes more reliable when contour classification is treated as a disciplined analytical procedure rather than as intuitive labeling.**
