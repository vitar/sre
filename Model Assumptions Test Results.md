# Model Assumptions Test Results

## Status

Executed v0.1 (2026-03-27)

## Scope and Method

This document executes the assumptions test sequence defined in **Model Assumptions Test Plan** against the current **Core Model Definition (Draft v0.1)**.

Execution method used the plan’s standard template for each assumption:

- claim,
- failure condition,
- strongest counterexample class,
- evidence/reasoning,
- rescue threshold,
- outcome,
- revision action.

This is a first-pass analytical execution (reasoned adversarial testing), not an empirical benchmark study.

---

## Executive Outcome

- Structural layer: **survives with reinterpretation/narrowing**.
- Operational layer: **survives with narrowing**.
- Framing layer: **survives with narrowing**.
- Overall result: **model is not falsified at the center, but scope and definitions must be tightened before law-like claims**.

Most critical pressure points remain:

1. proving contour sufficiency without category creep,
2. preserving contour distinctness in high-complexity social systems,
3. operationalizing “allocation” with observable proxies.

---

## Assumption Records

### A1 — Three contours are sufficient

- **Class:** Structural
- **Claim:** Survival, Reproduction, and Evolution are sufficient as a minimum irreducible decomposition.
- **Failure condition:** A fourth cross-domain contour is repeatedly required and cannot be reduced to mechanism/constraint/expression within the three.
- **Strongest counterexample class:** Governance/power/coordination-heavy systems (states, platforms, empires) where control appears primary.
- **Evidence/reasoning:**
  - In biological systems, candidate fourths (coordination/signaling) are usually mechanisms supporting viability, propagation, or adaptation.
  - In computational systems, orchestration/control similarly behaves as architecture enabling reliability, scaling, or change.
  - In organizations/politics, power and governance can look irreducible; however, most effects still cash out as preserving regime viability (Survival), extending institutional form (Reproduction), or redesigning capability/order (Evolution).
  - Stress remains: in social domains, “meaning/legitimacy” can appear constitutive rather than instrumental.
- **Rescue threshold:** Keep three contours as core only if governance/power/meaning are explicitly modeled as **cross-cutting mediators** rather than missing contours.
- **Outcome:** **Survives with reinterpretation**.
- **Revision action:** **Reinterpret** (add mediator layer in future formalization).

### A2 — Contours are analytically distinct

- **Class:** Structural
- **Claim:** The three contours are structurally real and separable enough for analysis.
- **Failure condition:** Persistent inability to classify allocations by primary contour without arbitrary judgment.
- **Strongest counterexample class:** Adaptive continuity efforts (e.g., reliability engineering, immune responses, institutional reform) where preservation and adaptation blend.
- **Evidence/reasoning:**
  - Distinctness is workable at functional intent level (“preserve current viability” vs “replicate current form” vs “change form/capability”).
  - Boundary blur is common in mixed interventions (e.g., SRE automation both stabilizes and adapts).
  - Distinctness weakens when time horizon is ignored: short-term Survival actions can be long-term Evolution enablers.
- **Rescue threshold:** Enforce a **primary-intent + time-horizon** tagging rule; allow secondary contour effects.
- **Outcome:** **Survives with reinterpretation**.
- **Revision action:** **Reinterpret** (classification protocol needed).

### A3 — Allocation to one contour constrains the others

- **Class:** Structural
- **Claim:** Under limited resources, contour investment is constrained and competitive.
- **Failure condition:** Durable broad class of systems where all contours can be increased without meaningful trade-offs.
- **Strongest counterexample class:** Automation/AI leverage and high-abundance growth phases.
- **Evidence/reasoning:**
  - Local synergies exist (tooling can improve reliability, scaling, and adaptation together).
  - At larger horizons, bottlenecks recur (attention, governance bandwidth, compute/capital, complexity load), restoring trade-offs.
  - Historical scaling systems show delayed, not eliminated, constraint.
- **Rescue threshold:** Trade-off claim may be softened to “constraints re-emerge over relevant planning horizons.”
- **Outcome:** **Survives**.
- **Revision action:** none.

### A4 — Cannot sustainably maximize all three simultaneously

- **Class:** Structural
- **Claim:** Sustainable joint maximization of Survival, Reproduction, and Evolution is not achievable.
- **Failure condition:** Demonstrated long-run class of systems maintaining near-maximal levels of all three without oscillation or deferred costs.
- **Strongest counterexample class:** Dominant technology firms or empires during prolonged expansion windows.
- **Evidence/reasoning:**
  - Apparent simultaneous maximization generally reflects phase effects and externalized costs.
  - Over time, expansion introduces fragility; heavy adaptation introduces coordination loss; heavy control slows novelty.
  - Long-run trajectories show cycling and rebalancing rather than stable triple maxima.
