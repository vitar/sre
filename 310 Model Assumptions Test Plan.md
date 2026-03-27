# Model Assumptions Test Plan

## Status

Draft v0.1

## Purpose

This document defines the assumption-testing approach for the core model. Its purpose is to identify, rank, and test the assumptions most capable of invalidating the model’s minimum stable structure, reducing its scope, or weakening its practical usefulness.

The goal is not to defend the model by default. The goal is to expose its weakest structural points early, test them in a disciplined order, and distinguish between:

* assumptions whose failure would require structural redesign,
* assumptions whose failure would reduce operational usefulness,
* and assumptions whose failure would narrow the model’s valid scope.

This document is a companion to **Core Model Definition**. It does not redefine the model. It defines how the model should be challenged.

---

## 1. Testing Philosophy

The model should be treated as a candidate explanatory structure, not as a protected framework.

Assumption testing therefore follows four principles:

1. **Test the center before the edges.**
   The earliest tests should target assumptions that can invalidate the minimum stable structure.

2. **Prefer adversarial cases over easy confirmations.**
   A model that survives only friendly examples is not reliable.

3. **Separate structural failure from scope reduction.**
   Not every failed assumption kills the model. Some only reduce where or how strongly it applies.

4. **Preserve revision discipline.**
   If an assumption fails, the response should be explicit: redesign, narrow, reinterpret, or reject.

---

## 2. What Counts as a Fatal Assumption

A **fatal assumption** is an assumption whose failure would invalidate the model’s minimum stable structure as defined in the core document.

At minimum, the core model depends on the existence of:

* bounded dynamic systems,
* limited resources,
* three competing contours,
* constrained allocation,
* and system state described through contour distribution.

An assumption is considered fatal when its failure removes one of these load-bearing elements or makes the model internally incoherent.

---

## 3. Assumption Classes

The assumptions are grouped into three classes.

### 3.1 Structural Assumptions

These determine whether the model’s core architecture is valid at all.

If a structural assumption fails, the model requires redesign or abandonment at the center.

### 3.2 Operational Assumptions

These determine whether the model can be used meaningfully for diagnosis, comparison, or decision support.

If an operational assumption fails, the model may survive as a lens, but becomes weak as a working tool.

### 3.3 Framing Assumptions

These determine the model’s valid scope and causal framing.

If a framing assumption fails, the model may still hold in narrower domains, but its explanatory range must be reduced.

---

## 4. Fatal Assumptions Ranked by Test Order

The ranking below follows one principle: assumptions are tested in the order most likely to invalidate the model’s minimum stable structure quickly.

### 4.1 Ranked List

| Rank | Assumption                                                                                                     | Why it should be tested in this order                                                                                                                                                                                |
| ---- | -------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1    | The three contours — Survival, Reproduction, Evolution — are sufficient as the core decomposition.             | This is the fastest structural kill-test because the model explicitly presents these three as its minimum stable structure. If a fourth irreducible contour is required, the model must be redesigned at the center. |
| 2    | The three contours are structurally real and analytically distinct, not merely naming conventions.             | Even if the number three survives, the model fails as a framework if the contours do not separate cleanly enough to function as real analytic categories.                                                            |
| 3    | Allocation to one contour constrains the others.                                                               | This tests whether the contours actually compete under scarcity. If they do not constrain one another, the model’s trade-off logic collapses.                                                                        |
| 4    | A system cannot sustainably maximize all three contours simultaneously.                                        | This tests the model’s claim that persistent tension is structural. If simultaneous sustainable maximization is possible, the tension logic is badly undermined.                                                     |
| 5    | System state can be meaningfully described by the current distribution of resources across the three contours. | Once the contour structure and competition logic survive, this becomes the next decisive test because it determines whether the model can actually describe and compare systems operationally.                       |
| 6    | Scarcity and competing demands are common enough to make trade-offs structurally important.                    | This is a scope gate. If scarcity and trade-offs are not central in intended domains, the model loses much of its applicable range.                                                                                  |
| 7    | System continuation depends materially on resource allocation under environmental conditions.                  | This is broad and load-bearing, but less discriminating than the contour tests. Once contour logic is examined, this tests whether the model’s wider causal framing still holds.                                     |
| 8    | Relevant phenomena can be treated as bounded dynamic systems.                                                  | This is fundamental, but often less likely to be the first point of failure in intended domains. It is best tested after the more specific structural assumptions.                                                   |

