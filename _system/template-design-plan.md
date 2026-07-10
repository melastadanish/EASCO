# Template Design Plan — Tracking

> Working file for the current template-design pass. Delete or fold into MEMORY.md
> once all templates below are designed, confirmed, and written.

---

## Status Legend
✅ Done and written · 🔲 Not started · 🟡 In progress/discussion

---

## Step 1 — Products

- ✅ Product page template — `Real Products data/product-page-template.md`
- ✅ Category archive page template — `Real Products data/category-archive-page-template.md`
- 🔲 First real product page written for any category
- ✅ First real category archive page written — Aluminum alloy turnstile

---

## Step 2 — Solutions

- ✅ Solutions Hub template — `Real Solutions data/solutions-hub-template.md`
  (Hero → Browse by Industry → CTA → FAQ)
- ✅ Industry single page template (tier 2) — `Real Solutions data/industry-page-template.md`
  (Hero → Browse Other Industries → Challenges → Solutions/Product Grid →
  Why Choose EASCO for [Industry] → Talk to an Expert → CTA → FAQ)
- ✅ Category × Industry sub-page template (tier 3) — `Real Solutions data/category-industry-page-template.md`
  (Hero → Issues in [Industry] (1 paragraph) → Why [Category] Fits [Industry]
  → Relevant Products → Why Choose EASCO (standalone, distinct angle from
  tier 2's version) → FAQ → CTA). 700–1,000 words, deliberately short to
  avoid thin/duplicate content across the 26 sub-pages.
- ✅ `Real Solutions data/` folder skeleton created — 8 industries, 26 sub-page
  placeholders, hub file placeholder (all empty, pending tier 3 template + content)

**Note:** Both templates use a "Browse Other X" grid section instead of a
persistent sidebar filter (changed from the original sidebar concept — see
matching change applied to the category archive page template).

**8 industries confirmed:** Commercial Buildings, Smart Campus, Transportation,
Hospitals, Factories, Government, Hospitality/Hotels, Sports Venues/Stadiums

---

## Step 3 — Case Studies — SKIPPED, not covered in this pass

- ⏸️ Case Study Archive/Hub template (new — `case-studies-hub.md` exists as
  content, no template behind it yet)
- ⏸️ Case Study single page template — old `templates/case-study-template.md`
  assumes real named projects with photos; independent research already
  confirmed no such data exists for any venue type. Live pages instead use a
  leaner 6-section fallback (Hero -> Illustrative Example, explicitly flagged
  as not real -> Common Requirements -> Recommended Products -> FAQ -> CTA).
  Also note: case-study "venue types" (office-buildings, schools, metro,
  airports, shopping-malls...) don't fully match the 8 Solutions industries
  -- worth reconciling whenever this step is picked back up.

---

## Step 4 — Blog

- ✅ Blog Archive/Hub template — `templates/blog-hub-template.md`
  (Banner (H1+description) → Left Sidebar Filter (5 categories + General) →
  Posts Grid (cards) → CTA). Note: uses a real sidebar filter, unlike the
  "Browse Other X" grid pattern used on Solutions/Category pages — hubs
  don't have to match sub-page conventions 1:1.
- ✅ Blog single article template — `templates/blog-template.md` updated:
  dead old-taxonomy links (`/speed-gates/` etc.) replaced with references to
  the 5 real categories, `Silo Link` field replaced with `Related Category`,
  metadata updated to `Slug`/`SEO Title`/`SEO Description`, AI SEO/GEO FAQ
  instructions added. Structure itself unchanged (already solid): Intro/Hook
  → Core Answer → Key Considerations → Comparison/Decision Framework →
  EASCO Perspective → FAQ → Soft CTA.
- ⏸️ Live blog posts (8 articles) still contain the old dead links —
  not fixed yet, template-only pass for now.

---

## Step 5 — Alternatives

- ✅ Alternatives single page template — `templates/alternative-template.md`
  updated: metadata convention to `Slug`/`SEO Title`/`SEO Description`, stale
  `silo pillar` references replaced with `relevant category archive page`,
  `why-choose-us.md` corrected to actual filename `why-us.md`, AI SEO/GEO FAQ
  instructions added. 9-section structure unchanged (already solid, matched
  live `easco-vs-hikvision.md` well).
- ✅ Alternatives Hub template (new) — `templates/alternatives-hub-template.md`
  (Hero → Browse Comparisons (grid, not sidebar — only 4 competitor pages,
  too few to warrant a persistent filter) → CTA)
- ⏸️ Live `alternatives/easco-vs-hikvision.md` still has old `Meta
  Title`/`Meta Description` convention and one dead old-taxonomy link
  (`/palm-vein-iris/`) — not fixed yet, template-only pass for now.

---

## Step 5.5 — Templates Complete

All 5 content-type template pairs (Products, Solutions, Case Studies*, Blog,
Alternatives) are now designed. *Case Studies deferred/skipped per Step 3.
Ready to move to Step 6 (cleanup) whenever confirmed.

---

## Step 6 — Cleanup (confirm before deleting anything)

- ✅ Removed `templates/product-page-template.md` — superseded by
  `Real Products data/product-page-template.md`
- ✅ Removed `templates/product-archive-template.md` — superseded by
  `Real Products data/category-archive-page-template.md`
- ✅ Removed `templates/solution-page-template.md` + `templates/industry-template.md`
  — both superseded by the new Step 2 Solutions templates
- ✅ `templates/other-page-template.md` — kept as-is structurally, only
  metadata convention updated to `Slug`/`SEO Title`/`SEO Description` for
  consistency with the rest of the pass
- ✅ Updated stale Template Map references in `_system/MEMORY.md` and
  `_system/INSTRUCTIONS.md` that pointed at the removed files (now point to
  the correct current templates); also corrected the industries count there
  from 6 to the confirmed 8
- ⏸️ `templates/pillar-page-template.md` + `templates/cluster-page-template.md`
  — tied to deleted `silos/` — DEFERRED, do not touch ("later" per standing
  instruction)

---

## Standing Rules Carried Into This Pass

- Do not write any page content or finalize any template section list before
  confirming with the user.
- No bulleted "Key Features" — alternating image/text paragraph blocks only.
- FAQ sections must carry AI SEO/GEO writing instructions (see product page
  template Section 12 for the canonical wording).
- Avoid duplicate sections across page types (e.g. no "Related Categories"
  where a sidebar filter already exists; no repeated "Why Choose EASCO" block
  where a CTA lead-in line already covers it).
- Metadata block convention: `Slug`, `SEO Title` (max 60 chars), `SEO
  Description` (max 160 chars) — not `Meta Title`/`Meta Description`.

---

## End of Template Design Plan
