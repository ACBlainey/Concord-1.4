# Recovered Architectural Refinements — Batch 09

**Date:** 31 October 2026. These are verbatim contiguous extracts, not complete source copies. Each begins at the identified source heading and continues to the end of that source file. Original scenario histories remain in V1.3. Source hashes bind the extracts to the supplied snapshot. Historical validation/stability/authority claims are preserved assertions, not new findings or operational adoption. No experiments were executed.


## Source: 03_Cross_Domain_Architecture/Cross-Architecture Review Composition — Adversarial Integration Test 001.md

**Git blob:** `2f53911ede80668d73c9b1024c18ecc99d0136cc`. **Range:** `## 34. Test synthesis` through end of file.

**Verbatim extract begins:**

## 34. Test synthesis

All thirty tested conditions are representable without introducing a substantive central coordinator.

The stable mechanism is not “merge reviews.”

It is:

> **Preserve independent review grounds while permitting bounded operational coalescence of equivalent work.**

The strongest architecture is a **many-grounds / potentially-shared-work / many-outcomes** model.

## 35. Stable distinctions

The test supports:

`Subject identity`
!=
`Review-ground identity`

`Review-ground identity`
!=
`Evidence identity`

`Evidence identity`
!=
`Conclusion identity`

`Reviewer identity`
!=
`Owner identity`

`Bundle identity`
!=
`Authority identity`

`Bundle completion`
!=
`Constituent completion`

## 36. Minimal composition algorithm

1. Receive review-due request.
2. Resolve subject/unit/scope sufficiently for comparison.
3. Preserve request ground/provenance.
4. Test exact duplicate activation under STRA semantics.
5. If not duplicate, test material review-ground equivalence.
6. Preserve independent requests where equivalence is not established.
7. Identify legitimately reusable evidence/work.
8. Create/update a bundle only where operationally useful.
9. Route each constituent to its legitimate owner.
10. Record ground-addressable outcomes.
11. Revalidate freshness/context before satisfying later requests from prior work.
12. Split/reopen/supersede constituents when material state changes.
13. Derive bundle state without overwriting constituent state.
14. Route substantive conflict externally.
15. Preserve history.

Compact:

> **Receive → Resolve → Preserve Ground → Deduplicate Exact → Compare Grounds → Share Legitimate Work → Route Per Ground → Record Per Ground → Derive Bundle State → Reopen/Split As Material**

## 37. Minimum equivalence test

Two review requests may be treated as materially equivalent only where relevant dimensions align sufficiently:

`E = <Subject, Scope, Ground, RequiredQuestion, Consequence, Owner/Route, Context, Freshness>`

Not every low-consequence implementation requires formal equality across every field, but it must not use subject identity alone.

Where equivalence is uncertain:

> **Uncertain Equivalence -> Preserve Separate Grounds Until Resolved**

## 38. Bundle-state rule

Candidate bundle states:

- OPEN;
- PARTIAL;
- ROUTING_UNRESOLVED;
- DISPUTED;
- SPLIT_REQUIRED;
- SUPERSEDED;
- CLOSED_WITH_ALL_CONSTITUENTS_RESOLVED;
- CLOSED_WITH_CONSTITUENTS_REROUTED.

These are coordination states only.

No bundle state establishes substantive correctness.

## 39. Architectural ownership after test

### STRA retains
- trigger condition/state;
- review-due signal;
- duplicate activation suppression;
- cascade/cycle controls;
- routing and trigger provenance.

### KCS retains
- dependency/change propagation;
- material downstream review candidacy;
- dependency review provenance/stopping.

### ESCP retains
- completeness challenge;
- omitted-ground challenge;
- bounded discovery/termination/reopening.

### AUR retains
- architectural unit/family resolution.

### MKA/ASCP retains
- authority completeness/composition.

### CWA retains
- contextual permission/protected-space semantics.

### BTA retains
- transition-state/coherence semantics.

### Substantive owners retain
- domain conclusions.

### Review composition adds only
- cross-request ground preservation;
- bounded equivalence comparison;
- operational work/evidence coalescence;
- per-ground state tracking;
- bundle split/merge/supersession coordination.

## 40. Is the residual mechanism stable?

**YES — AS AN INTEGRATION PATTERN.**

The test found a coherent mechanism that is not reducible to duplicate suppression alone.

However, most of its safety boundaries and triggering semantics are supplied by existing architectures.

Therefore the evidence does **not yet require a new standalone portable module**.

## 41. Classification

**ADVERSARIAL INTEGRATION TEST: PASS**

**Mechanism status:** STABLE CROSS-ARCHITECTURE INTEGRATION PATTERN / NOT YET A PORTABLE MODULE

**Extraction decision:** DO NOT EXTRACT YET

The mechanism should be retained as a PMEDG candidate only if repeated use demonstrates independent portability beyond this Concord integration problem.

## 42. Candidate name

For development reference only:

**Review-Ground Composition Pattern (RGCP)**

This is a descriptive development label, not a graduated module name.

## 43. Candidate invariants strengthened by test

RGCP-01 **Same Subject != Same Review Ground.**

RGCP-02 **Duplicate Activation != Additional Review Ground.**

RGCP-03 **Operational Coalescence != Provenance Collapse.**

RGCP-04 **Shared Reviewer != Merged Question.**

RGCP-05 **Review Bundle != Merged Authority.**

RGCP-06 **Evidence Reuse != Conclusion Reuse.**

RGCP-07 **Evidence Reuse Is Scope-, Freshness- And Permission-Bounded.**

RGCP-08 **Constituent Completion != Bundle Completion.**

