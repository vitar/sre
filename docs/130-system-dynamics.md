# System Dynamics

The previous chapters defined what the model describes and what the system is made of. This chapter defines what happens when the system operates — how allocation behaves under pressure, and how the system's own structure changes over time.

System Dynamics are divided into two categories:

**Allocation Dynamics** govern how resources move between contours under environmental pressure and internal tension. These mechanisms operate within the system's existing structure — they do not change what the system is, they change where resources go.

**Structural Dynamics** govern how the system's own architecture changes — its Code, its Boundaries, its Gate configuration. These mechanisms alter the infrastructure through which allocation operates. When structural dynamics succeed, the system that emerges is not the same system with different allocation — it is a different system.

The distinction matters because the two categories require different interventions. Allocation problems are addressed by changing resource distribution. Structural problems are addressed by changing the system's operating logic, boundaries, or permeability. Misidentifying which category a problem belongs to produces interventions that fail for structural reasons.

Each mechanism defined below is introduced at the level necessary to establish its role in the model. Detailed treatment of individual mechanisms — typologies, formal properties, failure modes — belongs in dedicated companion documents.

---

## Allocation Dynamics

Allocation dynamics describe the mechanisms through which contour balance shifts, distortion is masked, and allocation decisions are reinforced or corrected over time. Six mechanisms are defined.

### Displacement

Displacement is the mechanism by which one contour's allocation is reduced to serve another under pressure.

When resource availability declines relative to demand — or when demand on one contour intensifies — the system cannot maintain its current allocation across all three contours. Something must receive less. Displacement is what determines which contour loses resources and which gains them.

Displacement is triggered by the gap between available resources and required allocation, not by absolute scarcity. A system with abundant resources can experience displacement if demands grow faster than supply. A system with scarce resources may avoid displacement if demands are proportionally modest.

Displacement order — which contour is reduced first — is context-dependent, not universal. The order depends on what the system's Code treats as most expendable under pressure. In most human systems, Evolution is displaced first because its returns are distant and uncertain, and its absence produces no immediate consequence. Reproduction is typically displaced second, and Survival last — because Survival failure threatens the system's existence directly. However, a system whose Code prioritizes transformation over scale would displace Reproduction before Evolution. Displacement order is a property of the specific system's Code, not a universal law.

Displacement is gradual by default. Allocation shifts incrementally as pressure builds. However, displacement can appear sudden to observers when the system compensates — masking the ongoing shift through buffer expenditure. In such cases, displacement has been occurring invisibly. When compensation margin is exhausted, the accumulated displacement becomes visible all at once. The displacement was gradual; its appearance was sudden. This connection between Displacement and Compensation is one of the model's central explanatory claims.

Displacement produces contour distortion — a state where allocation deviates from the system's prior balance. Distortion is not inherently pathological. A system may displace deliberately, accepting reduced allocation to one contour in order to address a temporary pressure on another. Distortion becomes problematic when it persists without a restoration trajectory, or when the system is unaware that displacement is occurring.

### Compensation

Compensation is the mechanism by which a system maintains observable viability under contour distortion through the expenditure of a finite buffer that is not part of the system's primary allocation logic.

Compensation arises when three conditions hold simultaneously: allocation between contours has deviated from viable balance, the system does not directly correct the deviation, and the gap between expected and actual contour output is absorbed by a buffer.

Compensation has a three-element structure. A **trigger** — an observable gap between expected and actual contour output. A **buffer** — a finite resource or capacity that absorbs the gap. A **signal** — evidence that buffer expenditure is occurring.

Compensation can be classified by intent. **Adaptive Compensation** is intentional, bounded, and accompanied by a plan to restore balance — the system knows it is compensating and when it will stop. **Structural Compensation** is unintentional, unbounded, and proceeds without a restoration plan — the system compensates because it has no alternative.

Compensation is not inherently pathological. It is an adaptive mechanism with a finite operational horizon. It becomes pathological when buffer expenditure persists without correction, consuming capacity that cannot be replenished.

