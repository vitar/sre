# Comparability Rules

## Purpose

This document defines when and how states, cases, periods, subsystems, or portfolios may be compared using the model.

Its purpose is to prevent invalid comparison while enabling disciplined comparative use as the model’s proxy-supported applications expand.

The model already supports:

* contour classification,
* proxy-supported state estimation,
* failure and breakdown assessment,
* intervention logic,
* and a standard application artifact suite.

What remains is to define the rules under which two or more applications can be treated as meaningfully comparable.

This document is a companion to:

* **Core Model Definition v0.2**
* **Classification Protocol**
* **Metrics and Proxies**
* **Failure and Breakdown Definition**
* **Intervention Logic**
* **Use Constraints and Discipline**
* **Application Artifact Suite**

---

## 1. Why Comparability Rules Are Needed

The model becomes far more useful when it can be used not only to describe a single case, but to compare:

* one system to another,
* one period to another,
* one team to another,
* one product to another,
* or one state estimate to another.

However, comparison is one of the easiest places for the model to be misused.

Without explicit comparability rules:

* different boundaries may be compared as if they were equivalent,
* short-term and long-term states may be conflated,
* different proxy sets may be treated as interchangeable,
* mediator effects may be ignored,
* and weakly aligned cases may produce false conclusions.

Comparability therefore requires stricter discipline than single-case diagnosis.

---

## 2. Core Principle

Two cases are comparable only to the degree that their analytical conditions are aligned.

Comparability is not a property of the cases alone. It is a property of the relationship between:

* declared boundaries,
* time horizons,
* classification logic,
* proxy logic,
* mediator conditions,
* and use purpose.

The model therefore rejects the idea that any two contour descriptions are automatically comparable just because they use the same vocabulary.

---

## 3. Comparison Types

The model supports four primary comparison types.

### 3.1 Cross-Case Comparison

Comparing two or more distinct systems, units, or cases at roughly the same time.

Examples:

* one team vs another,
* one product vs another,
* one organization vs another.

### 3.2 Time-Series Comparison

Comparing the same system across time.

Examples:

* before vs after intervention,
* quarter vs quarter,
* pre-failure vs post-recovery.

### 3.3 Cross-Level Comparison

Comparing cases at different nesting levels.

Examples:

* team vs organization,
* subsystem vs platform,
* institution vs state.

This is the most dangerous comparison class and requires the strongest caution.

### 3.4 Portfolio Comparison

Comparing multiple aligned units inside a declared portfolio.

Examples:

* multiple products,
* multiple delivery teams,
* multiple components,
* multiple institutions within a sector.

---

## 4. Minimum Alignment Conditions

No comparison should be treated as valid unless the following conditions are addressed explicitly.

### 4.1 Boundary Alignment

The compared cases must have sufficiently aligned system boundaries, or the differences must be stated clearly.

Questions:

* Are the compared systems the same type of object?
* Are excluded externalities similar enough to support comparison?
* Is one case only a subsystem while the other is a whole system?

### 4.2 Horizon Alignment

The compared cases must use the same or explicitly mapped time horizons.

Questions:

* Are both cases being interpreted short-term?
* Is one case long-term and the other short-term?
* Are horizon differences part of the comparison, or an unacknowledged mismatch?

### 4.3 Classification Alignment

The compared cases must use contour classification under compatible logic.

Questions:

* Was primary intent determined using the same rules?
* Were mediator-first objects treated consistently?
* Were secondary effects handled similarly?

### 4.4 Proxy Alignment

The compared cases must use proxy sets that are sufficiently aligned in meaning.

Questions:

* Are the same proxy classes being used?
* If not, are the proxy sets interpretable as equivalents?
* Are proxy quality and confidence levels similar enough to support comparison?

### 4.5 Mediator Alignment

Mediator conditions must be considered where they materially shape contour interpretation.

Questions:

* Are one case’s allocations strongly shaped by governance friction while the other’s are not?
* Are trust, legitimacy, coordination, or power structures so different that contour posture cannot be interpreted on the same basis?