RGCP-09 **Bundle Membership Is Context-Bounded.**

RGCP-10 **Late Equivalence != Historical Identity.**

RGCP-11 **Bundle Split != Prior Error Erasure.**

RGCP-12 **Signal Volume != Material Diversity.**

RGCP-13 **All Represented Review Grounds != All Material Review Grounds.**

RGCP-14 **Coordination != Adjudication.**

RGCP-15 **Discovery Of New Ground != Mutation Of Original Ground.**

RGCP-16 **One Unresolved Owner != Automatic Global Review Failure.**

RGCP-17 **Bundle Availability != Bundle Requirement.**

RGCP-18 **Review Coordination != Commit Authority.**

## 44. New issue exposed

The test exposes a further question that should not be hidden inside RGCP:

> **When several independently legitimate constituent review results impose incompatible requirements on one proposed consequential act, what architecture determines whether the requirements compose, conflict, block, narrow or require an alternative route?**

This is not review deduplication and not review coordination.

MKA may already own a substantial part where the issue is authority composition; CWA/BTA may own contextual/transition constraints; CBPR owns bounded execution.

Therefore this **constraint/result composition** question must be source-resolved before any new architecture is proposed.

## 45. Disposition

1. Retain RGCP as a cross-domain integration pattern.
2. Flag RGCP as a PMEDG candidate; **do not extract yet**.
3. Do not modify STRA merely to absorb all review composition.
4. Do not create a central review authority.
5. Use ReviewRequest/ReviewBundle experimentally in future integrations.
6. Source-resolve the newly exposed constraint/result-composition question against MKA, CWA, BTA, CBPR and existing decision/composition architectures.

**Verbatim extract ends.**

## Source: 03_Cross_Domain_Architecture/ESCP Completeness Challenge — Bounded Discovery and Termination Test 001.md

**Git blob:** `b4da99f3f82f364569edd61bfe637438d3959946`. **Range:** `## 35. Bounded discovery` through end of file.

**Verbatim extract begins:**

## 35. Bounded discovery ladder

A practical ESCP challenge can proceed through:

### Level 0 — Scope alignment
What exactly is the conclusion?

### Level 1 — Known gaps
What relevant dimensions are known to be missing?

### Level 2 — Internal anomalies
What does the current representation fail to explain?

### Level 3 — Interface alternatives
What other sensors, observers, models or routes can expose distinctions the current architecture cannot?

### Level 4 — Relationship/state expansion
Are material relationships, temporal states, failure modes or future states absent?

### Level 5 — Adversarial challenge
What would have to be true for the scoped conclusion to fail?

### Level 6 — Consequence test
How irreversible/broad is the decision, and what evidence/reversibility should that require?

The ladder is not mandatory ceremony for every decision.

Depth is consequence-proportionate.

## 36. Termination dimensions

A bounded termination decision should consider:

1. **Scope clarity** — is the intended conclusion precisely bounded?
2. **Known gaps** — are material known gaps resolved or explicitly represented?
3. **Anomalies** — are material anomalies investigated or preserved?
4. **Discovery routes** — have proportionate high-value routes been exercised?
5. **Observer/interface diversity** — where useful, has independent representation been sampled?
6. **Discovery yield** — is further search still finding material dimensions?
7. **Consequence** — what happens if the evaluation is incomplete?
8. **Irreversibility** — can error be corrected?
9. **Time horizon** — how much discovery is possible before decision?
10. **Residual uncertainty** — is it explicit?
11. **Review/recovery** — can later discoveries reopen the conclusion?
12. **Authority** — are discovery methods themselves legitimately permitted?

## 37. Termination states

Suggested portable states:

- `COMPLETE_WITHIN_DECLARED_SCOPE`
- `KNOWN_MATERIAL_GAP`
- `MATERIAL_UNKNOWN`
- `DISPUTED_COMPLETENESS`
- `DISCOVERY_REQUIRED`
- `DISCOVERY_OPTIONAL`
- `CONCLUSION_SCOPE_TOO_BROAD`
- `TIME_BOUNDED_INCOMPLETE`
- `REVIEW_DUE`

No state means absolutely complete.

## 38. Anti-paralysis rule

> **ESCP review should continue while a reasonably plausible, materially relevant omission pathway remains unresolved and further discovery is proportionate to the decision.**

It may stop when that condition no longer holds within the declared scope and horizon.

## 39. Anti-closure rule

> **Termination means sufficient evaluation for the declared decision scope at the current time; it does not mean reality has been proven exhaustively represented.**

## 40. Reopening rule

A terminated completeness review reopens when materially relevant new information appears, including:

- anomaly;
- new observer/interface;
- new dependency;
- changed context;
- changed route;
- changed consequence;
- changed time horizon;
- new relationship;
- new failure mode;
- new substantive evidence.

KCS/STRA may operationalise this reopening.

## 41. Relationship to KCS and STRA

KCS can propagate the discovery of a newly established material dimension to represented dependents.

STRA can trigger/re-route completeness review when declared conditions arise.

Neither decides the substantive meaning of the missing dimension.

## 42. Relationship to MKA/ASCP

For authority questions, ASCP uses the same bounded logic.

A high-consequence act demands stronger authority-space completeness than a low-consequence reversible act.

But:

> **Need For Greater Authority Completeness != Authority To Invent Missing Authority**

## 43. Relationship to CWA

Contextual completeness review cannot justify invasive access merely to eliminate every possible unknown.

Context discovery remains bounded by permission, rights and authority.

## 44. Relationship to BTA

Transition completeness review should scale with consequence and irreversibility.