Without Compensation, the model can describe distortion but predicts that distortion produces visible consequences immediately. This does not match observed system behavior. Compensation explains the temporal gap between the onset of contour distortion and the emergence of observable failure — why systems hold longer than their allocation profile predicts, and why failure often appears sudden to external observers.

The temporal dynamics of compensation — how buffers accumulate, how they deplete under sustained load, what curve shapes govern their exhaustion, and how different buffer types produce different temporal profiles — are formalized in System Metabolism. Compensation as defined here is the mechanism; its behavior over time is an accumulation dynamic.

Detailed treatment — buffer typology, compensation margin, dynamics, failure modes, and formal propositions — belongs in the dedicated Compensation chapter.

### Contour Saturation

Contour Saturation is the state where one contour's allocation reaches the system's physical limit, eliminating the allocation space for the other two contours entirely.

Saturation is structurally distinct from dominance. Under dominance, one contour receives a disproportionate share of resources while the others receive reduced but nonzero allocation. The system is imbalanced but retains degrees of freedom — reallocation remains structurally possible. Under Saturation, the dominant contour has consumed the entire allocation space. The other contours receive not merely less, but nothing — their allocation is not reduced, it is structurally impossible. The system has no remaining degrees of freedom within which to reallocate.

Saturation is the terminal state of displacement. It is what displacement becomes when the pressure driving it is absolute — when the demand on one contour is not merely greater than the others, but has absorbed the system's full resource capacity. In this sense, Saturation is not a separate mechanism from displacement but the boundary condition that displacement reaches under extreme pressure.

Three conditions define Saturation:

**Allocation collapse** — the total available resource is bound to a single contour. This is not a matter of priority or preference — it is a physical state in which the system's resources are structurally committed and unavailable for redistribution.

**Demand persistence on displaced contours** — the functional demands that Reproduction and Evolution represent do not disappear because their allocation has been eliminated. They persist as unmet structural requirements. The gap between zero allocation and nonzero demand is the maximum displacement the model can describe.

**Compensation impossibility** — no buffer exists that can absorb the gap between zero allocation and the persistent demand on the displaced contours. Compensation requires a finite resource outside the primary allocation logic. At Saturation, no such resource remains — the saturating contour has absorbed everything that could serve as a buffer.

The consequence of Saturation is that the system's allocation logic ceases to function. Allocation logic operates by distributing resources among competing demands — it requires a space of possible distributions. When that space collapses to a single point (all resources to one contour), the logic has no decisions left to make. The system is not making a bad allocation — it is no longer allocating at all.

Saturation produces a characteristic exit dynamic. Because the displaced contours' demands persist at nonzero levels while their allocation is zero, the displacement pressure does not resolve — it accumulates without bound. No compensation buffer can absorb it. No feedback mechanism can redirect it, because there are no resources to redirect. The system reaches a state where the internal pressure from unmet demand exceeds the structural capacity of the system to contain it.

The exit from Saturation is not reallocation — reallocation requires degrees of freedom that Saturation has eliminated. The exit is system reconstitution: the current system's Boundary fails, its resources disperse, and a new system forms under different allocation conditions. Reconstitution dynamics — what persists across this transition, what resets, and what determines the new system's initial allocation — are defined in System Course.

Saturation is rare in human systems because resource pools are diverse enough and boundaries permeable enough that total allocation collapse is difficult to achieve. A human organization can always, in principle, reallocate some fraction of attention, time, or effort — the allocation space does not fully collapse. Saturation is more characteristic of physical systems where resource pools are singular and conservation laws are absolute — where the entire available resource can, under sufficient pressure, be bound to a single functional demand with no remainder.

The model's theoretical generality claim — that its structural logic holds across systems where scarcity, competing demands, and non-static behavior are present — requires that it can describe what happens at the boundary conditions of its own logic. Saturation is that description. It is the state where the model's central mechanism (allocation among competing contours) reaches its limit, and the model must hand off to a different dynamic (reconstitution) to describe what follows.

### Feedback

Feedback is the mechanism by which allocation outcomes modify future allocation decisions.

