# Shared System State

## Purpose

This document defines how the model should describe the state of an enclosing system when multiple units, each with their own local contour posture, operate within it.

Its purpose is to introduce a disciplined concept of **shared system state** that is not reducible either to:

* the state of any one local unit,
* or to a simple average of the participating units.

The current documentation set already defines:

* single-unit contour state,
* proxy-supported state estimation,
* inter-unit synchronization,
* and multi-unit failure and breakdown.

What remains is to define what the enclosing system itself is doing, or becoming, when multiple units interact inside it.

This document addresses that layer.

It is a companion to:

* **Core Model Definition v0.2.1**
* **Classification Protocol v0.2**
* **Metrics and Proxies v0.2**
* **Failure and Breakdown Definition**
* **Intervention Logic**
* **Inter-Unit Synchronization Logic**
* **Multi-Unit Failure and Breakdown**
* **Use Constraints and Discipline**
* **Application Artifact Suite**
* **Comparability Rules**

---

## 1. Why a Shared System State Document Is Needed

Once multiple units participate in one enclosing system, analysis requires more than a list of local states.

Examples:

* a Product Manager may emphasize Reproduction,
* a Software Engineer may emphasize Evolution,
* operations may emphasize Survival,
* and governance may distort all three through mediator effects.

In such cases, the shared system may display a recognizable posture of its own:

* viable,
* strained,
* compensating,
* distorted,
* degrading,
* or failing,

without any single local state fully explaining it.

Without a shared-system state concept, the model risks two opposite errors:

* reducing the whole system to one dominant local perspective,
* or treating the system as nothing more than a collection of local states.

This document is needed to avoid both.

---

## 2. Core Principle

A **shared system state** is the state of the enclosing system produced by:

* the local contour states of participating units,
* the relations among those units,
* mediator conditions shaping those relations,
* the cross-unit allocation structure,
* and the current viability of the shared boundary over the relevant time horizon.

Shared system state is therefore:

* **emergent** rather than local,
* **structured** rather than arbitrary,
* **boundary-relative**,
* **time-sensitive**,
* and often **non-equivalent** to any one unit’s state.

---

## 3. Core Definitions

### 3.1 Shared System

A **shared system** is the enclosing system in which two or more units must jointly sustain some degree of continuity, propagation, adaptation, or coordinated function.

### 3.2 Shared System State

A **shared system state** is the contour posture of the enclosing system as it actually exists across the participating units, their interactions, and the mediators that shape them.

### 3.3 Local State Set

A **local state set** is the set of contour postures held by the participating units.

### 3.4 Shared Viability

**Shared viability** is the ability of the enclosing system to continue functioning coherently across units within the declared boundary and relevant time horizon.

### 3.5 State Emergence

**State emergence** is the process by which the shared system’s posture arises from the interaction of local states, synchronization quality, mediator conditions, and compensation patterns.

---

## 4. Shared System State Is Not a Simple Aggregate

The shared system state should not be treated as:

* the average of unit states,
* the majority contour among units,
* the strongest local state,
* or the most visible function in the system.

A shared system may be:

* Survival-strained even when one unit is Evolution-heavy,
* Reproduction-heavy even when some units are trying to stabilize,
* Evolution-constrained even when one local unit is strongly adaptive,
* or degraded because the interaction logic between units is weak rather than because any one unit is badly configured.

This means that the enclosing state must be analyzed at the level of the shared boundary itself.

---

## 5. Inputs to Shared System State

The shared system state should be inferred from at least five inputs.

### 5.1 Local Contour States

What are the primary contour postures of the participating units?

### 5.2 Synchronization Quality

How viable are the relationships among those units?

### 5.3 Mediator Conditions

Are governance, trust, legitimacy, coordination, decision rights, or meaning structures supporting or blocking viable cross-unit operation?

### 5.4 Cross-Unit Compensation

Is one or more units carrying hidden load or preserving the shared system through unsustainable compensation?

