# Execution Plan — EASCO Content Production

> **How to use this file (agent mode):**
> Read this file at the start of every session. Pick the **first unchecked item** in the lowest-numbered open phase.
> Complete it. Check the box. Update `_system/progress.md`. Commit. Push. Then stop (one page per session) or pick the next item if instructed.
>
> **Before working on any page, read:**
> `_system/WritingSystem.md` (full — includes Data Source Hierarchy, Verbatim Authority Statements, Pass N Term Lists) · `_system/VERIFIED-COMPANY-DATA.md` · the template named on the task line · the data sources named on the task line.
>
> **Task types:**
> - `[WRITE]` — file is a stub or empty. Write the full page, then run all five passes (A→B→N→D→C).
> - `[REVIEW]` — file has content written before the current system. Run all five passes and fix every failure.
> - `[SYSTEM]` — infrastructure task, no page copy. No five-pass needed.
>
> Last Updated: 2026-07-06

---

## Definition of Done (Per Page)

- [ ] All 5 Tier 1 checks passed per section
- [ ] Pass A score ≥ 8.0/10 · Pass B fixes applied
- [ ] Pass N: all required category terms present (WritingSystem § Pass N Term Lists)
- [ ] Pass D: AI-quotable paragraph, required FAQ count, verbatim authority statements
- [ ] Pass C: all 6 tests passed, AI-written score ≤ 15%
- [ ] Every number traced per Data Source Hierarchy (WritingSystem)
- [ ] Minimum 2 differentiators explicit · applicable objections covered
- [ ] Pass log header added · `_system/progress.md` updated to ✅
- [ ] Committed: `[WRITE] path/file.md — five-pass complete`

---

## Completed (Do Not Redo)

- [x] `other-pages/home.md` — five-pass complete (A:9.8)
- [x] `other-pages/why-us.md` — five-pass complete (A:10.0)
- [x] `other-pages/faq.md` — five-pass complete (A:10.0, 47 Q&As)
- [x] `silos/S1-Turnstiles/turnstile-gates.md` — five-pass complete (legacy silo pillar — reuse copy for products hub / speed-gates archive where it fits)
- [x] `silos/S2-Biometrics/biometric-access-control.md` — five-pass complete (legacy — reuse for face-recognition archive)
- [x] `silos/S3-Vehicle-Access/vehicle-access-control.md` — five-pass complete (legacy — reuse for anpr-systems archive)
- [x] `silos/S4-Attendance/attendance-management.md` — five-pass complete (legacy — reuse for alcohol-detection / handheld archives)

---

## Phase 0 — System Build (Complete Before Writing Product Pages)

- [x] `[SYSTEM]` Upgrade `templates/product-archive-template.md` — 12 fixed sections, weldocnc-style design notes
- [x] `[SYSTEM]` Upgrade `templates/product-page-template.md` — 11 fixed sections, product detail
- [x] `[SYSTEM]` Add to `_system/WritingSystem.md`: Data Source Hierarchy · Verbatim Authority Statements · Pass N Term Lists by Product Category
- [x] `[SYSTEM]` Rewrite `_system/execution-plan.md` — phased checklist (this file)
- [x] `[SYSTEM]` Reconcile `_system/progress.md` with actual page statuses
- [x] `[SYSTEM]` Reorganize folders to match sitemap: `solutions pages/` → `solutions/`, case-studies stubs, `products/` tree with category stubs
- [x] `[SYSTEM]` Update `CLAUDE.md` — template mapping, folder names, data source hierarchy
- [x] `[SYSTEM]` Create `_system/memory.md` — session memory (state, decisions, open questions, session log)
- [x] `[SYSTEM]` Create `_system/design.md` — visual/design direction moved out of CLAUDE.md
- [x] `[SYSTEM]` Slim `CLAUDE.md` to 21 lines — instructions only, everything else lives in `_system/`
- [ ] `[SYSTEM]` Reconcile `seo/keyword-master-list.md` slugs + repo-file pointers with `_system/sitemap.md` (keyword list still points at `/products/flap-barrier` and `silos/...` files; sitemap is the single source of truth). Flag for the user: solutions/case-studies category sets differ (keyword list has scenic-spots, banks, stadiums-gyms — sitemap has government, metro, hospitals). User decides which set is final.
- [ ] `[SYSTEM]` Deduplicate data layer: fold `_system/client-data-map/` folder files (ESFAT, ESQV8, L8, MTH8, Stargate) into `_system/product-specs/` where they overlap; keep Certifications.md and Contact-and-Social.md as-is
- [ ] `[SYSTEM]` Extract specs from `products data/Facial recognition/` manuals (14 files) into `_system/product-specs/` format — needed before their detail pages can be written
- [ ] `[SYSTEM]` Decide with user: do Gate opener + Handheld parking products get category pages? (Raw manuals exist; neither is in the 10-category sitemap)

