# CLAUDE.md — EASCO Content Repository (REDESIGNED per Ayesha's Plan)

> **UPDATED:** Content structure redesigned according to EASCO_Website_Redesign_Plan by AYESHA
> **NEW FOCUS:** 9 Core Pages + Solutions by Industry + Case Studies + Product Categories
> **Reference Site:** turbooturnstile.com

---

## Session Start

Ask the user: **"Agent mode or manual mode?"**

- **Agent mode** — Read `_system/execution-plan.md`, identify the first unchecked task, complete it through the full 5-pass review, update `_system/progress.md`, commit, and stop.
- **Manual mode** — Await user instruction for which page to work on.

---

## Pre-Work Requirements (Every Session)

Before writing any page, read these files in order:

1. `_system/WritingSystem.md` — brand voice, copy rules, quality system, **Data Source Hierarchy, Verbatim Authority Statements, Pass N Term Lists by Product Category**
2. Spec data per the Data Source Hierarchy: `_system/product-specs/[model].md` FIRST → `_system/client-data-map.md` → `_system/VERIFIED-COMPANY-DATA.md` (company facts)
3. `_system/differentiator-card.md` — minimum 2 differentiators per page
4. `_system/objection-map.md` — Pass C objection coverage test
5. `_system/buyer-segment-table.md` — primary segment for the page being written
6. `_system/sitemap.md` — confirm URL slug before writing
7. The matching template for the page type:
   - **9 Core Pages** → `templates/other-page-template.md` (customize per page requirements)
   - **Solutions (by Industry)** → `templates/solution-page-template.md`
   - **Case Studies** → `templates/case-study-template.md`
   - **Product category (archive) page** → `templates/product-archive-template.md` ← 12 fixed sections
   - **Product detail page** → `templates/product-page-template.md` ← 11 fixed sections
   - Topic cluster page → `templates/cluster-page-template.md`
   - Blog / Informational → `templates/blog-template.md`
   - Alternatives / Competitor → `templates/alternative-template.md`

Every planned page already exists as a stub with frontmatter (Status, Template, URL Slug, Keyword Ref, Data Sources) — the stub's frontmatter is the page brief. Folders: `products/[category]/category.md` + detail pages, `solutions/`, `case-studies/`, `other-pages/`, `blogs/`, `alternatives/`.

---

## NEW Architecture (per Ayesha's Redesign Plan)

### **9 Core Pages** (Priority 1 — CRITICAL)

| # | Page | URL | Status | Template |
|---|---|---|---|---|
| 01 | **Homepage** (Full Redesign) | / | 🔲 | other-page-template.md |
| 02 | **Why Us / About** (Major Upgrade) | /why-us/ | 🔲 | other-page-template.md |
| 03 | **Products Hub** (Restructure) | /products/ | 🔲 | other-page-template.md |
| 04 | **Solutions by Industry** (NEW) | /solutions/ | 🔲 | solution-page-template.md |
| 05 | **Case Studies** (NEW) | /case-studies/ | ⚠️ BLOCKED | case-study-template.md |
| 06 | **Resources / Gallery** (NEW) | /resources/ | 🔲 | other-page-template.md |
| 07 | **Blog** (Fix + Improve) | /blog/ | 🔲 | blog-template.md |
| 08 | **Contact** (Redesign) | /contact/ | 🔲 | other-page-template.md |
| 09 | **Request Quote** (CTA) | /quote/ | 🔲 | other-page-template.md |

### **Solutions by Industry** (6 pages — NEW)
Critical for MOFU traffic capture. URL: `/solutions/[industry-name]/`

- Commercial Buildings
- Smart Campus / Schools
- Transportation Hubs (Airport, Metro, Bus)
- Hospitals
- Factories / Warehouses
- Government Buildings

### **Case Studies** (8 pages — NEW)  
⚠️ **BLOCKED** — requires client project photos and data

- Office Buildings
- Schools / Universities
- Factories
- Metro / Transit Systems
- Airports
- Hospitals
- Shopping Malls
- Government Buildings

### **Product Categories** (10 categories)
URL: `/products/[category-name]/`

- Speed Gates / Flap Barriers
- Tripod Turnstiles
- Cylindrical Turnstiles
- Android Turnstiles
- Face Recognition Terminals
- Handheld Face Recognition
- ANPR Systems
- Palm Vein + Iris Recognition
- Alcohol Detection Devices
- Visitor Registration Machines

---

---

## Page Development Workflow (Unchanged)

### Step 0 — Brief
- Identify primary buyer segment from `_system/buyer-segment-table.md`
- Map keyword slot from `seo/keyword-master-list.md` (if available)
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

## Quality Gate (Unchanged)

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

## Key Reference Files (Unchanged)

| File | Purpose |
|---|---|
| `_system/WritingSystem.md` | All writing rules, copy standards, quality system |
| `_system/client-data-map.md` | Single source of truth — all verified product specs |
| `_system/differentiator-card.md` | EASCO vs ZKTeco / Hikvision / Generic Alibaba |
| `_system/objection-map.md` | 20 buyer objections + spec-backed answers |
| `_system/buyer-segment-table.md` | 5 buyer segments — pain, drivers, messaging angle |
| `_system/competitors.md` | Competitor positioning reference |
| `_system/sitemap.md` | URL slugs, internal linking rules (REDESIGNED) |
| `_system/execution-plan.md` | Phased task queue (REDESIGNED) |
| `_system/progress.md` | Completion tracker (REDESIGNED) |
| `_system/reusablesections.md` | Reusable section library |
| `seo/keyword-master-list.md` | Keyword clusters (if available) |

