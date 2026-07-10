# INSTRUCTIONS.md — Full Workflow

## Pre-Work (read before writing any page)
1. `_system/WritingSystem.md` — brand voice, copy rules, quality system
2. `_system/client-data-map.md` — every spec number must be verified here
3. `_system/differentiator-card.md` — min 2 differentiators per page
4. `_system/objection-map.md` — Pass C objection coverage test
5. `_system/buyer-segment-table.md` — primary segment for this page
6. `_system/sitemap.md` — confirm URL slug
7. Matching template (see table in `_system/MEMORY.md`)

## Page Development Workflow — Two-Agent Handoff

Writing and reviewing are split across two independent subagents so the
reviewer never inherits the writer's assumptions. Do not have one agent (or
the main session) do both jobs on the same page — that collapses the
independence the split exists for.

### Step 0 — Brief (main session)
- Identify primary buyer segment (`_system/buyer-segment-table.md`)
- Map keyword slot (`seo/keyword-master-list.md`, if available)
- Check `_system/execution-plan.md` Known Blockers — do not hand off a
  blocked task
- Confirm section outline with user before writing (manual mode) or take the
  next unchecked task as-is (agent mode)

### Step 1 — Write (`content-writer` subagent)
- Give it the page/task and file path — it reads its own pre-work files
- Follows template structure, runs the 5 Tier 1 checks after every section
- Outputs a compiled draft with no Pass Log Header — that's the reviewer's job

### Step 2 — Review (`content-reviewer` subagent, fresh context)
- Give it only the draft file path — do not paste in the writer's reasoning
  or notes, the independence is the point
- Runs Tier 2 in order: **Pass A** (6-dimension audit) → **Pass B** (surgical
  rewrite of Pass A failures only) → **Pass N** (NLP semantic coverage) →
  **Pass D** (E-E-A-T/GEO) → **Pass C** (conversion review, AI-written
  score ≤15%)