---

## Phase 1 — Product Archive Pages (Hub + 10 Categories)

> Template: `templates/product-archive-template.md` · Keywords: `seo/keyword-master-list.md` §4 · Slugs: `_system/sitemap.md`

**HIGH priority first:**

- [ ] `[WRITE]` `products/speed-gates/category.md` — kw: flap barrier turnstile · specs: jx-stargate, esybz-compact, j-aluminum, luxury-stainless, stainless-swing-gate-304
- [ ] `[WRITE]` `products/face-recognition/category.md` — kw: face recognition terminal · specs: yunying-l8, esbl, mth8 + client-data-map §SILO2
- [ ] `[WRITE]` `products/anpr-systems/category.md` — kw: license plate recognition system · specs: es-t02-t03-t04, unattended-parking-toll, handheld-parking
- [ ] `[WRITE]` `products/android-turnstiles/category.md` — kw: intelligent turnstile gate · specs: jf-android
- [ ] `[WRITE]` `products/tripod-turnstiles/category.md` — kw: tripod turnstile · specs: single-arm-turnstile (⚠️ thin — request spec sheet, write with available data)
- [ ] `[WRITE]` `products/products-hub.md` — kw: keyword-master-list §3 Products Hub · links to all 10 categories (write after ≥5 categories exist)

**MEDIUM priority:**

