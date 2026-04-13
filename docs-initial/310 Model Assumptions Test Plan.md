# Model Assumptions Test Plan

## Purpose

This document defines the updated assumption-testing approach for the current documentation set of **Tri-Contour Dynamics of Limited Resource Allocation**.

Its purpose is to identify, rank, and test the assumptions most capable of:

* invalidating the model’s minimum stable structure,
* weakening its explanatory and operational usefulness,
* narrowing its valid scope,
* or exposing where the model now depends on additional layers such as mediators, shared-system logic, or inter-unit synchronization.

The goal is not to defend the model by default. The goal is to expose its weakest structural points early, test them in disciplined order, and distinguish clearly between:

* assumptions whose failure would require structural redesign,
* assumptions whose failure would force reinterpretation of the core,
* assumptions whose failure would weaken operational use,
* and assumptions whose failure would mainly narrow scope.

This document supersedes the earlier assumption plan by incorporating assumptions excavated from the newer model drafts, including mediator logic, artifact discipline, comparison logic, and the multi-unit layer. It should be read alongside the current documentation set, especially:

* **Core Model Definition v0.2.1**
* **Model Laws**
* **Inter-Unit Synchronization Logic**
* **Multi-Unit Failure and Breakdown**
* **Shared System State**
* **Use Constraints and Discipline**
* **Application Artifact Suite**
* **Comparability Rules**

This revision also reflects the latest assumption excavation artifacts.

---

## 1. Testing Philosophy

The model should be treated as a candidate explanatory structure, not as a protected framework.

Assumption testing therefore follows five principles.

1. **Test ontology before convenience.**
   The earliest tests should target assumptions that would invalidate the model’s core geometry or mediator treatment.

2. **Prefer adversarial cases over friendly confirmation.**
   A model that survives only cases already sympathetic to it is not reliable.

3. **Separate fatal failure from survivable revision.**
   Not every failed assumption kills the model. Some force reinterpretation, layering, or scope narrowing instead.

4. **Preserve revision discipline.**
   If an assumption fails, the response should be explicit: redesign, reinterpret, narrow, reject claim, or layer the model.

5. **Test the single-unit and multi-unit layers separately.**
   Some assumptions threaten the tri-contour core itself; others threaten only the shared-system, synchronization, or comparability layers.

---

## 2. What Counts as a Fatal Assumption

A **fatal assumption** is an assumption whose failure would invalidate the model’s minimum stable structure as currently defined.

At minimum, the current model depends on the existence of:

* bounded dynamic systems under meaningful resource limitation,
* three core contours,
* constrained allocation across those contours,
* meaningful state description through contour distribution,
* and cross-cutting factors being handled as mediators rather than as additional core contours.

An assumption is considered fatal when its failure removes one of these load-bearing elements or makes the model internally incoherent at the center.

---

## 3. Assumption Classes

The assumptions are grouped into four classes.

### 3.1 Foundational Assumptions

These determine whether the model’s core ontology and geometry are valid at all.

If a foundational assumption fails, the core model requires redesign or major reinterpretation.

### 3.2 Empirical Assumptions

These determine whether the model’s recurring pattern claims hold strongly enough to support explanation and law-like statements.

If an empirical assumption fails, the model may survive structurally but lose predictive strength.

### 3.3 Operational Assumptions

These determine whether the model can be applied reliably for classification, state estimation, comparison, and intervention.

If an operational assumption fails, the theory may survive as a lens, but working use becomes fragile.

### 3.4 Framing Assumptions

These determine the model’s valid scope, boundary conditions, and interpretive posture.

If a framing assumption fails, the model may still hold, but in narrower domains or with stronger caveats.

---

## 4. Updated Critical Assumption Set

The following assumptions are the current critical set excavated from the latest model drafts and supporting artifacts.

### 4.1 Foundational Critical Assumptions

