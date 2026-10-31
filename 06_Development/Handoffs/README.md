# Concord Development Handoff System

## Purpose
This is the persistent coordination layer for AI development instances. Conversation history is supplementary; GitHub files and verified commits are the durable state.

## Layout
- `Active/<task-id>/HANDOFF.md`: current objective, boundaries, source references, verified checkpoint, next exact action, blockers.
- `Active/<task-id>/PROGRESS.md`: append-only dated checkpoint journal with paths, commits, verification and remaining scope.
- `Completed/<task-id>/`: completed handoff and journal, archived without losing developmental provenance.

## Start or resume protocol
1. Read root `AI_DEVELOPER_NOTES.md`, this README and the task's HANDOFF and PROGRESS.
2. Read referenced registers and relevant source files. Check the latest GitHub state and commits; prior assistant statements are not verification.
3. Establish a precise checkpoint: last completed operation, paths, source hashes, outstanding work, and the next safe action.
4. If repository state differs from the handoff, document the discrepancy and reconcile it before edits. Do not overwrite another instance's work.
5. Work within the task's authorised scope. For architectural recovery, preserve first, reconcile second; do not edit operational documents.

## Checkpoint protocol
- After each meaningful batch or set of commits, update PROGRESS and then HANDOFF.
- Record exact commit SHA, affected paths, source-to-destination verification, incomplete operations and next action.
- Keep checkpoints small enough that a sudden instance limit does not erase an entire pass.
- Never report an attempted operation as complete until GitHub confirms it. Record failed/blocked actions explicitly.
- Keep an append-only record; do not silently rewrite historical checkpoints.
- If parallel instances work, give each a separate task ID or clearly divided scope. Never concurrently update the same task file without checking its latest SHA.

## Completion protocol
Verify deliverables and scope; mark the task complete; archive the final HANDOFF and PROGRESS under Completed with their history intact. Update root developer instructions or an index to the archive as appropriate. Do not delete the developmental record before verifying the archived copy.

## Operational boundary
This is a development coordination mechanism, not a grant of governance authority or a change to Concord's operational architecture.