---

## NEW Templates (per Redesign)

| Template | Purpose | Used For |
|---|---|---|
| `templates/solution-page-template.md` | Industry-specific solution pages | Solutions by Industry (6 pages) |
| `templates/case-study-template.md` | Venue-type case studies | Case Studies (8 pages) |
| `templates/other-page-template.md` | Core static pages | Homepage, Why Us, Contact, etc. |
| `templates/product-archive-template.md` | **Product category (archive) pages — 12 fixed sections** | Products Hub + 10 categories |
| `templates/product-page-template.md` | **Product detail pages — 11 fixed sections** | Individual models (Phase 2) |
| `templates/cluster-page-template.md` | Topic cluster pages (legacy) | Non-product clusters only |
| `templates/blog-template.md` | Blog posts | TOFU/MOFU/BOFU content |
| `templates/alternative-template.md` | Competitor comparison | EASCO vs ZKTeco, etc. |

---

## Critical Client Data Gaps (From Ayesha's Plan)

### 🔴 URGENT — Blocks Page Creation

1. **Factory Information**
   - Factory size (sqm) — NOT provided
   - Number of employees — NOT provided
   - Annual production capacity — NOT provided
   - R&D team headcount — NOT provided

2. **Case Study Projects** ⚠️ **CRITICAL GAP**
   - Real project photos with locations
   - Project names + client names (or anonymized)
   - Products used in each project
   - Challenge/Solution/Result for each

3. **Product Assets**
   - High-res white-background product photos (all products)
   - Product demo videos (YouTube links)
   - Full spec sheets
   - Top 3 SEO-priority products confirmed

4. **Company Assets**
   - Hero video for homepage (factory tour / product demo)
   - Factory exterior + production floor photos
   - Team photos
   - Exhibition booth photos (2023–2025)
   - Certificate scans (ISO, CE, ROHS, IP54)

### 🟡 IMPORTANT — Needed for Quality
- Notable clients or reference projects
- Awards, press mentions, plaques
- Company registration document
- Final export country list
- Blog content strategy (client provides vs Napollo writes?)

---

## Visual Design Direction (From Ayesha's Plan — Reference: turbooturnstile.com)

### Homepage Requirements
- Dark header with clean white logo
- Autoplay product demo video in hero (muted)
- White background for main content sections
- Counter animation: 63+ Patents, 20+ Years, 50+ Countries, 10+ R&D Team
- World map with clickable pins per export country
- CTA buttons: 'Get a Quote' (primary) + 'Learn More' (secondary)
- Sticky floating WhatsApp button bottom right
- Certificate badges (ISO, CE, ROHS, IP54) in a row

### Why Us Requirements
- Counter stats prominently displayed
- Factory tour section with photos
- R&D team section with team photo
- Certifications wall (all certs shown visually)
- Exhibition timeline with booth photos
- OEM/ODM capabilities grid
- Custom project showcase

### Contact Page Requirements
- Quote request form: Name, Email, Phone, Product Interest, Message
- WhatsApp button prominent (+86 13711422283)
- Google Maps embed
- Response time promise: '1 hour during business hours'
- All contact channels: Phone, WhatsApp, Email, Skype, LinkedIn, Facebook, YouTube
- Social media icons

---

## Blog Critical Fixes (From Ayesha's Plan)

**🔴 MUST FIX IMMEDIATELY:**
- All blog page titles showing '网站' → change to proper English titles
- No meta descriptions → add unique meta per post
- No category system → add TOFU/MOFU/BOFU categories
- No internal linking → link to product/solution pages
- No related posts → add suggestions at end

---

## EASCO vs Turboo Comparison (Reference Benchmark)

| Feature | Turboo (Reference) | EASCO Current | EASCO New Plan |
|---|---|---|---|
| Homepage hero | Video + trust bullets | Static slider | ✅ Video + trust bullets |
| Products structure | 10 category sub-pages | Mixed list | ✅ 10 category sub-pages |
| Solutions page | 4 industry sub-pages | ❌ Does NOT exist | ✅ 6 industry sub-pages |
| Case studies | 9 venue-type sub-pages | ❌ Does NOT exist | ✅ 8 venue-type sub-pages |
| About / Why Us | Stats + factory + certs | Text only | ✅ Full trust page + visuals |
| World map | Interactive map | ❌ Does NOT exist | ✅ World map on homepage |
| Resources | FAQ + Gallery | Installation only | ✅ FAQ + Gallery + Downloads |
| Blog | Categorized, active | Exists, needs SEO fix | ✅ Categorized + SEO fixed |
| Certificates | Prominent homepage | Text mention only | ✅ Visual badges homepage |
| WhatsApp CTA | Floating button | Footer link only | ✅ Floating all pages |

---

## End of CLAUDE.md
