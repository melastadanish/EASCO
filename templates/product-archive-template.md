# TEMPLATE — Product Archive Page (Category Listing)

**Copy this template when creating a new product category listing page.**
**Word count target: 800–1,200 words**
**URL pattern: szeasco.com/[category-slug] (first-level, no subfolder)**

---

## Pass Log Header (Add when complete)

```
---
Status: READY FOR DEVELOPMENT
Pass A: [score]/10
Pass B: [X fixes applied]
Pass N: [X/Y terms present]
Pass D: AI-quotable ✅ | FAQ [X] Q&As | Authority ✅ | GEO ✅
Pass C: Headlines ✅ | Objections ✅ | CTAs ✅ | AI-score [X]%
Last Updated: YYYY-MM-DD
---
```

---

## Page Metadata

```
Target URL:           /[category-slug]/
Primary Keyword:      [Main keyword — used in H1 only]
Secondary Keywords:   [2–4 supporting keywords]
Search Intent:        Commercial Investigation
Word Count Target:    800–1,200 words
Meta Title:           [Primary Keyword] — EASCO (max 60 chars)
Meta Description:     [Category benefit] + [primary keyword] + CTA (max 160 chars)
Silo:                 S[number] — [Name]
Primary Segment:      [From buyer-segment-table.md]
Differentiators:      [D-codes — minimum 2]
Objections:           [O-codes covered]
Schema Type:          ItemList
Status:               🔲 To Do
```

---

## Section Checklist

- [ ] Breadcrumb written
- [ ] H1 = primary keyword only, no additions
- [ ] Category specs callout complete (3 specs, all traced to client-data-map.md)
- [ ] Certification icons listed
- [ ] All product cards complete
- [ ] Application strip complete with internal links
- [ ] Micro-CTA written
- [ ] Resources strip complete (all 3 cards)
- [ ] FAQ: minimum 3 questions, maximum 5
- [ ] Minimum 2 differentiators explicit
- [ ] All numbers traced to client-data-map.md
- [ ] Internal links complete
- [ ] Pass A score ≥ 8.0/10
- [ ] Pass B fixes applied
- [ ] Pass N complete
- [ ] Pass D complete
- [ ] Pass C complete

---

## SEO Block

```
H1:               [Primary keyword — exact match, no additions]
H2 (Products):    [Category Name] Product Range
H2 (Apps):        Industries We Serve
H2 (FAQ):         Frequently Asked Questions
Meta Title:       [Primary Keyword] — EASCO | [max 60 chars]
Meta Description: [Lead benefit]. Explore EASCO's [category] range — [key spec]. [CTA]. [max 160 chars]
Alt Text (hero):  [Category name] by EASCO — [one key spec]
```

---

## BREADCRUMB

**Copy block:**

Home › [Category Name]

*Write as plain text. Developer renders as schema-marked breadcrumb trail.*

---

## S1 — CATEGORY HEADER HERO

**Layout:** Two-column. Left: copy block. Right: category hero image.
**Word count: 80–120 words**

**Left column — copy:**

[H1: Primary Keyword — exact match, nothing added before or after]

