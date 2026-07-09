# CLAUDE.md — Router

> Full workflow: `_system/INSTRUCTIONS.md` | Durable facts: `_system/MEMORY.md`

## Session Start
Ask: **"Agent mode or manual mode?"**
- **Agent** — read `_system/execution-plan.md`, do next unchecked task per
  `_system/INSTRUCTIONS.md`, update `_system/progress.md`, commit, stop.
- **Manual** — await user's page choice, then follow `_system/INSTRUCTIONS.md`.

## Before Writing Any Page
Read: `_system/WritingSystem.md`, `_system/client-data-map.md`,
`_system/differentiator-card.md`, `_system/objection-map.md`,
`_system/buyer-segment-table.md`, `_system/sitemap.md`, then the matching
template (type→template map in `_system/MEMORY.md`).

## Commit Format
`[WRITE] path/to/filename.md — five-pass complete`
One page per commit. Main branch only.

Full 5-pass steps + quality gate + architecture: `_system/INSTRUCTIONS.md`.
