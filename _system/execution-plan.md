# Execution Plan — EASCO

> Phased content production plan aligned with the CURRENT site architecture:
> 5 real product categories, 8 Solutions industries, `Real Products data/` +
> `Real Solutions data/` folder structure (replacing the old `products/` /
> `solutions/` / `silos/` layout).
> **Agent mode reads this file and completes the first unchecked task.**
> One page per session in agent mode. Mark complete in `progress.md` after each page.
> Last Updated: 2026-07-10 (full rebuild against actual current architecture + file state)

---

## Definition of Done (Per Page)

- [ ] All 5 Tier 1 checks passed per section
- [ ] Pass A score ≥ 8.0/10
- [ ] Pass B fixes applied
- [ ] Pass N: all required access control terms verified present
- [ ] Pass D: AI-quotable paragraph written, 5+ FAQ Q&As, authority signals, freshness date
- [ ] Pass C: all 6 tests passed, AI-written score ≤ 15%
- [ ] All numbers traced to `_system/client-data-map.md`
- [ ] Minimum 2 differentiators from `_system/differentiator-card.md` present
- [ ] Applicable objections from `_system/objection-map.md` covered
- [ ] Pass log header added to page file (`Status: READY FOR DEVELOPMENT`)
- [ ] `_system/progress.md` updated to ✅
- [ ] Committed: `[WRITE] filename.md — five-pass complete`

---

## Known Blockers (read before picking a task)

1. **Product category → model mapping doesn't exist yet.** `_system/client-data-map.md`
   is still organized under the old 5-SILO structure (Turnstile Gates, Biometric
   Access Control, Vehicle & Parking, Attendance, Custom & Airport), not the current
   5 real categories (Aluminum alloy turnstile, Stainless steel turnstile, Facial
   recognition, Handheld device, Gate opener). Before writing any category archive
   page beyond Aluminum alloy turnstile, or any individual product page, this mapping
   needs to be built (which SILO models belong under which of the 5 categories).
   This is a prerequisite task, not a page-writing task — do it first if picked up
   in agent mode, and record the mapping in `client-data-map.md` or a new reference
   file before writing pages against it.
2. **`Real Solutions data/` is 100% unwritten.** All 35 files (hub + 8 industry pages +
   26 category×industry sub-pages) are empty placeholders. Templates are ready
   (`solutions-hub-template.md`, `industry-page-template.md`,
   `category-industry-page-template.md`).
3. **Two live files are stale against their current templates and need a rewrite,
   not just a status flip:**
   - `blogs/blog-hub.md` — still uses the old Hero → Articles by Stage → FAQ → CTA
     structure. Current template (`templates/blog-hub-template.md`) specifies
     Banner → Left Sidebar Filter → Posts Grid → CTA.
   - `Real Products data/Aluminum alloy turnstile/aluminum-alloy-turnstile.md` —
     missing the "Browse Other Categories" grid section required by the current
     `category-archive-page-template.md`, and uses a bulleted "Key Features" list,
     which violates the standing no-bulleted-features rule. Also carries an
     AI-Written Score of 82% in its pass log (target ≤15%) — this page has not
     actually passed Pass C despite its header claiming a score elsewhere; treat
     as needing a full rewrite, not a touch-up.
4. **`alternatives/alternatives-hub.md` does not exist.** Only the template
   (`templates/alternatives-hub-template.md`) has been written. This page has never
   been created.

---

## Phase 0 — System (Complete)

| Task | File | Status |
|---|---|---|
| Git init + .gitignore | .gitignore | ✅ |
| CLAUDE.md | CLAUDE.md | ✅ |
| WritingSystem.md | _system/WritingSystem.md | ✅ |
| client-data-map.md | _system/client-data-map.md | ✅ (⚠️ still old SILO taxonomy — see Blocker 1) |
| differentiator-card.md | _system/differentiator-card.md | ✅ |
| objection-map.md | _system/objection-map.md | ✅ |
| buyer-segment-table.md | _system/buyer-segment-table.md | ✅ |
| competitors.md | _system/competitors.md | ✅ |
| execution-plan.md (this file, rebuilt) | _system/execution-plan.md | ✅ |
| progress.md (rebuilt) | _system/progress.md | ✅ |
| sitemap.md | _system/sitemap.md | 🔲 not yet reconciled with current architecture |
| Template Map (Products, Solutions, Case Studies, Blog, Alternatives) | templates/, Real Products data/, Real Solutions data/ | ✅ all 5 pairs designed, stale files removed |

---

## Phase 1 — Core Pages

### Page 01 — Homepage
| File | Status |
|---|---|
| other-pages/home.md | ✅ READY FOR DEVELOPMENT |