- [ ] `[WRITE]` `products/visitor-registration/category.md` — kw: visitor management system (5,400 vol — Quick Win #2) · specs: MTFKS01/02 ⚠️ request spec sheet; merge `silos/S2-Biometrics/visitor-registration.md` stub frontmatter, then retire that stub
- [ ] `[WRITE]` `products/cylindrical-turnstiles/category.md` — kw: swing gate turnstile · specs: esybz-compact, stainless-swing-gate-304
- [ ] `[WRITE]` `products/handheld-face-recognition/category.md` — kw: handheld biometric device · specs: esrs51 + products data/Handheld device/*
- [ ] `[WRITE]` `products/palm-vein-iris/category.md` — kw: palm vein recognition device · specs: esfpr-es-v8, mth8 + client-data-map ESQV8
- [ ] `[WRITE]` `products/alcohol-detection/category.md` — kw: alcohol detection device · specs: esfat + client-data-map ESQV8

---

## Phase 2 — Product Detail Pages

> Template: `templates/product-page-template.md` · URL: `/products/[category]/[product]/`
> Full-spec products first. ⚠️ = partial specs — write with confirmed data only, mark gaps.

**Batch 1 — full specs confirmed:**

- [ ] `[WRITE]` `products/speed-gates/jx-stargate-speed-gate.md` — spec: jx-stargate-iridescent-speed-gate.md
- [ ] `[WRITE]` `products/cylindrical-turnstiles/esybz-cylindrical-speed-gate.md` — spec: esybz-compact-speed-gate.md
- [ ] `[WRITE]` `products/face-recognition/l8-face-fingerprint-terminal.md` — spec: yunying-l8-face-fingerprint-terminal.md
- [ ] `[WRITE]` `products/face-recognition/esbl-embedded-face-terminal.md` — spec: esbl-embedded-face-terminal.md
- [ ] `[WRITE]` `products/alcohol-detection/esfat-alcohol-attendance-terminal.md` — spec: esfat-alcohol-attendance-terminal.md
- [ ] `[WRITE]` `products/palm-vein-iris/es-v8-palm-vein-terminal.md` — spec: esfpr-es-v8-palm-vein-recognition.md
- [ ] `[WRITE]` `products/handheld-face-recognition/esrs51-rugged-handheld.md` — spec: esrs51-rugged-handheld-terminal.md
- [ ] `[WRITE]` `products/anpr-systems/es-t-series-lpr-camera.md` — spec: es-t02-t03-t04-lpr-camera.md

**Batch 2 — partial specs (⚠️ spec sheet requested from client):**

- [ ] `[WRITE]` `products/palm-vein-iris/mth8-iris-face-terminal.md` — spec: mth8-iris-facial-terminal.md ⚠️
- [ ] `[WRITE]` `products/android-turnstiles/jf-android-speed-gate.md` — spec: jf-android-speed-gate.md ⚠️
- [ ] `[WRITE]` `products/speed-gates/j-series-aluminum-speed-gate.md` — spec: j-aluminum-speed-gate.md ⚠️
- [ ] `[WRITE]` `products/speed-gates/luxury-stainless-speed-gate.md` — spec: luxury-stainless-speed-gate.md ⚠️
- [ ] `[WRITE]` `products/cylindrical-turnstiles/stainless-swing-gate.md` — spec: stainless-swing-gate-304.md ⚠️
- [ ] `[WRITE]` `products/tripod-turnstiles/single-arm-turnstile.md` — spec: single-arm-turnstile.md ⚠️
- [ ] `[WRITE]` `products/anpr-systems/unattended-parking-toll-system.md` — spec: unattended-parking-toll-system.md ⚠️
- [ ] `[WRITE]` `products/anpr-systems/handheld-parking-device.md` — spec: handheld-parking-management-device.md ⚠️

**Batch 3 — blocked until spec extraction (Phase 0 task) or client sheets:**

- [ ] `[WRITE]` Face terminal detail pages from `products data/Facial recognition/` (Yunji, Yunwen, Lingdian, Yunling, Yunteng, Yuntu, RCM01/02, 15.6", 21.5") — after Phase 0 spec extraction
- [ ] `[WRITE]` `products/visitor-registration/mtfks-visitor-kiosk.md` — ⚠️ BLOCKED: no spec data

---

## Phase 3 — Solutions by Industry (Hub + 6)

> Template: `templates/solution-page-template.md` · Keywords: keyword-master-list §5 · Products to feature: sitemap.md Solutions table

- [ ] `[WRITE]` `solutions/commercial-buildings.md` — feature: speed gates, face recognition
- [ ] `[WRITE]` `solutions/smart-campus.md` — feature: attendance, visitor registration, turnstiles
- [ ] `[WRITE]` `solutions/factories.md` — feature: attendance, alcohol detection (D11)
- [ ] `[WRITE]` `solutions/transportation.md` — feature: cylindrical gates (D9), ANPR
- [ ] `[WRITE]` `solutions/hospitals.md` — feature: palm vein (D12), visitor registration
- [ ] `[WRITE]` `solutions/government.md` — feature: iris recognition (D4), high security
- [ ] `[WRITE]` `solutions/solutions-hub.md` — write after the 6 industry pages exist

---

## Phase 4 — Remaining Core Pages

> Template: `templates/other-page-template.md` unless noted

- [ ] `[WRITE]` `other-pages/contact.md` — form fields, WhatsApp, Google Maps, 1-hour promise, all channels (`_system/design.md` § Contact)
- [ ] `[WRITE]` `other-pages/request-quote.md` — BOFU CTA page
- [ ] `[WRITE]` `other-pages/resources.md` — hub: FAQ + Gallery + Downloads
- [ ] `[WRITE]` `other-pages/downloads.md` — spec sheets, SDK docs, certificates
- [ ] `[WRITE]` `blogs/blog-hub.md` — template: blog-template.md · include TOFU/MOFU/BOFU category system + list of 网站-title fixes for developer
- [ ] `[WRITE]` `other-pages/gallery.md` — ⚠️ BLOCKED: needs photos (structure can be written, images pending)

---

## Phase 5 — Blog Content

> Template: `templates/blog-template.md` · Existing stubs have keyword frontmatter — keep their filenames.

**Existing stubs (write first — keyword research done):**

- [ ] `[WRITE]` `blogs/what-is-a-turnstile-gate.md` — TOFU
- [ ] `[WRITE]` `blogs/how-to-choose-turnstile-gate.md` — MOFU
- [ ] `[WRITE]` `blogs/face-recognition-vs-fingerprint.md` — MOFU
- [ ] `[WRITE]` `blogs/biometric-access-control-explained.md` — TOFU
- [ ] `[WRITE]` `blogs/how-does-anpr-work.md` — TOFU (covers Ayesha's "How Does ANPR Work?")
- [ ] `[WRITE]` `blogs/what-is-liveness-detection.md` — TOFU, AI-citation target
- [ ] `[WRITE]` `blogs/oem-vs-odm.md` — BOFU (covers Ayesha's "OEM Biometric Device Supplier Guide" intent)
- [ ] `[WRITE]` `blogs/access-control-for-construction-sites.md` — MOFU (pairs with alcohol detection D11)

**From Ayesha's plan (create files when started):**

- [ ] `[WRITE]` `blogs/what-is-flap-barrier.md` — TOFU
- [ ] `[WRITE]` `blogs/how-face-recognition-works.md` — TOFU
- [ ] `[WRITE]` `blogs/flap-barrier-vs-speed-gate.md` — MOFU
- [ ] `[WRITE]` `blogs/best-face-recognition-2025.md` — MOFU
- [ ] `[WRITE]` `blogs/why-choose-easco.md` — BOFU
- [ ] `[WRITE]` `blogs/oem-biometric-supplier.md` — BOFU (skip if oem-vs-odm.md covers the keyword — check keyword-master-list first)

---

## Phase 6 — Alternatives (Competitor Comparison)

> Template: `templates/alternative-template.md` · Source: `_system/competitors.md` — verify competitor specs before writing

- [ ] `[WRITE]` `alternatives/easco-vs-zkteco.md`
- [ ] `[WRITE]` `alternatives/easco-vs-hikvision.md`
- [ ] `[WRITE]` `alternatives/zkteco-alternative.md`
- [ ] `[WRITE]` `alternatives/hikvision-alternative.md`

---

## Phase 7 — Supporting Pages (Trust & Legal)

> Template: `templates/other-page-template.md`

- [ ] `[WRITE]` `other-pages/oem-odm.md` — D6 differentiator page
- [ ] `[WRITE]` `other-pages/partners.md` — Importer/Distributor segment
- [ ] `[WRITE]` `other-pages/factory.md` — 3,000+ m² plant (⚠️ photos pending — copy can be written)
- [ ] `[WRITE]` `other-pages/events.md` — 2025 Shenzhen International Exhibition confirmed; 2023–2024 ⚠️ needs client list
- [ ] `[WRITE]` `other-pages/certifications.md` — ⚠️ cert scans pending — copy from Certifications.md can be written
- [ ] `[WRITE]` `other-pages/privacy-policy.md`
- [ ] `[WRITE]` `other-pages/terms.md`
- [ ] `[WRITE]` `other-pages/cookies.md`

---

## Phase 8 — Case Studies (⚠️ ALL BLOCKED — client data required)

> Template: `templates/case-study-template.md`
> Blocked until client supplies per project: title + location, products used, challenge, solution, result, 3–5 photos.

- [ ] `[WRITE]` `case-studies/office-buildings.md` — ⚠️ BLOCKED
- [ ] `[WRITE]` `case-studies/schools.md` — ⚠️ BLOCKED
- [ ] `[WRITE]` `case-studies/factories.md` — ⚠️ BLOCKED
- [ ] `[WRITE]` `case-studies/metro.md` — ⚠️ BLOCKED
- [ ] `[WRITE]` `case-studies/airports.md` — ⚠️ BLOCKED
- [ ] `[WRITE]` `case-studies/hospitals.md` — ⚠️ BLOCKED
- [ ] `[WRITE]` `case-studies/shopping-malls.md` — ⚠️ BLOCKED
- [ ] `[WRITE]` `case-studies/government.md` — ⚠️ BLOCKED
- [ ] `[WRITE]` `case-studies/case-studies-hub.md` — write last, after sub-pages

---

## Page Count

| Phase | Pages | Done |
|---|---|---|
| Completed (core + legacy silos) | 7 | 7 |
| Phase 0 — System | 11 tasks | 7 |
| Phase 1 — Product archives | 11 | 0 |
| Phase 2 — Product details | 17+ | 0 |
| Phase 3 — Solutions | 7 | 0 |
| Phase 4 — Core remaining | 6 | 0 |
| Phase 5 — Blog | 14 | 0 |
| Phase 6 — Alternatives | 4 | 0 |
| Phase 7 — Supporting | 8 | 0 |
| Phase 8 — Case studies (blocked) | 9 | 0 |

---

## Critical Client Action Items (Unchanged — blocks marked ⚠️ above)

### 🔴 URGENT
- Case study projects: title, location, products, challenge/solution/result, 3–5 photos each
- Spec sheets: MTH8 hardware, JF1–JF5 gate body, J3/J4, 锋影, 168 stainless, single-arm, parking toll, handheld parking, MTFKS01/02 visitor kiosk
- High-res white-background product photos (all products) · demo video links
- Top 3 SEO-priority product lines confirmed

### 🟡 IMPORTANT
- Annual production capacity · warranty periods · exact employee count
- ROHS / IP54 / UKCA / EAC certificates (currently BANNED in copy until confirmed)
- Notable clients · awards · exhibition list 2023–2024 · final export country list
- Factory/team/exhibition photos · certificate scans

---

## End of Execution Plan
