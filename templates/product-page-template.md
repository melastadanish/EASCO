# TEMPLATE — Product Detail Page (Individual Model)

> Structural blueprint for EVERY individual product page (a specific model with a spec file).
> Do not invent new sections. Do not skip sections. Do not reorder sections.
> Content inside each section changes per product — the structure does not.
>
> This template is for PRODUCT DETAIL pages only.
> For CATEGORY (ARCHIVE) pages use: `templates/product-archive-template.md`
> The two templates are intentionally different — do not mix them.

---

## RULES — Read Before Writing

1. Read first: `_system/WritingSystem.md` · the product's spec file in `_system/product-specs/` · `_system/differentiator-card.md` · `_system/objection-map.md`
2. **Data source hierarchy:** `_system/product-specs/[model].md` (first) → `_system/client-data-map.md` (second) → `products data/` raw manual for this model (verify before use). If a number is in none of them, do not write it.
3. Every spec in the table must appear in the spec file. Unconfirmed value → ⚠️ mark or leave the row out. Never guess a model number.
4. URL: `/products/[category-slug]/[product-slug]/` — category slug from `_system/sitemap.md`.
5. **Pass N:** weave in this category's required semantic terms — `_system/WritingSystem.md` § "Pass N Term Lists by Product Category".
6. **Authority claims:** verbatim strings only — `_system/WritingSystem.md` § "Verbatim Authority Statements".
7. FAQ: exactly 8 questions covering the 8 required topics (see Section 9).
8. Minimum 2 differentiators explicit. Applicable objections answered.
9. Tier 1 checks after every section; five passes (A→B→N→D→C) on the compiled page; pass log header added on completion.

---

## Pass Log Header (Add when complete)

```
---
Status: READY FOR DEVELOPMENT
Pass A: [score]/10
Pass B: [n] fixes applied
Pass N: [n]/[n] terms present
Pass D: AI-quotable ✅ | FAQ 8 Q&As ✅ | Authority ✅ | GEO ✅
Pass C: All 6 tests ✅ | AI-score [n]%
Last Updated: YYYY-MM-DD
---
```

---

## Page Metadata (Fill before writing)

```
Target URL:        /products/[category-slug]/[product-slug]/
Primary Keyword:   [product type + model — e.g. "ESFAT alcohol detection attendance terminal"]
Secondary Keywords: [2–4]
Schema Markup:     Product (JSON-LD below)
Search Intent:     Commercial (Transactional)
Word Count Target: 800–1,500 words
Meta Title:        [Product Name] — EASCO (max 60 chars)
Meta Description:  [Product] + [key spec] + [CTA] (max 155 chars)
Category:          /products/[category-slug]/
Model Number:      [from _system/product-specs/ — ⚠️ if unconfirmed]
Spec File:         _system/product-specs/[file].md
Primary Segment:   [from _system/buyer-segment-table.md]
Differentiators:   [D-numbers]
Objections:        [O-numbers]
Status:            🔲 To Do
```

---

## Section Count: 11 sections + internal links + schema

---

### SECTION 1 — Product Header
**Design:** 50/50 split. Gallery left (3–5 images), copy right. White background.