---

## 5. Compact Reading of the Test Order

The ranked order follows this dependency chain:

1. **Do the three contours exist as enough categories?**
2. **Are they analytically distinct?**
3. **Do they actually compete under scarcity?**
4. **Does that competition create persistent tension?**
5. **Can contour allocation describe system state?**
6. **Is scarcity central enough for this to matter?**
7. **Does system continuation depend on allocation under environmental pressure?**
8. **Do the intended phenomena fit the system framing at all?**

---

## 6. Earliest Decisive Breakpoints

The following assumptions are the most likely to produce an immediate stop if they fail.

| Breakpoint assumption                                | Why it is an early stop                                            |
| ---------------------------------------------------- | ------------------------------------------------------------------ |
| The three contours are sufficient.                   | Failure here forces structural redesign.                           |
| The three contours are distinct.                     | Failure here removes the model’s main analytic categories.         |
| Allocation to one contour constrains the others.     | Failure here removes the model’s competition and trade-off engine. |
| System state can be described by contour allocation. | Failure here removes much of the model’s operational usefulness.   |

---

## 7. Standard Test Method

Each assumption should be tested using the same evaluation format.

### 7.1 Claim

State the assumption in one sentence.

### 7.2 Failure Condition

Define what would count as failure. This should be strict enough to matter.

### 7.3 Strongest Counterexample Class

Identify the class of cases most likely to break the assumption.

### 7.4 Rescue Threshold

Define what revision, reinterpretation, or narrowing would preserve the model short of total collapse.

### 7.5 Assessment Outcome

Each test should end with one of four outcomes:

* **Survives** — the assumption holds without meaningful revision.
* **Survives with narrowing** — the assumption holds only within a reduced scope.
* **Survives with reinterpretation** — the assumption can remain, but requires a clarified definition or reframing.
* **Fails** — the assumption does not hold and forces redesign or removal of the claim.

---

## 8. Test Sequence by Assumption Class

### 8.1 Structural Assumptions

These should be tested first.

#### A1. The three contours are sufficient.

The primary question is whether a fourth irreducible core function is repeatedly needed across domains and cannot be reduced to Survival, Reproduction, or Evolution without distortion.

Candidate challengers likely to test this assumption include:

* coordination,
* meaning,
* governance,
* power,
* extraction,
* or cooperation.

The key decision is whether these are truly additional contours or whether they are mechanisms, conditions, or structures acting through the three contours.

#### A2. The three contours are analytically distinct.

The primary question is whether the contours can be separated consistently enough to support analysis.

This assumption is weakened if:

* Survival absorbs all continuity functions and makes Reproduction redundant,
* Evolution collapses into adaptive Survival,
* or Reproduction cannot be distinguished from continuity at scale.

The test should ask whether resource allocation can be classified meaningfully by primary contour without collapsing into interpretive ambiguity.

#### A3. Allocation to one contour constrains the others.

The primary question is whether the contours genuinely compete under limited resources.

This assumption is challenged by cases of apparent synergy, abundance, automation, or compounding systems in which investment appears to reinforce multiple contours at once.

The test should distinguish local synergies from deeper structural scarcity.

#### A4. The three contours cannot be sustainably maximized simultaneously.

The key word is **sustainably**. Short-term growth windows, temporary abundance, or local compounding do not invalidate the assumption unless they remain stable under longer-term constraints.

The model survives if simultaneous improvement exists only within temporary windows before trade-offs reappear.

---

### 8.2 Operational Assumptions

These should be tested after the structural assumptions survive.

#### B1. System state can be described by contour allocation.