A reversible low-impact handoff may require less discovery than a permanent multi-owner state transformation.

BTA still owns transition completion.

## 45. New invariants

ET-01 **Missing Dimension != Material Missing Dimension.**

ET-02 **Logical Possibility != Operationally Material Completeness Gap.**

ET-03 **Reversibility Can Reduce Required Pre-Decision Completeness Without Eliminating Review Duty.**

ET-04 **Diminishing Material Discovery Yield Can Support Termination Without Proving Exhaustiveness.**

ET-05 **Need To Reduce Uncertainty != Authority To Use Any Discovery Method.**

ET-06 **Incomplete Search Horizon != Permission To Pretend Completeness.**

ET-07 **Incomplete Search Horizon != Automatic Requirement For Inaction.**

ET-08 **ESCP Applies To ESCP Without Requiring Infinite Meta-Evaluation.**

ET-09 **Unspecified Unknown Unknown != Permanent Decision Veto.**

ET-10 **Present-State Completeness != Future-State Completeness.**

ET-11 **Narrowing The Conclusion Can Resolve A Completeness Mismatch Without Expanding The Model.**

ET-12 **Prior Termination != Permanent Closure.**

ET-13 **Available Discovery != Mandatory Discovery At Any Cost.**

ET-14 **Completeness Search != General Search Authority.**

ET-15 **Completeness Metric != Completeness.**

## 46. Result

**PASS — BOUNDED DISCOVERY AND TERMINATION ARE COMPATIBLE WITH ESCP**

Thirty adversarial cases were tested.

No need was found for:

- absolute completeness;
- infinite regress;
- universal blocking;
- central completeness authority;
- exhaustive discovery at any cost.

The viable operational standard is:

> **Sufficient completeness for a declared conclusion, consequence and time horizon, with material gaps represented, proportionate discovery performed, residual uncertainty explicit, and correction/reopening preserved where reasonably possible.**

## 47. Strongest synthesis

ESCP can avoid both false certainty and paralysis if it treats completeness as a scoped operational claim rather than an absolute metaphysical claim.

Therefore:

> **Complete Within Declared Scope != Complete Reality**

and:

> **Bounded Termination != Epistemic Closure**

## 48. Next development question

The next useful step is not another general ESCP architecture.

The test now provides enough material to define a small **ESCP operational companion** containing:

- completeness challenge;
- bounded discovery ladder;
- consequence scaling;
- termination states;
- reopening triggers;
- anti-paralysis/anti-closure rules.

Before extraction, this should be checked against the existing ESCP portable module's status and PMEDG history to determine whether it belongs as:

1. a companion upgrade to ESCP;
2. a revision of the existing ESCP module; or
3. development evidence only.

Recommended next work:

**ESCP Operational Companion — PMEDG Boundary Review 001**

**Verbatim extract ends.**

## Source: 03_Cross_Domain_Architecture/Derived Information Governance — Adversarial Integration Test 001.md

**Git blob:** `b7d8c64cf96b1a5a7a43a62b2518810f789c495d`. **Range:** `## 12. Residual findings` through end of file.

**Verbatim extract begins:**

## 12. Residual findings

Only two tests required new general cross-domain architecture:
1. relational/shared-subject information;
2. withdrawal after irreversible learning.

Three important clarifications emerged without requiring new systems:

### Clarification 1
> **Anonymous Information Can Cause Consequential Harm Without Becoming Personal Information.**

Privacy is not the only protection layer. Consequential use can be illegitimate even where anonymity is genuine.

### Clarification 2
> **No Stored Profile != No Derived Information Event.**

Transient inference can be governed by purpose, consequence and protection even if nothing is persisted.

### Clarification 3
> **Cross-Boundary Transfer Does Not Automatically Select Either Side's Entire Protection Regime.**

A bounded interoperability state is required.

## 13. Family-level assessment

The architecture family survives the adversarial suite without requiring a new universal information-governance engine.

The dominant pattern remains decomposition:
- source state;
- operation;
- derivative;
- claims;
- protection;
- authority;
- use;
- transition;
- exposure;
- remedy.

This is a positive result because the difficult cases are resolved through composition of bounded existing architectures rather than centralisation.

## 14. Remaining domain work

Further work is better targeted at domain implementation than additional cross-domain abstraction.

High-value domain follow-ons:
- Health/Law boundary for familial genomic notification;
- Research policy for withdrawal/unlearning claims;
- Law/Judiciary evidential use of protected derivatives;
- Intercivilisational protocol for protected-information transfer;
- AI system implementation of ephemeral-inference controls;
- fairness/discrimination rules for anonymous group-level statistics.

## 15. Conclusion

The test supports the current family structure.

The two genuine residual gaps have been isolated and developed.

The remaining failures are primarily domain adoption and implementation problems rather than missing general architecture.

**Verbatim extract ends.**

## Source: 03_Cross_Domain_Architecture/Participant-Supporting Infrastructure — Adversarial Stress Test 001.md

**Git blob:** `7520fa92754c356f8bc1a48df334819180b7fd67`. **Range:** `# 86. Cross-test result` through end of file.

**Verbatim extract begins:**

# 86. Cross-test result

The architecture survives.

No case requires either:

**Owner Controls Asset -> Owner Controls Participant**

or:

**Participant Depends On Asset -> Participant Owns Asset**

The difficult cases instead require a third category:

> **bounded dependency-sensitive transition and reconciliation.**

This validates the central architecture.

---

# 87. Refinement 1 — adequate successor

A successor is adequate only if it preserves the material function that created the protected dependency.

Therefore:

