# V1.3 → V1.4 Migration and Architecture Reconciliation

The [complete V1.3 snapshot inventory](./Full%20V1.3%20Snapshot%20Inventory.md) is the central source-file register for this migration.

It includes **all 1,718 files** from the user-supplied V1.3 ZIP snapshot, including 1,473 Markdown documents and supporting code, workflows, data, and images.

## Status codes

| Code | Meaning | Next action |
|---|---|---|
| **M** | Migrated, source/destination SHA verified in prior migration work | No action unless content review reveals a conflict |
| **D** | Development/archive triage (source path or metadata) | Retain V1.3 provenance; examine for unextracted living results as needed |
| **R** | Possible living architecture, foundational reasoning, implementation or interface | Check current V1.4 coverage; migrate only already-adopted unchanged material; otherwise open development work item |
| **U** | Classification unresolved | Inspect and classify |

**Important limitation:** These are first-pass triage flags. The destination V1.4 recursive tree was not available to the inventory generator. **R and U do not mean missing**. **D is not proof that no living architectural result remains inside the document**. Some M records were verified during prior passes, but most known living copies still need explicit inventory hash annotation.

## Rules for ongoing updates

1. Preserve each original V1.3 source path in the inventory.
2. Record the V1.4 destination path, Git blob SHA verification, and integration outcome when checked.
3. If a D document contains unincorporated living architecture, change its status to R and open a scoped note under `06_Development/` matching the intended destination.
4. Never copy old developmental versions wholesale into operational folders. Reconcile with the current architecture and carry forward only the living result.
5. Keep foundational WHY documents, guides, book, and ethical justification in scope even when non-operational.
6. Do not edit the V1.3 source repository.
7. Reconcile the full destination tree before declaring migration complete.

**Snapshot limitation:** this register describes the provided V1.3 ZIP, not an independently confirmed live V1.3 branch state. Differences discovered later should be recorded explicitly.
