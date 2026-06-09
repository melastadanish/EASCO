# Reusable Sections Library

**Parent:** [[README]]
**Rule:** Always check this file before starting any new page. After finishing a page, add any reusable sections here.

---

## How to Use
1. Before writing a new page → scan this file for sections you can drop in directly
2. After writing a new page → identify sections that could be reused and add them below
3. Reference format in page files: `*(reused from [[reusablesections]])*`

---

## RS-01 — CTA: Request a Quote

**Used on:** All product pages, pillar pages, why-choose-us
**Placement:** Bottom of page, after FAQ

```markdown
### Get a Quote for [PRODUCT NAME]

Tell us your quantity and project requirements. We respond within 24 business hours.

| Channel | Contact |
|---|---|
| 💬 WhatsApp | [+86 13711422283](https://wa.me/8613711422283) |
| 📧 Email | [hwenyin280@gmail.com](mailto:hwenyin280@gmail.com) |
| 📋 Inquiry Form | [Request a Quote](/request-quote/) |
```

---

## RS-02 — Company Trust Block

**Used on:** Pillar pages, about-us, why-choose-us, factory
**Placement:** Mid-page or before CTA

```markdown
### Why EASCO?

Shenzhen Easco Intelligent Equipment Co., Ltd. has 20 years of experience manufacturing
access control and security hardware. Factory direct — no middlemen. ISO certified.
OEM/ODM available for custom projects.

- ✅ 20 years manufacturing experience
- ✅ Factory direct pricing
- ✅ ISO 9001 · CE · FCC · RoHS certified
- ✅ OEM/ODM customisation available
- ✅ Global shipping · Full after-sales support
```

---

## RS-03 — FAQ Schema Note

**Used on:** All pages with FAQ sections
**Placement:** Above the FAQ H2

```markdown
> The following Q&A is eligible for [FAQPage schema markup](https://schema.org/FAQPage).
> Add JSON-LD to the page `<head>` using the template in [[templates/cluster-page-template]].
```

---

## RS-04 — Internal Link Footer Block

**Used on:** All cluster pages
**Placement:** Very bottom, after CTA

```markdown
---
**Related Pages**
- [Turnstile Gates Overview](/turnstile-gates/) — full range
- [Biometric Access Control](/biometric-access-control/) — face, palm & iris
- [Request a Quote](/request-quote/) — get pricing
- [Download Datasheet](/downloads/) — spec sheets & manuals
```

---

## RS-05 — Product Spec Table (Turnstile)

**Used on:** All turnstile product cluster pages
**Placement:** After H2: Technical Specifications

```markdown
| Parameter | Specification |
|---|---|
| Model No. | *(fill in)* |
| Dimensions (W×D×H mm) | *(fill in)* |
| Material | Aluminum Alloy / 304 Stainless Steel |
| Throughput | *(fill in)* persons/min |
| Power Supply | AC 100–240V, 50/60Hz |
| Power Consumption | *(fill in)* W |
| IP Rating | IP54 / IP65 |
| Operating Temperature | -20°C to +60°C |
| Communication | RS485 / Wiegand / TCP-IP |
| Biometric Interface | Yes — third-party module compatible |
| Certifications | CE · FCC · RoHS |
```

---

## RS-06 — Product Spec Table (Biometric Device)

**Used on:** Face recognition, palm vein, iris cluster pages
**Placement:** After H2: Technical Specifications

```markdown
| Parameter | Specification |
|---|---|
| Model No. | *(fill in)* |
| Recognition Technology | *(Face / Palm Vein / Iris)* |
| Recognition Speed | < 0.5 seconds |
| False Acceptance Rate (FAR) | < 0.0001% |
| False Rejection Rate (FRR) | < 0.1% |
| Liveness Detection | Yes — financial-grade |
| Display | *(fill in)* inch touchscreen |
| Camera | *(fill in)* MP, IR night vision |
| Communication | TCP/IP · RS485 · Wiegand · USB |
| Power Supply | DC 12V / PoE |
| Operating Temperature | -10°C to +55°C |
| Certifications | CE · FCC · RoHS |
```

---

## RS-07 — Applications List (Generic)

**Used on:** Pillar pages, product pages where application section is short
**Placement:** H2: Applications / Where to Use

```markdown
### Common Applications

- **Corporate offices & HQ campuses** — lobby and floor access control
- **Metro & transportation hubs** — high-throughput passenger flow management
- **Hospitals & healthcare** — restricted zone access, visitor management
- **Schools & universities** — student entry/exit tracking
- **Industrial factories** — shift attendance and safety zone access
- **Residential communities** — resident and visitor access management
- **Stadiums & event venues** — ticket validation and crowd flow
- **Government buildings** — high-security personnel access
```

---

## RS-08 — OEM/ODM Callout Block

**Used on:** Pillar pages, product pages, factory, why-choose-us
**Placement:** After specifications or before CTA

```markdown
### Need a Custom Version?

EASCO offers full OEM/ODM customisation — your logo, housing colour, software interface
and hardware configuration. Prototype in 30–45 days. Flexible MOQ.

→ [Learn about OEM/ODM Services](/custom-solutions/oem-odm/)
```

---

## RS-09 — Video Embed Placeholder

**Used on:** Product pages, pillar pages, how-to guides
**Placement:** After intro or within relevant section

```markdown
### See It in Action

*(Embed YouTube video here — add to [[video-center]] when uploaded)*

**Video:** [PRODUCT NAME] Demo — EASCO Factory
```

---

## RS-10 — Content Pass Checklist

**Used on:** Every page file during content writing workflow
**Placement:** Top of file, under Status block — remove before publishing

```markdown
#### Content Writing Checklist
- [ ] Section outline confirmed by user
- [ ] Pass 1 complete (technical depth)
- [ ] Pass 1 reviewed for AI detection patterns
- [ ] Pass 2 complete (humanised — varied rhythm, industry voice)
- [ ] Keyword count verified (5–6 minimum)
- [ ] FAQ has 5+ Q&A with long-tail keywords
- [ ] Internal links added (pillar + 2 cluster min.)
- [ ] Reusable sections checked from [[reusablesections]]
- [ ] Suggested new reusable sections added to [[reusablesections]]
- [ ] User confirmed final content before file saved
```

---

## Section Registry

| ID | Section Name | Used On |
|---|---|---|
| RS-01 | CTA: Request a Quote | All product + pillar pages |
| RS-02 | Company Trust Block | Pillar, about, why-choose-us |
| RS-03 | FAQ Schema Note | All pages with FAQ |
| RS-04 | Internal Link Footer | All cluster pages |
| RS-05 | Spec Table — Turnstile | S1 cluster pages |
| RS-06 | Spec Table — Biometric | S2 cluster pages |
| RS-07 | Applications List | Pillar + product pages |
| RS-08 | OEM/ODM Callout | Pillar, product, factory |
| RS-09 | Video Embed Placeholder | Product + pillar pages |
| RS-10 | Content Pass Checklist | Every page during writing |
