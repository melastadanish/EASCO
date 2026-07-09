# INSTRUCTIONS.md — Full Workflow

## Pre-Work (read before writing any page)
1. `_system/WritingSystem.md` — brand voice, copy rules, quality system
2. `_system/client-data-map.md` — every spec number must be verified here
3. `_system/differentiator-card.md` — min 2 differentiators per page
4. `_system/objection-map.md` — Pass C objection coverage test
5. `_system/buyer-segment-table.md` — primary segment for this page
6. `_system/sitemap.md` — confirm URL slug
7. Matching template (see table in `_system/MEMORY.md`)

## Page Development Workflow

### Step 0 — Brief
- Identify primary buyer segment (`_system/buyer-segment-table.md`)
- Map keyword slot (`seo/keyword-master-list.md`, if available)
- Confirm section outline with user before writing

### Step 1 — Write
- Follow template structure
- Run 5 Tier 1 checks after every section before moving on
- Don't show a section until it passes all 5

### Step 2 — Five-Pass Review
- **Pass A** — full-page quality audit (6 dimensions, scored)
- **Pass B** — surgical rewrite (fix Pass A failures only)
- **Pass N** — NLP semantic coverage (access control terminology)
- **Pass D** — E-E-A-T / GEO check (AI-quotable paragraph, FAQ, authority signals)
- **Pass C** — conversion review (6 tests, objection coverage, AI-written score ≤15%)

### Step 3 — Save & Track
- Add pass log header to top of page file
- Update `_system/progress.md` to ✅
- Commit: `[WRITE] filename.md — five-pass complete`
- Push to main

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
| # | Page | URL | Template |
|---|---|---|---|
| 01 | Homepage | / | other-page-template.md |
| 02 | Why Us / About | /why-us/ | other-page-template.md |
| 03 | Products Hub | /products/ | other-page-template.md |
| 04 | Solutions by Industry | /solutions/ | solution-page-template.md |
| 05 | Case Studies ⚠️ BLOCKED | /case-studies/ | case-study-template.md |
| 06 | Resources / Gallery | /resources/ | other-page-template.md |
| 07 | Blog | /blog/ | blog-template.md |
| 08 | Contact | /contact/ | other-page-template.md |
| 09 | Request Quote | /quote/ | other-page-template.md |

### Solutions by Industry (6): Commercial Buildings, Smart Campus/Schools,
Transportation Hubs, Hospitals, Factories/Warehouses, Government Buildings
URL: `/solutions/[industry-name]/`

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