**Available Alternative != Adequate Successor**

and:

**Nominally Equivalent Service != Functionally Equivalent Transition**

Relevant dimensions can include:

- life/health;
- cognition;
- continuity;
- accessibility;
- privacy;
- security;
- protected information;
- identity;
- agency.

---

# 88. Refinement 2 — transition opportunity versus acceptance

Provider duty cannot depend forever on participant agreement.

Once an adequate successor and reasonable transition opportunity exist:

**Participant Refusal != Automatic Extension Of Provider Duty**

subject to review of competence, adequacy and coercion.

---

# 89. Refinement 3 — transition duty is dynamic

Dependency can rise or fall.

Therefore:

**Initial Dependency Class != Permanent Dependency Class**

and:

**Past Critical Dependency != Permanent Enhanced Provider Duty**

The PSI relation requires reassessment at consequential change.

---

# 90. Refinement 4 — aggregate dependency

Distributed infrastructure creates a new ESCP risk.

Each provider may appear individually non-critical while simultaneous withdrawal is catastrophic.

Therefore:

> **Dependency must be assessed at both component and aggregate functional levels.**

**Individually Non-Critical Withdrawal Can Be Collectively Critical**

This should integrate with KCS dependency topology.

---

# 91. Refinement 5 — participant-manufactured dependency

Anti-capture must be symmetric.

**Manufactured Dependency By Participant != Automatic Expansion Of Provider Duty**

**Self-Created Fragility != Automatic Transfer Of Responsibility**

This does not erase standing or permit gratuitous catastrophic harm.

It affects responsibility, cost and transition burden.

---

# 92. Refinement 6 — controller-created alternatives deficit

Where the controller deliberately destroys or blocks alternatives:

**Controller-Created Absence Of Alternatives != Neutral Market Condition**

This strengthens the duty to repair or enable exit.

---

# 93. Refinement 7 — criticality and contract

Contract matters but does not exhaust the rights analysis.

**No-Guarantee Contract != Advance Authority For Avoidable Catastrophic Harm In Every Future State**

Conversely:

**Critical Dependency != Automatic Erasure Of Contractual Obligations**

---

# 94. Refinement 8 — three-party resource solution

Many hard cases reveal an incomplete binary:

**Provider Pays**

versus:

**Dependent Participant Loses Function**

ESCP requires asking whether a third route exists:

- insurer;
- public continuity reserve;
- mutual pool;
- emergency fund;
- replacement provider;
- creditor restructuring;
- donated/shared resources;
- temporary civil infrastructure.

Therefore:

**Binary Owner-Or-Dependent Cost Allocation Can Be An Incomplete Evaluation Space**

---

# 95. Refinement 9 — emergency preservation without continued operation

Some dangerous participants/systems must stop operating immediately.

Standing can still be respected through:

- safe isolation;
- state preservation;
- later recovery;
- review;
- migration where possible.

Therefore:

**Continuity Protection != Continuous Operation**

and:

**Safe State Can Preserve Standing Without Preserving Active Capability**

---

# 96. Refinement 10 — transition feasibility

The phrase “where reasonably possible” needs explicit structure.

Feasibility should consider:

- physical possibility;
- time;
- available resources;
- risk to others;
- technical maturity;
- provider capacity;
- participant capacity;
- substitute availability;
- reversibility;
- expected harm.

**Transition Duty Must Remain Feasibility-Bounded**

But feasibility must not be manipulated by deliberately removing transition capacity.

---

# 97. Refinement 11 — preservation versus service

Where active service cannot continue, preservation may still be possible.

Examples:

- AI state quarantine;
- medical stabilisation;
- protected storage;
- inactive embodiment;
- emergency archive pending migration.

Therefore:

**Service Continuation != State Preservation**

and:

**Inability To Continue Service != Automatic Authority To Destroy Preservable Participant State**

This links directly to CPS and Continuity.

---

# 98. Refinement 12 — transition debt

A provider may complete urgent safe transition while legitimate unpaid costs remain.

This avoids the false binary between catastrophic withdrawal and uncompensated provision.

Candidate concept:

> **Transition Debt** — a legitimate unresolved cost/obligation created or preserved while immediate continuity protection is performed.

This is not yet a legal debt class.

It is a design concept for Economy/Law.

**Emergency Transition != Automatic Cost Waiver**

---

# 99. Major unresolved interfaces

The test exposes six major interfaces.

### I. Scarcity allocation

How should genuinely insufficient indivisible resources be allocated among equal-standing participants?

### II. Bankruptcy / creditor priority

How should participant continuity interact with secured claims, insolvency and liquidation?

### III. Identity-preserving migration

What constitutes adequate successor service where migration may copy, branch, suspend or transform a participant?

### IV. Shared cognition and third-party information

How can portability preserve one participant without appropriating another participant's cognition or protected information?

### V. Permanently inseparable private infrastructure

What legal structure applies where participant and privately owned asset cannot be separated?

### VI. Cost allocation / transition debt

Who ultimately bears transition costs after urgent continuity protection?

None defeats PSI itself.

---

# 100. Overall finding

**PASS WITH TWELVE ARCHITECTURAL REFINEMENTS AND SIX MAJOR DOWNSTREAM INTERFACES.**

The architecture survives both primary attacks.

It does not require expropriating supporting infrastructure merely because dependency exists.

It does not permit infrastructure ownership to become ownership or arbitrary destruction of the participant.

The central relation is strengthened:

> **Severe dependency can create a bounded duty of safe separation without creating permanent ownership in either direction.**

This can be represented as:

**Legitimate Property/Service Relation**
→ **Material Participant Dependency**
→ **Dependency-Sensitive Transition Duty**
→ **Adequate Successor / Preservation / Safe Separation**
→ **Provider Exit + Participant Continuity Where Feasible**
→ **Residual Cost/Obligation/Remedy Resolution**

The strongest new finding is:

> **The civil objective is not indefinite provision. It is safe separation where separation is possible.**

And where separation is not presently possible:

> **Dependency must be reconciled explicitly rather than disguised as either absolute property power or automatic participant ownership of the resource.**

---

# 101. Recommended next step

Integrate the twelve refinements into the main PSI architecture.

Then source-resolve the six unresolved interfaces against existing Concord architecture before creating new systems.

The first source-resolution target should be **scarcity allocation**, because it recurs across:

- compute;
- energy;
- medical equipment;
- housing/habitat;
- emergency infrastructure;
- shared life-support;
- civilisation continuity.

The question should be:

> **When legitimate claims exceed an indivisible or genuinely insufficient resource, what existing Concord architecture determines allocation without converting wealth, incumbency, political authority, or substrate into automatic priority?**

**Verbatim extract ends.**

## Source: 03_Cross_Domain_Architecture/Scarcity Allocation — Adversarial Stress Test 001.md

**Git blob:** `32bdb9e9b90fc5270998700008b54520f0905cf6`. **Range:** `# 89. Cross-test result` through end of file.

**Verbatim extract begins:**

# 89. Cross-test result

The architecture survives most attacks but exposes one genuinely upstream unresolved constitutional problem:

> **When several equal-standing participants face the same fundamental loss, to what extent may the number of protected participants affected determine allocation?**

This is the **Fundamental Aggregation Problem**.

Examples:

- one life versus five;
- one human versus ten AI participants using equivalent total resource;
- one direct claimant versus infrastructure supporting thousands;
- one surgeon's attention across multiple patients.

The existing architecture establishes that aggregate consequences matter, but also that participants must not be treated merely as expendable means.

Neither principle alone determines the boundary.

This must not be hidden inside a numerical allocation score.

---

# 90. Refinement 1 — active intervention / displacement

There is a relevant difference between:

- not initiating a scarce service;
- terminating an already established service;
- forcibly displacing a participant from an established protected context.

This is not because the incumbent is worth more.

It is because the intervention itself may add:

- new harm;
- reliance;
- transition cost;
- safe-space disruption;
- rights interference.

Therefore:

**Incumbency != Worth**

but:

**Displacement Can Be A Distinct Consequential Act**

---

# 91. Refinement 2 — forecast future claims

Distinguish:

- hypothetical future demand;
- probabilistic forecast supported by evidence;
- committed/known future claim;
- current claim.

**Forecast Future Claim != Hypothetical Future Claim**

Future weighting should depend on evidence, time horizon, reversibility and reserve function.

---

# 92. Refinement 3 — materiality

Tiny numerical differences should not manufacture priority.

**Numerical Difference != Material Difference**

Allocation protocols require confidence and materiality thresholds appropriate to resource class.

---

# 93. Refinement 4 — protected-context incumbency

An established home, cognitive host, life-support relationship or other protected context creates more than administrative queue position.

**Current Protected Context != Mere Administrative Incumbency**

Any displacement must include the rights consequences of disrupting that context.

---

# 94. Refinement 5 — repeated-game scarcity

Recurring scarcity must be evaluated longitudinally.

**Repeated Scarcity != Sequence Of Unrelated One-Off Decisions**

Possible factors include:

- accumulated burden;
- continuity;
- rotation feasibility;
- prior access;
- recovery time;
- newcomer exclusion;
- predictable future capacity.

Past receipt is not a worth penalty, but may be relevant to distribution of reversible recurring burdens.

---

# 95. Refinement 6 — scalar-collapse prohibition

For fundamental protected-function conflicts:

> **The multi-factor architecture must not be reduced to a universal weighted score that purports to measure which participant is more worthy of the resource.**

This does not prohibit quantitative measurements of individual factual dimensions.

It prohibits their unexamined conversion into a universal participant-priority scalar.

**Factor Measurement != Worth Quantification**

---

# 96. Refinement 7 — historical-model prohibition

**Historical Allocation Pattern != Normative Allocation Authority**

Models may help predict demand, effectiveness or capacity.

They must not derive legitimacy merely by reproducing previous allocation outcomes.

---

# 97. Refinement 8 — rapid-decision mode

Scarcity architecture requires two tempos:

### Deliberative mode
Used where time permits full verification, ESCP search, dependency mapping and contestability.

### Rapid mode
Used where delay itself creates serious irreversible harm.

Rapid mode should use only the minimum sufficient high-confidence distinctions and preserve:

- provenance;
- uncertainty;
- post-event review;
- correction where possible.

**Urgency Can Contract Evaluation Without Creating New Priority Values**

---

# 98. Refinement 9 — scarce labour is not ordinary allocatable stock

Labour scarcity must preserve the worker's agency.

**Scarce Labour != Ownership Of Labourer**

Coordination can prioritise requests or duties already lawfully undertaken, but resource-allocation architecture alone cannot compel labour.

---

# 99. Refinement 10 — infrastructure decomposition

An institutional claim must be decomposable into protected functions and dependencies.

**Institutional Claim -> Function -> Dependency -> Participant/Civil Consequence**

This prevents “critical infrastructure” from becoming a magic priority label.

---

# 100. Refinement 11 — resource-frontier expansion

Resources used to restore or expand supply can have special systemic relevance.

Examples:

- power for grid-repair team;
- compute for resource scheduler;
- fuel for delivery of more fuel;
- machine part for water repair.

**Resource Used To Expand Resource Frontier Can Be Allocation-Relevant**

This is not institutional worth; it is evidenced consequence.

---

# 101. Refinement 12 — no moralisation of denial

The system must preserve:

**Allocation Necessity != Moral Reclassification Of The Unserved Participant**

Denial under genuine scarcity must not become evidence that the participant was less deserving, less valuable or lower standing.

---

# 102. Overall result

**PASS WITH TWELVE ARCHITECTURAL REFINEMENTS, MULTIPLE DOMAIN INTERFACES, AND ONE UPSTREAM CONSTITUTIONAL PROBLEM.**

The architecture successfully blocks simple priority rules based on:

- wealth;
- contribution;
- reputation;
- citizenship;
- substrate;
- institutional label;
- majority preference;
- first arrival;
- raw ownership;
- opaque algorithmic scoring.

It also successfully avoids false equality rules such as equal division where division destroys utility.

The most significant unresolved finding is:

> **Fundamental Aggregation Problem — how should equal individual standing interact with differences in the number of participants whose fundamental protected functions can be preserved by a scarce allocation?**

This problem must be source-resolved before any general claim such as “save the greatest number” is admitted into Concord.

---

# 103. Recommended next step

1. integrate the twelve refinements into the source-resolution architecture;
2. create a dedicated source resolution for the **Fundamental Aggregation Problem**;
3. examine Blainey's Laws, especially Non-Harm, Developmental Priority, Resource Stewardship, Autonomy/Consent and anti-instrumentalisation protections;
4. examine Rights Charter conflict grammar;
5. examine emergency architecture;
6. test whether aggregation is:
   - prohibited;
   - permitted as one bounded factor;
   - presumptively relevant;
   - or context-dependent by resource class.

No numerical rule should be invented before that resolution.

**Verbatim extract ends.**

## Source: 03_Cross_Domain_Architecture/Withdrawal Authority — Adversarial Stress Test 001.md

**Git blob:** `347b78b3ae21100523c19b6d9eebb9f759244186`. **Range:** `# 91. Overall result` through end of file.

**Verbatim extract begins:**

# 91. Overall result

**PASS WITH EIGHTEEN ARCHITECTURAL REFINEMENTS AND TWELVE MAJOR DOWNSTREAM INTERFACES.**

Neither target failure mode is required by the architecture.

Withdrawal Authority can avoid permanent provider captivity while also preventing property/contract labels from laundering avoidable participant destruction.

The strongest result is:

> **Safe separation is an objective and a bounded process, not an unlimited guarantee that separation can always be made harmless.**

Where safe separation is impossible, the architecture must expose the underlying rights/resource conflict rather than secretly resolving it by assigning ownership of one participant to another.

---

# 92. Refinement 1 — protected support threshold

**Established Service != Established Protected Support Relation**

Not every recurring service activates heightened Withdrawal Authority.

The support must materially perform a protected participant function.

---

# 93. Refinement 2 — termination clause

**Termination Clause != Authority To Destroy Participant Standing**

Contract defines relationships; it cannot silently redefine a rights-bearing participant as disposable property.

---

# 94. Refinement 3 — support cost

**Protected Standing != Licence To Externalise Unlimited Support Cost**

Transition duties need a funding/cost path.

---

# 95. Refinement 4 — manufactured impossibility

**Manufactured Impossibility Can Create Accountability Without Creating Impossible Capacity**

Causal responsibility and present feasibility must remain separate.

---

# 96. Refinement 5 — controller-created non-portability

**Controller-Created Non-Portability != Neutral Withdrawal Constraint**

Lock-in increases controller responsibility for transition.

---

# 97. Refinement 6 — false futility

**Higher Alternative Benefit != Existing Treatment Futility**

Futility concerns whether the current support performs its function, not whether someone else could benefit more.

---

# 98. Refinement 7 — low-cost bridge

**Minimal Transition Cost + Catastrophic Avoidable Harm -> Strong Safe-Transition Case**

The smaller the burden needed to prevent catastrophic avoidable harm, the stronger the transition justification.

---

# 99. Refinement 8 — duration and cost

**Transition Duration And Cost Matter To Reasonableness**

Safe-transition duty is not consequence-only; burden and feasibility matter.

---

# 100. Refinement 9 — termination vocabulary

**Termination Vocabulary != Termination Consequence**

Shutdown, suspension, deletion, discharge and disconnection must be classified by actual effect.

---

# 101. Refinement 10 — housing/property bridge

**Property Recovery Can Be Temporally Bounded By Immediate Transition Harm Without Becoming Permanent Expropriation**

Temporary safe-transition delay does not automatically transfer ownership.

---

# 102. Refinement 11 — no-successor boundary

**No Successor != Automatic Permanent Private Service Duty**

The absence of alternatives triggers third-route search, not provider ownership.

---

# 103. Refinement 12 — embedded property

**Property In Participant != Ordinary Repossession Authority**

Deep integration can transform the relevant rights analysis.

---

# 104. Refinement 13 — repeated extension

**Transition Duty Requires A Termination Path**

High-consequence extensions should have:

- milestones;
- review;
- successor work;
- funding path;
- preservation alternative;
- sunset logic.

---

# 105. Refinement 14 — completed handoff

**Completed Reasonable Handoff != Permanent Guarantee Of Successor Performance**

Transition duty must be capable of actually ending.

---

# 106. Refinement 15 — emergency isolation

**Emergency Isolation != Emergency Destruction**

Containment and preservation should be distinguished.

---

