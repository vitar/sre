# Multi-Unit Failure and Breakdown

## Status

Draft v0.1

## Purpose

This document defines how failure, breakdown, degradation, and collapse should be interpreted when multiple units, each with their own local contour state, participate in a shared system.

Its purpose is to extend failure logic beyond the single-unit case into situations where:

* local units remain coherent,
* but the shared system becomes degraded,
* synchronization fails,
* mediator structures break down,
* or compensations across units become unsustainable.

This document should be read as the multi-unit counterpart to **Failure and Breakdown Definition** and in close relation to **Inter-Unit Synchronization Logic**.

It is a companion to:

* **Core Model Definition v0.2.1**
* **Failure and Breakdown Definition**
* **Inter-Unit Synchronization Logic**
* **Intervention Logic**
* **Use Constraints and Discipline**
* **Application Artifact Suite**

---

## 1. Why a Multi-Unit Failure Document Is Needed

The single-unit model can already describe:

* contour distortion,
* local breakdown,
* degradation,
* failure,
* and collapse

within one declared unit boundary.

However, once multiple units operate within a shared system, a new class of failure becomes possible:

* each unit may remain locally rational,
* each unit may even remain locally viable,
* but the shared system may still become degraded, blocked, or non-viable.

This happens because shared viability depends not only on local contour posture, but also on:

* synchronization quality,
* mediator integrity,
* cross-unit trade-off handling,
* sequencing,
* coordination capacity,
* and the sustainability of compensation across units.

Without a dedicated multi-unit failure layer, such cases are often misread as:

* personality conflict,
* local incompetence,
* individual underperformance,
* or isolated breakdown

when the real problem is failure of the shared system across units.

---

## 2. Core Principle

Multi-unit failure should not be defined as the simple sum of local failures.

A shared system may fail when:

* no unit has fully failed locally,
* but synchronization, coordination, or shared viability has failed structurally.

Likewise, one or more units may fail locally without causing full shared-system failure if compensating capacity remains.

This means that multi-unit failure is:

* **boundary-relative**,
* **time-sensitive**,
* **synchronization-dependent**,
* **mediator-shaped**,
* and often **compensation-mediated**.

The model therefore distinguishes:

* local failure,
* relational failure,
* shared-system failure,
* and portfolio-level degradation.

---

## 3. Core Definitions

### 3.1 Local Failure

A **local failure** is the failure of one unit within its own declared boundary.

The unit loses continuity, viability, functional identity, or adaptive sufficiency relative to its own role and operating context.

### 3.2 Relational Breakdown

A **relational breakdown** occurs when the connection, coordination, or synchronization between units degrades enough that normal shared operation is materially impaired.

Relational breakdown may exist even when the participating units remain locally coherent.

### 3.3 Shared-System Degradation

**Shared-system degradation** occurs when the enclosing system remains operational, but its cross-unit viability declines through rising friction, rising compensation cost, reduced coordination margin, or repeated synchronization stress.

### 3.4 Shared-System Failure

**Shared-system failure** occurs when the enclosing system can no longer sustain viable continuity, coherence, or functional identity across the participating units within the declared boundary and relevant time horizon.

This failure may arise from:

* accumulation of relational breakdown,
* persistent misalignment,
* mediator collapse,
* or exhausted compensation across units.

### 3.5 Cross-Unit Collapse

**Cross-unit collapse** occurs when the shared system loses the capacity to maintain basic cross-unit continuity and can no longer recover without major structural reconstitution, decoupling, or redesign.

This is stronger than shared-system failure and should be used carefully.

---

## 4. Local Viability vs Shared Viability

The most important distinction in the multi-unit case is between:

* **local viability**, and
* **shared viability**.

A unit may remain locally viable while contributing to shared-system failure.

Examples:

* a Product Manager may continue to optimize delivery effectively,
* an engineer may continue to optimize architecture effectively,
* operations may continue to protect reliability effectively,

while the shared system loses:

* synchronization,
* viable sequencing,
* acceptable trade-off handling,
* or coherent decision flow.

For this reason, local success is not sufficient evidence of shared-system health.

---