### Page 02 — Why Us / About
| File | Status |
|---|---|
| other-pages/why-us.md | ✅ READY FOR DEVELOPMENT |

### Page 03 — Products (5 real categories)

| Category | Category Archive File | Status |
|---|---|---|
| Aluminum alloy turnstile | `Real Products data/Aluminum alloy turnstile/aluminum-alloy-turnstile.md` | 📝 written but stale — needs rewrite (see Blocker 3) |
| Stainless steel turnstile | — (folder not yet created) | 🔲 blocked on Blocker 1 |
| Facial recognition | — (folder not yet created) | 🔲 blocked on Blocker 1 |
| Handheld device | — (folder not yet created) | 🔲 blocked on Blocker 1 |
| Gate opener | — (folder not yet created) | 🔲 blocked on Blocker 1 |

**Individual product-model pages:** none written yet, for any category. Fully
blocked on Blocker 1 (model-to-category mapping).

### Page 04 — Solutions (Hub + 8 Industry pages + Category×Industry sub-pages)

| Page | File | Status |
|---|---|---|
| Solutions Hub | `Real Solutions data/solutions-hub.md` | 🔲 empty placeholder |
| Commercial Buildings | `Real Solutions data/Commercial Buildings/commercial-buildings.md` | 🔲 empty placeholder |
| Smart Campus | `Real Solutions data/Smart Campus/smart-campus.md` | 🔲 empty placeholder |
| Transportation | `Real Solutions data/Transportation/transportation.md` | 🔲 empty placeholder |
| Hospitals | `Real Solutions data/Hospitals/hospitals.md` | 🔲 empty placeholder |
| Factories | `Real Solutions data/Factories/factories.md` | 🔲 empty placeholder |
| Government | `Real Solutions data/Government/government.md` | 🔲 empty placeholder |
| Hospitality/Hotels | `Real Solutions data/Hospitality Hotels/hospitality-hotels.md` | 🔲 empty placeholder |
| Sports Venues/Stadiums | `Real Solutions data/Sports Venues Stadiums/sports-venues-stadiums.md` | 🔲 empty placeholder |

**Category × Industry sub-pages (26 total):** all empty placeholders across the
8 industry folders. See `Real Solutions data/` for exact filenames — only pair
a category with an industry where the placeholder file already exists (the
folder skeleton already excludes non-fitting pairs).

### Page 05 — Case Studies (written per template fallback rule — client confirmed no further data coming)

| Page | File | Status |
|---|---|---|
| Case Studies Hub | case-studies/case-studies-hub.md | ✅ READY FOR DEVELOPMENT |
| Office Buildings | case-studies/office-buildings.md | ✅ Complete (illustrative example, named projects confirmed unavailable) |
| Schools / Universities | case-studies/schools.md | ✅ Complete (illustrative example) |
| Factories | case-studies/factories.md | ✅ Complete (illustrative example) |
| Metro / Transit | case-studies/metro.md | ✅ Complete (illustrative example) |
| Airports | case-studies/airports.md | ✅ Complete (illustrative example) |
| Hospitals | case-studies/hospitals.md | ✅ Complete (illustrative example) |
| Shopping Malls | case-studies/shopping-malls.md | ✅ Complete (illustrative example) |
| Government | case-studies/government.md | ✅ Complete (illustrative example) |

⚠️ Case study "venue types" above don't fully match the 8 Solutions industries
(e.g. Shopping Malls / Metro have no Solutions industry counterpart; Hospitality
and Sports Venues have no case study counterpart). Reconciliation deferred —
see `_system/template-design-plan.md` Step 3.

### Page 06 — Resources (FAQ + Gallery + Downloads, no hub page)

| Sub-Section | File | Status |
|---|---|---|
| FAQ | other-pages/faq.md | ✅ READY FOR DEVELOPMENT |
| Photo Gallery | other-pages/gallery.md | ✅ READY FOR DEVELOPMENT (text complete; photos pending upload) |
| Downloads Center | other-pages/downloads.md | ✅ READY FOR DEVELOPMENT |

### Page 07 — Blog (Hub + 8 articles)