Every allocation decision produces consequences — changes in contour output, environmental response, signal generation. Those consequences travel back through the system's element infrastructure — as Signals reaching Receivers — and inform subsequent allocation. Feedback is this return path: from outcome back to decision.

Feedback operates in two modes.

**Reinforcing feedback** amplifies the current allocation direction. A system that displaces Evolution and experiences short-term stability receives a signal that the displacement was viable — reinforcing further displacement. Reinforcing feedback accelerates existing trends. It can accelerate beneficial trends (a system investing in Evolution that receives positive environmental response) or destructive ones (a system depleting its Survival resources while Reproduction metrics remain strong).

**Balancing feedback** counteracts the current allocation direction. A system that displaces Evolution and subsequently loses adaptive capacity receives a signal that the displacement has consequences — creating pressure to restore Evolution allocation. Balancing feedback dampens oscillation and promotes return toward a prior balance.

Whether feedback reaches the system's allocation logic depends on the element infrastructure defined in the previous chapter. Feedback signals must cross Gates, match Receiver Legibility Range, exceed Receiver Threshold, and be parsed within the system's Code context. A system may generate feedback signals that never reach its own allocation logic — because Gates block them, because Receivers are not configured to parse them, or because Code defines them as irrelevant.

This structural dependency explains why some systems self-correct and others do not. Self-correction requires not only that balancing feedback exists, but that the system's element infrastructure permits it to reach allocation decisions. A system with functioning feedback loops and open signal paths is structurally capable of self-correction. A system with blocked or distorted feedback paths is not — regardless of whether balancing signals are being generated.

The most consequential reinforcing feedback pattern in the model — the loop between accumulating Evolution debt and increasing Survival overhead, in which capability degradation drives higher maintenance effort which further reduces Evolution investment — is formalized as an accumulation interaction in System Metabolism. Feedback as defined here is the mechanism; its sustained operation over time produces the accumulation dynamics that determine system trajectory.

### Endogenous Phase Transition

Endogenous Phase Transition is displacement triggered not by external pressure or environmental change, but by the system's internal state crossing a critical threshold at which the current allocation pattern becomes unstable.

Displacement, as defined above, is triggered by a gap between available resources and required allocation — typically produced by environmental change, demand intensification, or resource reduction. These are exogenous triggers: something outside the system's current allocation pattern changes, and the system responds.

Endogenous Phase Transition describes a different causal path. The system's environment may be stable. Demands may be constant. Resources may be unchanged. But the system's internal accumulation — debt, potential, overhead, or structural complexity — reaches a threshold at which the current allocation pattern can no longer sustain itself. The transition is triggered by what has accumulated inside, not by what has changed outside.

Three conditions define an Endogenous Phase Transition:

**Accumulation threshold** — a quantitative change in the system's internal state has reached a critical level. The threshold is not a single value but a boundary in the system's state space beyond which the current allocation regime is no longer self-sustaining. Below the threshold, the system's allocation pattern is stable under its current conditions. Above it, the same pattern becomes structurally unstable — small perturbations that would previously have been absorbed now trigger cascading reallocation.

**Absence of external trigger** — the transition is not caused by environmental change, demand shift, or resource shock. These may coincide with the transition — and when they do, the external event is typically credited as the cause. But the structural claim is that the transition would have occurred without the external event, because the internal state had already crossed the threshold. The external event, if present, is a catalyst for a transition that was already structurally inevitable.

**Discontinuous allocation shift** — the resulting displacement is not gradual. It is a rapid, qualitative change in allocation pattern — a shift from one allocation regime to a different one. The system does not smoothly adjust; it transitions. Before the threshold, incremental internal changes produce no visible allocation effect. After the threshold, a small additional increment produces a large allocation shift. The transition is discontinuous in the same sense that a phase change in physics is discontinuous — the underlying variable (temperature, accumulation) changes continuously, but the system's macro-state (liquid/gas, allocation regime) changes abruptly.