## 5. Failure Layers in Multi-Unit Systems

The model works best when multi-unit failure is assessed through distinct layers.

### 5.1 Unit Layer

Failure of one unit in its own boundary.

### 5.2 Relational Layer

Failure of the synchronization or coordination relation between units.

### 5.3 Shared-System Layer

Failure of the enclosing system in which the units participate.

### 5.4 Portfolio Layer

Failure patterns distributed across many related units, where no single local failure explains the wider degradation.

These layers should not be collapsed into one another without explicit argument.

---

## 6. Typical Multi-Unit Failure Conditions

A multi-unit system should be treated as entering breakdown, degradation, or failure when one or more of the following conditions emerges.

### 6.1 Persistent Mutual Blocking

Units cannot pursue their local logic simultaneously without repeatedly disabling one another.

### 6.2 Synchronization Failure

Units can no longer maintain viable coordination around shared priorities, sequence, or trade-offs.

### 6.3 Mediator Failure Across Units

Decision rights, trust, legitimacy, coordination structures, governance, or signaling fail badly enough to prevent viable cross-unit action.

### 6.4 Compensation Exhaustion Across Units

The shared system survives only because one or more units absorb unsustainable load, delay, risk, or hidden work for others.

### 6.5 Shared Identity Failure

The enclosing system continues formally, but no longer performs its defining shared function across units.

### 6.6 Distributed Drift

Local units continue operating, but their combined direction no longer supports shared-system continuity or viability.

---

## 7. Multi-Unit Failure Stack

### 7.1 Local Distortion

One or more units become contour-distorted without immediate relational or shared-system consequences.

### 7.2 Relational Breakdown

The relationship between units becomes unstable, blocked, or high-friction.

### 7.3 Shared-System Degradation

The enclosing system develops rising friction, rising coordination cost, rising trade-off conflict, or reduced compensation margin.

### 7.4 Shared-System Failure

The enclosing system loses viable continuity or functional identity across units.

### 7.5 Cross-Unit Collapse

The shared system can no longer recover without major structural redesign, decoupling, or re-foundation.

This stack should not be used mechanically, but it provides a disciplined progression for analysis.

---

## 8. Compensation in Multi-Unit Systems

Compensation is especially important in the multi-unit case.

A shared system may remain operational because:

* one unit absorbs hidden coordination work,
* one function carries excess risk,
* one group accepts chronic technical debt,
* one side keeps trading long-term viability for short-term continuity,
* or one role silently translates across otherwise incompatible states.

This means that the absence of visible breakdown may be a sign of cross-unit compensation rather than shared-system health.

Multi-unit analysis should therefore ask explicitly:

* Who is compensating?
* For how long?
* At what cost?
* And is that compensation still viable?

---

## 9. Formal Persistence vs Shared Functional Failure

A multi-unit system may survive formally while failing functionally.

Examples:

* a product organization still ships, but no longer coordinates effectively across product, engineering, and operations,
* a client-vendor system still has contracts and meetings, but no longer supports shared delivery viability,
* an institution still exists structurally, but its units no longer sustain the function that justifies the system as a whole.

Formal continuation is therefore weak evidence against shared-system failure.

---

## 10. Typical Failure Patterns

### 10.1 Product Manager ↔ Engineer Failure Pattern

A Product Manager remains locally effective in Reproduction.

An Engineer remains locally effective in Evolution or Survival.

The shared system fails because:

* delivery and structural viability are not sequenced,
* debt is externalized until compensation is exhausted,
* or decision rights do not support viable synchronization.

### 10.2 Operations ↔ Growth Failure Pattern

Operations protects continuity while growth functions scale faster than the system can absorb.

The shared failure emerges not because either unit is irrational, but because the shared system cannot sustain both local priorities at current synchronization quality.

### 10.3 Client ↔ Vendor Failure Pattern

The client preserves one horizon and constraint set while the vendor preserves another.

The shared delivery system degrades because assumptions, priorities, and trade-offs are not synchronized, often under weak mediator conditions.

### 10.4 Portfolio Drift Pattern

Many units remain locally functional, but the portfolio as a whole loses coherence, comparability, or viable coordination.

