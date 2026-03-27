# Metrics and Proxies

## Status

Draft v0.2

## Purpose

This document defines how the core model may be supported through observable indicators, proxy measures, and disciplined state description.

Its purpose is not to convert the model into false precision. Its purpose is to make application more rigorous, more comparable, and more operationally useful where direct observation of contour allocation is not possible.

This document is a companion to **Core Model Definition v0.2.1** and **Classification Protocol v0.2**. It assumes that:

* the three-contour core remains intact,
* contour classification should follow primary intent and time horizon,
* mediators may shape allocation and feedback,
* system state is often qualitative unless supported by explicit allocation proxies,
* serious use should leave behind structured artifacts,
* and comparison requires explicit validity checks rather than assumed equivalence.

This draft maintains the logic of the prior version while updating its documentation context after the introduction of the broader companion set. It should now be read alongside:

* **Failure and Breakdown Definition**
* **Intervention Logic**
* **Use Constraints and Discipline**
* **Application Artifact Suite**
* **Comparability Rules**
* **Model Assumptions Test Plan**

---

## 1. Why Metrics and Proxies Are Needed

The core model defines system state as the current distribution of resources across:

* **Survival**
* **Reproduction**
* **Evolution**

In many real systems, however, allocation is not directly visible.

A system may not expose its true resource commitments through explicit accounting. Time, budget, decision attention, political capital, risk tolerance, infrastructure load, and cognitive effort may all be partly hidden, mixed, or distributed across layers.

For this reason, the model relies on **proxy-supported inference** rather than direct measurement in most applications.

The role of metrics in this model is therefore limited and disciplined:

* to support interpretation,
* to improve repeatability,
* to compare states over time,
* to challenge intuitive classification where observable evidence points elsewhere,
* and to support later failure, intervention, and comparison judgments without replacing them.

Metrics are used to strengthen reasoning, not replace it.

---

## 2. Core Measurement Principle

The model does not require exact measurement of contours. It requires **credible inference about allocation**.

For practical use, the relevant question is usually not:

> What is the exact percentage of resources in each contour?

but rather:

> What observable indicators suggest that one contour is receiving more, less, or changing allocation relative to the others?

The protocol therefore prefers:

* directional estimates over false precision,
* relative comparison over absolute scoring,
* and explicit confidence statements over hidden assumptions.

This document should be read as support for disciplined estimation, not as a license for premature quantification.

---

## 3. Definitions

### 3.1 Metric

A **metric** is a direct or normalized observable measure used to describe some aspect of system behavior.

### 3.2 Proxy

A **proxy** is an observable indicator used to infer allocation or contour emphasis when direct measurement is unavailable or incomplete.

### 3.3 Proxy Set

A **proxy set** is a group of related indicators used together to support a contour interpretation.

### 3.4 State Estimate

A **state estimate** is a qualitative or semi-quantitative assessment of the current contour distribution supported by a stated proxy set.

### 3.5 Confidence Level

A **confidence level** expresses how strongly the available proxies support the current state estimate.

---

## 4. Measurement Posture

At the current maturity of the model, contour measurement should be treated as:

* **qualitative by default**,
* **proxy-supported where possible**,
* and **semi-quantitative only where proxy quality is strong and boundary conditions are explicit**.

The model is not yet mature enough to claim universal numeric thresholds for healthy balance, distortion, or system failure.

For that reason, metrics should be used mainly for:

* direction,
* comparison,
* trend detection,
* contradiction testing,
* and evidence-backed support for diagnosis.

Where stronger judgments are made, they should be linked to the relevant companion documents rather than inferred from metrics alone.

---

## 5. Proxy Classes by Contour

The same metric may mean different things in different systems. The following proxy classes are therefore indicative, not universal.

### 5.1 Survival Proxy Classes

Use these when assessing whether the system is allocating toward current viability, continuity, integrity, and resilience.

Typical proxy classes include:

