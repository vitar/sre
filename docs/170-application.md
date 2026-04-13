# Application

The previous chapters defined the theory — what the model is, what systems are made of, how they behave, how they degrade and recover, and how composed systems operate. This chapter defines how the theory is applied: the discipline required to use the model on real systems without misapplication.

Application is not a separate theory. It is the procedural bridge between the model's concepts and their use in diagnosis, intervention, and comparison. Every concept defined in the theory chapters can be misapplied — through imprecise classification, unmeasured estimation, undeclared boundaries, or intervention mismatched to diagnosis. Application defines the constraints that prevent this.

---

## Classification

Classification is the act of assigning a contour label — Survival, Reproduction, or Evolution — to a system activity, resource flow, or allocation decision.

### Primary Intent Rule

Classification is based on primary functional intent — the contour demand the activity was undertaken to address. An activity that scales existing output is Reproduction, even if it incidentally improves process reliability (a Survival effect). An activity that restructures a capability is Evolution, even if it incidentally produces new output (a Reproduction effect).

Secondary effects do not change classification. They are recorded separately. An activity classified as Reproduction with a secondary Survival effect is not reclassified as Survival — it remains Reproduction with a noted secondary effect.

### Ambiguous Cases

When primary intent is unclear, classification should be deferred until sufficient evidence is available. Premature classification produces interpretive drift — the analyst assigns a label based on partial information, and subsequent analysis is shaped by that label rather than by the system's actual behavior.

The most common source of ambiguity is the Survival–Reproduction boundary in organizational systems. Activities that maintain delivery capacity (Survival) and activities that scale delivery output (Reproduction) can appear identical from the outside. The distinction lies in intent: is the system preserving what it has, or expanding it? When the answer is unclear, the analyst should declare the ambiguity rather than force a classification.

### Classification Discipline

Every classification should be accompanied by:

- the declared unit boundary (what system is being analyzed),
- the time horizon (over what period is primary intent assessed),
- the confidence level (how certain the classification is),
- and any secondary effects noted.

Classification without these declarations is undisciplined and should be treated as provisional.

---

## Diagnosis

Diagnosis is the structured assessment of a system's state using the model's concepts. It is not freeform analysis — it follows a sequence that ensures all relevant structural features are examined.

### Diagnostic Sequence

**Declare the boundary.** What system is being analyzed? What is inside the boundary, what is outside? If multi-unit, which units are included and at what level of decomposition?

**Identify contour posture.** What is the system's current allocation across Survival, Reproduction, and Evolution? Which contour appears dominant, which appears under-allocated? Is the current posture deliberate or the result of displacement?

**Identify active dynamics.** Which mechanisms from System Dynamics are currently operating? Is displacement occurring — and if so, which contour is being displaced and by what? Is compensation active — and if so, what type and through what buffer? Is feedback reinforcing the current posture or counteracting it? Are mediators amplifying, blocking, or redirecting any of these dynamics?

**Assess system course stage.** Where is the system in the progression defined in System Course? Is it in distortion, stress, degradation, breakdown, or failure? What structural choices are available at the current stage?

**Examine element infrastructure.** Are any system elements exhibiting failure modes? Is Code coherent or drifting? Are Gates appropriately calibrated? Are Signals reaching Receivers? Are Receivers configured to parse the signals the system needs to respond to?

**Identify compound patterns.** Are any compound failure patterns (self-attack, unregulated replication, signal isolation) present?

**If multi-unit: assess inter-unit relations.** What is the coupling profile? Are units synchronized or desynchronized? What is the shared state type? Is cross-unit compensation occurring?

**State the diagnosis.** Name the system's state, the dynamics producing it, and the structural choices available. Declare confidence level and note what evidence would change the diagnosis.

### Diagnostic Discipline

A diagnosis is only as reliable as its boundary declaration and evidence base. Two constraints apply:

**Boundary consistency.** The analyst must maintain the same boundary throughout the diagnosis. Shifting between local and shared boundaries without explicit notice produces incoherent diagnosis — mixing unit-level and system-level observations as if they describe the same thing.

**Evidence over inference.** The diagnosis should be grounded in observable indicators — allocation patterns, signal behavior, gate configuration, output metrics — not in assumed intent or projected outcomes. Where direct evidence is unavailable, the analyst should declare the inference and its basis.

---

## Metrics and Proxies

The model's concepts — contour posture, compensation margin, displacement pressure, feedback direction — are not directly measurable in most systems. They must be estimated through observable indicators.

### Proxies

A proxy is an observable quantity that correlates with a model concept without measuring it directly. Proxies are estimates, not measurements. They are useful when direct measurement is impossible and misleading when treated as precise.

Each model concept requires its own proxy set, selected for the specific system under analysis. No universal proxy set exists — what indicates Survival-dominant allocation in one system may indicate something different in another. Proxy selection is part of the diagnostic process and should be declared explicitly.

### Proxy Discipline

Every proxy should be accompanied by:

- the model concept it estimates,
- the direction of the relationship (does an increase in the proxy indicate an increase or decrease in the concept?),
- the confidence level of the correlation,
- and known conditions under which the proxy becomes unreliable.

