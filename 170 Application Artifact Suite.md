# Application Artifact Suite

## Purpose

This document defines the standard artifact suite for applying the model in a repeatable, reviewable, and comparable way.

Its purpose is not to add new theory. Its purpose is to specify the minimal set of records, templates, and outputs that should accompany real use of the model.

The model already defines:

* core contours,
* classification rules,
* proxy-supported state estimation,
* failure and breakdown assessment,
* intervention logic,
* and use discipline.

What remains is to define the artifact set that makes those elements operational as a coherent practice rather than a collection of separate documents.

This document is a companion to:

* **Core Model Definition v0.2**
* **Classification Protocol**
* **Metrics and Proxies**
* **Failure and Breakdown Definition**
* **Intervention Logic**
* **Use Constraints and Discipline**
* **Model Assumptions Test Plan**

---

## 1. Why an Artifact Suite Is Needed

A model may be conceptually sound but still hard to apply consistently if each user improvises the structure of analysis.

Without a defined artifact suite:

* boundary declarations may be omitted,
* classifications may be informal and non-repeatable,
* proxy logic may remain implicit,
* failure claims may not be reviewable,
* intervention recommendations may not be traceable back to diagnosis,
* and comparisons across cases may become invalid.

A standard artifact suite solves this by creating a minimal application grammar.

The suite does not eliminate judgment. It makes judgment visible.

---

## 2. Core Principle

Every serious use of the model should leave behind enough structured evidence that another analyst can understand:

* what was analyzed,
* how it was classified,
* what evidence supported the state estimate,
* what failure or breakdown claim was made,
* what intervention logic followed,
* and what assumptions or limitations still remain.

The artifact suite exists to make that chain explicit.

---

## 3. Artifact Classes

The application suite is organized into five classes of artifacts:

1. **Framing artifacts**
2. **Analytical artifacts**
3. **Decision artifacts**
4. **Validation artifacts**
5. **Comparative artifacts**

Not every use case requires every artifact, but serious diagnostic or intervention use should produce artifacts from at least the first three classes.

---

## 4. Framing Artifacts

Framing artifacts define the conditions under which all later analysis should be interpreted.

### 4.1 Boundary Declaration

Defines:

* focal system,
* nesting level,
* main excluded externalities,
* and intended analytical boundary.

This is a required artifact for all serious applications.

### 4.2 Horizon Declaration

Defines:

* short-term,
* medium-term,
* and/or long-term time horizon relevant to the case.

A single case may include more than one horizon, but at least one declared horizon is required.

### 4.3 Use Mode Declaration

Defines the intended use mode:

* exploratory,
* diagnostic,
* comparative,
* intervention,
* or formalization.

This prevents weak exploratory outputs from being treated as strong intervention-grade conclusions.

---

## 5. Analytical Artifacts

Analytical artifacts capture how the system was interpreted.

### 5.1 Classification Record

Captures the classification of a defined object using the rules in **Classification Protocol**.

Minimum fields:

* object,
* system boundary,
* nesting level,
* time horizon,
* mediator-first yes/no,
* primary contour,
* rationale trace for primary assignment,
* secondary effects (tagged),
* proxy support,
* linked supporting artifacts,
* confidence,
* notes.

### 5.2 Proxy Record

Captures the proxy set used to support contour or mediator interpretation.

Minimum fields:

* system boundary,
* nesting level,
* time horizon,
* contour being estimated,
* proxy set,
* observed indicators,
* triangulation logic,
* known proxy failure modes,
* mediator fields where relevant (type, channel, direction, strength, lag),
* known limitations,
* confidence band,
* uncertainty notes,
* drift-check cadence,
* comparison basis,
* notes.

### 5.3 State Estimate

Captures the interpreted contour posture of the system.

The state estimate may be:

* qualitative,
* relative,
* or semi-quantitative.

Minimum fields:

* boundary,
* time horizon,
* estimated contour posture,
* mediator notes,
* confidence band,
* evidence basis,
* uncertainty notes,
* estimate status: stable / provisional / fragile.

