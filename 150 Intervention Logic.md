# Intervention Logic

## Status

Draft v0.1

## Purpose

This document defines how the model moves from diagnosis to action.

Its purpose is to provide a disciplined bridge between:

* contour classification,
* state estimation,
* failure and breakdown assessment,
* and recommended intervention classes.

The model already explains how systems allocate limited resources across:

* **Survival**
* **Reproduction**
* **Evolution**

It also distinguishes distortions, breakdowns, degradation, and failure. What remains is to define how these diagnosed conditions should guide action without collapsing into over-simplified prescriptions.

This document is a companion to:

* **Core Model Definition v0.2**
* **Classification Protocol**
* **Metrics and Proxies**
* **Failure and Breakdown Definition**

---

## 1. Why Intervention Logic Is Needed

A model that only describes system state remains incomplete for practical use.

Without intervention logic:

* diagnosis cannot reliably produce decisions,
* distortion findings remain observational,
* failure definitions remain retrospective,
* and different analysts may recommend incompatible actions from the same diagnosis.

Intervention logic is therefore needed to answer:

**Given the diagnosed state of the system, what class of move is justified next?**

This document does not define detailed implementation plans. It defines intervention classes and selection logic.

---

## 2. Core Principle

Interventions should respond to the diagnosed structure of the problem, not merely to the visible symptom.

The model therefore treats interventions as responses to one or more of the following:

* contour imbalance,
* contour underfunding,
* local breakdown,
* systemic degradation,
* mediator blockage,
* exhausted compensation margin,
* or boundary mismatch in the diagnosis itself.

The goal of intervention is not always “balance” in the abstract.

The goal is to restore or preserve viable continuity within the declared boundary and relevant time horizon.

This means that the right intervention may be:

* rebalancing,
* stabilization,
* containment,
* adaptive investment,
* scaling control,
* mediator repair,
* recovery,
* reconstitution,
* or boundary redefinition.

---

## 3. Intervention Object

An **intervention object** is the system condition being acted upon.

Depending on the case, the intervention object may be:

* a contour imbalance,
* a repeated breakdown pattern,
* a failing subsystem,
* a misallocated resource flow,
* a distorted incentive structure,
* a mediator bottleneck,
* a misdrawn system boundary,
* or a combination of these.

Intervention quality depends on whether the intervention object is defined correctly.

---

## 4. Intervention Classes

The model uses the following core intervention classes.

### 4.1 Stabilize

Use when the immediate problem is loss of continuity, integrity, coherence, or short-term viability.

Primary purpose:

* restore or preserve Survival function.

Typical uses:

* operational instability,
* repeated incidents,
* acute fragility,
* pre-collapse conditions,
* continuity threats.

### 4.2 Contain

Use when harmful dynamics are spreading and the immediate need is to prevent wider system damage.

Primary purpose:

* limit propagation of breakdown, distortion, or failure.

Typical uses:

* cascading failure,
* brittle scaling,
* uncontrolled experimentation,
* feedback amplification,
* mediator-driven escalation.

### 4.3 Rebalance

Use when contour allocation is distorted but the system remains viable enough for deliberate correction.

Primary purpose:

* shift resources across contours to reduce structural distortion.

Typical uses:

* Survival dominance causing stagnation,
* Reproduction dominance causing brittle growth,
* Evolution dominance causing overheating,
* chronic underfunding of one contour.

### 4.4 Adapt

Use when the system remains viable but is becoming unfit for its environment.

Primary purpose:

* strengthen Evolution function and future fit.

Typical uses:

* adaptive lag,
* environmental change,
* lock-in to obsolete form,
* declining capability relevance.

### 4.5 Consolidate

Use when the system has changed, grown, or experimented faster than it has stabilized.

Primary purpose:

* convert fragile gain into durable form.

Typical uses:

* post-growth fragility,
* post-innovation instability,
* scaling without process maturity,
* weak consolidation after experimentation.

### 4.6 Scale

Use when the system is viable, sufficiently coherent, and under-reproducing relative to its context or purpose.

Primary purpose:

* increase Reproduction function without compromising Survival beyond acceptable bounds.

Typical uses:

* healthy under-extension,
* replication opportunity,
* low utilization of proven form,
* propagation bottlenecks.

### 4.7 Repair Mediator

Use when cross-cutting mediators are blocking viable allocation, signaling, coordination, or legitimacy.

Primary purpose:

* restore or improve allocation conditions rather than directly shifting contour resources.

Typical uses:

* governance bottlenecks,
* coordination collapse,
* legitimacy loss,
* trust erosion,
* power structures that prevent coherent response.

### 4.8 Recover

Use when the system has already crossed into failure or severe degradation but remains recoverable within the current boundary.

Primary purpose:

* rebuild viable continuity without total re-foundation.

