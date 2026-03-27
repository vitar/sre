# Inter-Unit Synchronization Logic

## Status

Draft v0.1

## Purpose

This document defines how the model should be applied when two or more units, each with their own contour state, must operate within a shared system.

Its purpose is to extend the model from single-unit diagnosis to inter-unit alignment, coordination, and conflict handling.

The current documentation set defines how to describe:

* a single unit,
* its contour posture,
* its proxy-supported state,
* its distortion patterns,
* its failure conditions,
* and its intervention logic.

What it does not yet define is how separately valid local states should be interpreted when they must coexist, coordinate, or synchronize inside one larger system.

This document addresses that missing layer.

It is a companion to:

* **Core Model Definition v0.2.1**
* **Classification Protocol v0.2**
* **Metrics and Proxies v0.2**
* **Failure and Breakdown Definition**
* **Intervention Logic**
* **Use Constraints and Discipline**
* **Application Artifact Suite**
* **Comparability Rules**

---

## 1. Why Inter-Unit Logic Is Needed

A system often contains multiple units that do not share the same contour posture at the same time.

Examples:

* a Product Manager emphasizing Reproduction while a Software Engineer emphasizes Evolution,
* operations emphasizing Survival while growth functions emphasize Reproduction,
* one team optimizing for continuity while another optimizes for experimentation,
* a client emphasizing immediate delivery while a vendor emphasizes structural adaptability.

In such cases, disagreement is not necessarily caused by error, bad intent, or irrationality.

It may arise because each unit is locally rational relative to:

* its own role,
* its own resources,
* its own time horizon,
* its own mediators,
* and its own local system boundary.

The practical problem then becomes:

**How should multiple locally valid contour states be synchronized within a shared system?**

This document defines the first logic for that question.

---

## 2. Core Principle

Inter-unit conflict should not be treated as disagreement of opinion by default.

It should first be treated as a possible misalignment of contour states, time horizons, system boundaries, or mediator conditions across units participating in a shared system.

Synchronization is therefore not the forced equalization of all local states.

It is the disciplined alignment of enough:

* contour priorities,
* timing,
* trade-off expectations,
* resource assumptions,
* and mediator conditions

for the shared system to remain viable.

---

## 3. Core Definitions

### 3.1 Unit

A **unit** is any bounded actor, role, team, subsystem, or functional node with its own local contour posture and resource allocation logic.

A unit may be:

* an individual role,
* a team,
* a function,
* a subsystem,
* a vendor,
* a client-side group,
* or another bounded participant in a shared system.

### 3.2 Local State

A **local state** is the contour posture of a given unit when analyzed within its own effective operating boundary.

### 3.3 Shared System

A **shared system** is the enclosing system in which two or more units must coordinate, exchange, sequence, or jointly sustain viability.

### 3.4 Synchronization

**Synchronization** is the process of bringing multiple units into sufficient alignment for the shared system to function viably, even if their local states remain different.

### 3.5 Misalignment

**Misalignment** is a condition in which units interpret priorities, horizons, trade-offs, or viability conditions differently enough to create friction, blockage, harmful local optimization, or breakdown in the shared system.

### 3.6 Synchronization Object

A **synchronization object** is the specific thing that must be aligned across units.

Possible synchronization objects include:

* priority,
* contour emphasis,
* time horizon,
* sequence of work,
* resource assumption,
* acceptable trade-off,
* decision authority,
* or mediator condition.

---

## 4. Shared System vs Local System

Each unit may have a locally rational contour state while the shared system remains misaligned.

This means that:

* local optimization may damage shared viability,
* shared viability may require temporary local sacrifice,
* and the same action may be rational within a local boundary but harmful within the enclosing one.

The model therefore requires analysts to distinguish between:

* **local contour logic**, and
* **shared system contour logic**.

Failure to make this distinction produces many false conflicts and many poor interventions.

---

## 5. Inter-Unit State Relations

The relationship between two or more units should be assessed explicitly.

### 5.1 Aligned

Units emphasize compatible contours, horizons, and trade-off assumptions strongly enough that shared coordination is low-friction.

### 5.2 Compatible but Tense

Units emphasize different contours, but the differences are structurally manageable if acknowledged and sequenced properly.

### 5.3 Partially Conflicting

Units pursue contour priorities that create recurring friction or trade-off disagreement, but the conflict is still negotiable.

### 5.4 Structurally Misaligned

Units operate under contour postures, horizons, or mediator conditions that repeatedly undermine one another.

### 5.5 Mutually Blocking