### 4.6 Use-Purpose Alignment

The comparison must serve a clear purpose.

Examples:

* state comparison,
* trend detection,
* intervention effect assessment,
* portfolio ranking,
* structural contrast.

A comparison without clear purpose tends to drift into superficial analogy.

---

## 5. Comparison Validity Levels

The model should express comparison validity explicitly rather than treating all comparisons as equal.

### 5.1 Strongly Comparable

Use when:

* boundaries are closely aligned,
* horizons are aligned,
* classification logic is consistent,
* proxy logic is aligned,
* and mediator differences are known and manageable.

### 5.2 Conditionally Comparable

Use when:

* comparison is useful,
* but one or more alignment conditions differ enough to require caution.

Typical reasons:

* partially different boundaries,
* non-identical proxies,
* moderate mediator variation,
* or confidence asymmetry.

### 5.3 Weakly Comparable

Use when:

* core alignment conditions are materially different,
* proxy equivalence is partial or uncertain,
* mediator contexts differ strongly,
* or confidence asymmetry is high.

Weakly comparable cases may still be contrasted for exploratory learning, but should not support strong ranking or causal claims.

### 5.4 Not Comparable

Use when:

* boundary mismatch,
* horizon mismatch,
* proxy mismatch,
* or level mismatch is too strong for meaningful comparison.

The model prefers explicit “not comparable” judgments over misleading precision.

---

## 6. Comparison Object

The **comparison object** must be stated explicitly.

Possible comparison objects include:

* contour posture,
* distortion pattern,
* failure posture,
* intervention posture,
* mediator profile,
* state transition,
* or application artifact quality.

This matters because two cases may be comparable on one dimension and not on another.

Example:

* two systems may be comparable in failure posture,
* but not comparable in proxy-supported contour scoring.

---

## 7. Rules for Cross-Case Comparison

### 7.1 Compare Like with Like Where Possible

Prefer comparison of cases with similar function, scale, and analytical boundary.

### 7.2 State Boundary Differences Explicitly

If boundaries are not fully aligned, state what differs and why the comparison remains useful.

### 7.3 Do Not Hide Mediator Asymmetry

If one case is strongly shaped by governance, legitimacy, trust, or coordination distortion and the other is not, that asymmetry must be recorded.

### 7.4 Keep the Comparison Object Stable

Do not shift from comparing contour posture to comparing intervention outcome without stating the change in object.

---

## 8. Rules for Time-Series Comparison

### 8.1 Preserve Boundary Consistency Across Time

The same system should remain the same analytical object unless a boundary redefinition is itself part of the result.

### 8.2 Preserve Proxy Logic Across Time

Use the same proxy logic if possible. If the proxy set changes, the difference must be stated.

### 8.3 Preserve Classification Logic Across Time

Do not change contour interpretation rules silently between periods.

### 8.4 Distinguish State Change from Interpretation Change

A system may appear to have changed when only the observer’s boundary, horizon, or proxy logic changed.

The comparison must distinguish between:

* real system movement,
* and analytical reclassification.

---

## 9. Rules for Cross-Level Comparison

Cross-level comparison is allowed only with explicit caution.

### 9.1 Default Warning

A team, an organization, and a state may all be describable by the model, but that does not make them directly comparable.

### 9.2 Allowed Use

Cross-level comparison is most useful for:

* structural analogy,
* nested system analysis,
* mediator contrast,
* or contour inheritance patterns.

### 9.3 Disallowed Use

Cross-level comparison should not be used for:

* naïve ranking,
* false scoring equivalence,
* or claims of proportional contour balance across unmatched levels.

### 9.4 Required Label

Every cross-level comparison should be labeled explicitly as:

* **structural analogy**,
* **nested comparison**,
* or **non-equivalent illustrative comparison**.

---

## 10. Rules for Portfolio Comparison

Portfolio comparison is useful when multiple units share a common context, but it requires alignment discipline.

### 10.1 Unit Definition Rule