Typical uses:

* post-failure restoration,
* major breakdown recovery,
* depleted reserve restoration,
* identity repair within a still-valid boundary.

### 4.9 Reconstitute

Use when recovery within the current form is no longer viable.

Primary purpose:

* replace, re-found, or substantially reconstruct the system.

Typical uses:

* collapse,
* identity failure beyond repair,
* irrecoverable mediator distortion,
* structural exhaustion.

### 4.10 Redefine Boundary

Use when the diagnosis itself is unstable because the current system boundary is misdrawn or analytically misleading.

Primary purpose:

* correct the unit of analysis before acting.

Typical uses:

* boundary-sensitive failure claims,
* subsystem failure misread as whole-system failure,
* externality omission distorting contour estimates,
* scale mismatch between symptoms and intervention target.

---

## 5. Decision Outputs

For practical use, intervention logic should produce a **decision output**, not only a narrative recommendation.

A decision output should include:

* **intervention class**,
* **target contour or mediator**,
* **intended time horizon**,
* **expected trade-off**,
* **confidence level**,
* and **stop / reassess condition**.

This allows movement from diagnosis to action without pretending the action is self-justifying.

### 5.1 Minimal Decision Output Template

* **Diagnosed condition:**
* **Intervention class:**
* **Target:** Survival / Reproduction / Evolution / Mediator / Boundary
* **Primary objective:**
* **Expected trade-off:**
* **Time horizon:**
* **Confidence level:** high / medium / low
* **Reassessment trigger:**
* **Notes:**

---

## 6. Intervention Selection Logic

The following sequence should be used when selecting an intervention.

### Step 1 — Declare the boundary

What system is being acted on, at what level?

### Step 2 — Declare the time horizon

What period of viability or adaptation is being protected or changed?

### Step 3 — Identify the diagnosed condition

Is the primary issue:

* distortion,
* breakdown,
* degradation,
* failure,
* collapse,
* mediator blockage,
* or boundary mismatch?

### Step 4 — Check compensation margin

Is the system still operating with real recovery reserve, or only through unsustainable compensation?

### Step 5 — Identify the primary contour or mediator problem

Which function is most critically under threat, over-dominant, blocked, or misallocated?

### Step 6 — Select intervention class

Choose the narrowest intervention class that fits the diagnosed condition.

### Step 7 — State the trade-off explicitly

What will likely be reduced, delayed, or constrained by this move?

### Step 8 — Define reassessment condition

When will the intervention be reviewed, stopped, or replaced?

---

## 7. Intervention Logic by Diagnosed Condition

### 7.1 Distortion Without Failure

When the system remains viable but clearly distorted, the default intervention class is usually:

* **Rebalance**
* or **Consolidate**
* or **Adapt**

Choice depends on which contour is dominant and whether the problem is primarily excess, neglect, or timing.

#### Survival-Dominant Distortion

Typical response:

* Rebalance toward Evolution or Reproduction,
* or Repair Mediator if controls or governance are over-constraining.

#### Reproduction-Dominant Distortion

Typical response:

* Contain spread,
* Consolidate gains,
* Rebalance toward Survival or Evolution.

#### Evolution-Dominant Distortion

Typical response:

* Stabilize,
* Consolidate,
* or Rebalance toward Survival.

### 7.2 Local Breakdown

When the problem is localized and compensable, the default intervention class is usually:

* **Stabilize**
* or **Contain**

followed later by:

* **Rebalance**,
* **Consolidate**,
* or **Repair Mediator**.

### 7.3 Systemic Degradation

When viability is still present but compensation cost is rising and margin is shrinking, the default intervention class is usually:

* **Stabilize** if continuity is threatened,
* **Repair Mediator** if allocation is blocked,
* **Adapt** if long-term misfit is central,
* or **Recover** if degradation has crossed into major functional loss.

### 7.4 Failure

When failure has already occurred, the default intervention class is usually:

* **Recover** if recovery within the current form is still plausible,
* or **Reconstitute** if the current form is no longer viable.

### 7.5 Boundary Mismatch

When the diagnosis itself depends on a poorly chosen system boundary, the default intervention class is:

* **Redefine Boundary**

before stronger action is taken.

### 7.6 Mediator-Induced Failure or Breakdown

When allocation, signaling, legitimacy, coordination, or governance is the central block, the default intervention class is:

* **Repair Mediator**

possibly combined with:

* Stabilize,
* Contain,
* or Recover,

if the mediator issue has already damaged contour function.

---

## 8. Time-Horizon Discipline in Interventions

An intervention should always be explicit about which time horizon it serves.

This is necessary because many interventions protect one horizon at the expense of another.

Examples:

* a short-term Stabilize move may delay needed Evolution,
* a long-term Adapt move may reduce short-term Survival margin,
* a Scale move may be justified medium-term but harmful long-term if consolidation is weak.