### 5.4 Distortion Assessment

Captures whether the diagnosed state reflects:

* relative balance,
* contour dominance,
* contour neglect,
* chronic tension,
* or unstable transition.

Minimum fields:

* diagnosed distortion type,
* dominant contour or underfunded contour,
* likely structural consequences,
* confidence,
* supporting artifacts referenced.

### 5.5 Multi-Unit Extension Contract

Used when analysis depends on interactions across multiple units in a shared system.

Minimum fields:

* unit state map,
* coupling type,
* propagation pathway,
* recovery mode assumptions,
* shared-boundary risk notes,
* confidence and unknowns.

---

## 6. Decision Artifacts

Decision artifacts capture the move from analysis to judgment and action.

### 6.1 Failure Record

Captures the failure-related interpretation of the case using **Failure and Breakdown Definition**.

Minimum fields:

* system boundary,
* nesting level,
* time horizon,
* issue type: distortion / breakdown / degradation / failure / collapse,
* primary contour or mediator involved,
* failure condition triggered,
* compensation margin status,
* formal vs functional survival,
* confidence,
* notes.

### 6.2 Intervention Record

Captures the selected intervention logic using **Intervention Logic**.

Minimum fields:

* system boundary,
* nesting level,
* time horizon,
* diagnosed condition,
* primary contour or mediator involved,
* compensation margin status,
* selected intervention class,
* expected trade-off,
* reassessment trigger,
* confidence,
* notes.

### 6.3 Decision Output

Captures the most concise actionable conclusion from the analysis.

Minimum fields:

* diagnosed condition,
* intervention class,
* target,
* primary objective,
* expected trade-off,
* time horizon,
* confidence,
* reassessment trigger,
* notes.

The decision output is intentionally smaller than the intervention record. It exists so that analysis can be handed off without losing its operational consequence.

---

## 7. Validation Artifacts

Validation artifacts help test whether the application itself is reliable.

### 7.1 Use Discipline Record

Captures whether the application followed the model’s use constraints.

Minimum fields:

* system boundary,
* nesting level,
* time horizon,
* use mode,
* classification object,
* evidence basis,
* mediator relevant yes/no,
* confidence,
* trade-off declared yes/no/not applicable,
* known limitations,
* notes.

### 7.2 Assumption Test Record

Captures a challenge to one of the model’s assumptions, using the structure defined in **Model Assumptions Test Plan**.

Minimum fields:

* assumption ID,
* claim,
* failure condition,
* counterexample class,
* evidence or reasoning,
* rescue threshold,
* outcome,
* resulting revision action.

### 7.3 Revision Log

Captures changes made to the analysis or artifact interpretation after review, new evidence, or boundary correction.

Minimum fields:

* artifact changed,
* reason for change,
* prior state,
* revised state,
* reviewer or author,
* date,
* notes.

---

## 8. Comparative Artifacts

Comparative artifacts support multi-case or time-series use.

### 8.1 Comparison Record

Captures the basis on which two or more cases are being compared.

Minimum fields:

* compared cases,
* shared boundary logic,
* shared horizon logic,
* shared proxy logic,
* main differences,
* comparison validity notes,
* confidence.

### 8.2 State Change Record

Captures movement in the same system across time.

Minimum fields:

* system boundary,
* time period A,
* time period B,
* change in contour posture,
* change in mediator conditions,
* change in failure posture,
* change in intervention posture,
* evidence basis,
* confidence.

### 8.3 Portfolio View

Captures a set of related cases or subsystems at once.

Typical uses:

* multiple teams,
* multiple products,
* multiple components,
* multiple institutions,
* or multiple periods.

Minimum fields:

* portfolio scope,
* unit definition,
* alignment conditions,
* comparable artifacts used,
* summary posture,
* key cautions.

---

## 9. Minimal Application Stack by Use Mode

Not all use modes require the full suite.

### 9.1 Exploratory Use

Minimum stack:

* Boundary Declaration
* Horizon Declaration
* Classification Record
* Use Discipline Record

### 9.2 Diagnostic Use

Minimum stack:

* Boundary Declaration
* Horizon Declaration
* Classification Record
* Proxy Record
* State Estimate
* Distortion Assessment
* Use Discipline Record

### 9.3 Intervention Use

Minimum stack:

* Diagnostic stack
* Failure Record
* Intervention Record
* Decision Output
* Use Discipline Record

### 9.4 Comparative Use

Minimum stack:

* Diagnostic stack for each compared case
* Comparison Record
* State Change Record or Portfolio View
* Use Discipline Record

### 9.5 Formalization Use

Minimum stack:

* Assumption Test Record
* Revision Log
* referenced diagnostic artifacts where relevant

---

## 10. Artifact Relationships

The suite is designed to create traceable flow.

### 10.1 Basic Analytical Chain

Boundary Declaration
→ Horizon Declaration
→ Classification Record
→ Proxy Record
→ State Estimate
→ Distortion Assessment

### 10.2 Action Chain

Distortion Assessment
→ Failure Record
→ Intervention Record
→ Decision Output

### 10.3 Discipline and Validation Chain

Use Discipline Record
→ Assumption Test Record
→ Revision Log

### 10.4 Comparative Chain

Multiple State Estimates
→ Comparison Record
→ State Change Record or Portfolio View

This relational structure is important. The suite is not merely a list of documents; it is a chain of accountable interpretation.

---

## 11. Artifact Granularity Rules

### 11.1 One Object per Classification Record

Do not overload one classification artifact with multiple distinct objects unless they are intentionally being treated as a single composite object.

### 11.2 One Boundary per State Estimate

A state estimate should not silently shift boundaries inside the same record.

### 11.3 One Primary Judgment per Failure Record

Failure records should use the narrowest accurate diagnosis.

### 11.4 One Main Move per Decision Output

Decision outputs should not bundle many actions without stating sequencing.

### 11.5 Revision History Must Be Preserved

When an artifact changes, the change should be logged rather than overwritten silently in formal or high-stakes use.

---

## 12. Common Artifact Failures

### 12.1 Artifact Skipping

Jumping to intervention without creating classification, proxy, or state artifacts.

### 12.2 Artifact Compression

Combining too many functions into one note, making the reasoning chain impossible to review.

### 12.3 Hidden Assumptions

Leaving boundary, time horizon, confidence, or trade-off implicit.

### 12.4 Template Ritualism

Filling templates without preserving real analytical discipline.

### 12.5 Traceability Loss

Producing conclusions that cannot be linked back to supporting records.

---

## 13. Standard Metadata Fields

Every artifact in the suite should include basic metadata.

Minimum metadata:

* artifact type,
* date,
* author or analyst,
* linked artifacts,
* use mode,
* system boundary,
* time horizon,
* confidence level.

This supports traceability, revision, and later comparison.

---

## 14. Recommended Initial File Set

A practical initial file set for a single case may look like this:

1. **Boundary Declaration**
2. **Classification Record**
3. **Proxy Record**
4. **State Estimate**
5. **Distortion Assessment**
6. **Failure Record**
7. **Intervention Record**
8. **Decision Output**
9. **Use Discipline Record**

Additional artifacts can be added as needed for comparison, formalization, or revision.

---

## 15. Relationship to Comparability Rules

This document defines what artifacts should exist. It does not yet define in full when two artifacts are validly comparable.

That belongs to a separate **Comparability Rules** document.

However, the suite is designed so that comparability becomes possible only when relevant fields are recorded consistently.

---

## 16. Working Summary

This document defines the minimum artifact suite required to apply the model in a repeatable, reviewable, and eventually comparable way.

Its central claim is practical:

**the model becomes more reliable when each serious use leaves behind a traceable chain of framing, analysis, failure judgment, intervention logic, and discipline records.**

Used this way, the artifact suite turns the model from a reasoning language into an application practice.