[2–3 sentence intro. State what the category is, who it is for, and the single most important reason to choose EASCO for this category. Do not use filler phrases. Lead with the buyer's problem or the strongest spec.]

**Category Specs Bar (3 specs, horizontal row):**

| Spec Label | Value | Spec Label | Value | Spec Label | Value |
|---|---|---|---|---|---|
| [e.g. Throughput] | [e.g. Up to 45 persons/min] | [e.g. IP Rating] | [e.g. IP54] | [e.g. Comm. Protocol] | [e.g. RS485 + TCP/IP] |

*All values must be traced to client-data-map.md before publishing.*

**Certification Icons Row:**

[List applicable certs as text labels — developer renders as icons]
Example: CE Certified | ISO 9001 | RoHS Compliant | FCC

**Right column:**

[Hero image of the category — placeholder if asset not yet available]
Alt text: [Category name] by EASCO — [one key spec]

---

**Tier 1 Checks — S1**
- [ ] H1 is primary keyword only — no prefix or suffix added
- [ ] Intro opens with buyer problem or strongest spec — no filler
- [ ] All 3 spec values traced to client-data-map.md
- [ ] Certifications listed match confirmed certs only — no unverified claims
- [ ] Differentiator present (minimum 1 of the 3 specs must reflect a D-code)

---

## S2 — PRODUCT GRID

**Layout:** 3 cards per row on desktop. Each card is one product.
**Word count: 30–50 words per card**

**Repeat this card block for every product in the category:**

---

**[Product Name]**
[Model Number]

- [Key Spec 1 — decision-relevant]
- [Key Spec 2 — decision-relevant]
- [Key Spec 3 — decision-relevant]

Best for: [One line — specific use case or buyer type]

[Application Tags: Office | Airport | School | Factory — include only applicable tags]

[CTA: View Product] → links to /[category-slug]/[product-slug]/
[CTA: Request Quote] → WhatsApp pre-filled: "Hi, I'm interested in [Product Name]"

---

*End of card block. Repeat for each product. Minimum 2 products, maximum 12.*

---

**Tier 1 Checks — S2**
- [ ] Every product has exactly 3 specs — all traced to client-data-map.md
- [ ] Best-for line is specific — not generic ("ideal for high-traffic venues" not "great for many uses")
- [ ] Application tags match the product's actual deployment contexts
- [ ] WhatsApp CTA pre-fill text includes the exact product name
- [ ] View Product link points to the correct product page slug

---

## S3 — APPLICATIONS STRIP

**H2: Industries We Serve**
**Layout:** Horizontal icon row or card row. Each item = one industry with a link.
**Word count: 40–60 words total (intro line + labels)**

[1–2 sentence intro. State that these products are deployed across the following sectors. Keep it factual.]

Example: EASCO [category name] are installed across a wide range of industries. Select your sector to see recommended configurations and case references.

**Industry tiles (include only confirmed deployments):**

| Icon | Industry Label | Link |
|---|---|---|
| [icon placeholder] | Corporate Offices | /industries/corporate-offices/ |
| [icon placeholder] | Schools & Universities | /industries/schools-universities/ |
| [icon placeholder] | Hospitals | /industries/hospitals/ |
| [icon placeholder] | Government Buildings | /industries/government-buildings/ |
| [icon placeholder] | Warehouses & Factories | /industries/warehouses/ |
| [icon placeholder] | Construction Sites | /industries/construction-sites/ |

*Remove any industry row that EASCO cannot support with confirmed product data or a case reference.*

---

**Tier 1 Checks — S3**
- [ ] Only confirmed deployment industries are listed — no aspirational entries
- [ ] Every industry tile links to an existing or planned industry page (slug confirmed in sitemap.md)
- [ ] Intro sentence does not repeat H1 keyword — use a natural variant
- [ ] No industry listed without at least one applicable product from S2
- [ ] Section heading is H2

---

## S4 — "NEED AN EXPERT OPINION?" MICRO-CTA

**Layout:** Single full-width band. Short copy + two CTAs side by side.
**Word count: 25–40 words**

**H3: Not sure which [category name] is right for your project?**

[1 sentence. Acknowledge the decision complexity briefly. Offer the expert consultation without pressure.]

Example: Our technical team reviews your site layout, throughput requirements, and integration stack — then recommends the right configuration.

[CTA 1: Talk to an Expert] → WhatsApp
[CTA 2: Send Your Requirements] → Contact / Quote form

---

**Tier 1 Checks — S4**
- [ ] H3 contains the category name — not a generic "our products"
- [ ] Body copy is one sentence only — no padding
- [ ] Both CTAs present — one WhatsApp, one form
- [ ] No discount or price promise made
- [ ] Tone is helpful, not pushy

---

## S5 — RESOURCES STRIP

**H2: Resources**
**Layout:** 3 equal cards, horizontal row.
**Word count: 15–25 words per card**

---

**Card 1 — Catalogue & Manuals**

[Icon placeholder]

Catalogue & Manuals

Download the full [category name] product catalogue, technical datasheets, and installation manuals.

[CTA: Download Now] → /downloads/ or relevant download page

---

**Card 2 — Guides & Blogs**

[Icon placeholder]

Guides & Blogs

Read our [category name] buying guides, comparison articles, and installation tips.

[CTA: Read Guides] → /blog/ or relevant pillar page

---

**Card 3 — Knowledge Base**

[Icon placeholder]

Knowledge Base

Find answers to common [category name] questions — specs, integrations, maintenance, and troubleshooting.

[CTA: Visit Knowledge Base] → /faq/ or dedicated knowledge base page

---

**Tier 1 Checks — S5**
- [ ] Each card has a headline, body line, and CTA — no card is incomplete
- [ ] Category name is used in each card body — not generic copy
- [ ] CTA links resolve to real or planned pages (confirm in sitemap.md)
- [ ] Word count per card does not exceed 25 words
- [ ] Icons noted for developer — placeholder acceptable if assets not ready

---

## S6 — FAQ

**H2: Frequently Asked Questions**
**Word count: 150–250 words total**
**Minimum 3 questions, maximum 5**

Write questions from the buyer's perspective. Prioritise questions that:
- Reflect a real buying objection (check objection-map.md)
- Are likely to be asked to an AI assistant (Perplexity, ChatGPT)
- Have not been answered in the product cards above

**Format:**

**Q: [Question as a buyer would phrase it]**
A: [Direct answer. 2–4 sentences. Include one spec or verifiable fact. End with a soft CTA if natural.]

---

*Repeat for each FAQ item.*

---

**Tier 1 Checks — S6**
- [ ] Minimum 3 questions present
- [ ] Every answer includes at least one verifiable fact or spec
- [ ] At least one question addresses a pricing or quality objection (from objection-map.md)
- [ ] At least one answer is written to be AI-quotable (clear, self-contained, factual)
- [ ] No answer ends with a hard sell — CTA is soft and optional

---

## Internal Links Required

Every published archive page must include these links:

| Link Type | Destination | Where it appears |
|---|---|---|
| Up — Pillar | /[silo-pillar-slug]/ | Breadcrumb + S1 intro |
| Down — Products | /[category]/[product-slug]/ | S2 product cards |
| Sideways — Related Silo | /[adjacent-category-slug]/ | S3 applications strip or S5 guides card |
| Industry Pages | /industries/[industry-slug]/ | S3 applications strip |
| Buying Guide | /[category]/buying-guide/ | S5 guides card |
| Download Center | /downloads/ | S5 catalogue card |

*Confirm all slugs in _system/sitemap.md before publishing.*