| Page | File | Status |
|---|---|---|
| Blog Hub | blogs/blog-hub.md | 📝 written but stale — needs full rewrite to current template (see Blocker 3) |
| What Is a Turnstile Gate? | blogs/what-is-a-turnstile-gate.md | ✅ READY FOR DEVELOPMENT |
| Biometric Access Control Explained | blogs/biometric-access-control-explained.md | ✅ READY FOR DEVELOPMENT |
| How to Choose a Turnstile Gate | blogs/how-to-choose-turnstile-gate.md | ✅ READY FOR DEVELOPMENT |
| Face Recognition vs Fingerprint | blogs/face-recognition-vs-fingerprint.md | ✅ READY FOR DEVELOPMENT |
| Access Control for Construction Sites | blogs/access-control-for-construction-sites.md | ✅ READY FOR DEVELOPMENT |
| OEM vs ODM | blogs/oem-vs-odm.md | ✅ READY FOR DEVELOPMENT |
| How Does ANPR Work? | blogs/how-does-anpr-work.md | ✅ READY FOR DEVELOPMENT |
| What Is Liveness Detection? | blogs/what-is-liveness-detection.md | ✅ READY FOR DEVELOPMENT |

⚠️ All 8 articles still contain old dead-taxonomy category links (noted, not
fixed — see `_system/template-design-plan.md` Step 4).

### Page 08 — Contact
| File | Status |
|---|---|
| other-pages/contact.md | ✅ READY FOR DEVELOPMENT |

### Page 09 — Request Quote
| File | Status |
|---|---|
| other-pages/request-quote.md | ✅ READY FOR DEVELOPMENT |

---

## Alternatives (not one of the 9 core pages — has its own Hub + single-page templates)

| Page | File | Status |
|---|---|---|
| Alternatives Hub | alternatives/alternatives-hub.md | 🔲 does not exist — needs to be written (see Blocker 4) |
| EASCO vs ZKTeco | alternatives/easco-vs-zkteco.md | ✅ READY FOR DEVELOPMENT |
| EASCO vs Hikvision | alternatives/easco-vs-hikvision.md | ✅ READY FOR DEVELOPMENT |
| ZKTeco Alternative | alternatives/zkteco-alternative.md | ✅ READY FOR DEVELOPMENT |
| Hikvision Alternative | alternatives/hikvision-alternative.md | ✅ READY FOR DEVELOPMENT |

⚠️ Live comparison pages still have old `Meta Title`/`Meta Description`
metadata convention and at least one dead old-taxonomy link
(`/palm-vein-iris/`) — noted, not fixed (see `_system/template-design-plan.md`
Step 5).

---

## Phase 2 — Supporting Pages (Trust & Legal)

| Task | File | Status |
|---|---|---|
| Factory Tour | other-pages/factory.md | ✅ READY FOR DEVELOPMENT (photos pending) |
| Certifications | other-pages/certifications.md | ✅ READY FOR DEVELOPMENT (cert scans pending) |
| OEM/ODM Services | other-pages/oem-odm.md | ✅ READY FOR DEVELOPMENT |
| Partners & Distributors | other-pages/partners.md | ✅ READY FOR DEVELOPMENT |
| Trade Shows & Events | other-pages/events.md | ✅ READY FOR DEVELOPMENT |
| Privacy Policy | other-pages/privacy-policy.md | ⚠️ DRAFT — needs legal counsel review |
| Terms of Service | other-pages/terms.md | ⚠️ DRAFT — needs legal counsel review |
| Cookie Policy | other-pages/cookies.md | ✅ READY FOR DEVELOPMENT |

---

## Total Page Count (Current Architecture)

| Section | Pages | Written & Current | Written but Stale | Not Started |
|---|---|---|---|---|
| Phase 0 — System | 12 files | 12 | 0 | 0 |
| Core Pages 01, 02, 08, 09 | 4 | 4 | 0 | 0 |
| Products (5 categories) | 5 category archives + N model pages | 0 | 1 | 4 categories + all model pages |
| Solutions (Hub + 8 + 26) | 35 | 0 | 0 | 35 |
| Case Studies (Hub + 8) | 9 | 9 | 0 | 0 |
| Resources (3) | 3 | 3 | 0 | 0 |
| Blog (Hub + 8) | 9 | 8 | 1 | 0 |
| Contact + Request Quote | 2 | 2 | 0 | 0 |
| Alternatives (Hub + 4) | 5 | 4 | 0 | 1 |
| Supporting/Legal (8) | 8 | 6 | 0 | 2 (legal review, not content gap) |

---

## Critical Client Action Items

### 🔴 Urgent — blocks page creation
1. **Product category → model mapping** (Blocker 1) — needed before any further
   Products page can be written accurately.
2. Factory size (sqm), employee count, annual production capacity, R&D headcount
3. Real case study project photos+locations+client/product/result data (still none
   received — illustrative examples used as an explicit stand-in)
4. Product photos, demo videos, full spec sheets

### 🟡 Important — needed for quality
Notable clients/reference projects, awards/press mentions, company registration
doc, final export country list, factory/team/exhibition photos, cert scans

---

## End of Execution Plan
