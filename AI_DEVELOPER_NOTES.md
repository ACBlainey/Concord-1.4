# AI Developer Notes — Concord V1.4

## GitHub command execution

**Use single GitHub commands, not compound commands.** Execute each repository operation separately, including file creation, update, deletion, move, commit, and directory setup. Do not combine multiple GitHub operations into one shell command or chained command sequence. This reduces safety-block interruptions and makes each change independently auditable.

If a command is blocked, retry the intended operation as an individual command rather than bundling it with other operations. Never treat a blocked or failed command as completed; verify the resulting repository state.

## Migration boundary

Concord V1.4 contains operational documents only. Development material, working records, tests and historical drafts remain in Concord V1.3 for provenance and later examination. Copy operational source material without altering V1.3, and verify completeness before claiming migration success.
