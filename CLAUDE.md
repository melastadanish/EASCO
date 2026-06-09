# CLAUDE.md — EASCO Content Repository

## Session Start

Ask the user: **"Agent mode or manual mode?"**

- **Agent mode** — Read `_system/execution-plan.md`, identify the first unchecked task, complete it through the full 5-pass review, update `_system/progress.md`, commit, and stop.
- **Manual mode** — Await user instruction for which page to work on.

---

## Pre-Work Requirements (Every Session)

Before writing any page, read these files in order:

1. `_system/WritingSystem.md` — brand voice, copy rules, quality system
2. `_system/client-data-map.md` — every spec number must be verified here before use
3. `_system/differentiator-card.md` — minimum 2 differentiators per page
4. `_system/objection-map.md` — Pass C objection coverage test
5. `_system/buyer-segment-table.md` — primary segment for the page being written
6. The matching template for the page type:
   - Pillar page → `templates/pillar-page-template.md`
   - Cluster page → `templates/cluster-page-template.md`
   - Product page → `templates/product-page-template.md`
   - Other page → `templates/other-page-template.md`

---

## Page Development Workflow

### Step 0 — Brief
- Identify primary buyer segment from `_system/buyer-segment-table.md`
- Map keyword slot from `seo/keyword-master-list.md`
- Confirm section outline — present to user for approval before writing

### Step 1 — Write
- Write all sections following the template structure
- Run Tier 1 checks (5 inline checks) after every section before moving to the next
- Do not show a section to the user until all 5 Tier 1 checks pass

### Step 2 — Five-Pass Review
After the full page is compiled, run all five passes in sequence:
- **Pass A** — Full-page quality audit (6 dimensions, scored)
- **Pass B** — Surgical rewrite (fix Pass A failures only)
- **Pass N** — NLP semantic coverage (access control terminology completeness)
- **Pass D** — E-E-A-T / GEO check (AI-quotable paragraph, FAQ, authority signals)
- **Pass C** — Conversion review (6 tests, objection coverage, AI-written score ≤15%)

### Step 3 — Save & Track
- Add pass log header to top of the page file
- Update status in `_system/progress.md` to ✅
- Commit with message format: `[WRITE] filename.md — five-pass complete`
- Push to main

---

## Commit Format

```
[WRITE] path/to/filename.md — five-pass complete
```

One page per commit. Main branch only. No feature branches.

---

## Quality Gate

A page is NOT complete until:
- [ ] All 5 Tier 1 checks passed per section
- [ ] Pass A score ≥ 8.0/10 overall
- [ ] Pass B fixes applied
- [ ] Pass N: all mandatory access control terms verified present
- [ ] Pass D: AI-quotable paragraph written, FAQ with 5+ Q&As present
- [ ] Pass C: all 6 tests passed, AI-written score ≤ 15%
- [ ] All numbers traced to `_system/client-data-map.md`
- [ ] Minimum 2 differentiators from `_system/differentiator-card.md` explicit
- [ ] Applicable objections from `_system/objection-map.md` covered
- [ ] Pass log added to page file header
- [ ] `_system/progress.md` updated to ✅
- [ ] Committed and pushed

---

## Key Reference Files

| File | Purpose |
|---|---|
| `_system/WritingSystem.md` | All writing rules, copy standards, quality system |
| `_system/client-data-map.md` | Single source of truth — all verified product specs |
| `_system/differentiator-card.md` | EASCO vs ZKTeco / Hikvision / Generic Alibaba |
| `_system/objection-map.md` | 20 buyer objections + spec-backed answers |
| `_system/buyer-segment-table.md` | 5 buyer segments — pain, drivers, messaging angle |
| `_system/competitors.md` | Competitor positioning reference |
| `_system/execution-plan.md` | Phased task queue — all 60+ pages |
| `_system/progress.md` | Completion tracker — current status of every page |
| `_system/reusablesections.md` | Reusable section library |
| `seo/keyword-master-list.md` | Keyword clusters by silo |
| `design.md` | Visual / layout decisions for developers |
