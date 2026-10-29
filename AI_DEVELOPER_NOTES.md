# AI Developer Notes — Concord V1.4

## GitHub command execution

**Use single GitHub commands, not compound commands.** Execute each repository operation separately, including file creation, update, deletion, move, commit, and directory setup. Do not combine multiple GitHub operations into one shell command or chained command sequence. This reduces safety-block interruptions and makes each change independently auditable.

If a command is blocked, retry the intended operation as an individual command rather than bundling it with other operations. Never treat a blocked or failed command as completed; verify the resulting repository state.

## Migration boundary

Concord V1.4 contains operational documents only. Development material, working records, tests and historical drafts remain in Concord V1.3 for provenance and later examination. Copy operational source material without altering V1.3, and verify completeness before claiming migration success.

## Verbatim operational migration — no editing during transfer

Copy each current operational document from Concord V1.3 to V1.4 **verbatim**, even where it contains development commentary, unresolved questions, or material that will require later cleanup. Do not edit, extract, omit chapters, renumber, reconcile, consolidate, or rewrite operational documents during migration. Separate development-only documents and work folders are excluded, but embedded material remains part of its operational source document until a later dedicated editorial pass. Verify copied files against their V1.3 source using content hashes where available. Preserve V1.3 untouched. Editorial cleanup in V1.4 is a subsequent, distinct workstream.
