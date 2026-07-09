# Loop Instructions — EASCO

> Instructions for running Claude Code in autonomous loop mode.
> Use when you want to produce multiple pages in a continuous session without manual intervention per page.

---

## How to Start a Loop

```
/loop
```

When asked "agent mode or manual mode?" — respond: **agent**

---

## What Happens Each Loop Iteration

1. Read `_system/execution-plan.md`
2. Find the first unchecked task (🔲) in phase order
3. Read all pre-work files (WritingSystem.md, client-data-map.md, differentiator-card.md, objection-map.md, buyer-segment-table.md)
4. Read the appropriate template
5. Present section outline to user — wait for confirmation before writing
6. Write page section by section, running Tier 1 checks after each section
7. Run five-pass review (A → B → N → D → C)
8. Add pass log header to page file
9. Update `_system/progress.md` to ✅
10. Commit: `[WRITE] filename.md — five-pass complete`
11. Push to main
12. Stop — report completion and wait for next loop trigger

---

## Loop Stops When

- A page requires client data that is marked ⚠️ in client-data-map.md
- A page is blocked (waiting for assets or references)
- User interrupts

---

## Loop Does NOT

- Skip the section outline confirmation step
- Write multiple pages per loop iteration
- Edit any file that the user has not confirmed
- Use any unverified number or claim

---

## Recommended Loop Cadence

One page per session. Each page takes approximately:
- Phase 1 (core static): 45–60 min
- Phase 2–7 (silo pages): 30–45 min per cluster, 60–90 min per pillar
- Phase 8 (legal/legal): 20–30 min

---

## Resuming After a Break

When resuming:
1. Read `_system/progress.md` to find current status
2. Read `_system/execution-plan.md` to find next unchecked task
3. Continue from next 🔲 task
