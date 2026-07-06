# TEMPLATE — Product Archive Page (Category Listing)

> Structural blueprint for EVERY product category page and the Products Hub.
> Do not invent new sections. Do not skip sections. Do not reorder sections.
> Content inside each section changes per category — the structure does not.
>
> This template is for CATEGORY (ARCHIVE) pages only.
> For individual PRODUCT DETAIL pages use: `templates/product-page-template.md`
> The two templates are intentionally different — do not mix them.

---

## RULES — Read Before Writing

1. Read first: `_system/WritingSystem.md` · `_system/VERIFIED-COMPANY-DATA.md` · `_system/product-specs/_index.md` · `_system/differentiator-card.md` · `_system/objection-map.md` · `_system/competitors.md`
2. **Data source hierarchy:** `_system/product-specs/[model].md` (first) → `_system/client-data-map.md` (second) → `products data/` raw manuals (verify before use). If a number is in none of them, do not write it.
3. **H1** = primary keyword only. Nothing added before or after. Slug must match `_system/sitemap.md` exactly.
4. List ONLY products with a spec file in `_system/product-specs/` or confirmed data in `_system/client-data-map.md`. Unconfirmed model number → ⚠️ note, never a guess.
5. **Certifications** = confirmed only: ISO 9001:2015 · ISO 14001 · ISO 45001 · CE · FCC. Banned until client confirms: ROHS badge, IP54 badge (product-level IP ratings only from spec files), "20+ years" (use 16+).
6. **Product cards** = model + best-for + 3 key specs + CTAs. Full spec tables belong on product detail pages.
7. **Pass N:** weave in the required semantic terms for this category — see `_system/WritingSystem.md` § "Pass N Term Lists by Product Category".
8. **Authority claims:** verbatim strings only — see `_system/WritingSystem.md` § "Verbatim Authority Statements".
9. Minimum 2 differentiators from `_system/differentiator-card.md` explicit in body copy. Applicable objections from `_system/objection-map.md` answered — primarily in FAQ.
10. FAQ: exactly 10 questions covering all 8 required topics (see S11).
11. No banned phrases — `_system/WritingSystem.md` §3. All Tier 1 checks per section, five passes (A→B→N→D→C) on the compiled page.

---

## Pass Log Header (Add when five-pass complete)

```
---
Status: READY FOR DEVELOPMENT
Pass A: [score]/10
Pass B: [n] fixes applied
Pass N: [n]/[n] terms present
Pass D: AI-quotable ✅ | FAQ 10 Q&As ✅ | Authority ✅ | GEO ✅
Pass C: All 6 tests ✅ | AI-score [n]%
Last Updated: YYYY-MM-DD
---
```

---

## Page Metadata (Fill before writing)

```
Target URL:           /products/[category-slug]/   ← from _system/sitemap.md
Primary Keyword:      [from seo/keyword-master-list.md §4 — exact match]
Secondary Keywords:   [3–5 from same cluster]
Search Intent:        Commercial Investigation
Word Count Target:    1,200–1,800 words
Meta Title:           [Primary Keyword] | EASCO — Factory Direct from Shenzhen (max 60 chars)
Meta Description:     Benefit-led, primary keyword in first 10 words (max 155 chars)
Primary Segment:      [from _system/buyer-segment-table.md]
Differentiators:      [min 2 — D-numbers]
Objections:           [O-numbers covered]
Data Sources:         [list the _system/product-specs/ files used]
Schema Type:          ItemList
Status:               🔲 To Do
```

---

## Section Count: 12 sections + breadcrumb + internal links

---

## BREADCRUMB

`Home › Products › [Category Name]`

---

## S1 — Category Hero
**Design:** 50/50 split. Text left, category hero image right. White background.
- Label tag above H1: `[CATEGORY NAME]`
- H1: [Primary Keyword — exact match]
- Subheading: 1–2 sentences. Sentence 1: buyer problem or hook. Sentence 2: EASCO differentiator with one verified spec. Do not repeat stats-bar numbers.
- Trust badges: ✔ Founded 2009 | ✔ ISO 9001:2015 · CE · FCC | ✔ 63 Patents
- CTA Primary: Request a quote for [category] — reply within 1 hour during business hours
- CTA Secondary: Compare models and specifications below
- Alt text: EASCO [category] — [one key spec], factory direct from Shenzhen