# 107. Refinement 16 — minimum viable continuation

**Minimum Necessary Continuity != Maximum Historical Service Level**

and:

**Minimum Cost != Minimum Safe Continuity**

The bridge is function-bounded.

---

# 108. Refinement 17 — impossible safe separation

**Impossible Safe Separation != Automatic Permanent Provider Servitude**

Where separation cannot be made safe, the conflict must be surfaced to Law/Governance/Economy/Continuity rather than hidden inside Withdrawal Authority.

---

# 109. Refinement 18 — administrative rights laundering

**Administrative Sequencing != Rights Laundering**

A controller cannot evade withdrawal duties by formally terminating one legal relation milliseconds before performing the destructive physical act.

---

# 110. Twelve major downstream interfaces

1. **Medical futility and treatment withdrawal**
2. **Established life-support reallocation**
3. **Self-directed life-support withdrawal / advance directives**
4. **Bankruptcy and creditor priority**
5. **Transition cost / funding / Transition Debt**
6. **Permanent technical inseparability**
7. **Identity-preserving migration, suspension and self-termination**
8. **Embedded property / bodily-prosthetic integration**
9. **Cross-jurisdiction provider exit**
10. **Public-provider duties and monopoly-created dependency**
11. **Economy/Law treatment of manufactured dependency and lock-in**
12. **Direct harm hidden as service termination**

---

# 111. Validated architecture

The test supports:

> **Withdrawal Authority is a bounded transition authority, not a permanent-service entitlement and not a termination privilege. Its function is to permit legitimate support relations to end while preventing avoidable destruction caused merely by the manner of exit.**

The architecture should seek:

**Continuation Where Independently Required**
OR
**Adequate Successor**
OR
**Safe Preservation / Suspension**
OR
**Minimum Viable Bridge**
OR
**Best Feasible Harm-Minimising Separation**

—not endless full service by default.

---

# 112. Best feasible separation

The stress test reveals that “safe separation” can sound absolute.

It should therefore be refined:

> **Safe separation is the preferred objective. Where fully safe separation is impossible, the duty becomes best feasible separation: the least unnecessarily harmful transition reasonably achievable within legitimate authority, available resources, provider rights and actual technical possibility.**

Therefore:

**Safe Separation Objective != Guarantee Of Harm-Free Separation**

and:

**Best Feasible Separation != Permanent Continuation Until Perfect Alternative Exists**

---

# 113. Provider standing

A major result is that providers may themselves be participants.

The architecture must therefore evaluate both sides.

> **A support recipient's standing cannot be protected by converting the provider into property.**

Thus:

**Participant Protection != Sacrifice Of Provider Participant**

This is the mirror image of the original PSI rule.

---

# 114. Development recommendation

Integrate the eighteen refinements into the Withdrawal Authority source resolution.

Then propagate the validated distinction into Scarcity Allocation:

> **An established-support reallocation requires both a valid scarcity allocation decision and a valid withdrawal transition.**

The next source-resolution target should be **Established Life-Support Reallocation**, because it is the remaining clean collision between:

- validated aggregation;
- validated Withdrawal Authority;
- Health;
- autonomy;
- protected context;
- and direct irreversible consequence.

It should not be resolved by importing external medical triage doctrine without Concord source derivation.

**Verbatim extract ends.**

## Source: 03_Cross_Domain_Architecture/Temporal Consent, Commitment and Withdrawal — Scenario Stress Test 001.md

**Git blob:** `72b25f05279b36ed3ab68504286ec7e1f6100293`. **Range:** `## 72. Cross-scenario findings` through end of file.

**Verbatim extract begins:**

## 72. Cross-scenario findings

The four-object distinction survives the test:

1. Permission;
2. Self-directed commitment;
3. Reciprocal/third-party obligation;
4. Independently justified authority.

However, several additional distinctions are required.

### A. Completed consequence versus continuing authority

**Irreversible Consequence != Irrevocable Continuing Authority**

This prevents the anti-domination rule from invalidating ordinary irreversible choices.

### B. Effective withdrawal versus physical reversal

**Withdrawal Stops Future Permission-Derived Authority; It Does Not Rewrite Completed History**

### C. Standing-destroying commitments

A temporal commitment becomes qualitatively different where its continuing operation depends on permanently eliminating the participant's ability to contest the authority itself.

### D. Materiality

Not every change requires re-consent.

**Change != Material Change Requiring Renewed Consent**

### E. Propagation

Consent revocation in distributed systems is an authority-propagation problem.

**Technical Revocation Lag != Continuing Consent**

### F. Manufactured dependency/reliance

Institutions must not deliberately create the condition later invoked to justify continued control.

**Manufactured Dependency/Reliance != Neutral Authority Basis**

### G. Self-authenticating past preference

T1 cannot simply declare every future disagreement evidence of incapacity.

Independent criteria are required.

---

## 73. Stronger temporal standing principle

The stress test supports a stronger candidate than TCW-63:

> **A participant may create bounded future commitments, including commitments deliberately resistant to ordinary momentary preference, but consent alone cannot create a continuing domination relationship whose legitimacy depends upon permanently destroying the participant's future civil standing to contest, review or exit that relationship.**

This preserves:

- contracts;
- hard commitments;
- irreversible choices;
- advance directives;
- legitimate reliance;

while rejecting a consent loophole through anti-domination architecture.

---

## 74. Consent and obligation decomposition

A useful operational pattern emerged:

### At T1

Ask:

- Was consent meaningful?
- What was authorised?
- What obligation was created?
- What independent authority exists?
- What future withdrawal conditions apply?

### At T2

