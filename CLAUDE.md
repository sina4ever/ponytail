# Ponytail

Rules live in @AGENTS.md. Follow them.

- Test: `npm test` (node --test tests/*.test.js, then pi-extension tests).
- Many per-tool dirs (`.cursor`, `.kiro`, `.windsurf`, ...) carry copies of the rules; `scripts/check-rule-copies.js` and `scripts/check-versions.js` keep them in sync. Edit the source, then run them. Do not grep across all dirs.
- Read only the file you need. README.md and INSTALL.md are large; skip them unless the task is docs.