---

## S2 — Stats Bar
**Design:** 4-stat callouts. Dark background. Full width.
- Stat 1: 16+ Years | Manufacturing Experience
- Stat 2: 80,000+ | Installations Worldwide
- Stat 3: [Most relevant verified CATEGORY spec — e.g. 0.5 s opening · 1-in-10,000,000 misrecognition · 45 persons/min]
- Stat 4: 50+ Countries | Export Destinations

> All from `_system/VERIFIED-COMPANY-DATA.md` or a product spec file. Nothing else.

---

## S3 — What Is [Category]?
**Design:** H2 left-aligned. 2-column — body text left, image right. White background.
**H2:** What Is a [Category Name]?

**MUST open with the AI-quotable paragraph** — self-contained, contains ALL of:
- Brand name: EASCO
- Category name (exact keyword)
- One verified spec
- Location: Shenzhen, China
- One differentiator (factory direct · 63 patents · multi-modal biometrics)
- Certification: ISO 9001:2015

Then 2–3 additional paragraphs:
- Para 2: Plain-English explanation of how the product type works
- Para 3: What separates a capable unit from a cheap one (mechanism, sensor, firmware) — PAS structure
- Para 4: Experience signal — real deployment context + founded December 2009

---

## S4 — Product Grid
**Design:** H2 centred. 2–4 column product card grid. Light grey background.
**H2:** [Buyer action phrase — e.g. "Choose Your Gate", not a category label]