| ID | Assumption                                                                                                                                  | Why it is foundational                                                                                              |
| -- | ------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- |
| F1 | Viable dynamic systems under meaningful resource limitation allocate across **three** core contours: Survival, Reproduction, and Evolution. | This is the model’s defining structural claim.                                                                      |
| F2 | All three contours remain analytically relevant even when one is hidden, displaced, blocked, or externally compensated.                     | This protects the tri-contour frame from apparent counterexamples created by displacement rather than true absence. |
| F3 | Allocation to one contour constrains allocation to the others over the relevant horizon.                                                    | This creates the model’s trade-off engine.                                                                          |
| F4 | The meaningful state of a system can be described through contour distribution.                                                             | This makes state estimation and state-based diagnosis possible at all.                                              |
| F5 | Complexity and nesting do not automatically require a different core geometry; they add interacting local allocations instead.              | This preserves the model’s cross-scale ambition.                                                                    |
| F6 | Major cross-cutting factors are better treated as mediators than as additional core contours.                                               | This protects the model from contour proliferation and preserves the minimal structure.                             |

### 4.2 Empirical Critical Assumptions

| ID | Assumption                                                                                                               | Why it is empirical                                                          |
| -- | ------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------- |
| E1 | Prolonged contour dominance tends to produce characteristic distortions.                                                 | This is a recurring pattern claim about real systems, not a pure definition. |
| E2 | Simultaneous sustainable maximization of all three contours does not occur under meaningful scarcity.                    | This is the strongest regularity claim behind the model’s tension logic.     |
| E3 | Deep system behavior can often be understood through contour allocation, mediator conditions, and feedback.              | This is the model’s broad explanatory claim.                                 |
| E4 | Viable continuity, including formal survival versus functional survival, is an appropriate anchor for failure diagnosis. | This is a strong empirical claim about how failure appears in real systems.  |

### 4.3 Operational Critical Assumptions

| ID | Assumption                                                                                                                            | Why it is operational                                                                         |
| -- | ------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| O1 | Primary functional intent can usually be identified well enough to classify objects.                                                  | Without this, contour assignment becomes unstable or rhetorical.                              |
| O2 | Mediator-first handling is sufficient for cross-cutting objects and avoids forced misclassification.                                  | This is how the model operationalizes governance, trust, power, legitimacy, and coordination. |
| O3 | Proxy-supported inference can credibly estimate contour posture when direct allocation is hidden.                                     | This supports serious use in opaque real systems.                                             |
| O4 | Boundary and time-horizon declaration can discipline interpretation rather than merely relativize it.                                 | This is what prevents variation in diagnosis from becoming arbitrary.                         |
| O5 | Comparability can be established conditionally through aligned artifacts, boundaries, horizons, proxy logic, and mediator conditions. | This enables comparison without false equivalence.                                            |
| O6 | Better discipline and artifact traceability materially improve reliability.                                                           | This is the model’s self-protective governance claim.                                         |

### 4.4 Framing Critical Assumptions

| ID | Assumption                                                                                                                          | Why it is framing-sensitive                                                                                    |
| -- | ----------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- |
| C1 | Relevant phenomena can be treated as bounded dynamic systems strongly enough for structured analysis.                               | This is the outer framing condition of the whole model.                                                        |
| C2 | Meaningful resource limitation and competing demands remain structurally important in the intended domains.                         | This protects the model from being applied where its tension logic is weak or artificial.                      |
| C3 | Multi-unit and shared-system cases can be treated as layered extensions of the same core rather than as wholly separate ontologies. | This matters now that the documentation includes synchronization, shared state, and multi-unit failure layers. |

---

## 5. Highest-Risk Assumptions

The following assumptions are currently the highest-risk assumptions for the model’s distinctiveness and integrity.