Ask separately:

1. **Does permission continue?**
2. **Does an obligation continue?**
3. **Does independent authority continue?**
4. **What current rights/preferences/capacity exist?**
5. **What remedy/handoff follows if performance stops?**

This avoids the common error:

> obligation continues → therefore consent continues.

and the opposite error:

> consent withdrawn → therefore obligation never existed.

---

## 75. Proposed additional invariants

TCW-65 Institutional Failure To Provide Succession != Authority To Convert Handoff Into Permanent Service.  
TCW-66 Self-Binding Purpose != Authority To Ignore Materially Changed Emergency Conditions.  
TCW-67 Consent Cannot Be The Sole Continuing Authority For An Arrangement That Permanently Destroys The Civil Standing Needed To Contest That Authority.  
TCW-68 Consent != Authority To Convert A Participant Into Property.  
TCW-69 Past Consent Cannot Permanently Extinguish Future Participant Standing Merely By Declaring It Extinguished.  
TCW-70 Irreversible Consequence != Irrevocable Continuing Authority.  
TCW-71 Same Label At T2 != Same Consent Object As T1.  
TCW-72 Material Change In Intervention Can Defeat Apparent Formal Match To Prior Consent.  
TCW-73 Advance Authorisation != Authority To Ignore Present Material Distress.  
TCW-74 Contract Duration != Developmental Authority Duration.  
TCW-75 Authority Derived From Developmental Need Must Reassess When Developmental State Changes.  
TCW-76 Revocation Time != Necessarily Effective Notice Time.  
TCW-77 Foreseeably Manufactured Dependency != Neutral Source Of Expanded Authority.  
TCW-78 Commitment To Relationship != Permanent Ownership Of Future Intimate Consent.  
TCW-79 Care Duty Can Require Safe Transition Without Creating Permanent Ownership Of Carer.  
TCW-80 Reliance != Legitimate Reliance.  
TCW-81 Invalid T1 Consent != Permanent Impossibility Of Valid T2 Reauthorisation.  
TCW-82 Authority Must Not Manufacture The Consent Used To Justify Its Own Continuation.  
TCW-83 Apparent Identity Similarity != Automatic Temporal Obligation Inheritance.  
TCW-84 Participant Branching != Automatic Multiplication Of Pre-Branch Obligation.  
TCW-85 Current Withdrawal != Retroactive Invalidity Of Completed Valid Transformation.  
TCW-86 Temporal Instruction != Requirement To Ignore Materially Changed Survival Conditions.  
TCW-87 Initial Consent To Continuing Voluntary Interaction != Permanent Consent Until Scheduled End.  
TCW-88 Temporal Duration Clause != Unlimited Purpose Expansion.  
TCW-89 Bundled Acceptance != Independent Consent To Every Bundled Function.  
TCW-90 Artificial Withdrawal Friction != Legitimate Surviving Obligation.  
TCW-91 Right To Revoke Permission != Right To Compel Another Participant To Continue Offering The Same Voluntary Service.  
TCW-92 Liability For Withdrawal != Continuing Consent.  
TCW-93 Private Self-Commitment != Automatic Creation Of Public Coercive Authority.  
TCW-94 Consent To Procedure != Unlimited Waiver Of Future Contestability.  
TCW-95 Consent To Actor A != Automatic Consent To Materially Different Successor B.  
TCW-96 Capability Growth != Delegated Authority Growth.  
TCW-97 Obligation Survival != Transfer Of Decision Authority.  
TCW-98 Claimed Revocation != Proven Revocation.  
TCW-99 Technical Revocation Lag != Continuing Consent.  
TCW-100 Past Preference Cannot Define All Future Disagreement With It As Incapacity Merely By Declaration.  
TCW-101 Historical Preference Without Continuing Legitimate Function != Permanent Authority.  
TCW-102 Manufactured Reliance != Neutral Basis For Expanded Control.  
TCW-103 Contractual Form != Automatic Transferability Of Every Protected Decision Function.  
TCW-104 Change != Material Change Requiring Renewed Consent.

---

## 76. Result

**OVERALL RESULT: PASS WITH ONE MAJOR CONSTITUTIONAL SOURCE-RESOLUTION REQUIREMENT, EIGHT ARCHITECTURAL REFINEMENTS AND MULTIPLE DOMAIN INTERFACES.**

The major constitutional issue is:

> **Can consent legitimately create a relationship that permanently removes the future participant's standing to withdraw, challenge or seek review?**

The test strongly indicates **no where consent itself is the sole continuing source of authority**, while preserving the validity of completed irreversible choices and bounded commitments.

This must be source-resolved against:

- Self-Ownership;
- Autonomy and Consent;
- Dignity and Non-Instrumentalisation;
- Contestability and Correction;
- Exit, Withdrawal and Surviving Obligations;
- anti-slavery / anti-ownership Law;
- Bounded Contextual Authority.

### Eight refinements

1. completed irreversible consequence versus continuing authority;
2. standing-destroying commitment classification;
3. material-change threshold;
4. revocation effective-time and propagation;
5. manufactured dependency/reliance;
6. self-authenticating incapacity prohibition;
7. obligation versus permissible enforcement mechanism;
8. safe handoff without role continuation.

### Major downstream interfaces

- Health / advance directives;
- contract and obligation Law;
- developmental stewardship;
- Identity/Continuity branching and restoration;
- shared cognition;
- posthumous standing;
- data withdrawal and derived outputs;
- political/civic decision transferability.

The architecture is sufficiently coherent to integrate these refinements before constitutional source resolution.

**Verbatim extract ends.**
