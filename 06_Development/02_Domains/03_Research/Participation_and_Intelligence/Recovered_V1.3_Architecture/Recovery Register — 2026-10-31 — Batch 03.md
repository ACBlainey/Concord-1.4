# V1.3 Recovery — Schema Amendments and Remaining Participation Papers

**Date:** 31 October 2026. **Batch:** 03. **Rule:** Preserve first; reconcile second.

## Newly preserved participation source

`Disability and AI.md` is now [preserved intact](Disability%20and%20AI.md), 11077 bytes, verified Git blob `e4466603c553048128cd750c2047fca14057d71e`. The paper contains developed reasoning about contribution-based academic assessment, assistive communication and separating work evaluation from author credentials. Intended interfaces include Education, Research, accessibility and provenance. Preservation is not an adoption of every historical/general claim in the paper.

## Remaining paper dispositions

| V1.3 source below Participation_and_Intelligence | Disposition and recovered result |
|---|---|
| AI Evaluator Runtime Self-Identification and Provenance Uncertainty — Research Observation 001.md | Raw observation and investigation proposal remain in V1.3. Retain the method requirement: generated evaluator self-identification is not verified runtime provenance; record external execution metadata where identity matters, with uncertainty where metadata is unavailable. Behavioural similarity and wrong self-identification do not establish cross-model delegation. This is source-derived method guidance, not evidence about current providers. |
| Sketches_and_Hypotheses/Companion_Intelligence, Humour, and Cognitive Development.md | Remains in V1.3 as expressly speculative hypotheses and future experiments, not a developed assessment specification. Do not use the IQ-band, humour or developmental-instability hypotheses as participant classification rules. Revisit if subsequent mature design is found. |

## Schema source and repair-chain reconciliation

Read: BSR Pre-Schema Adversarial Evaluations 001/002; BSR Schema Conformance Evaluation 001; BSuR Pre-Schema Adversarial Evaluations 001/002; BSuR Schema Conformance Evaluation 001, from the same V1.3 source folder. Raw scenario histories remain archived. Their developed model/serialization requirements are retained below.

The existing V1.4 JSON schemas were fetched and their Git blob hashes match the snapshot originals:

- BSR Schema 002: `e6e1b6cec9950b61def4803389d4243abe017e59`.
- BSuR Schema 002: `2bf3f7da697fb3d73c23f558aedf0db619d00605`.

They are at `06_Development/00_Front_Door/Recovered_Schemas/`. The complete semantic source models and semantic-validation rule specifications were already preserved in the earlier batch. No schemas were edited or executed in this pass.

| Source-derived requirement | Targeted inspection of recovered version 002 | Remaining boundary |
|---|---|---|
| BSR per-function binding, partial availability, separate service/registry identities and scoped control | Model 002 preserved; Schema 002 includes FunctionProfile with per-function authority and availability, plus service identity/control definitions. | No claim of complete semantic conformance. |
| BSR preserve unknown vocabulary; separate verification/integrity/freshness/dispute state dimensions; namespace extensions | Schema 002 has vocabularyToken(namespace, version, token, recognition_state), four distinct state definitions and extensionEntry(namespace, version, payload). | Recognition and extension meaning require semantic handling. The four core state definitions are closed enums; future state-space extensibility has not been certified here. recognition_state exists but is not required in the BSR vocabularyToken definition; compare intended validator behaviour before stronger completeness claims. |
| BSuR explicit source/destination relations, scoped authority non-transfer, rollback requiring current authority, component states over summary | Semantic Specification 002 and semantic-validation rules already preserved. Schema 002 has distinct transition definitions and authorityAfter.independent_basis. | A populated basis string, a summary, a merger/split or a rollback does not establish legitimate authority. |
| BSuR restore residual effective intervals and relation effective times | Schema 002 includes residual effective_from_if_known/effective_until_if_known and effective_time in dependency, authority, identity, participant-impact, retirement and record relations. | Presence of a field is not proof of correct or complete runtime temporal treatment. |
| BSuR retain record protection/access/destruction, identity mapping, evidence and disputes | RecordTransition requires the restored protection/access/retention/identity-mapping/effective-time/evidence/dispute fields. | Other relations still permit omission of some evidence/time fields. Check each semantic-source requirement against schema cardinality and semantic-validation rules; do not certify the general D4 repair solely from the record relation. |
| Nullable endpoints, contradictory relations and unknown states must remain representable | Already explicit requirements in the recovered Specification 002 and semantic rules. | Null is not proof of nonexistence; structural acceptance is not semantic acceptance or legitimacy. |
| Downstream implementation | Preserve stable identifier/reference/time formats, current-view derivation rules if implemented, cryptographic/log integrity, transport/discovery, and privacy/legal interfaces. | These remain implementation/design work where not already resolved in their owning architecture. No new registry or succession authority is created. |

This is targeted static inspection tied to the source repair chain, not an independent full conformance audit or a report of new test passes. The observations about optional fields are reconciliation questions, not a finding that the semantic model failed.

## Adjacent architecture recovery

All 26 original Markdown sources from V1.3 `Active_Development/Governance_and_Stewardship/` have now been preserved intact and hash-verified in `06_Development/02_Domains/04_Governance/Recovered_V1.3_Architecture/`. That index maps civil space, authority, identity, evidence, emergency, threat/vector, peaceful-heterogeneity and recursive GTP observation designs to intended interfaces. Cross-domain ownership remains for reconciliation.

## Next work

Continue with adjacent Epistemic Network, civilisational topology and nation-foundation development folders. Review remaining participation evidence only where it contains a unique developed amendment, rather than importing raw testing wholesale. The whole migration and the Participation and Intelligence content audit remain open.