Units cannot maintain their local logic simultaneously without disabling the shared system’s viability.

These relation types should be treated as analytical categories, not moral labels.

---

## 6. Typical Multi-Unit Patterns

### 6.1 Survival ↔ Reproduction Pattern

One unit emphasizes continuity and risk control while another emphasizes scaling, throughput, or extension.

Typical tension:

* caution vs speed,
* resilience vs rollout,
* control vs reach.

### 6.2 Survival ↔ Evolution Pattern

One unit emphasizes continuity while another emphasizes redesign, adaptation, or experimentation.

Typical tension:

* reliability vs change,
* preservation vs restructuring,
* operational safety vs future fit.

### 6.3 Reproduction ↔ Evolution Pattern

One unit emphasizes delivery, expansion, or market movement while another emphasizes structural improvement, capability building, or redesign.

Typical tension:

* shipping vs redesign,
* scaling current form vs improving future form,
* market timing vs technical adaptability.

### 6.4 Three-Way Pattern

Different units emphasize all three contours differently.

Example:

* Product or growth function → Reproduction
* Engineering or architecture function → Evolution
* Operations or reliability function → Survival

This is not a model failure. It is a common real-world configuration.

The problem is not that the units differ. The problem is whether the shared system has enough synchronization logic to keep those differences viable.

---

## 7. Synchronization Modes

The model supports several distinct synchronization modes.

### 7.1 Alignment

Used when units can be brought into direct agreement on contour priority, horizon, or trade-off assumptions.

### 7.2 Negotiation

Used when units have valid but conflicting local logic and must explicitly negotiate acceptable trade-offs.

### 7.3 Sequencing

Used when units cannot prioritize the same contour at the same time, but can support shared viability through staged ordering.

### 7.4 Temporary Asymmetry

Used when one unit must carry a contour burden temporarily while others defer, compensate, or protect later rebalancing.

### 7.5 Decoupling

Used when units should not be forced into tight synchronization because coupling costs exceed benefits.

### 7.6 Mediator Repair

Used when misalignment persists because governance, trust, legitimacy, coordination, decision rights, or signaling structures are distorting synchronization itself.

### 7.7 Escalation to Shared Failure Logic

Used when local misalignment has crossed into shared-system degradation, breakdown, or failure and can no longer be treated as mere coordination tension.

---

## 8. Synchronization Logic Sequence

Use the following sequence when analyzing or designing synchronization across units.

### Step 1 — Define the units

Which units are being related?

### Step 2 — Declare the shared system boundary

What enclosing system are they jointly participating in?

### Step 3 — Declare local boundaries if needed

Where does each unit’s local logic become intelligible?

### Step 4 — Identify each unit’s local state

What is the current contour posture of each unit?

### Step 5 — Identify the synchronization object

What specifically must be aligned?

### Step 6 — Check horizon alignment

Are the units operating on the same time basis?

### Step 7 — Check mediator conditions

Are governance, trust, coordination, legitimacy, or decision rights shaping the misalignment?

### Step 8 — Assess the inter-unit state relation

Are the units aligned, compatible but tense, partially conflicting, structurally misaligned, or mutually blocking?

### Step 9 — Select synchronization mode

Choose the narrowest viable synchronization mode.

### Step 10 — State trade-offs and reassessment trigger

What must one or more units give up, delay, or accept to preserve the shared system, and when will synchronization be reassessed?

---

## 9. Synchronization Failure

Not all inter-unit tension is failure.

Synchronization failure occurs when units can no longer sustain viable coordination inside the shared system under the relevant boundary and time horizon.

This may happen when:

* local priorities remain mutually blocking,
* trade-offs are not acknowledged,
* mediator conditions prevent negotiation or sequencing,
* one unit’s compensation burden becomes unsustainable,
* or the shared system loses continuity because inter-unit logic has broken down.

Synchronization failure may exist even if each unit remains locally coherent.

This is one of the most important extensions of the model beyond single-unit analysis.

---

## 10. Mediators in Inter-Unit Synchronization

Many cross-unit problems that appear to be contour conflicts are actually mediator failures.

Examples:

* unclear decision rights,
* legitimacy mismatch,
* trust erosion,
* coordination bottlenecks,
* role ambiguity,
* incentive misalignment,
* missing escalation path.

For this reason, inter-unit analysis should always ask:

**Is this truly a contour conflict, or is a mediator preventing viable synchronization?**

The answer determines whether the right move is:

* align or sequence contour priorities,
* or repair the mediator layer.

---