| Risk rank | Assumption                                  | Why it is high-risk                                                                                                                                |
| --------- | ------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1         | **F1 — Three-contour sufficiency**          | If three contours are not enough, the model’s defining architecture is undercut.                                                                   |
| 2         | **F6 — Mediator-not-contour treatment**     | If governance, power, legitimacy, meaning, coordination, or trust repeatedly behave like irreducible core contours, the minimal structure weakens. |
| 3         | **F4 — State by distribution**              | If contour distribution does not actually track system state well, the model loses diagnostic traction.                                            |
| 4         | **O1 — Primary-intent classification**      | If analysts cannot identify primary function reliably, operational use collapses into disagreement and rhetoric.                                   |
| 5         | **O3 — Proxy-supported inference**          | If proxy logic does not map reliably to real allocation, most serious applications become fragile.                                                 |
| 6         | **F5 — Complexity without changed core**    | If nested complexity repeatedly requires new core geometry, cross-scale universality weakens.                                                      |
| 7         | **E2 — No sustainable triple-maximization** | A durable counterexample would damage the model’s scarcity-driven tension logic.                                                                   |

Moderate-risk assumptions include E1, E4, O2, O4, O5, O6, and C3. Their failure would more likely narrow or revise the model than break it outright.

---

## 6. Fatal If False vs Survivable If False

### 6.1 Fatal If False

If any of the following fail cleanly, the model’s core would need major redesign rather than minor revision.

| ID | Assumption                                                                                            | Why failure is fatal                                                |
| -- | ----------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------- |
| F1 | Three contours are structurally sufficient as the core.                                               | Failure breaks the model’s defining architecture.                   |
| F2 | All viable dynamic systems under relevant conditions allocate across all three contours in some form. | Failure creates true missing-contour systems inside intended scope. |
| F3 | Allocation to one contour constrains the others over the relevant horizon.                            | Failure removes the model’s trade-off engine.                       |
| F4 | System state is meaningfully expressible through contour distribution.                                | Failure removes the model’s state-description engine.               |
| F6 | Cross-cutting factors can be treated as mediators without becoming extra core contours.               | Failure means the tri-contour core is structurally incomplete.      |

### 6.2 Survivable If False

If the following fail, the model could still survive, but as a narrower, weaker, or more heavily revised framework.

| ID | Assumption                                                                                    | Why failure is survivable                                                                              |
| -- | --------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ |
| F5 | Complexity increases interactions without changing the core.                                  | Failure may force scope limits or extra layers, but not necessarily total abandonment.                 |
| E1 | Dominance produces characteristic distortions.                                                | Failure weakens predictive pattern claims more than the core geometry.                                 |
| E2 | Triple-maximization is not sustainably possible under scarcity.                               | Failure would narrow the strength of tension claims, though some allocation logic may remain.          |
| E3 | Deep behavior is often understandable through contour allocation plus mediators and feedback. | Failure reduces explanatory reach more than the underlying structure.                                  |
| E4 | Failure is best anchored in viable continuity and functional identity.                        | Failure would require a different failure layer, not necessarily a new core.                           |
| O1 | Primary intent can usually be classified reliably.                                            | Failure makes application noisy, but the theory might still stand as a conceptual frame.               |
| O2 | Mediator-first handling works operationally.                                                  | Failure may require a richer protocol rather than a new ontology.                                      |
| O3 | Proxy-supported inference is usually good enough.                                             | Failure weakens real-world measurability more than the abstract model.                                 |
| O4 | Boundary and horizon declaration discipline interpretation.                                   | Failure makes use unstable, but does not necessarily disprove the core.                                |
| O5 | Conditional comparability can be achieved.                                                    | Failure mainly removes comparison as a valid use mode.                                                 |
| O6 | Better discipline improves reliability.                                                       | Failure undercuts governance of use, not the core structure.                                           |
| C3 | Multi-unit and shared-system layers can be treated as extensions of the same core.            | Failure would force a separate multi-unit ontology, but not necessarily destroy the single-unit model. |

---

## 7. Fatal Assumptions Ranked by Test Order