* reliability and uptime,
* incident frequency,
* recovery capacity,
* maintenance effort,
* compliance and control effort,
* risk mitigation expenditure,
* continuity investment,
* reserve capacity,
* defensive response load.

Examples of usable indicators:

* downtime,
* incident count,
* MTTR,
* maintenance backlog,
* security hardening effort,
* support burden,
* resilience budget share.

### 5.2 Reproduction Proxy Classes

Use these when assessing whether the system is allocating toward scaling, copying, extension, or propagation of current form.

Typical proxy classes include:

* throughput growth,
* user or customer growth,
* rollout effort,
* expansion spending,
* replication effort,
* distribution reach,
* hiring for scale,
* commercialization effort,
* deployment volume.

Examples of usable indicators:

* number of new regions or markets,
* revenue growth,
* project volume,
* headcount growth for delivery,
* rollout count,
* transaction volume,
* copy or replication rate.

### 5.3 Evolution Proxy Classes

Use these when assessing whether the system is allocating toward adaptation, innovation, learning, redesign, or future-fit capability.

Typical proxy classes include:

* experimentation effort,
* R&D allocation,
* learning investment,
* redesign work,
* capability building,
* structural change activity,
* innovation portfolio share,
* change velocity,
* adaptation response effort.

Examples of usable indicators:

* experiment count,
* R&D spend,
* architecture redesign work,
* training and learning investment,
* percentage of work on new capabilities,
* number of major change initiatives,
* proportion of resources not tied to current operations.

---

## 6. Proxy Classes for Mediators

Because mediators shape contour behavior, they may need their own supporting indicators.

Typical mediator proxy classes include:

* governance latency,
* coordination overhead,
* decision bottlenecks,
* trust signals,
* legitimacy signals,
* rule density,
* approval layers,
* information asymmetry,
* incentive structure.

These do not directly replace contour proxies. They help explain why contour distributions appear as they do.

Examples:

* approval cycle time,
* number of cross-team dependencies,
* escalation volume,
* policy exception frequency,
* trust or engagement indicators,
* centralization of decision rights.

---

## 7. Proxy Use Rules

### 7.1 Multi-Proxy Rule

Do not infer contour allocation from a single proxy when a stronger proxy set is available.

For contested or high-impact claims, use at least two independent proxy classes and record how they converge or diverge.

Single indicators are often misleading.

Example:

* increased hiring may signal Reproduction,
* or it may reflect Survival stress,
* or Evolutionary capability building,
* depending on boundary and function.

### 7.2 Boundary Rule

Proxies are only meaningful within a declared system boundary.

The same indicator may support different contour interpretations depending on whether the focal system is:

* a team,
* an organization,
* a platform,
* a market,
* or a state.

### 7.3 Time Horizon Rule

A proxy should be interpreted against a stated time horizon.

Example:

* short-term maintenance load may look Survival-dominant,
* while the same work may support long-term Evolution if it is clearing technical debt to enable structural change.

### 7.4 Contradiction Rule

If proxies contradict intuitive classification, the contradiction must be stated explicitly rather than ignored.

### 7.5 Confidence Rule

Every proxy-supported estimate should include a confidence level and uncertainty statement:

* **high** — multiple aligned proxies with clear boundary and horizon,
* **medium** — some proxy support with moderate ambiguity,
* **low** — weak or conflicting proxies, major uncertainty, or unstable boundary.

Confidence statements should also note major observability gaps and whether the estimate is stable, provisional, or fragile.

### 7.6 Artifact Traceability Rule

Proxy-supported interpretation should leave behind enough structured record to support later review, intervention logic, and comparison.

In practice, this means proxy use should normally produce or update a **Proxy Record** and contribute to a **State Estimate** within the **Application Artifact Suite**.

### 7.7 Drift Check Rule

For repeated measurement or trend use, declare how proxy drift will be detected and handled.

Minimum drift handling should state:

* recalibration trigger,
* replacement criteria,
* and comparability impact when proxy sets change.

### 7.8 Comparison Caution Rule