Interventions should therefore be labeled as primarily:

* short-term,
* medium-term,
* or long-term.

Mixed-horizon interventions should state their sequencing explicitly.

---

## 9. Trade-Off Declaration Rule

Every intervention has a cost.

The model therefore requires that intervention proposals declare at least one expected trade-off.

Typical trade-offs include:

* short-term speed for stability,
* scale for quality,
* exploration for continuity,
* flexibility for control,
* adaptation for immediate efficiency,
* local optimization for systemic coherence.

Interventions that do not declare trade-offs should be treated as under-specified.

---

## 10. Sequencing Logic

Some cases require more than one intervention class, but sequencing matters.

A useful default sequence is:

1. **Contain** acute spread if necessary
2. **Stabilize** continuity if under threat
3. **Repair Mediator** if allocation or coordination is blocked
4. **Recover** or **Reconstitute** if failure has already occurred
5. **Rebalance**, **Adapt**, or **Consolidate** once viable action space exists
6. **Scale** only when the resulting posture can tolerate extension

This sequence should not be applied mechanically. It is a default logic for avoiding premature scaling, premature adaptation, or cosmetic fixes over blocked allocation conditions.

---

## 11. Common Intervention Errors

### 11.1 Symptom-Only Intervention

Acting on visible symptoms without addressing the underlying contour or mediator condition.

### 11.2 Premature Rebalancing

Trying to rebalance a system that first requires stabilization or containment.

### 11.3 Premature Scaling

Extending a form that is still brittle, degraded, or weakly consolidated.

### 11.4 Mediator Blindness

Treating allocation symptoms as if they can be solved without repairing the structures that govern allocation.

### 11.5 Horizon Neglect

Applying short-term corrective logic to a long-horizon failure problem, or vice versa.

### 11.6 Boundary Error

Intervening at the wrong system level because the boundary was misdrawn.

### 11.7 Compensation Dependence

Designing intervention around keeping compensation mechanisms alive rather than restoring viable function.

---

## 12. Minimal Intervention Record Template

### Intervention Record

* **System boundary:**
* **Nesting level:**
* **Time horizon:**
* **Diagnosed condition:** distortion / breakdown / degradation / failure / collapse / mediator blockage / boundary mismatch
* **Primary contour or mediator involved:**
* **Compensation margin status:** intact / shrinking / exhausted
* **Selected intervention class:**
* **Expected trade-off:**
* **Reassessment trigger:**
* **Confidence level:** high / medium / low
* **Notes:**

---

## 13. Example Intervention Forms

### 13.1 Example A — Evolution Overheating

* Diagnosed condition: Evolution-dominant distortion
* Primary contour involved: Evolution
* Intervention class: Stabilize + Consolidate
* Time horizon: short-to-medium term
* Expected trade-off: slower experimentation in exchange for restored coherence
* Reassessment trigger: incident load and coordination friction drop below threshold

### 13.2 Example B — Brittle Growth

* Diagnosed condition: Reproduction-dominant degradation
* Primary contour involved: Reproduction
* Intervention class: Contain + Rebalance
* Time horizon: medium term
* Expected trade-off: slower expansion in exchange for restored Survival margin
* Reassessment trigger: quality and support stability improve

### 13.3 Example C — Governance Bottleneck

* Diagnosed condition: mediator-induced breakdown
* Primary contour involved: Mediator
* Intervention class: Repair Mediator
* Time horizon: medium term
* Expected trade-off: temporary decision ambiguity during governance redesign
* Reassessment trigger: approval latency and escalation volume decrease

### 13.4 Example D — Functional Identity Failure

* Diagnosed condition: failure
* Primary contour involved: mixed, with identity loss
* Intervention class: Recover or Reconstitute, depending on residual viability
* Time horizon: medium-to-long term
* Expected trade-off: loss of continuity in current form in exchange for restored viable identity
* Reassessment trigger: viability conditions re-established or recovery deemed no longer plausible

---

## 14. Relationship to Future Documents

This document defines intervention classes and selection logic, but not yet:

* detailed design patterns,
* domain-specific playbooks,
* or ranked intervention portfolios.

Those may later emerge through:

* distortion pattern work,
* applied cases,
* artifact standardization,
* and comparability rules.

At the current stage, the model should favor intervention discipline over premature procedural detail.

---

## 15. Working Summary

This document defines how the model moves from diagnosis to action.

Its central claim is:

**the right intervention depends on the diagnosed structure of the problem, not only on its visible symptom.**

For that reason, the model organizes intervention around:

* diagnosed condition,
* contour or mediator involvement,
* time horizon,
* compensation margin,
* and explicit trade-off declaration.

Used this way, intervention logic helps the model support not only explanation, but disciplined action selection.