### 5.5 Shared Boundary Pressures

What environmental or system-level pressures act on the enclosing boundary rather than on a single unit alone?

These inputs should be treated as the minimum basis for serious shared-state assessment.

---

## 6. Shared System State Dimensions

The model does not introduce new contours at the shared-system level. It retains the same tri-contour structure, but interprets it at the level of the enclosing system.

### 6.1 Shared Survival

The degree to which the enclosing system can preserve continuity, coherence, and viability across units.

Shared Survival is weakened when:

* cross-unit coordination is fragile,
* mediator structures are unstable,
* local units repeatedly undermine one another,
* or compensation is near exhaustion.

### 6.2 Shared Reproduction

The degree to which the enclosing system can propagate, scale, extend, or replicate itself across units or through their coordinated outputs.

Shared Reproduction is weakened when:

* scaling is locally pursued but globally incoherent,
* propagation depends on unstable coupling,
* or extension outpaces shared-system integrity.

### 6.3 Shared Evolution

The degree to which the enclosing system can adapt, reorganize, or change its form through the coordinated behavior of its units.

Shared Evolution is weakened when:

* local adaptation does not integrate into system-wide change,
* mediators suppress viable learning,
* or synchronization costs block structural response.

---

## 7. Shared System State Types

The following categories provide a first practical classification of shared system posture.

### 7.1 Coherent

Local states differ, but the shared system remains viable, synchronized enough, and structurally legible.

### 7.2 Tense but Viable

Cross-unit tension is real, but the system still sustains acceptable continuity and trade-off handling.

### 7.3 Compensated

The shared system remains viable mainly because one or more units are carrying disproportionate hidden load, sequencing burden, translation work, or deferred cost.

### 7.4 Distorted

The shared system has a recognizable contour bias or relational weakness that creates structural risk even if it remains functional.

### 7.5 Degrading

The shared system is losing margin, coherence, or adaptation capacity faster than it is recovering them.

### 7.6 Failing

The shared system can no longer sustain viable continuity, coherence, or functional identity across units.

These categories are not meant to replace local diagnosis. They sit above it.

---

## 8. Shared State Emergence Patterns

### 8.1 Convergent Emergence

Several local states reinforce a shared system posture.

Example:

* multiple units prioritize rapid scaling,
* resulting in a shared Reproduction-heavy system.

### 8.2 Compensated Emergence

Conflicting local states still produce temporary shared viability through hidden balancing work.

Example:

* one unit preserves delivery credibility,
* another silently absorbs technical fragility,
* a third translates between them.

### 8.3 Blocked Emergence

Local states do not integrate into a viable shared posture because synchronization or mediator conditions prevent it.

Example:

* each unit is locally coherent,
* but no shared state forms that can sustain the enclosing system.

### 8.4 Drift Emergence

The system has no coherent shared posture, only drifting interactions among local states.

This is especially common in larger portfolios or under weak governance.

---

## 9. Shared System State Assessment Sequence

Use the following sequence when assessing shared system state.

### Step 1 — Declare the shared boundary

What enclosing system is being analyzed?

### Step 2 — Identify the units

Which local units materially participate in that system?

### Step 3 — Describe local states

What is the contour posture of each unit?

### Step 4 — Assess synchronization quality

How viable are the relations among those units?

### Step 5 — Assess mediator conditions

What cross-cutting structures are shaping shared operation?

### Step 6 — Assess compensation patterns

Who is carrying hidden load or preserving shared viability?

### Step 7 — Estimate shared contour posture

What is the best interpretation of the enclosing system’s shared Survival, Reproduction, and Evolution posture?

### Step 8 — Assign shared state type

Is the system coherent, tense but viable, compensated, distorted, degrading, or failing?

### Step 9 — Record uncertainty and sensitivity

What might change if the boundary, horizon, or participating units are redefined?

---

## 10. Product Manager ↔ Software Engineer Example

### 10.1 Local States