Proxies without these declarations are undisciplined and may produce false confidence in diagnosis.

---

## Intervention

Intervention is action taken to change a system's contour posture, dynamics, or course. The model informs intervention by connecting diagnosis to intervention class — what type of action is structurally appropriate for what type of diagnosed state.

### Intervention Classes

**Reallocation** — shifting resources between contours. Appropriate when the diagnosis is distortion caused by displacement and the system has not yet reached degradation. The system's structure is sound; its allocation is imbalanced.

**Compensation management** — making compensation visible, monitoring margin, establishing exit conditions. Appropriate when the diagnosis identifies active compensation — particularly structural compensation without awareness or exit conditions. The intervention target is not the compensation itself but the underlying distortion it masks.

**Feedback intervention** — opening blocked feedback paths, dampening reinforcing loops, strengthening balancing loops. Appropriate when the diagnosis identifies feedback dysfunction — reinforcing loops accelerating distortion, or balancing signals failing to reach allocation logic due to Gate or Receiver failure.

**Mediator intervention** — changing the cross-cutting factors that shape allocation dynamics. Appropriate when the diagnosis identifies mediator dysfunction — mediators blocking necessary signals, amplifying destructive dynamics, or conflicting with each other. Mediator intervention is indirect — it changes the conditions under which allocation occurs, not the allocation itself.

**Structural intervention** — changing the system's elements: Code rewrite, Boundary redefinition, Gate reconfiguration, Receiver reorientation. Appropriate when the diagnosis identifies element failure or when the system's current structure cannot support viable allocation under any reallocation. Structural intervention is the most consequential class — it changes the system itself, not just its allocation.

**Decoupling** — reducing inter-unit dependency. Appropriate in multi-unit systems where failure is cascading through tight coupling and cannot be arrested through other intervention classes. Decoupling reduces the composed system's scope but arrests propagation.

### Intervention Discipline

**Match intervention to diagnosis.** Each intervention class is appropriate for a specific diagnostic state. Applying structural intervention to an allocation problem is excessive. Applying reallocation to an element failure is insufficient. The mapping between diagnosis and intervention class is the core discipline of intervention design.

**Intervene on the cause, not the symptom.** Compensation is a symptom of displacement. Feedback dysfunction is a symptom of element failure. Intervening on symptoms (managing compensation without addressing displacement, fixing feedback without fixing the Gate that blocks it) produces temporary relief and structural persistence of the underlying problem.

**Declare the expected effect.** Every intervention should be accompanied by a stated expectation: what contour posture change, what dynamic change, or what element change the intervention is intended to produce. Without a declared expectation, the intervention cannot be evaluated — success and failure are indistinguishable.

**Monitor for unintended displacement.** Every intervention that changes allocation on one contour affects the others. An intervention that restores Evolution allocation may displace Survival or Reproduction. The analyst should anticipate which contour will absorb the reallocation and monitor for secondary distortion.

---

## Comparability

Comparison is the act of relating two or more system states — across time, across units, or across cases. Not all comparisons are valid. Comparability defines when comparison is legitimate and when it produces false equivalence.

### Comparability Conditions

Two system states are comparable when:

- they share the same unit boundary definition (or the boundary difference is explicitly declared),
- they are assessed at the same level of decomposition,
- the time horizons are compatible,
- and the environmental conditions are either the same or the difference is accounted for.

When any condition is not met, comparison is invalid unless the analyst explicitly declares the difference and accounts for its effect on the comparison.

### Common Comparability Errors

**Boundary mismatch** — comparing a team-level diagnosis with an organization-level diagnosis as if they describe the same thing.

**Decomposition mismatch** — comparing a single-unit analysis of one system with a multi-unit analysis of another.

**Temporal mismatch** — comparing a system's state at two points in time without accounting for environmental change between them.

**Environmental mismatch** — comparing two systems operating under different environmental conditions as if their contour postures are equally available to both.

---

## Use Constraints

The model can be misapplied. Use constraints define the boundaries of legitimate application — what the model can and cannot support.

### The Model Does Not Prescribe Outcomes

No contour balance is inherently correct. The model describes the consequences of allocation patterns — it does not rank them. An analyst who uses the model to argue that a system "should" allocate more to Evolution is making a normative claim that the model does not support. The model can say what will happen if Evolution remains under-allocated. It cannot say that this outcome is wrong.

### The Model Requires Declared Context

Every application of the model requires explicit declaration of: unit boundary, time horizon, environmental conditions, and confidence level. Application without these declarations is undisciplined and may produce conclusions that do not hold under different boundary or horizon assumptions.

### The Model Does Not Replace Domain Expertise

The model provides a structural lens for diagnosis and intervention. It does not replace the domain knowledge needed to interpret what contour allocation means in a specific context, what proxies are valid for a specific system, or what intervention is feasible under specific constraints. The model structures thinking — it does not substitute for it.

### The Model Is Falsifiable

The model makes structural claims that can be tested. If a system with limited resources, competing demands, and non-static behavior does not exhibit contour tension — the model's applicability claim is falsified for that case. If displacement does not produce distortion — the dynamics claim is falsified. The model invites testing and expects to be revised where evidence warrants it.