The ranking below now follows **diagnostic leverage** rather than only abstract dependency: earlier tests target the assumptions that would invalidate the most downstream structure with the least interpretive overhead.

| Test order | Fatal assumption                         | Why test here                                                                                                                                                                       |
| ---------- | ---------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1          | **F1 — Three-contour sufficiency**       | This is the shortest path to falsifying the model’s core architecture. If a fourth irreducible contour is needed inside intended scope, much else becomes secondary.                |
| 2          | **F6 — Mediator-not-contour treatment**  | This is the most likely structural breach mechanism, since the model now explicitly pushes governance, power, legitimacy, meaning, and coordination into mediator status.           |
| 3          | **F2 — Universal tri-contour relevance** | After sufficiency, test universality: are there viable in-scope systems missing one contour in a non-displaceable way?                                                              |
| 4          | **F3 — Constraint through allocation**   | If trade-offs do not reliably hold, the model’s core tension logic weakens sharply.                                                                                                 |
| 5          | **F4 — State by distribution**           | This should be tested after ontology and competition, because it depends on the contours being real and sufficient before asking whether distribution actually tracks system state. |

### Reading note

The first two tests target whether the model has the **right ontology**. The next two test whether that ontology is **universally present and tension-generating**. The last tests whether the ontology is **actually explanatory and diagnostically usable**.

---

## 8. Compact Reading of the Updated Test Order

The updated ranked order follows this dependency chain:

1. **Are three contours enough?**
2. **Can mediators remain mediators, rather than collapsing into extra contours?**
3. **Are all three contours genuinely present within intended scope, even when hidden or displaced?**
4. **Do they actually constrain one another under scarcity?**
5. **Can contour distribution describe system state meaningfully?**
6. **Can the model still function operationally through classification, proxies, and boundary discipline?**
7. **Do the broader empirical and framing claims still hold across intended domains and multi-unit extensions?**

---

## 9. Earliest Decisive Breakpoints

The following assumptions are the most likely to produce an immediate stop if they fail.

| Breakpoint assumption                                           | Why it is an early stop                                                                              |
| --------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| The three contours are sufficient.                              | Failure here forces structural redesign.                                                             |
| Mediators can remain mediators rather than extra core contours. | Failure here structurally reopens the ontology and may force a fourth contour or a layered redesign. |
| Allocation to one contour constrains the others.                | Failure here removes the competition and trade-off engine.                                           |
| System state can be described by contour allocation.            | Failure here removes much of the model’s operational usefulness.                                     |

---

## 10. Standard Test Method

Each assumption should be tested using the same evaluation format.

### 10.1 Claim

State the assumption in one sentence.

### 10.2 Failure Condition

Define what would count as failure. This should be strict enough to matter.

### 10.3 Strongest Counterexample Class

Identify the class of cases most likely to break the assumption.

### 10.4 Rescue Threshold

Define what revision, reinterpretation, narrowing, or layering would preserve the model short of total collapse.

### 10.5 Assessment Outcome

Each test should end with one of five outcomes:

* **Survives** — the assumption holds without meaningful revision.
* **Survives with narrowing** — the assumption holds only within reduced scope.
* **Survives with reinterpretation** — the assumption can remain, but requires clarified definition or reclassification.
* **Survives with layering** — the core can remain, but an additional explicit layer is required.
* **Fails** — the assumption does not hold and forces redesign or claim removal.

The added **layering** outcome is needed because the model now explicitly includes multi-unit, shared-state, and artifact-governed extensions.

---

## 11. Test Sequence by Assumption Class

### 11.1 Foundational Assumptions

These should be tested first.

#### A1. Three-contour sufficiency (F1)

The primary question is whether a fourth irreducible core function is repeatedly needed across domains and cannot be reduced to Survival, Reproduction, or Evolution without distortion.

Candidate challengers likely to test this assumption include:

* coordination,
* meaning,
* governance,
* power,
* extraction,
* cooperation,
* legitimacy,
* or synchronization.