The primary question is whether the current distribution of resources across Survival, Reproduction, and Evolution provides a meaningful description of the system’s present condition.

This assumption fails if contour allocation is too vague, too unstable, or too weakly observable to support comparison or diagnosis.

The key issue is whether allocation can function as a useful explanatory state description rather than a loose metaphor.

#### B2. Scarcity and competing demands are structurally important.

This is a domain-validity test.

The model survives strongly only where scarcity, limitation, or competing demands materially shape system behavior. If intended domains contain too many cases where trade-offs are negligible or irrelevant, the model’s practical range shrinks.

---

### 8.3 Framing Assumptions

These should be tested after the core and operational assumptions.

#### C1. System continuation depends materially on resource allocation under environmental conditions.

This assumption asks whether the model’s broad causal framing is valid.

It should be challenged with cases where continuation appears to depend more on symbolic structures, norms, institutional inertia, or endogenous dynamics than on direct allocation logic.

The question is whether such phenomena can still be treated as resource-mediated at a deeper level.

#### C2. Relevant phenomena can be treated as bounded dynamic systems.

This is the outer framing test.

The model weakens where the unit of analysis cannot be meaningfully bounded, where dynamics are too diffuse, or where the observed phenomenon is static, symbolic, or purely descriptive rather than systemic.

The key question is not whether boundaries are perfect, but whether they are useful enough for analysis.

---

## 9. Counterexample Strategy

Counterexamples should be selected deliberately rather than opportunistically.

The strongest tests should come from cases that appear likely to invalidate the model, not from cases already known to fit it.

Counterexamples should be drawn from at least four domains:

1. biological systems,
2. technical or computational systems,
3. organizational or economic systems,
4. social or political systems.

Where possible, assumption tests should use both:

* **friendly cases** that the model is expected to explain, and
* **hostile cases** that are most likely to break it.

---

## 10. Revision Rules

If an assumption fails, the model should not be defended rhetorically. The response must follow one of four revision actions:

### 10.1 Redesign

Used when a structural assumption fails and the model’s center must change.

### 10.2 Narrow

Used when the model remains useful only in a more limited range of cases.

### 10.3 Reinterpret

Used when the model survives, but a concept requires sharper definition or reclassification.

### 10.4 Reject Claim

Used when a derived claim is unsustainable even if the larger model remains intact.

These actions should be recorded explicitly to preserve conceptual discipline.

---

## 11. Testing Outputs

Each assumption test should produce a short structured record containing:

* assumption ID,
* claim,
* failure condition,
* counterexample class,
* evidence or reasoning,
* rescue threshold,
* outcome,
* and resulting revision action if needed.

This creates a test history that can later support maturity claims about the model.

---

## 12. What Success Looks Like

The purpose of this document is not to prove the model universally true.

A successful assumption-testing process would instead show that:

* the model’s minimum stable structure survives strong adversarial testing,
* its boundaries are clearer than before,
* its operational claims are better disciplined,
* and its future law statements are grounded in tested assumptions rather than intuition alone.

---

## 13. Current Testing Posture

At the current stage, the model should be treated as:

* structurally promising,
* qualitatively useful,
* and still vulnerable at the contour level.

The most dangerous open question remains whether Survival, Reproduction, and Evolution are truly sufficient as the minimum decomposition across intended domains.

That is the first and most important test.

---

## 14. Immediate Follow-on Work

The next recommended work sequence is:

1. test the four structural assumptions first,
2. record hostile counterexamples,
3. define rescue thresholds before testing,
4. revise the core model only when test outcomes require it,
5. and postpone law statements until the structural assumption layer is stable.

---

## 15. Working Summary

This document defines how the model should be challenged before being further formalized.

It treats the model as a candidate minimum structure whose validity depends on whether:

* three contours are enough,
* those contours are distinct,
* they genuinely compete under scarcity,
* and contour allocation can describe system state.

If those assumptions survive, the model can proceed toward stronger laws, metrics, and integrations. If they fail, revision must happen at the right layer rather than through ad hoc explanation.
