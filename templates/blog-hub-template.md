# TEMPLATE — Blog Hub

**For the single top-level hub page linking to all blog articles**
**Word count target: 300–500 words (excluding post cards)**

---

## Pass Log Header (Add when complete)

```
---
Status: READY FOR DEVELOPMENT
Pass A: [score]/10
Pass B: [X fixes applied]
Pass N: [X/Y terms present]
Pass D: AI-quotable ✅ | Authority ✅ | GEO ✅
Pass C: Headlines ✅ | CTAs ✅ | AI-score [X]%
Last Updated: YYYY-MM-DD
---
```

---

## Page Metadata

```
Target URL:        /blog/
Slug:              blog
Primary Keyword:   access control blog
Secondary Keywords: turnstile gate guides, biometric access control articles
Schema Markup:     CollectionPage
Search Intent:     Informational / Navigational
Word Count Target: 300–500 words
SEO Title:         Access Control & Biometrics Blog | EASCO
SEO Description:   Guides on turnstiles, biometric access control, and OEM manufacturing from EASCO — filter by category to find the right article.
Primary Segment:   All segments
Status:            🔲 To Do
```

---

## Section Checklist

- [ ] Section 1 — Banner (H1 + description) — written, Tier 1 ✅, approved
- [ ] Section 2 — Left Sidebar Filter (categories) — written, Tier 1 ✅, approved
- [ ] Section 3 — Posts Grid (cards) — written, Tier 1 ✅, approved
- [ ] Section 4 — CTA — written, Tier 1 ✅, approved
- [ ] Pass A complete
- [ ] Pass B complete
- [ ] Pass N complete
- [ ] Pass D complete
- [ ] Pass C complete

---

## Content

---

### SECTION 1 — Banner

**H1: Access Control & Biometrics Blog**

[1–2 sentence description. What this blog covers and who it's for — buyers researching before they have a spec, not yet ready to request a quote.]

**Tier 1 checks:** ☐ Banned phrases ☐ Claims verified ☐ Readability ☐ Benefit-first

---

### SECTION 2 — Left Sidebar Filter

*(Persistent left-hand filter listing blog categories. Filtering the Posts Grid in Section 3, not a separate page per category.)*

- All Posts
- Aluminum Alloy Turnstile
- Stainless Steel Turnstile
- Facial Recognition
- Handheld Device
- Gate Opener
- General / Buying Guides *(cross-cutting topics — OEM/ODM, comparisons, industry-specific guides that don't map to one product category)*

**Tier 1 checks:** ☐ Claims verified (each filter maps to at least one published post)

---

### SECTION 3 — Posts Grid

*(Card grid, right side of the sidebar. One card per post.)*

**Card structure per post:**
- Post title
- 1-line excerpt (not the full intro — a distinct teaser sentence)
- Category tag (matches a sidebar filter)
- [Read More] → links to the post

**Tier 1 checks:** ☐ Claims verified (links resolve) ☐ CTA (Read More on every card)

---

### SECTION 4 — CTA

**H2: Have a Project-Specific Question?**

[Short line — these articles cover the general case; a direct conversation gets a faster answer for a specific facility or spec.]

> **[Ask EASCO Directly]**
> [WhatsApp: +86 13711422283](https://wa.me/8613711422283) · [Email: hwenyin280@gmail.com](mailto:hwenyin280@gmail.com) · [Request Quote](/quote/)

**Tier 1 checks:** ☐ Banned phrases ☐ Claims verified ☐ Readability ☐ Benefit-first ☐ CTA

---

## Internal Links Required

- [ ] Sidebar filters map to real categories with at least one post each
- [ ] Every post card links to its article
- [ ] Link to Products Hub
- [ ] Link to Contact page

---

## Schema Markup (JSON-LD)

```json
{
  "@context": "https://schema.org/",
  "@type": "CollectionPage",
  "name": "Access Control & Biometrics Blog — EASCO",
  "description": "EASCO blog covering turnstiles, biometric access control, and OEM manufacturing.",
  "mainEntity": {
    "@type": "ItemList",
    "itemListElement": []
  }
}
```