The key decision is whether these are truly additional contours or whether they are conditions, mechanisms, or structures acting through the three contours.

#### A2. Mediator-not-contour treatment (F6)

The primary question is whether the model is correct to treat cross-cutting factors as mediators rather than as core contours.

This assumption is weakened if governance, legitimacy, meaning, power, trust, or coordination repeatedly behave like irreducible contour-level functions rather than cross-cutting modifiers.

This is now a first-rank test because the newer model drafts rely on mediator logic heavily.

#### A3. Universal tri-contour relevance (F2)

The primary question is whether viable in-scope systems can truly be missing one contour in a non-displaceable way, rather than merely hiding, delaying, or externalizing it.

The test should distinguish true absence from displacement, blockage, externalization, or compensation.

#### A4. Constraint through allocation (F3)

The primary question is whether the contours genuinely compete under limited resources over the relevant horizon.

This assumption is challenged by cases of apparent synergy, abundance, automation, and compounding systems in which investment appears to reinforce multiple contours at once.

The test should distinguish local synergy from deeper structural scarcity.

#### A5. State by distribution (F4)

The primary question is whether contour distribution actually tracks system state well enough to support diagnosis, comparison, and later action selection.

This assumption fails if contour allocation is too vague, too unstable, too indirect, or too weakly inferable to support meaningful state estimation.

#### A6. Complexity without changed core (F5)

The primary question is whether increasing complexity and nesting still preserve the same tri-contour core, or whether recurring classes of systems require a different fundamental geometry.

This assumption now matters more because the model has extended into shared-system and multi-unit layers.

### 11.2 Empirical Assumptions

These should be tested after the foundational assumptions survive.

#### B1. Dominance produces characteristic distortions (E1)

The primary question is whether prolonged contour dominance reliably produces recurring distortions rather than only domain-specific anomalies.

#### B2. No sustainable triple-maximization under scarcity (E2)

The primary question is whether durable counterexamples exist in which all three contours are sustainably maximized under meaningful scarcity.

#### B3. Deep behavior is often understandable through contour allocation plus mediators and feedback (E3)

The primary question is whether this explanatory frame has enough recurring traction across intended domains.

#### B4. Failure is best anchored in viable continuity and functional identity (E4)

The primary question is whether the current failure layer is empirically stronger than likely alternatives.

### 11.3 Operational Assumptions

These should be tested after the foundational and empirical layers survive.

#### C1. Primary intent can usually be classified (O1)

The primary question is whether analysts can identify primary function well enough for reliable contour assignment.

#### C2. Mediator-first handling works operationally (O2)

The primary question is whether mediator-first handling prevents distortion more often than it creates ambiguity.

#### C3. Proxy-supported inference is usually good enough (O3)

The primary question is whether proxies map credibly enough to real allocation for serious application.

#### C4. Boundary and horizon declarations discipline interpretation (O4)

The primary question is whether explicit framing improves reliability rather than merely multiplying analyst disagreement.

#### C5. Conditional comparability can be achieved (O5)

The primary question is whether aligned artifacts, boundaries, horizons, proxy logic, and mediator conditions are enough to support meaningful comparison.

#### C6. Better discipline and artifact traceability improve reliability (O6)

The primary question is whether the model’s self-governance layer genuinely reduces drift and misuse.

### 11.4 Framing Assumptions

These should be tested after the core and operational assumptions.

#### D1. Relevant phenomena can be treated as bounded dynamic systems (C1)

This is the outer framing test.

The model weakens where the unit of analysis cannot be meaningfully bounded, where dynamics are too diffuse, or where the phenomenon is too static or purely symbolic for structured use.

#### D2. Scarcity and competing demands are structurally important in intended domains (C2)

This is a scope gate.

The model survives strongly only where limitation and competing demand materially shape behavior.

#### D3. Multi-unit and shared-system layers can be treated as extensions of the same core (C3)

