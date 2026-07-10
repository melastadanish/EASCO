# Progress Tracker — EASCO

> Updated after every completed page. One row per page.
> Rebuilt 2026-07-10 against the ACTUAL current architecture (5 real product
> categories, 8 Solutions industries, `Real Products data/` + `Real Solutions
> data/` folders) and the ACTUAL current file state (verified by reading each
> file's own pass-log header — not assumed).
> Commit format: `[WRITE] filename.md — five-pass complete`

---

## Status Legend

| Icon | Meaning |
|---|---|
| ✅ | Written, pass log header present, matches current template — ready for development |
| 📝 | Written, but stale — does not match the current template/rules, needs rewrite |
| 🔲 | Not started (file doesn't exist, or is an empty placeholder) |
| ⚠️ | Blocked — waiting for client data, a prerequisite mapping, or legal review |

---

## Completion Summary

- **✅ Complete and current: 42** (Homepage, Why Us, 9 case studies, 3 resources,
  8 blog articles, Contact, Request Quote, 4 alternatives, 6 supporting pages,
  Phase 0 system files)
- **📝 Written but stale, needs rewrite: 2** (blog-hub.md, aluminum-alloy-turnstile.md)
- **🔲 Not started: 41** (Alternatives Hub, 4 remaining product category archives,
  all individual product-model pages, Solutions Hub, 8 Solutions industry pages,
  26 Solutions category×industry sub-pages)
- **⚠️ Blocked: 2** (Privacy Policy, Terms of Service — legal counsel review;
  separately, all Products work beyond the one stale category page is blocked
  on the product category → model mapping — see Known Blockers in
  `execution-plan.md`)

---

## Phase 1 — Core Pages

### Page 01 — Homepage
| File | Status | Notes |
|---|---|---|
| other-pages/home.md | ✅ | Pass log: READY FOR DEVELOPMENT |

### Page 02 — Why Us / About
| File | Status | Notes |
|---|---|---|
| other-pages/why-us.md | ✅ | Pass log: READY FOR DEVELOPMENT |

### Page 03 — Products (5 real categories)

| Category | Category Archive | Status | Notes |
|---|---|---|---|
| Aluminum alloy turnstile | `Real Products data/Aluminum alloy turnstile/aluminum-alloy-turnstile.md` | 📝 | Written, but missing the "Browse Other Categories" grid section from the current template; uses a bulleted "Key Features" list (violates standing no-bullets rule); pass log lists an AI-Written Score of 82% against a ≤15% target. Needs a full rewrite against the current `category-archive-page-template.md`, not a patch. |
| Stainless steel turnstile | — | 🔲 | Folder not created. Blocked on category→model mapping. |
| Facial recognition | — | 🔲 | Folder not created. Blocked on category→model mapping. |
| Handheld device | — | 🔲 | Folder not created. Blocked on category→model mapping. |
| Gate opener | — | 🔲 | Folder not created. Blocked on category→model mapping. |

**Individual product-model pages:** 0 written. Fully blocked — see
`execution-plan.md` Known Blocker 1 (client-data-map.md still organized by the
old 5-SILO structure, not the current 5 categories).

### Page 04 — Solutions (Hub + 8 Industry pages + Category×Industry sub-pages)

| Page | File | Status |
|---|---|---|
| Solutions Hub | `Real Solutions data/solutions-hub.md` | 🔲 empty |
| Commercial Buildings | `Real Solutions data/Commercial Buildings/commercial-buildings.md` | 🔲 empty |
| Smart Campus | `Real Solutions data/Smart Campus/smart-campus.md` | 🔲 empty |
| Transportation | `Real Solutions data/Transportation/transportation.md` | 🔲 empty |
| Hospitals | `Real Solutions data/Hospitals/hospitals.md` | 🔲 empty |
| Factories | `Real Solutions data/Factories/factories.md` | 🔲 empty |
| Government | `Real Solutions data/Government/government.md` | 🔲 empty |
| Hospitality/Hotels | `Real Solutions data/Hospitality Hotels/hospitality-hotels.md` | 🔲 empty |
| Sports Venues/Stadiums | `Real Solutions data/Sports Venues Stadiums/sports-venues-stadiums.md` | 🔲 empty |

**Category × Industry sub-pages — 26 total, all 🔲 empty:**

| Industry | Sub-pages (empty placeholders) |
|---|---|
| Commercial Buildings | aluminum-alloy-turnstile, facial-recognition |
| Smart Campus | aluminum-alloy-turnstile, facial-recognition, handheld-device |
| Transportation | facial-recognition, gate-opener, handheld-device, stainless-steel-turnstile |
| Hospitals | aluminum-alloy-turnstile, facial-recognition, handheld-device |
| Factories | facial-recognition, gate-opener, handheld-device, stainless-steel-turnstile |
| Government | facial-recognition, handheld-device, stainless-steel-turnstile |
| Hospitality/Hotels | aluminum-alloy-turnstile, facial-recognition, gate-opener |
| Sports Venues/Stadiums | facial-recognition, gate-opener, handheld-device, stainless-steel-turnstile |

### Page 05 — Case Studies

| Page | File | Status | Notes |
|---|---|---|---|
| Case Studies Hub | case-studies/case-studies-hub.md | ✅ | READY FOR DEVELOPMENT |
| Office Buildings | case-studies/office-buildings.md | ✅ | Complete — illustrative example, named projects confirmed unavailable |
| Schools / Universities | case-studies/schools.md | ✅ | Complete — illustrative example |
| Factories | case-studies/factories.md | ✅ | Complete — illustrative example |
| Metro / Transit | case-studies/metro.md | ✅ | Complete — illustrative example |
| Airports | case-studies/airports.md | ✅ | Complete — illustrative example |
| Hospitals | case-studies/hospitals.md | ✅ | Complete — illustrative example |
| Shopping Malls | case-studies/shopping-malls.md | ✅ | Complete — illustrative example |
| Government | case-studies/government.md | ✅ | Complete — illustrative example |

### Page 06 — Resources

| Resource | File | Status | Notes |
|---|---|---|---|
| FAQ | other-pages/faq.md | ✅ | READY FOR DEVELOPMENT |
| Photo Gallery | other-pages/gallery.md | ✅ | Text complete; photos ⚠️ pending upload |
| Downloads Center | other-pages/downloads.md | ✅ | READY FOR DEVELOPMENT |

### Page 07 — Blog

| Page | File | Status | Notes |
|---|---|---|---|
| Blog Hub | blogs/blog-hub.md | 📝 | Written, but uses the old Hero → Articles by Stage → FAQ → CTA structure. Current template (`templates/blog-hub-template.md`) requires Banner → Left Sidebar Filter → Posts Grid → CTA. Needs full rewrite. |
| What Is a Turnstile Gate? | blogs/what-is-a-turnstile-gate.md | ✅ | READY FOR DEVELOPMENT |
| Biometric Access Control Explained | blogs/biometric-access-control-explained.md | ✅ | READY FOR DEVELOPMENT |
| How to Choose a Turnstile Gate | blogs/how-to-choose-turnstile-gate.md | ✅ | READY FOR DEVELOPMENT |
| Face Recognition vs Fingerprint | blogs/face-recognition-vs-fingerprint.md | ✅ | READY FOR DEVELOPMENT |
| Access Control for Construction Sites | blogs/access-control-for-construction-sites.md | ✅ | READY FOR DEVELOPMENT |
| OEM vs ODM | blogs/oem-vs-odm.md | ✅ | READY FOR DEVELOPMENT |
| How Does ANPR Work? | blogs/how-does-anpr-work.md | ✅ | READY FOR DEVELOPMENT |
| What Is Liveness Detection? | blogs/what-is-liveness-detection.md | ✅ | READY FOR DEVELOPMENT |

⚠️ All 8 articles still contain old dead-taxonomy category links — noted in
`_system/template-design-plan.md`, not fixed yet.

### Page 08 — Contact
| File | Status |
|---|---|
| other-pages/contact.md | ✅ READY FOR DEVELOPMENT |

### Page 09 — Request Quote
| File | Status |
|---|---|
| other-pages/request-quote.md | ✅ READY FOR DEVELOPMENT |

---

## Alternatives

| Page | File | Status | Notes |
|---|---|---|---|
| Alternatives Hub | alternatives/alternatives-hub.md | 🔲 | Does not exist. Template ready (`templates/alternatives-hub-template.md`). |
| EASCO vs ZKTeco | alternatives/easco-vs-zkteco.md | ✅ | READY FOR DEVELOPMENT |
| EASCO vs Hikvision | alternatives/easco-vs-hikvision.md | ✅ | READY FOR DEVELOPMENT |
| ZKTeco Alternative | alternatives/zkteco-alternative.md | ✅ | READY FOR DEVELOPMENT |
| Hikvision Alternative | alternatives/hikvision-alternative.md | ✅ | READY FOR DEVELOPMENT |

⚠️ Live comparison pages still carry the old `Meta Title`/`Meta Description`
metadata convention and at least one dead old-taxonomy link
(`/palm-vein-iris/` in easco-vs-hikvision.md) — noted, not fixed.

---

## Phase 2 — Supporting Pages (Trust & Legal)

| Page | File | Status | Notes |
|---|---|---|---|
| Factory Tour | other-pages/factory.md | ✅ | Photos ⚠️ pending |
| Certifications | other-pages/certifications.md | ✅ | Cert scans ⚠️ pending |
| OEM/ODM Services | other-pages/oem-odm.md | ✅ | READY FOR DEVELOPMENT |
| Partners & Distributors | other-pages/partners.md | ✅ | READY FOR DEVELOPMENT |
| Trade Shows & Events | other-pages/events.md | ✅ | READY FOR DEVELOPMENT |
| Privacy Policy | other-pages/privacy-policy.md | ⚠️ | DRAFT — needs legal counsel review |
| Terms of Service | other-pages/terms.md | ⚠️ | DRAFT — needs legal counsel review |
| Cookie Policy | other-pages/cookies.md | ✅ | READY FOR DEVELOPMENT |

---

## Critical Client Data Gaps

### 🔴 Urgent — Blocks Multiple Pages

1. **Product category → model mapping** — `client-data-map.md` is still organized
   by the old 5-SILO structure. Needs to be remapped against the current 5 real
   categories before any further Products page can be written.
2. Factory size (sqm), employee count, annual production capacity, R&D headcount
3. Real case study project data (photos, locations, client/product/result) —
   still none received; illustrative examples used as an explicit, clearly-labeled
   stand-in per client's own direction
4. Product photos (white-background, multi-angle), demo videos, full spec sheets

### 🟡 Important — Needed for Quality

- Notable clients/reference projects, awards/press mentions
- Company registration document
- Final confirmed export country list
- Factory exterior/production floor photos, team photos, exhibition booth photos
- Certificate scans (ISO, CE, RoHS, IP65)

---

## End of Progress Tracker