- Breadcrumb: `Home › Products › [Category] › [Product]`
- H1: [Product Name — exact target keyword, includes model]
- One-line value proposition: key outcome, max 15 words, one verified spec
- Trust badges: ✔ ISO 9001:2015 · CE · FCC | ✔ Factory Direct | ✔ OEM/ODM Available
- Quick contact: [WhatsApp](https://wa.me/8613711422283) · [Email](mailto:hwenyin280@gmail.com) · [Get Quote](#)
- Gallery alt texts (each): EASCO [model] [product type] — [angle/feature shown]

---

### SECTION 2 — Product Overview
**Design:** H2 + 2 paragraphs. White background.
**H2:** [Outcome-led headline]

**MUST open with the AI-quotable paragraph** — self-contained:
> EASCO [model] [capability] — [key spec] — [use case] — [differentiator]. Manufactured in Shenzhen, ISO 9001:2015 certified.

Then 1–2 paragraphs: who buys it, what problem it solves, where it sits in the range (vs sibling models).

---

### SECTION 3 — Key Features
**Design:** H2 + 4–6 feature cards or bullet blocks. Light grey background.
**H2:** [Outcome-led headline]

4–6 features, benefit-first, each paired with a spec from the spec file:
- **[Benefit-led feature title]:** [Benefit sentence. Verified spec.]

Order by buyer priority (core function → security → integration → convenience).

---

### SECTION 4 — Technical Specifications
**Design:** H2 + full-width 2-column spec table. White background.
**H2:** [Model] Technical Specifications

All values from the spec file. Include only rows that exist in the spec file; ⚠️ for unconfirmed:

| Parameter | Specification |
|---|---|
| Model No. | |
| Dimensions (W×D×H mm) | |
| Material / Housing | |
| Throughput / Recognition Speed | |
| Passage Width / Recognition Distance | |
| Capacity (faces / templates / users) | |
| IP Rating | |
| Operating Temperature / Humidity | |
| Power Supply / Consumption | |
| Communication Interfaces | |
| Display / OS | |
| Certifications | |

**CTA:** Download the [model] specification sheet or request it on WhatsApp

---

### SECTION 5 — Variants & Configurations
**Design:** H2 + small table or cards. Light grey background. *(Remove section if the model has no variants.)*
**H2:** [Model] Variants

One row/card per variant (e.g. LCD vs LCD+Face, single vs dual lane, wall-mount vs desktop): what changes, what stays the same, which sites each fits.

---

### SECTION 6 — Applications
**Design:** H2 + 3–4 environment blocks. White background.
**H2:** [Outcome-led headline]

3–4 deployment environments — for each: why THIS model fits + one spec. Link each environment to its `/solutions/[industry]/` page with keyword anchor text.

---

### SECTION 7 — Integration
**Design:** H2 + short list. Light grey background.
**H2:** Integration With Your Platform

- Protocols this model supports (from spec file only): Wiegand / RS485 / TCP/IP / dry contact / SDK
- 1–2 sentences: what an integrator needs to know (offline mode, API, third-party software compatibility)

---

### SECTION 8 — OEM & Custom Options
**Design:** H2 + 1 paragraph + CTA. White background. *(Remove if OEM not applicable.)*
**H2:** OEM and Custom Options

80–100 words: what can be customized (housing, branding, firmware, display, interfaces) — prototype in 30–45 days (D6). CTA: Discuss OEM requirements → /oem-odm/

---

### SECTION 9 — FAQ
**Design:** H2. Accordion. First item open.
**H2:** [Model] — Frequently Asked Questions

Exactly 8 questions, one per required topic:
1. Core spec capability (this model's headline number)
2. How it works (mechanism / recognition process)
3. Difference vs sibling model (why choose this one)
4. Lead time + shipping
5. MOQ / order volume
6. Integration / compatibility
7. Pricing factors
8. Comparison vs ZKTeco / Hikvision equivalent (spec-to-spec)

Each answer: 3–5 sentences, direct answer first, one verified number, self-contained.

---

### SECTION 10 — Related Products
**Design:** H2 + 3 cards. Light grey background.
**H2:** Related Products

- Back to [Category] → `/products/[category-slug]/` (keyword anchor)
- 2 sibling or complementary products with one-line descriptions

---

### SECTION 11 — Final CTA
**Design:** Full-width dark. H2 + short paragraph + CTA row.
**H2:** Get Pricing for [Product Name]

50–70 words: exactly what to send (quantity, destination, integration needs) and what they get back (quote, spec sheet, model recommendation) — reply within 1 hour during business hours.

> **Request pricing for [model] — tell us your quantity and destination**
> [WhatsApp](https://wa.me/8613711422283) · [Email](mailto:hwenyin280@gmail.com) · [Inquiry Form](#)

---

## Internal Links Required

- [ ] Up to category archive: `/products/[category-slug]/` — keyword anchor
- [ ] 2–3 sibling/related product pages
- [ ] 1–2 `/solutions/[industry]/` pages from Section 6
- [ ] OEM/ODM page if Section 8 present

---

## Schema Markup (JSON-LD)

```json
{
  "@context": "https://schema.org/",
  "@type": "Product",
  "name": "PRODUCT NAME",
  "model": "MODEL NUMBER",
  "image": ["IMAGE_URL_1", "IMAGE_URL_2"],
  "description": "AI-quotable paragraph from Section 2",
  "brand": { "@type": "Brand", "name": "EASCO" },
  "manufacturer": {
    "@type": "Organization",
    "name": "Shenzhen Easco Intelligent Equipment Co., Ltd.",
    "url": "https://www.szeasco.com"
  },
  "offers": {
    "@type": "Offer",
    "availability": "https://schema.org/InStock",
    "priceCurrency": "USD",
    "seller": { "@type": "Organization", "name": "EASCO" }
  }
}
```
