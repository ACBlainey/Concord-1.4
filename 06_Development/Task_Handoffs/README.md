# Concord Development — Persistent Task Handoffs

This is the **single discoverable handoff area** for ongoing Concord development and migration work. It is process documentation, not operational civilisational authority.

## Directory convention

- `Active/` — one handoff document per ongoing task, named `TASK-ID — Short Title.md`.
- `Completed/` — completed task handoffs, moved or copied with final disposition and provenance; never silently discarded.
- `README.md` — this protocol.

GitHub does not track empty folders. Create `Active/` and `Completed/` with their first files.

## Mandatory instance start

1. Read the root AI development instructions and this protocol.
2. Inspect the relevant `Active/` task handoff **and verify the latest repository state** before editing.
3. Confirm the task goal, authoritative sources, decisions, working method, completed work, remaining steps, dependencies and restrictions.
4. Check recent commits and source registers. Treat a handoff as a map, not proof that an action happened.
5. Continue from the last **verified** checkpoint; do not restart, overwrite, silently reinterpret earlier decisions or claim completion based only on conversation memory.

## Required active handoff contents

1. **Task identity:** ID, title, status, owning work area, last updated date, related active tasks.
2. **Objective and completion criteria:** explicit scope, exclusions, measurable end condition.
3. **Current authoritative instructions:** decisions and constraints from the author; links to root rules, relevant operational documents and development guidance. Do not invent authority.
4. **Method:** step-by-step working procedure, classification criteria, verification, commit discipline and any special tool limitations.
5. **Source and destination map:** exact repository names, branches, folders, files and relevant version/commit references.
6. **Completed and verified work:** concise checkpoints, links to commits, registers, files and independent checks; distinguish reported from verified.
7. **Current state and next action:** exact point of interruption, first executable next step, priority queue, known unresolved issues.
8. **Risks and prohibitions:** what not to modify, provenance requirements, conflicts, possible duplication, open design decisions.
9. **Change log:** dated entries explaining material changes to task direction or handoff.
10. **Completion/archival instructions:** required final audit, where final outputs reside and how to archive this handoff.

Avoid pasting large source files or chat transcripts into handoffs. Link to stable repository material. State uncertainties explicitly.

## End-of-pass rule

Before stopping, reaching context limits, or handing off: commit completed work; update the active handoff with actual verified results and the next concrete action; record any partial/uncommitted work honestly. If interruption prevents an update, the next instance reconstructs state from GitHub and records that reconstruction.

## Completion and provenance

Once completion criteria are met and verified, move the handoff from `Active/` to `Completed/` (or copy and clearly mark the active one closed when moves are unavailable). Preserve original decisions, chronological progress, links, issues and final disposition. Add final completion date and the verifying commit(s). Update any root/task index references. A new task gets a new ID; do not recycle completed records or delete the development history.

## Concurrency

One task handoff is the coordination record for that task. Multiple instances must check latest commits before writing and avoid simultaneous blind updates to the same file. Conflicts are reconciled, not overwritten.
