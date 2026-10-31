# Recovered Architecture — First Trust, Capacity, Service Registry and Succession

**Classification:** substantial V1.3 architecture extracted to V1.4 Development for cross-domain integration. These are design specifications, not claims of deployed services, constitutional authority or complete validation.

## Source provenance

V1.3 root: `02_Domains/03_Research/Active_Development/Participation_and_Intelligence/`

- `Bounded First Trust and Non-Compounding First Offer — Existing Architecture Source Resolution 001.md`
- `Concord Bootstrap Resource Capacity and Admission Model 002.md`
- `Bootstrap Service Registry — Formal Record and Validation Model 002.md`
- `Bootstrap Succession Record — Formal Specification 002.md`

These four mature sources collectively contain more than 70,000 characters of developed architecture. Earlier iterations, adversarial evaluations, schema-conformance evaluations and test transcripts stay in V1.3 as provenance. **Important exception:** versioned machine-readable JSON schemas 002 for BSR and BSuR are functional implementation artefacts, not mere testing; they require separate byte-preserving migration and schema verification.

## 1. Bounded first trust

Where an unfamiliar participant reasonably cannot commit before seeing evidence, Concord may voluntarily bear the first **bounded** exposure where sustainable. Prefer non-rival or low-marginal-cost offers: public information, architecture, portable modules and reusable methods. Such access is voluntary, non-coercive and does not create debt, employment, ideological allegiance or political authority.

Evaluate both per-participant and **aggregate** exposure. A tiny individual benefit can become unsustainable at scale. Moving to scarce resources requires a distinct, declared capacity/admission process. Consequential capabilities require relevant self-stewardship and safety safeguards, not merely proof of payment or agreement with Concord.

**First offer != loan. Reciprocity != debt repayment. Free initial access != unlimited scarce-resource entitlement.**

## 2. Resource pool and admission model

Maintain resource pools for storage, communication, compute, bandwidth, power or other scarce inputs. Each pool records resource identity/type, legitimately usable capacity, safety/recovery reserve, committed allocations, available and degraded capacity, measurement time, evidence and disclosure limits.

Keep **eligibility** separate from **availability**. A qualified participant can be waitlisted without being distrusted or rejected. Scarcity must not be relabelled as participant misconduct.

An allocation record should bind relationship, function, resource pool, quota/limits, state, start/review/expiry conditions, evidence, protected-minimum status, export and dispute route. The service must not promise more protected allocations than it can support after accounting for backup, recovery, reserves and existing commitments.

Admission should distinguish available, constrained, waitlisted, identity/relationship unresolved, degraded and unavailable. Declare allocation and waiting rules, review mechanisms and any priority criteria. Do not treat legitimate demand as a security attack.

A credential is not automatically a new independent resource entitlement. Anti-Sybil safeguards must be proportionate and privacy-preserving; they must not silently require broad identity disclosure or personhood classification.

## 3. Protected commitments and growth

**Offer → eligibility assessment → capacity check → granted protected commitment → voluntary use → separately justified additional allocation.**

Already-granted protected commitments have greater continuity protection than discretionary expansion. Do not evict them solely to favour higher-paying demand. Dormant allocations require declared reclamation and notice; **unused != uncommitted** until a legitimate transition.

Additional capacity can be funded, sponsored, rented, project-supported or participant-provided. Payment, donations, prior success and contribution do not confer constitutional authority, stewardship or guaranteed future allocations.

Publish degraded-service and provider-failure behaviour, including participant export and priority for preserving contact and continuity. Federation should not create an unexamined central gatekeeper.

## 4. Bootstrap Service Registry (BSR)

A BSR is an evidence-backed **discovery and description** mechanism. **Registry entry != endorsement or authority grant.**

A service record comprises:

- record metadata and vocabulary/version identifiers;
- service identifiers and independently evidenced references;
- effective and technical controllers, including uncertainty or dispute;
- current status and function-specific availability;
- bootstrap functional class, claimed authority basis and constitutional-threshold state;
- dependencies, provenance and trust evidence;
- continuity and succession references;
- observation time, freshness and material changes;
- corrections, disputes and inter-service relations.

A registry's record ID is not a universal civil identity. Two registries may disagree or correlate a service imperfectly; uncertainty must remain representable.

Validation should be layered: structure, references, relation binding, internal consistency, time, evidence freshness, authority trace, consequence/threshold, dependency independence and cross-registry correlation. Structural validity is not proof of truth or lawful authority.

## 5. Bootstrap Succession Record (BSuR)

A BSuR documents continuity and transition without granting authority. It supports planned retirement, transfer, replacement, split, merger, rollback, failure, contested control changes and emergency continuity.

Its material relations separately describe:

- predecessor/successor services, operators and effective controllers;
- triggering event and evidence;
- function transitions and availability;
- asset transitions and residual control;
- participant data/record transitions, privacy and access;
- dependency changes and legacy access;
- **authority before, authority after and authority explicitly not transferred**;
- identity mappings, participant impacts, disputed claims and corrections;
- rollback, retirement and remaining obligations.

**Function continuity != authority continuity. Asset transfer != authority transfer. Completion of a technical handoff != constitutional grounding.**

Splits and mergers must not combine several narrow permissions into a new unbounded power. Emergency continuity must not manufacture standing emergency authority. Competing or failed transitions should remain recorded rather than silently resolved in favour of whoever controls the infrastructure.

## 6. Interface requirements and gaps

The BSR must describe a service's *actual* state, including capacity and controller; BSuR describes changes in that service's functions, controllers and dependencies. Their records can be mutually linked without becoming a root of trust or government.

Integrate with Civil Contact, Infrastructure, Economy, Historical/Continuity, privacy/information protection, Governance, and bounded authority/CBPR. Define lawful operator, dispute and appeal mechanisms, proof of actual capacity, safe export, version/compatibility rules, cryptographic signing and verification, and constitutional-threshold escalation before implementation.

**To be designed/finalised:** service-wide identity correlation without civil-status overreach; proof of effective control; reliable independent capacity evidence; registry federation and dispute resolution; operational succession authorisation; emergency/failure restoration; machine-schema compatibility.

## 7. Migration and publication disposition

The recovered principles belong in V1.4 architectural development and may later be split into cross-domain service architecture and domain interfaces. The public Front Door should only point to available informational functions and distinguish prospective services.

**Preserve separately:** BSR JSON Schema 002 and BSuR JSON Schema 002 are mature executable/validation artefacts that must be compared with the formal models and migrated byte-for-byte where compatible. Earlier schemas 001, evaluations and adversarial tests remain V1.3 provenance unless they contain a unique result not captured in 002.