This is the newest framing test.

It should be challenged with cases where synchronization, shared state, or multi-unit failure appear to require a genuinely separate ontology rather than a layered extension of the tri-contour core.

---

## 12. Counterexample Strategy

Counterexamples should be selected deliberately rather than opportunistically.

The strongest tests should come from cases that appear likely to invalidate the model, not from cases already known to fit it.

Counterexamples should be drawn from at least six domains:

1. biological systems,
2. technical or computational systems,
3. organizational or economic systems,
4. social or political systems,
5. multi-unit work systems and role interactions,
6. shared-system or portfolio cases.

Where possible, assumption tests should use both:

* **friendly cases** the model is expected to explain, and
* **hostile cases** most likely to break it.

Special attention should be given to cases that challenge:

* mediator sufficiency,
* shared-state emergence,
* proxy credibility,
* and cross-unit viability logic.

---

## 13. Revision Rules

If an assumption fails, the model should not be defended rhetorically. The response must follow one of five revision actions.

### 13.1 Redesign

Used when a foundational assumption fails and the model’s center must change.

### 13.2 Narrow

Used when the model remains useful only in a more limited range of cases.

### 13.3 Reinterpret

Used when the model survives, but a concept requires sharper definition or reclassification.

### 13.4 Layer

Used when the core survives, but an additional explicit layer is required to handle recurring structures without distorting the core.

### 13.5 Reject Claim

Used when a derived claim is unsustainable even if the larger model remains intact.

These actions should be recorded explicitly to preserve conceptual discipline.

---

## 14. Testing Outputs

Each assumption test should produce a short structured record containing:

* assumption ID,
* claim,
* failure condition,
* counterexample class,
* evidence or reasoning,
* rescue threshold,
* outcome,
* resulting revision action if needed,
* and any affected documents.

This creates a test history that can later support maturity claims about the model.

---

## 15. What Success Looks Like

The purpose of this document is not to prove the model universally true.

A successful assumption-testing process would instead show that:

* the model’s minimum stable structure survives strong adversarial testing,
* its mediator treatment remains justified,
* its boundaries are clearer than before,
* its operational claims are better disciplined,
* its multi-unit extensions are either validated or explicitly narrowed,
* and its law statements remain grounded in tested assumptions rather than intuition alone.

---

## 16. Current Testing Posture

At the current stage, the model should be treated as:

* structurally strong enough to justify continued formalization,
* operationally promising but still exposed at classification and proxy layers,
* and increasingly dependent on whether mediator treatment and shared-system layering remain defensible.

The most dangerous open questions are now:

1. whether three contours remain sufficient,
2. whether mediators can remain mediators rather than extra contours,
3. whether contour distribution truly tracks state robustly enough for serious use,
4. and whether the newer multi-unit layers remain extensions of the same core rather than evidence of a second ontology.

These should be treated as the current highest-priority tests.

---

## 17. Immediate Follow-on Work

The next recommended work sequence is:

1. test the five fatal foundational assumptions first,
2. prioritize hostile cases against F1, F6, F2, F3, and F4,
3. test shared-system and multi-unit cases specifically against F5 and C3,
4. test classification and proxy credibility through repeated application records,
5. update laws only when assumption outcomes justify it,
6. and record revision actions explicitly rather than patching theory informally.

---

## 18. Working Summary

This document defines how the current model should be challenged before being further stabilized.

It treats **Tri-Contour Dynamics of Limited Resource Allocation** as a candidate minimum structure whose validity depends especially on whether:

* three contours are enough,
* mediators can remain mediators,
* all three contours remain relevant across intended scope,
* contour allocation genuinely generates trade-offs,
* contour distribution can describe system state,
* and the newer shared-system layers remain legitimate extensions of the same core.

If these assumptions survive, the model can proceed toward stronger laws, patterns, and integrations. If they fail, revision must happen at the right layer rather than through ad hoc explanation.