- **Rescue threshold:** Define “sustainable” explicitly (multi-cycle horizon, not single expansion era).
- **Outcome:** **Survives**.
- **Revision action:** none.

### B1 — System state describable by contour allocation

- **Class:** Operational
- **Claim:** Current contour allocation can meaningfully describe system state.
- **Failure condition:** Allocation cannot be observed or estimated reliably enough to compare states or inform diagnosis.
- **Strongest counterexample class:** High-symbolic social systems and opaque institutions with hard-to-measure resource flows.
- **Evidence/reasoning:**
  - Qualitative state description is often useful (e.g., “Survival-dominant bureaucracy,” “Reproduction-dominant growth startup”).
  - Precision is weak without standardized proxies, especially for non-financial resources (attention, legitimacy, trust).
  - Inter-rater variance likely high unless coding rules are explicit.
- **Rescue threshold:** Require a proxy schema (budget, headcount, decision throughput, risk posture, innovation share) plus uncertainty bands.
- **Outcome:** **Survives with narrowing**.
- **Revision action:** **Narrow** (operational use limited to proxy-supported contexts).

### B2 — Scarcity and competing demands are structurally important

- **Class:** Operational
- **Claim:** Scarcity/trade-offs are common enough to make the model broadly useful.
- **Failure condition:** Intended domains are predominantly non-scarce or trade-off-light.
- **Strongest counterexample class:** Digital goods with near-zero marginal cost and heavily subsidized environments.
- **Evidence/reasoning:**
  - Even with cheap replication, strategic constraints persist (talent, trust, coordination, regulation, latency, energy).
  - Scarcity shifts form rather than disappearing.
  - Some micro-domains may be temporarily abundance-like.
- **Rescue threshold:** Domain note that scarcity can be second-order (governance/attention) rather than purely material.
- **Outcome:** **Survives with narrowing**.
- **Revision action:** **Narrow** (declare low-scarcity edge cases explicitly).

### C1 — Continuation depends materially on allocation under environment

- **Class:** Framing
- **Claim:** System continuation is materially shaped by allocation decisions under environmental pressure.
- **Failure condition:** Continuation is largely explained without resource-allocation dynamics.
- **Strongest counterexample class:** Norm-locked institutions and identity-driven movements where symbolic legitimacy seems primary.
- **Evidence/reasoning:**
  - Symbolic structures matter, but they are usually maintained through resource-bearing channels (education, media, enforcement, organizational labor).
  - Environmental shocks often reveal latent allocation dependencies.
  - Still, causal distance can be long and mediated.
- **Rescue threshold:** Treat symbolic/institutional factors as mediating layers that modulate allocation effects.
- **Outcome:** **Survives with reinterpretation**.
- **Revision action:** **Reinterpret**.

### C2 — Relevant phenomena can be treated as bounded dynamic systems

- **Class:** Framing
- **Claim:** Target phenomena can be bounded sufficiently for system analysis.
- **Failure condition:** Boundaries are too unstable/contested to support repeatable inference.
- **Strongest counterexample class:** Open network publics, transnational information ecosystems, diffuse cultures.
- **Evidence/reasoning:**
  - Practical boundaries are often possible at analysis-specific slices (organization, platform segment, policy regime).
  - Some macro phenomena remain weakly bounded and produce model drift.
  - Boundary choice strongly affects contour interpretation.
- **Rescue threshold:** Require explicit boundary declaration, nesting level, and excluded externalities per analysis.
- **Outcome:** **Survives with narrowing**.
- **Revision action:** **Narrow**.

---

## Cross-Domain Counterexample Coverage

Adversarial reasoning included the four required classes:

1. **Biological:** immune regulation, reproductive trade-offs, adaptation windows.
2. **Technical/computational:** reliability engineering, platform scaling, automation synergies.
3. **Organizational/economic:** startup scale dynamics, bureaucratic lock-in, quality-vs-growth conflict.
4. **Social/political:** legitimacy regimes, governance power concentration, diffuse network publics.

---

## Immediate Required Revisions

1. **Add an explicit mediator layer** (governance, coordination, meaning, power) to prevent contour sufficiency from being misread as category denial.
2. **Define contour classification protocol** using primary intent and time horizon.
3. **Specify allocation proxy schema** for operational state description.
4. **Require boundary declaration template** for each application.

These are not center-collapse revisions; they are required for discipline and falsifiability.

---

## Updated Posture After Execution

After executing the current test plan, the model is best described as:

- **structurally retained**,
- **operationally conditional**,
- **scope-sensitive at framing boundaries**.

The model may proceed to metrics and law-candidate work only if the four required revisions above are completed first.
