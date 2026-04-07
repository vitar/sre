# Dynamics

The previous chapters defined what the model describes and what the system is made of. This chapter defines what happens when the system operates — how allocation behaves under pressure, and how the system's own structure changes over time.

Dynamics are divided into two categories:

**Allocation Dynamics** govern how resources move between contours under environmental pressure and internal tension. These mechanisms operate within the system's existing structure — they do not change what the system is, they change where resources go.

**Structural Dynamics** govern how the system's own architecture changes — its Code, its Boundaries, its Gate configuration. These mechanisms alter the infrastructure through which allocation operates. When structural dynamics succeed, the system that emerges is not the same system with different allocation — it is a different system.

The distinction matters because the two categories require different interventions. Allocation problems are addressed by changing resource distribution. Structural problems are addressed by changing the system's operating logic, boundaries, or permeability. Misidentifying which category a problem belongs to produces interventions that fail for structural reasons.

Each mechanism defined below is introduced at the level necessary to establish its role in the model. Detailed treatment of individual mechanisms — typologies, formal properties, failure modes — belongs in dedicated companion documents.

---

## Allocation Dynamics

Allocation dynamics describe the mechanisms through which contour balance shifts, distortion is masked, and allocation decisions are reinforced or corrected over time. Four mechanisms are defined.

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

Detailed treatment — buffer typology, compensation margin, dynamics, failure modes, and formal propositions — belongs in the dedicated Compensation chapter.

### Feedback

Feedback is the mechanism by which allocation outcomes modify future allocation decisions.

Every allocation decision produces consequences — changes in contour output, environmental response, signal generation. Those consequences travel back through the system's element infrastructure — as Signals reaching Receivers — and inform subsequent allocation. Feedback is this return path: from outcome back to decision.

Feedback operates in two modes.

**Reinforcing feedback** amplifies the current allocation direction. A system that displaces Evolution and experiences short-term stability receives a signal that the displacement was viable — reinforcing further displacement. Reinforcing feedback accelerates existing trends. It can accelerate beneficial trends (a system investing in Evolution that receives positive environmental response) or destructive ones (a system depleting its Survival resources while Reproduction metrics remain strong).

**Balancing feedback** counteracts the current allocation direction. A system that displaces Evolution and subsequently loses adaptive capacity receives a signal that the displacement has consequences — creating pressure to restore Evolution allocation. Balancing feedback dampens oscillation and promotes return toward a prior balance.

Whether feedback reaches the system's allocation logic depends on the element infrastructure defined in the previous chapter. Feedback signals must cross Gates, match Receiver Legibility Range, exceed Receiver Threshold, and be parsed within the system's Code context. A system may generate feedback signals that never reach its own allocation logic — because Gates block them, because Receivers are not configured to parse them, or because Code defines them as irrelevant.

This structural dependency explains why some systems self-correct and others do not. Self-correction requires not only that balancing feedback exists, but that the system's element infrastructure permits it to reach allocation decisions. A system with functioning feedback loops and open signal paths is structurally capable of self-correction. A system with blocked or distorted feedback paths is not — regardless of whether balancing signals are being generated.

### Mediator Dynamics

Mediator dynamics describe how mediators — the cross-cutting factors defined in the model and architecturally positioned in the previous chapter — actively shape allocation mechanisms in motion.

Mediators do not merely exist as structural features. They participate in allocation dynamics by amplifying, blocking, or redirecting the other three mechanisms.

A mediator may **amplify** a mechanism — accelerating displacement, extending compensation, or strengthening feedback. Trust, for instance, amplifies feedback: in a high-trust system, signals from actors experiencing displacement are more likely to be received, parsed, and acted upon. In a low-trust system, the same signals are discounted or ignored.

A mediator may **block** a mechanism — preventing displacement from reaching a contour, shielding a buffer from exhaustion signals, or interrupting a feedback loop. Power structures, for instance, may block feedback that would threaten the current allocation pattern — protecting the positions of actors who benefit from the existing distribution.

A mediator may **redirect** a mechanism — changing which contour is displaced, which buffer absorbs distortion, or which feedback signal reaches the allocation logic. Governance, for instance, may redirect displacement from one contour to another by imposing allocation rules that override what the system's actors would choose under pressure.

Mediators can conflict. When two or more mediators push in opposing directions — one amplifying Evolution feedback while another blocks it — the system experiences mediator tension. Mediator tension is distinct from contour tension: contour tension arises from resource scarcity, mediator tension arises from competing cross-cutting forces shaping how that scarcity is managed.

The consequences of mediator dynamics depend on mediator strength, persistence, and alignment. Aligned mediators produce coherent allocation behavior. Conflicting mediators produce erratic or contradictory allocation — the system appears to pursue incompatible strategies simultaneously. Detailed treatment of mediator interaction patterns belongs in a dedicated chapter.

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

### Boundary Dissolution

Boundary dissolution is a system state in which environmental stress exceeds Boundary enforcement capacity, temporarily suspending normal Gate control.

Under normal conditions, Boundary and Gate regulate what enters and exits the system. Gate selectivity — configured by Code — determines which signals, resources, and actors are admitted. This selectivity is part of the system's structural integrity.

Under sufficient stress, this enforcement breaks down. Gates that normally block certain signals or actors become permeable. Flows that would normally be filtered or rejected enter the system without passing through the usual selection process. The system's interior becomes temporarily accessible to influences that existing Code would normally exclude.

Boundary dissolution is not failure. It is a transient state with a characteristic window. During the window, structural change that would otherwise be blocked becomes possible — including Code rewrite that could not satisfy the suppression condition under normal enforcement. The window is brief. When stress subsides or the system adapts, enforcement reconstitutes — often more aggressively than before, as the system's Code incorporates the dissolution experience into its threat model.

Boundary dissolution is triggered by systemic stress that exceeds the system's enforcement capacity — not by local pressure or incremental change. In human systems, triggers include existential competitive threat, organizational crisis, leadership collapse, or external shocks that invalidate the assumptions underlying current Gate configuration.

The outcome of boundary dissolution depends on what enters during the window. If actors carrying viable Code alternatives gain access, the system may undergo productive structural change. If no coherent alternative is available, dissolution produces disruption without transformation — the system restores its prior Code with additional defensive reinforcement.