- Writes the Pass Log Header to the draft file itself
- Returns a verdict: `READY FOR DEVELOPMENT` or `NEEDS FURTHER WORK` (with a
  numbered list of exactly what's still failing)

### Step 3 — Gate (main session)
- **NEEDS FURTHER WORK** → send the reviewer's failure list back to a new
  `content-writer` invocation for a revision pass, then re-review. Do not
  commit a NEEDS FURTHER WORK draft.
- **READY** → update `_system/progress.md` to ✅, commit:
  `[WRITE] filename.md — five-pass complete`, push to main

## Quality Gate — page is NOT complete until:
- [ ] All 5 Tier 1 checks passed per section
- [ ] Pass A score ≥ 8.0/10 overall
- [ ] Pass B fixes applied
- [ ] Pass N: mandatory access control terms present
- [ ] Pass D: AI-quotable paragraph + FAQ with 5+ Q&As
- [ ] Pass C: all 6 tests passed, AI-written score ≤ 15%
- [ ] All numbers traced to `_system/client-data-map.md`
- [ ] ≥2 differentiators from `_system/differentiator-card.md` explicit
- [ ] Applicable objections from `_system/objection-map.md` covered
- [ ] Pass log added to page file header
- [ ] `_system/progress.md` updated to ✅
- [ ] Committed and pushed

## Page Architecture

### 9 Core Pages
> Full, current URL/file map lives in `_system/sitemap.md` — treat it as the single source
> of truth for site structure. Two items below are **not** hub pages despite the numbering:
> Products (03) is a mega-menu linking directly to 10 category pages — there is no
> `/products/` hub file. Resources (06) is FAQ + Gallery + Downloads as separate standalone
> pages — there is no `/resources/` hub file either. Do not create either hub page.

| # | Page | URL | Template |
|---|---|---|---|
| 01 | Homepage | / | other-page-template.md |
| 02 | Why Us / About | /why-us/ | other-page-template.md |
| 03 | Products (5 categories: product detail + category archive) | /[category-slug]/ | Real Products data/product-page-template.md, Real Products data/category-archive-page-template.md |
| 04 | Solutions (Hub + 8 Industry pages + Category×Industry sub-pages) | /solutions/ | Real Solutions data/solutions-hub-template.md, Real Solutions data/industry-page-template.md, Real Solutions data/category-industry-page-template.md |
| 05 | Case Studies ⚠️ BLOCKED | /case-studies/ | case-study-template.md (⚠️ Step 3 skipped, see template-design-plan.md) |
| 06 | Resources (FAQ + Gallery + Downloads, no hub) | /faq/, /gallery/, /downloads/ | other-page-template.md |
| 07 | Blog (Hub + articles) | /blog/ | blog-hub-template.md, blog-template.md |
| 08 | Contact | /contact/ | other-page-template.md |
| 09 | Request Quote | /quote/ | other-page-template.md |

*(Alternatives is not one of the 9 core pages but has its own Hub + single-page templates: `templates/alternatives-hub-template.md`, `templates/alternative-template.md`.)*

### Solutions by Industry (8): Commercial Buildings, Smart Campus, Transportation,
Hospitals, Factories, Government, Hospitality/Hotels, Sports Venues/Stadiums
URL: `/solutions/[industry-slug]/`

### Case Studies (8, BLOCKED — needs client photos/data): Office Buildings,
Schools/Universities, Factories, Metro/Transit, Airports, Hospitals,
Shopping Malls, Government Buildings

### Product Categories (10): Speed Gates/Flap Barriers, Tripod Turnstiles,
Cylindrical Turnstiles, Android Turnstiles, Face Recognition Terminals,
Handheld Face Recognition, ANPR Systems, Palm Vein + Iris Recognition,
Alcohol Detection Devices, Visitor Registration Machines
URL: `/products/[category-name]/`

## Blog Critical Fixes
- Titles showing '网站' → proper English titles
- Add unique meta descriptions per post
- Add TOFU/MOFU/BOFU category system
- Add internal links to product/solution pages
- Add related-posts suggestions at end

## Visual Design Direction (Reference: turbooturnstile.com)

**Homepage:** dark header, white logo, autoplay muted hero video, white content
background, counter animation (63+ Patents / 20+ Years / 50+ Countries / 10+ R&D),
clickable world map, 'Get a Quote' + 'Learn More' CTAs, floating WhatsApp button,
certificate badges row (ISO, CE, ROHS, IP54).

**Why Us:** counter stats, factory tour photos, R&D team section, certifications
wall, exhibition timeline, OEM/ODM capabilities grid, custom project showcase.

**Contact:** quote form (Name/Email/Phone/Product Interest/Message), WhatsApp
button (+86 13711422283), Google Maps embed, "1 hour during business hours"
response promise, all channels (Phone/WhatsApp/Email/Skype/LinkedIn/Facebook/YouTube).

## EASCO vs Turboo Benchmark
| Feature | Turboo | EASCO Current | EASCO Plan |
|---|---|---|---|
| Homepage hero | Video + trust bullets | Static slider | ✅ Video + trust bullets |
| Products structure | 10 category sub-pages | Mixed list | ✅ 10 category sub-pages |
| Solutions page | 4 industry sub-pages | ❌ Missing | ✅ 6 industry sub-pages |
| Case studies | 9 venue sub-pages | ❌ Missing | ✅ 8 venue sub-pages |
| About/Why Us | Stats + factory + certs | Text only | ✅ Full trust page |
| World map | Interactive | ❌ Missing | ✅ World map |
| Resources | FAQ + Gallery | Installation only | ✅ FAQ + Gallery + Downloads |
| Blog | Categorized, active | Needs SEO fix | ✅ Categorized + fixed |
| Certificates | Prominent homepage | Text mention | ✅ Visual badges |
| WhatsApp CTA | Floating button | Footer link | ✅ Floating all pages |

## Critical Client Data Gaps

### 🔴 Urgent — blocks page creation
1. **Factory info**: size (sqm), employee count, annual production capacity, R&D headcount — none provided
2. **Case study projects** (critical gap): real photos+locations, project/client names, products used, challenge/solution/result per project
3. **Product assets**: white-bg photos, demo videos, full spec sheets, top-3 SEO-priority products confirmed
4. **Company assets**: hero video, factory photos, team photos, exhibition booth photos (2023–2025), certificate scans

### 🟡 Important — needed for quality
Notable clients/reference projects, awards/press mentions, company registration doc,
final export country list, blog content strategy (client vs Napollo-written)