Endogenous Phase Transition has diagnostic value because it explains a class of system failures and transformations that appear to have no external cause. When a system that has been stable under constant conditions suddenly shifts its allocation pattern, the standard diagnostic — what changed in the environment? — may find nothing. The change was internal. Accumulated debt crossed a self-sustaining threshold. Accumulated complexity exceeded coordination capacity. Accumulated overhead reached a regime boundary. The system transitioned because its own metabolic state made the prior regime untenable, not because anything pushed it.

The relationship to other mechanisms is specific. Displacement describes what happens (allocation shifts between contours). Compensation may mask the accumulation that is approaching the threshold. Feedback may accelerate or delay the approach. The Endogenous Phase Transition describes the trigger condition — the moment when accumulated internal state converts from a quantitative change to a qualitative one.

The temporal dynamics of Endogenous Phase Transitions — what accumulation curves produce them, what threshold shapes are characteristic, and how the transition point can be estimated — are treated in System Metabolism. The mechanism is defined here; its temporal behavior is an accumulation dynamic.

### Mediator Dynamics

Mediator dynamics describe how mediators — the cross-cutting factors defined in the model and architecturally positioned in the previous chapter — actively shape allocation mechanisms in motion.

Mediators do not merely exist as structural features. They participate in allocation dynamics by amplifying, blocking, or redirecting the other five mechanisms.

A mediator may **amplify** a mechanism — accelerating displacement, extending compensation, strengthening feedback, lowering the threshold for Endogenous Phase Transition, or hastening the approach to Contour Saturation. Trust, for instance, amplifies feedback: in a high-trust system, signals from actors experiencing displacement are more likely to be received, parsed, and acted upon. In a low-trust system, the same signals are discounted or ignored.

A mediator may **block** a mechanism — preventing displacement from reaching a contour, shielding a buffer from exhaustion signals, or interrupting a feedback loop. Power structures, for instance, may block feedback that would threaten the current allocation pattern — protecting the positions of actors who benefit from the existing distribution. A mediator may also raise the threshold for Endogenous Phase Transition — institutional resilience, for instance, may allow higher internal accumulation before the allocation regime becomes unstable.

A mediator may **redirect** a mechanism — changing which contour is displaced, which buffer absorbs distortion, or which feedback signal reaches the allocation logic. Governance, for instance, may redirect displacement from one contour to another by imposing allocation rules that override what the system's actors would choose under pressure.

Mediators can conflict. When two or more mediators push in opposing directions — one amplifying Evolution feedback while another blocks it — the system experiences mediator tension. Mediator tension is distinct from contour tension: contour tension arises from resource scarcity, mediator tension arises from competing cross-cutting forces shaping how that scarcity is managed.

The consequences of mediator dynamics depend on mediator strength, persistence, and alignment. Aligned mediators produce coherent allocation behavior. Conflicting mediators produce erratic or contradictory allocation — the system appears to pursue incompatible strategies simultaneously. Detailed treatment of mediator interaction patterns belongs in a dedicated chapter.

### Mediator Reciprocity

The preceding section describes mediators acting on mechanisms — amplifying, blocking, or redirecting displacement, compensation, feedback, and the other allocation dynamics. The relationship is not one-directional. Allocation mechanisms act back on mediators, modifying their configuration properties over time.

Mediator Reciprocity is the structural claim that sustained allocation patterns alter the mediators that shape them. A mediator that shapes allocation is itself shaped by the allocation outcomes it produces. The relationship is bidirectional: mediator configuration → allocation pattern → mediator reconfiguration.

Reciprocity operates through the mediator's configuration properties defined in System Structure — selectivity, resolution, and temporal behavior. Sustained allocation outcomes modify these properties, not the mediator's existence. The mediator persists, but its structural character changes.

Three reciprocal pathways are defined.

**Allocation-driven selectivity shift.** Sustained displacement in one direction alters the mediator's selectivity pattern over time. A mediator that initially shapes allocation with smooth selectivity may sharpen under sustained Survival-dominant distortion — as the system's allocation logic increasingly treats resource flows as binary (critical/non-critical), the mediator's discrimination pattern narrows to match. Conversely, a mediator operating with sharp selectivity under balanced allocation may soften if the system enters a period of exploratory Evolution investment — the governance structures that previously enforced binary approval may gradually shift toward continuous influence as the system's Code incorporates experimentation as legitimate.