Proxy-supported estimates should not be treated as comparable across cases or over time unless comparison conditions have been checked explicitly.

Detailed validity conditions for this belong to **Comparability Rules**, not to this document alone.

---

## 8. State Estimation Modes

The model supports three levels of state estimation.

### 8.1 Qualitative State Description

Used when proxy support is weak or the system is highly opaque.

Example:

* Survival dominant,
* Reproduction underfunded,
* Evolution constrained.

### 8.2 Relative State Comparison

Used when the main goal is comparison rather than absolute scoring.

Examples:

* this quarter is more Evolution-weighted than the last,
* team A is more Survival-loaded than team B,
* the organization shifted from Reproduction to Survival after an incident cycle.

### 8.3 Semi-Quantitative State Estimate

Used when proxy support is strong enough to justify approximate scoring.

Example format:

* Survival: medium-high
* Reproduction: high
* Evolution: low-medium

or, where justified:

* Survival: 0.6
* Reproduction: 0.8
* Evolution: 0.3

This mode should never imply false precision. The scoring logic must be documented.

---

## 9. Suggested Proxy Mapping Workflow

Use the following workflow when creating a proxy-supported estimate.

### Step 1 — Declare the analysis boundary

What system is being measured?

### Step 2 — Declare the time horizon

What period is the estimate intended to describe?

### Step 3 — Identify candidate proxy classes

Which observable indicators plausibly map to Survival, Reproduction, Evolution, and any relevant mediators?

### Step 4 — Screen for proxy quality

Which proxies are meaningful, available, and not too distorted by boundary mismatch?

### Step 5 — Group proxies into contour sets

Which indicators together suggest stronger Survival, Reproduction, or Evolution emphasis?

### Step 6 — Estimate contour posture

Produce a qualitative, relative, or semi-quantitative state estimate.

### Step 7 — Record confidence and ambiguity

State uncertainty explicitly.

### Step 8 — Reassess over time

Use the same proxy logic again later to detect movement, trend, or distortion.

### Step 9 — Connect forward only through proper artifacts

If the proxy-supported estimate is later used for failure judgment, intervention selection, or comparison, it should be passed through the relevant companion records rather than treated as sufficient on its own.

---

## 10. What Good Metrics Use Looks Like

Good metrics use in this model does not mean numerical sophistication. It means disciplined support for interpretation.

A good proxy-supported estimate should be:

* explicit about boundary,
* explicit about time horizon,
* explicit about what each proxy is standing in for,
* explicit about mediator effects where relevant,
* explicit about confidence and limitations,
* and structured enough to support downstream review.

Metrics are being used well when they help an analyst say:

* why a system appears Survival-heavy,
* why Reproduction has accelerated,
* why Evolution is constrained,
* why an intuitive reading is probably wrong,
* or why later failure/intervention claims should be treated cautiously.

---

## 11. Common Metric and Proxy Errors

### 11.1 False Precision

Assigning exact numeric values without sufficient measurement basis.

### 11.2 Proxy Collapse

Using one indicator as if it fully represents a contour.

### 11.3 Boundary Mismatch

Using proxies from one system level to describe another without adjustment.

### 11.4 Horizon Confusion

Treating short-term and long-term contour signals as if they were the same.

### 11.5 Mediator Blindness

Ignoring cross-cutting factors that distort how proxies should be read.

### 11.6 Rhetoric Capture

Using official labels, budgets, or declared intent as if they automatically reflect true allocation.

Declared innovation spending, for example, may function operationally as Survival preservation or symbolic legitimacy rather than genuine Evolution.

### 11.7 Comparison Drift

Treating proxy-supported estimates as directly comparable when alignment conditions have not been checked.

### 11.8 Artifact-Free Quantification

Creating numeric-looking state estimates without enough supporting record to reconstruct the inference path later.

---

## 12. Minimal Proxy Recording Template

The following template should be used in practical applications.

### Proxy Record