One card per product (verified products only). Each card:
- Product photo — alt text: EASCO [model] [product type] — [distinguishing feature]
- Product name + Model: [Model Number — or ⚠️ if unconfirmed]
- Best for: one sentence — venue type, buyer problem, why this model over the others
- 3 key specs as short lines (from the product's spec file)
- View the [Product Name] → `/products/[category-slug]/[product-slug]/`
- Request a quote → WhatsApp +86 13711422283 (pre-fill: "Hi, I'm interested in [Product Name] [Model]")

---

## S5 — Which Model Fits Your Project?
**Design:** H2. Full-width comparison table. White background.
**H2:** Which [Category Name] Fits Your Site?

Comparison table — one column per model, rows:
- Best for (site type / scenario)
- Key spec 1 (throughput / recognition speed / accuracy)
- Key spec 2 (passage width / capacity / range)
- Material / housing
- Indoor / outdoor (IP rating only if in spec file)
- Integration (Wiegand / RS485 / TCP/IP — as verified per model)

Closing note: name the specific inputs the buyer should send — site layout, daily footfall, lane count, integration requirements — WhatsApp +86 13711422283, reply within 1 hour during business hours.

---

## S6 — Applications & Industries
**Design:** H2. Left: applications table (Deployment | Why This Category). Right: industry label grid linking to solution pages. White background.
**H2:** Where [Category Name] Is Deployed

- Applications table: minimum 5 rows (office lobby, campus entrance, metro station, factory gate, hospital reception — as relevant)
- One intro sentence naming what differs by industry — throughput demands, compliance, integration constraints
- Industry labels link to `/solutions/[industry]/`: Commercial Buildings · Smart Campus · Transportation · Hospitals · Factories · Government (only industries in sitemap.md)

---

## S7 — Integration & Protocols
**Design:** H2. 2-column — protocol list left, plain-English explanation right. Light grey background.
**H2:** Works With Your Existing Access Control System

- List only protocols verified in the spec files: Wiegand, RS485, TCP/IP, dry contact, SDK/API (as applicable per category)
- One sentence per protocol: what it means for the integrator
- Answer the third-party software objection here (objection-map)

---

## S8 — Quality & Certifications
**Design:** Dark background. H2 + 3-step layout. White text.
**H2:** Quality Control From a National High-Tech Enterprise

- Step 1 — R&D: 10+ R&D engineers · 63 patents · 5 software copyrights
- Step 2 — Manufacturing: 3,000+ m² Shenzhen factory · integrated R&D, manufacturing, and sales
- Step 3 — Certification: ISO 9001:2015 · ISO 14001 · ISO 45001 · CE · FCC

---

## S9 — Why EASCO
**Design:** H2. 2-column — large feature card with stat left, 5-item accordion right. White background.
**H2:** Why Buyers Specify EASCO [Category Name]

**Feature card (left):** Stat: Founded 2009 · Heading + 2–3 sentences with deployment proof (80,000+ installations across 50+ countries).

**Accordion (right — exactly 5 items):** pick 5 from `_system/differentiator-card.md` — minimum 2 primary (D1–D8) + category-relevant secondary (D14 anti-crushing for turnstiles, D5 liveness for face terminals, D9 0.5 s opening for cylindrical, D11 for alcohol detection). Each item: bold specific title + 2–4 sentence body. Never open an item with "We".

---

## S10 — OEM/ODM Strip
**Design:** Full-width banner. H3 + 1 paragraph + CTA. Light grey background.
- H3: Need Custom Housing, Firmware, or Branding?
- Body: OEM/ODM available — prototype in 30–45 days (D6). One sentence on what can be customized for this category.
- CTA: Send your OEM requirements → hwenyin280@gmail.com

---

## S11 — FAQ
**Design:** H2. Accordion. White background. First item open.
**H2:** [Category Name] — Frequently Asked Questions

Exactly 10 questions. Written as a buyer would type into Google or ChatGPT. Must cover all 8 required topics:
1. Core spec capability (throughput / accuracy / speed)
2. Process explanation (how does [product type] work)
3. Model options (which models, what's the difference)
4. Lead time + shipping
5. Order volume / MOQ
6. Integration (protocols, third-party software)
7. Cost / pricing factors (what drives the quote)
8. Comparison (vs ZKTeco or Hikvision — spec-to-spec, from `_system/competitors.md`)

Remaining 2: category-specific (fire-safety fail-open for turnstiles, low-light performance for face terminals, etc.)

Each answer: 3–5 sentences · direct answer first · self-contained · at least one verified number · soft CTA only if natural.

---

## S12 — Final CTA
**Design:** Full-width dark. H2 + subtext + bullets + primary CTA + WhatsApp.
**H2:** Get a [Category Name] Quote — Reply Within 1 Hour

**Subtext:** 1–2 sentences — what to send (model, quantity, destination) + response promise.

**Bullets (4–5, all verified):**
- ✅ Factory direct from Shenzhen — no trading company
- ✅ ISO 9001:2015 · CE · FCC certified
- ✅ 80,000+ installations across 50+ countries
- ✅ [Category-specific verified spec]
- ✅ OEM/ODM available — prototype in 30–45 days

**CTA Button:** Request a quote for [category]
**WhatsApp:** +86 13711422283 · **Email:** hwenyin280@gmail.com

---

## Internal Links Required

- **Up:** Products Hub (`/products/`)
- **Down:** every product detail page in this category
- **Across:** 2–3 relevant `/solutions/[industry]/` pages
- **Resources:** 1–2 relevant blog posts
- Anchor text = exact target keyword of the destination page. Never "click here" / "learn more".

---

## Section Checklist (Tick before five-pass)

- [ ] Breadcrumb + H1 exact keyword, slug matches sitemap.md
- [ ] S2 stats all verified
- [ ] S3 opens with complete AI-quotable paragraph
- [ ] S4 cards: verified products only, no spec dumps
- [ ] S5 comparison table complete per model
- [ ] S6 links to solution pages with keyword anchors
- [ ] S7 protocols verified per spec files
- [ ] S8 verbatim authority statements only
- [ ] S9 exactly 5 accordion items, min 2 primary differentiators, no "We" openers
- [ ] S11 exactly 10 FAQs covering all 8 topics
- [ ] S12 bullets all verified
- [ ] Internal links complete with keyword anchors
- [ ] Tier 1 checks passed per section