The mechanism is Code-mediated. The mediator's selectivity is configured by Code (as defined in System Structure). Sustained allocation patterns produce Code drift (as defined in Structural Dynamics). Code drift modifies the configuration under which the mediator operates. The mediator's selectivity shifts not because the mediator itself "decides" to change, but because the Code substrate it operates on has drifted.

**Allocation-driven resolution shift.** Sustained allocation patterns may alter the scale at which a mediator differentiates. Under sustained overhead ratchet (defined in System Metabolism), governance mediators often lose fine resolution — the elevated Survival allocation produces reporting, approval, and compliance structures that operate at aggregate scale, while individual-level or team-level resource flows become unmediated. The mediator's resolution coarsens as a consequence of the allocation pattern it is embedded in.

The reverse also occurs. A system that sustains balanced allocation with active Evolution investment may develop finer mediator resolution over time — trust, for instance, may differentiate at increasingly specific levels as actors accumulate shared experience across diverse contexts.

**Allocation-driven temporal shift.** The temporal behavior of a mediator — whether it is static or dynamic — may change as a consequence of sustained allocation patterns. A mediator that was static under balanced allocation may become dynamic under sustained distortion. Trust, for instance, may oscillate under chronic Survival-dominant allocation — periodically restored by crisis-response solidarity, then eroded by the ongoing displacement of Evolution and Reproduction investment. The oscillation is not inherent to trust as a mediator — it is produced by the allocation pattern that trust is embedded in.

Reciprocity produces a characteristic diagnostic challenge. When a system's allocation behavior changes, the change may originate in the allocation dynamics (a new displacement pressure, a compensation buffer exhausting, a feedback loop activating) or in the mediator configuration (selectivity shifting, resolution coarsening, temporal behavior changing). Because the two are reciprocally linked, the causal direction may be ambiguous. Diagnostic discipline requires identifying whether the allocation change preceded and caused the mediator reconfiguration, or whether the mediator reconfiguration preceded and caused the allocation change. The temporal sequence is the primary diagnostic tool: what changed first determines the causal direction. When both appear to change simultaneously, the system is likely in an active reciprocal loop — the allocation pattern is modifying the mediator that is modifying the allocation pattern. Intervening on either side of the loop can arrest it, but the choice of intervention target determines what changes and what persists.

Reciprocity is the structural mechanism that explains why mediators in long-lived systems rarely maintain their original configuration. Governance, trust, power, legitimacy — all are shaped by the allocation history of the system they operate within. A mediator's current configuration is a product of both its initial design and the cumulative allocation patterns it has experienced. Diagnosing a mediator's configuration without accounting for its allocation history produces a snapshot that misses the trajectory.

---

## Structural Dynamics

Structural dynamics describe mechanisms that change the system itself — its Code, its Boundaries, its Gate configuration. Unlike allocation dynamics, which operate within existing structure, structural dynamics alter the infrastructure through which allocation operates.

Structural change is distinct from allocation change. A system that shifts resources from Survival to Evolution has changed its allocation. A system that rewrites its Code to redefine what constitutes Survival has changed its structure. The first produces a different posture within the same system. The second produces a different system.

### Code Rewrite

Code rewrite is the mechanism by which a system's operating logic changes — deliberately or through emergent drift.

Code can change through two paths. **Drift** is gradual, unintentional change accumulating through repeated small departures from existing Code — each individually insignificant, collectively transformative. Drift is the default path. Most systems undergo Code change through drift rather than deliberate intervention. **Deliberate rewrite** is intentional change targeting specific elements of the system's operating logic. Deliberate rewrite is rarer and more difficult than drift, because the system's existing structure tends to resist it.

Deliberate Code rewrite requires four conditions to succeed:

**Targeting** — the actor or process attempting the rewrite must identify which element of Code is to be changed. Without precise targeting, change activity occurs without contacting the operating logic — the system experiences disruption but its Code remains intact.