## 11. Product Manager ↔ Software Engineer Example

### 11.1 Local States

A Product Manager may be locally oriented toward **Reproduction**:

* delivery,
* rollout,
* throughput,
* market timing,
* outward extension.

A Software Engineer may be locally oriented toward **Evolution** and/or **Survival**:

* structural adaptability,
* architecture,
* maintainability,
* reliability,
* reduction of fragility.

### 11.2 Misread Version

This configuration is often misread as:

* business vs engineering,
* speed vs perfection,
* product vs technology,
* or simply disagreement of judgment.

### 11.3 Model Read

The model instead reads this first as:

* locally valid but different contour states,
* likely horizon mismatch,
* possible shared-system misalignment,
* and possibly mediator weakness in role definition, decision rights, or sequencing.

### 11.4 Synchronization Object

What often needs synchronization is not the people themselves, but:

* shared horizon,
* sequencing of Reproduction and Evolution work,
* acceptable trade-off between speed and structural debt,
* or decision authority for when one contour may temporarily dominate.

### 11.5 Likely Synchronization Modes

Common viable modes include:

* **Negotiation** when trade-offs must be made explicit,
* **Sequencing** when immediate delivery and later structural work must both occur,
* **Temporary Asymmetry** when one side temporarily carries the load with explicit future correction,
* or **Mediator Repair** when the issue is role ambiguity or missing authority structure.

This example demonstrates why the model needs an inter-unit layer: neither local state is necessarily wrong, but the shared system may still become degraded if synchronization is weak.

---

## 12. Minimal Synchronization Record

### Inter-Unit Synchronization Record

* **Unit A:**
* **Unit B (or additional units):**
* **Shared system boundary:**
* **Local boundaries if relevant:**
* **Time horizon:**
* **Local state of Unit A:**
* **Local state of Unit B:**
* **Synchronization object:**
* **Inter-unit state relation:** aligned / compatible but tense / partially conflicting / structurally misaligned / mutually blocking
* **Mediator issues present:**
* **Coupling type:** loose / sequential / reciprocal / tightly coupled
* **Propagation pathway assumptions:**
* **Recovery mode assumptions:**
* **Monitoring triggers for escalation:**
* **Selected synchronization mode:**
* **Expected trade-off:**
* **Reassessment trigger:**
* **Confidence level:** high / medium / low
* **Notes:**

This record should be treated as part of the broader **Application Artifact Suite**.

---

## 13. Common Synchronization Errors

### 13.1 Opinion Reduction

Reducing contour-state misalignment to mere personal disagreement.

### 13.2 Local Rationality Blindness

Treating one unit as irrational when the real issue is shared-system misalignment.

### 13.3 Forced Equalization

Trying to make all units share the same contour posture instead of designing viable synchronization.

### 13.4 Mediator Blindness

Treating a synchronization problem as contour disagreement when decision rights, trust, legitimacy, or coordination structures are the real blocker.

### 13.5 Boundary Confusion

Failing to distinguish local and shared system boundaries.

### 13.6 Horizon Confusion

Assuming units disagree about values when they are actually working on different time horizons.

### 13.7 Premature Escalation

Treating manageable tension as failure before negotiation, sequencing, or temporary asymmetry has been attempted.

---

## 14. Relationship to Other Documents

This document does not replace:

* single-unit contour classification,
* proxy-supported state estimation,
* failure definition,
* intervention logic,
* or use discipline.

It extends them into the multi-unit case.

In particular:

* **Classification Protocol** still applies to local states,
* **Metrics and Proxies** may support local or shared-state estimates,
* **Failure and Breakdown Definition** still applies when shared synchronization degrades into failure,
* **Intervention Logic** still applies to synchronization moves once the inter-unit condition is diagnosed,
* **Use Constraints and Discipline** still governs boundary, horizon, confidence, and trade-off discipline,
* and **Application Artifact Suite** should hold the synchronization record and related artifacts.

---

## 15. Working Summary

This document defines the first multi-unit extension of the model.

Its central claim is:

**when multiple units must operate inside a shared system, conflict should first be read as possible contour-state misalignment, horizon mismatch, boundary mismatch, or mediator failure rather than as mere disagreement of opinion.**

For that reason, the model extends from single-unit diagnosis to inter-unit synchronization through:

* local state recognition,
* shared-system framing,
* synchronization objects,
* inter-unit relation types,
* synchronization modes,
* and explicit synchronization records.

Used this way, the model can describe not only how one unit allocates resources, but how multiple units remain viable together.