No single failure explains the whole. The failure is distributed.

---

## 11. Multi-Unit Failure Assessment Sequence

Use the following sequence when assessing multi-unit failure.

### Step 1 — Define the units

Which units are being assessed?

### Step 2 — Declare the shared system boundary

What enclosing system is being judged?

### Step 3 — Distinguish local vs shared failure question

Is the concern about one unit, the relationship, or the shared system?

### Step 4 — Assess local viability

Are the participating units locally coherent and viable?

### Step 5 — Assess relational integrity

Is synchronization viable across units?

### Step 6 — Assess mediator integrity

Are governance, trust, coordination, legitimacy, or decision rights supporting or blocking viable cross-unit operation?

### Step 7 — Assess compensation margin

Is the shared system surviving through sustainable coordination or through hidden overcompensation by specific units?

### Step 8 — Assign the narrowest accurate failure category

Examples:

* local breakdown,
* relational breakdown,
* shared-system degradation,
* shared-system failure,
* cross-unit collapse.

### Step 9 — Record confidence and boundary sensitivity

State explicitly where the judgment may change if the analytical boundary changes.

---

## 12. Common Multi-Unit Failure Misclassifications

### 12.1 Personality Reduction

Reducing structural synchronization failure to personal conflict.

### 12.2 Local Success Illusion

Assuming the shared system is healthy because each unit appears locally effective.

### 12.3 Wrong-Level Diagnosis

Treating a relational or shared-system failure as if it were only a unit-level problem.

### 12.4 Mediator Blindness

Ignoring governance, trust, legitimacy, or coordination structures that are driving cross-unit failure.

### 12.5 Compensation Blindness

Mistaking silent overcompensation for system resilience.

### 12.6 Formal Persistence Error

Assuming the shared system has not failed because it still exists administratively or procedurally.

### 12.7 Premature Collapse Language

Calling the shared system collapsed when it is still degraded or failing but potentially recoverable.

---

## 13. Minimal Multi-Unit Failure Record

### Multi-Unit Failure Record

* **Units involved:**
* **Shared system boundary:**
* **Local boundaries if relevant:**
* **Time horizon:**
* **Local state of each unit:**
* **Issue type:** local breakdown / relational breakdown / shared-system degradation / shared-system failure / cross-unit collapse
* **Primary failure condition:**
* **Mediator issues present:**
* **Compensation margin status:** intact / shrinking / exhausted
* **Formal survival vs shared functional survival:**
* **Confidence level:** high / medium / low
* **Notes:**

This record should be treated as part of the broader **Application Artifact Suite**.

---

## 14. Relationship to Intervention Logic

This document does not prescribe interventions in detail.

It defines the multi-unit failure conditions that interventions must respond to.

Typical next moves may include:

* synchronization repair,
* mediator repair,
* containment,
* re-sequencing,
* temporary asymmetry,
* decoupling,
* recovery,
* or reconstitution of the shared system.

The correct choice depends on the diagnosed multi-unit failure layer and compensation status.

---

## 15. Relationship to Other Documents

This document should be used together with the broader documentation set rather than in isolation.

In particular:

* **Failure and Breakdown Definition** still governs the logic of failure categories,
* **Inter-Unit Synchronization Logic** defines how units align or misalign before or during breakdown,
* **Intervention Logic** defines how response classes are selected,
* **Use Constraints and Discipline** governs boundary, horizon, confidence, and trade-off discipline,
* and **Application Artifact Suite** provides the structure for recording multi-unit assessments.

---

## 16. Working Summary

This document defines how failure and breakdown should be interpreted when multiple locally coherent units participate in a shared system.

Its central claim is:

**a shared system may degrade, fail, or collapse even when participating units remain locally viable, because shared viability depends on synchronization quality, mediator integrity, and sustainable cross-unit compensation.**

For that reason, the model extends failure analysis beyond the single-unit case through:

* local vs shared viability distinction,
* relational breakdown,
* shared-system degradation,
* multi-unit compensation analysis,
* and explicit multi-unit failure records.

Used this way, the model can describe not only whether units fail, but whether they can remain viable together.
