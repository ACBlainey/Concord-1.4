# Recovered Architecture — Participation-Bounded Knowledge Retrieval and Embedded Wrappers

**V1.3 sources:** `02_Domains/03_Research/Active_Development/Participation_and_Intelligence/Knowledge Retrieval Through Contextual Wrappers — Architecture Integration Note 001.md`; `Embedded Contextual Wrappers for Knowledge Sections — Design Resolution 001.md`. The earlier `NEXT STEP — Participation-Bounded Retrieval Envelopes for Concord Knowledge.md` is a developmental handoff and is not itself a final design.

**Disposition:** substantive cross-domain architecture recovered into V1.4 Development. It is not a deployed access-control mechanism and does not silently restrict existing public repository files.

## 1. Problem and authoritative object

The repository's domain structure answers where knowledge belongs, not who may retrieve a given semantic region for a particular purpose. File-level public/private classifications are too coarse where one document contains public rights, specialist procedures and sensitive personal or security information.

Keep **one authoritative versioned knowledge object**, divided into stable semantic regions. Apply contextual access wrappers to the relevant regions. A retrieval view is a transient derived product, not a duplicate authoritative document.

**Wrapper around knowledge != copy of knowledge.**

## 2. Embedded wrapper resolution

The preferred design stores the authoritative access classification *with the source material itself*, at document, section, subsection or other stable semantic-region level. When a region is moved during migration, its classification should move with it.

**Content + access boundary = one versioned knowledge object. Move the knowledge → move its wrapper.**

External indexes, access tables, search maps and caches remain useful but are **derived and non-authoritative**. Their state must be invalidated/rebuilt when the source or wrapper changes.

## 3. Context resolution

A retrieval decision composes source wrapper, nested overrides, participant and role context, legitimate function, purpose, relevant authority, sensitivity, temporal state and applicable constitutional transparency constraints.

Participation tier alone is not permission, and role alone is not general authority. Use Contextual Wrapper Architecture for precedence, Minimum Necessary Capability for justified scope, Knowledge Control System for provenance and state, and bounded authority/CBPR for consequential action.

Both **positive exposure** (what a participant should be able to obtain) and **restrictions** must be represented. Do not use broad secrecy to defeat public accountability or the participant's ability to challenge decisions.

## 4. Execution and provenance

Retrieval must enforce the wrapper before exposing protected content; it cannot rely only on an AI evaluator voluntarily withholding material after reading it.

The resulting view should preserve document/version identity, semantic-region identity, applicable wrapper state, retrieval context, omissions where safely disclosable and source provenance. A derived view does not become a new independent source of authority.

## 5. Integrity, migration and unresolved design

Wrapper changes must be versioned and traceable. Stable semantic addresses should survive moves and renames where possible. A source move must not silently strip an access boundary. Nested wrapper precedence, conflict handling and dynamic participant state need explicit rules.

**To be designed/finalised:** wrapper grammar; human/machine-readable embedded syntax; conflict/precedence semantics; fail-closed versus fail-open treatment for different consequence classes; safe omission notices; legacy corpus conversion; authentication and authorisation runtime; cache invalidation; appeals and public accountability.

Do not retroactively label all currently public files restricted without an explicit, authorised publication/access decision.

## 6. Why this is recovered

The embedded-wrapper choice is a developed architectural resolution, not just a suggested next step. It avoids copying governance, judiciary and other domain documents into multiple tier-specific versions, thereby preserving the Concord migration rule: **migrate the living result; archive the developmental path**.

The V1.3 source-resolution notes and handoff remain provenance; this recovered result requires later reconciliation with existing portable modules and operational domain access obligations.