Portfolio units must be defined consistently.

### 10.2 Shared Template Rule

Portfolio comparisons should use the same artifact template set where possible.

### 10.3 Common Proxy Logic Rule

Proxy meaning should be aligned across units, or the differences should be documented.

### 10.4 Ranking Caution Rule

Portfolio ranking should be used carefully, especially when confidence, boundary cleanliness, or mediator asymmetry varies by unit.

A portfolio summary is often more trustworthy than a hard ranking.

---

## 11. Comparability and Confidence

Comparison confidence depends not only on the strength of each case, but on the alignment between them.

A comparison should therefore record:

* confidence in case A,
* confidence in case B,
* confidence in the comparison itself,
* residual uncertainty,
* proxy-confidence compatibility across compared cases,
* and drift risk in longer time-span comparisons.

High-confidence cases can still produce a low-confidence comparison if their analytical conditions are misaligned.

---

## 12. Common Comparison Errors

### 12.1 Boundary Substitution

Treating different system boundaries as equivalent.

### 12.2 Horizon Collapse

Comparing short-term state to long-term posture without adjustment.

### 12.3 Proxy Equivalence Assumption

Treating different metrics or proxies as if they mean the same thing automatically.

### 12.4 Mediator Blindness

Ignoring differences in governance, legitimacy, trust, coordination, or power that materially alter contour interpretation.

### 12.5 Cross-Level Flattening

Treating different nesting levels as if they were directly scoreable on the same basis.

### 12.6 Confidence Omission

Reporting a comparison without stating how strong the comparison really is.

### 12.7 Artifact Mismatch

Comparing cases that do not leave behind equivalent or sufficiently complete artifact records.

---

## 13. Minimum Comparison Record

### Comparison Record

* **Comparison type:** cross-case / time-series / cross-level / portfolio
* **Comparison object:**
* **Case A:**
* **Case B or comparison set:**
* **Boundary alignment:** strong / partial / weak
* **Horizon alignment:** strong / partial / weak
* **Classification alignment:** strong / partial / weak
* **Proxy alignment:** strong / partial / weak
* **Mediator comparability:** strong / partial / weak
* **Overall validity level:** strongly comparable / conditionally comparable / weakly comparable / not comparable
* **Comparison confidence:** high / medium / low
* **Residual uncertainty statement:**
* **Proxy-confidence compatibility:**
* **Drift risk notes (time-series/longitudinal use):**
* **Main limitations:**
* **Notes:**

---

## 14. Recommended Comparison Sequence

### Step 1 — Define the comparison purpose

Why are these cases being compared?

### Step 2 — Define the comparison object

What exactly is being compared?

### Step 3 — Check boundary alignment

Are the cases analytically similar enough?

### Step 4 — Check horizon alignment

Are the cases interpreted over the same time basis?

### Step 5 — Check classification alignment

Was the same contour logic used?

### Step 6 — Check proxy alignment

Are the supporting indicators sufficiently equivalent?

### Step 7 — Check mediator asymmetry

Are cross-cutting conditions different enough to distort comparison?

### Step 8 — Assign validity level

How comparable are these cases overall?

### Step 9 — State confidence and limitations

What should not be overclaimed from this comparison?

---

## 15. Relationship to the Artifact Suite

Comparability depends on artifacts being sufficiently complete and aligned.

In most cases, valid comparison should rely on at least:

* boundary declarations,
* classification records,
* proxy records,
* state estimates,
* and use discipline records.

For intervention comparison, it should also rely on:

* failure records,
* intervention records,
* and decision outputs.

This is why the model treats comparability as a late-stage discipline rather than a default capability.

---

## 16. Working Summary

This document defines when and how the model may be used for comparison without producing false equivalence.

Its central claim is:

**cases are comparable only to the extent that their boundaries, horizons, classification logic, proxy logic, mediator conditions, and analytical purpose are aligned.**

Used this way, comparison strengthens the model’s practical value. Used carelessly, it becomes one of the fastest ways to distort it.