* **System boundary:**
* **Nesting level:**
* **Time horizon:**
* **Contour being estimated:** Survival / Reproduction / Evolution / Mediator
* **Proxy set:**
* **Observed indicators:**
* **Triangulation logic:**
* **Known proxy failure modes:**
* **Mediator instrumentation (if used):** type / channel / directional effect / strength / lag
* **Known limitations:**
* **Confidence level:** high / medium / low
* **Uncertainty notes and observability gaps:**
* **Estimate status:** stable / provisional / fragile
* **Drift-check cadence (for repeated use):**
* **Comparison basis:** baseline / prior period / peer system / target state
* **Notes:**

This template should be treated as part of the broader **Application Artifact Suite** rather than as a standalone note pattern.

---

## 13. Example Proxy Sets

### 13.1 Example A — Software Service

**System boundary:** production software service
**Time horizon:** current quarter

* Survival proxies: uptime, incidents, MTTR, maintenance effort
* Reproduction proxies: user growth, rollout count, throughput increase
* Evolution proxies: experiment count, architecture redesign share, R&D time
* Mediator proxies: approval latency, dependency count, change governance friction

### 13.2 Example B — Delivery Organization

**System boundary:** delivery unit
**Time horizon:** annual cycle

* Survival proxies: attrition risk, operational load, incident recovery, margin protection effort
* Reproduction proxies: client growth, project volume, hiring for delivery scale
* Evolution proxies: training investment, capability development, new practice incubation
* Mediator proxies: decision rights concentration, calibration overhead, governance friction

### 13.3 Example C — State-Level System

**System boundary:** state administrative system
**Time horizon:** five-year period

* Survival proxies: reserve capacity, infrastructure stability, internal security burden
* Reproduction proxies: territorial reach, demographic extension, production throughput
* Evolution proxies: education investment, institutional reform activity, adaptive policy capacity
* Mediator proxies: trust, legitimacy, coordination quality, corruption intensity, power centralization

---

## 14. Proxy Interpretation by Use Case

### 14.1 Diagnostic Use

Proxies help identify which contour is dominant, underfunded, or unstable.

### 14.2 Comparative Use

Proxies help compare states across teams, periods, products, or institutions only where comparability conditions are met.

### 14.3 Trend Use

Proxies help detect movement over time.

### 14.4 Contradiction Use

Proxies help challenge intuitive or rhetorical narratives.

### 14.5 Integration Use

Proxies help connect this model to other frameworks by grounding abstract interpretation in observable evidence.

### 14.6 Failure and Intervention Support Use

Proxies may support later failure judgments or intervention selection, but they should not replace the dedicated logic of those documents.

---

## 15. Relationship to Future Quantification

This document does not define fixed scoring formulas, universal thresholds, or required numeric indices.

Those may emerge later, but only after:

* repeated use across cases,
* stronger classification discipline,
* boundary handling maturity,
* better evidence about which proxies are consistently useful,
* and stronger comparability discipline.

At this stage, the model should resist premature mathematization.

The immediate priority is disciplined proxy-supported interpretation, not numerical elegance.

---

## 16. Relationship to Other Documents

This document should be used together with the other companion documents rather than as a complete application method by itself.

In particular:

* **Classification Protocol** defines how contour assignment should be made,
* **Failure and Breakdown Definition** defines how proxy-supported diagnosis should and should not escalate into failure claims,
* **Intervention Logic** defines how diagnosis connects to action,
* **Use Constraints and Discipline** defines the minimum rules that make proxy use trustworthy,
* **Application Artifact Suite** defines how proxy records fit into repeatable application,
* and **Comparability Rules** defines when proxy-supported estimates can be validly compared across cases or over time.

---

## 17. Working Summary

This document defines how metrics and proxies should support the model without distorting it.

Its central claim is practical:

**system state is usually not directly measurable, but it can often be estimated credibly through explicit proxy sets, clear boundaries, stated time horizons, disciplined confidence handling, and traceable analytical records.**

Used this way, metrics strengthen the model’s operational usefulness while preserving its structural humility.
