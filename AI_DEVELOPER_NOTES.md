# AI Developer Notes — Concord V1.4

## GitHub command execution

**Use single GitHub commands, not compound commands.** Execute each repository operation separately, including file creation, update, deletion, move, commit, and directory setup. Do not combine multiple GitHub operations into one shell command or chained command sequence. This reduces safety-block interruptions and makes each change independently auditable.

If a command is blocked, retry the intended operation as an individual command rather than bundling it with other operations. Never treat a blocked or failed command as completed; verify the resulting repository state.

## Migration boundary

Concord V1.4 contains the **living Concord**, including foundational justification and explanatory material (the Concord book, WHY corpus, ethical kernel, Front Door, human and AI guides) as well as current operational architecture. A foundational document is not excluded merely because it is philosophical, educational or non-operational. Development material, working records, tests and historical drafts remain in Concord V1.3 for provenance and later examination. Copy living foundational and operational source material without altering V1.3, and verify completeness before claiming migration success.

## Verbatim living-framework migration — no editing during transfer

Copy each living foundational or current operational document from Concord V1.3 to V1.4 **verbatim**, even where it contains development commentary, unresolved questions, or material that will require later cleanup. Do not edit, extract, omit chapters, renumber, reconcile, consolidate, or rewrite operational documents during migration. Separate development-only documents and work folders are excluded, but embedded material remains part of its operational source document until a later dedicated editorial pass. Verify copied files against their V1.3 source using content hashes where available. Preserve V1.3 untouched. Editorial cleanup in V1.4 is a subsequent, distinct workstream.

## Ethical provenance boundary

*Unified Paths of Light* remains in V1.3 as the large developmental and comparative source corpus that informed Blainey's Laws. V1.4 retains Blainey's Laws as the authoritative ethical kernel and provides a concise origin reference in the Constitutional Core README; it does not import the Unified Paths corpus or its research README.

## Persistent task handoff

Before resuming architectural recovery, read [the active recovery handoff](06_Development/ACTIVE_ARCHITECTURAL_RECOVERY_HANDOFF.md), the Development README and the relevant recovery registers. Verify the repository state before proceeding. Update the handoff with the last verified commit, completed source families, outstanding work, and the next exact action at each task boundary. When completed, archive the handoff in Development/Completed while retaining provenance, and update this pointer. Do not treat conversation memory as a substitute for the GitHub handoff.