* Product Manager: Reproduction-oriented
* Software Engineer: Evolution-oriented, possibly Survival-sensitive

### 10.2 Shared System Possibilities

The shared product-delivery system may become:

* **coherent**, if sequencing and decision rights are clear,
* **tense but viable**, if trade-offs are explicit and periodically renegotiated,
* **compensated**, if engineering silently absorbs structural debt while product preserves outward delivery,
* **distorted**, if delivery pressure dominates and adaptation is chronically deferred,
* **degrading**, if compensation margin shrinks and recurring friction rises,
* **failing**, if the shared system can no longer sustain delivery, coherence, and structural viability together.

### 10.3 Analytical Value

This example shows why shared system state is needed.

Without it, the analyst is forced to choose between:

* “the PM is right,”
* “the engineer is right,”
* or “they disagree.”

With shared system state, the question becomes:

**What state is the shared system actually in, given these local postures and the way they interact?**

---

## 11. Relationship to Failure and Synchronization

Shared system state sits conceptually between:

* **Inter-Unit Synchronization Logic**, which explains how units align or misalign,
* and **Multi-Unit Failure and Breakdown**, which explains when the shared system degrades or fails.

This means:

* synchronization quality is a major input into shared state,
* shared state is a major input into multi-unit failure judgment,
* and both local and shared states matter when selecting interventions.

---

## 12. Minimal Shared System State Record

### Shared System State Record

* **Shared system boundary:**
* **Participating units:**
* **Unit state inventory:**
* **Time horizon:**
* **Coupling topology:**
* **Synchronization quality:**
* **Mediator map with directional effects:**
* **Compensation pattern:**
* **Failure propagation pathways:**
* **Recovery and re-synchronization modes:**
* **Estimated shared Survival posture:**
* **Estimated shared Reproduction posture:**
* **Estimated shared Evolution posture:**
* **Shared state type:** coherent / tense but viable / compensated / distorted / degrading / failing
* **Confidence level:** high / medium / low
* **Observability gaps:**
* **Notes:**

This record should be treated as part of the broader **Application Artifact Suite**.

---

## 13. Common Shared-State Errors

### 13.1 Majority-State Reduction

Assuming the shared state is simply whatever contour most units emphasize.

### 13.2 Dominant-Voice Reduction

Treating the loudest, most powerful, or most visible unit as the whole system.

### 13.3 Local-Average Reduction

Averaging local states and calling the result the shared state.

### 13.4 Synchronization Blindness

Ignoring the quality of inter-unit relations when estimating shared state.

### 13.5 Mediator Blindness

Ignoring governance, trust, coordination, legitimacy, or power conditions that shape the shared system.

### 13.6 Compensation Blindness

Treating compensated viability as stable shared coherence.

### 13.7 Boundary Confusion

Shifting between local and shared boundaries without explicit notice.

---

## 14. Relationship to Other Documents

This document extends the model beyond the single-unit case, but does not replace the existing documents.

In particular:

* **Classification Protocol** still governs local contour assignment,
* **Metrics and Proxies** may support both local and shared-state estimates,
* **Inter-Unit Synchronization Logic** defines how local states relate,
* **Multi-Unit Failure and Breakdown** defines how shared degradation and failure should be judged,
* **Intervention Logic** defines how action should follow from shared-state diagnosis,
* **Use Constraints and Discipline** still governs boundary, horizon, confidence, and trade-off rigor,
* and **Application Artifact Suite** should hold the shared-state record and related artifacts.

---

## 15. Working Summary

This document defines how to describe the state of an enclosing system when multiple locally distinct units participate in it.

Its central claim is:

**shared system state is an emergent posture of the enclosing system produced by local states, synchronization quality, mediator conditions, compensation patterns, and shared boundary pressures.**

For that reason, the model should not treat a multi-unit system as:

* one unit writ large,
* a mere average of local states,
* or a collection of unrelated local diagnoses.

Used this way, shared system state becomes the missing layer between local contour posture and multi-unit failure or intervention.