**Vector** — the rewrite must have a delivery mechanism capable of reaching the Code. In human systems, vectors include trusted actors whose signals cross Survival-contour Gates, crises that bypass normal gatekeeping, or external events that carry new logic inside the system's Boundary.

**Suppression** — the system's resistance to Code change must be sufficiently reduced for the rewrite to take hold. Systems actively resist Code change — existing Code configures Gates and Receivers to reject signals that threaten it. Successful rewrite requires that this resistance is temporarily weakened, whether through legitimacy of the change agent, severity of crisis, or exhaustion of existing Code's credibility.

**Expression** — the rewritten Code must be active in the system's operating context. A Code change that is formally adopted but never enacted — the system says the new thing but runs the old logic — has not achieved expression. Expression requires that the system's Receivers, Gates, and Boundaries actually operate according to the new Code, not merely acknowledge it.

Failure at any condition produces a characteristic outcome. Without targeting: activity without structural contact. Without vector: the rewrite never reaches inside the Boundary. Without suppression: the rewrite is rejected and the change agent may be expelled. Without expression: the rewrite is nominal — new narrative, old Code.

### Code–Narrative Divergence

Code and Narrative may diverge. When they do, the system's expressed story — what it says about itself, what it communicates to its environment — no longer reflects its operating logic.

Divergence is not rare. It is a common system state, particularly in human organizations where narrative is more easily changed than Code. A system may adopt new values, publish new principles, or announce new priorities — all narrative changes — without its Code changing. The system's actual allocation behavior, Gate configuration, and Receiver orientation remain unchanged. The narrative is new; the behavior is old.

Divergence has diagnostic value. A system whose narrative and Code are aligned produces behavior consistent with its stated intent. A system whose narrative and Code have diverged produces behavior that contradicts its stated intent — and the contradiction is often visible to actors inside the system before it is visible to observers outside.

Divergence is not inherently pathological. A system may deliberately adopt narrative that leads its Code — stating aspirational intent before the operating logic has caught up. This is coherent if the system is actively pursuing Code rewrite toward the stated narrative. It becomes pathological when the divergence is permanent and unacknowledged — the system sustains a false story about itself without any trajectory toward alignment.

The temporal dynamics of divergence — why it occurs so readily and why it persists — have a structural explanation. Narrative operates at Signal speed: it can propagate through the system nearly instantaneously. Code changes at metabolic rates: constrained by the actual transformation of operating logic, practices, and institutional behavior. The speed difference between Narrative and Code is not incidental — it is a consequence of their different relationships to time. This temporal relationship, and its diagnostic implications, is treated in System Metabolism.

### Boundary Dissolution

Boundary dissolution is a system state in which environmental stress exceeds Boundary enforcement capacity, temporarily suspending normal Gate control.

Under normal conditions, Boundary and Gate regulate what enters and exits the system. Gate selectivity — configured by Code — determines which signals, resources, and actors are admitted. This selectivity is part of the system's structural integrity.

Under sufficient stress, this enforcement breaks down. Gates that normally block certain signals or actors become permeable. Flows that would normally be filtered or rejected enter the system without passing through the usual selection process. The system's interior becomes temporarily accessible to influences that existing Code would normally exclude.

Boundary dissolution is not failure. It is a transient state with a characteristic window. During the window, structural change that would otherwise be blocked becomes possible — including Code rewrite that could not satisfy the suppression condition under normal enforcement. The window is brief. When stress subsides or the system adapts, enforcement reconstitutes — often more aggressively than before, as the system's Code incorporates the dissolution experience into its threat model.

Boundary dissolution is triggered by systemic stress that exceeds the system's enforcement capacity — not by local pressure or incremental change. In human systems, triggers include existential competitive threat, organizational crisis, leadership collapse, or external shocks that invalidate the assumptions underlying current Gate configuration.

The outcome of boundary dissolution depends on what enters during the window. If actors carrying viable Code alternatives gain access, the system may undergo productive structural change. If no coherent alternative is available, dissolution produces disruption without transformation — the system restores its prior Code with additional defensive reinforcement.
