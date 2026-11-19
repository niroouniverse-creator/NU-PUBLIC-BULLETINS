# Mandatory repository anti-destruction instructions

These instructions apply to every AI model, coding agent, bot, script and contributor operating in this repository. The latest direct user instruction is the strict authority for task scope.

## Explicit scope lock
- Change only the feature/files explicitly named by the user and proven direct dependencies. If asked to fix one animal, do not touch the other animals: no adjacent refactors, restyling, renaming, migration, optimization, dependency upgrades or speculative cleanup.
- Before any write, record exact in-scope paths, forbidden areas, baseline commit/checkpoint and minimum change budget. Inspect the proposed diff and remove all unrelated changes.
- Preserve unrelated work, files and data. Never reset the whole repository, force-push or perform a broad rollback for a scoped request. Roll back only named paths from a verified checkpoint.
- If scope, ownership, dependency or recovery cannot be verified, stop before writing. An unexpected diff or unrelated regression is a stop condition.
- Run focused tests and report exact changed paths, checkpoint, machine results, deployment/read-back and human QA separately. Do not claim branch protection unless verified in GitHub settings.
- For a scoped task, this lock overrides generic inventory-first wording to the extent that it would widen the change. Inspect only direct dependencies. Cross-repository discovery is required only when the user explicitly requests cross-repository work or a shared dependency is demonstrated.
- Further development outside the current lock requires a new explicit, focused user instruction.

## Canonical protocol
https://github.com/mobinabinshun-beep/mobinabinshun-beep/blob/11279ea003fc001b2ccc5a014e32cc664134cd3c/docs/operations/ANTI-DESTRUCTION-EXPLICIT-SCOPE-PROTOCOL-2026-11-19.md
