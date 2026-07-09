# WritingSystem.md — EASCO

> Master writing reference. Read before every page. Every rule here overrides any instinct.
> Consolidated from: client-brief.md + quality-check-system.md

---

## 1. Brand Voice

| Rule | EASCO Setting |
|---|---|
| Person | Second person — "your facility", "your project", "your security zone" |
| Tone | Direct, technical, grounded. Confident without being salesy. |
| Claims | Every claim backed by a verified spec number. Nothing unverified in copy. |
| Jargon | B2B buyers know: Wiegand, RS485, TCP/IP, IP65, FAR, FRR, ANPR, LPR, OEM/ODM. Use freely. Explain: liveness detection, crank-link transmission, multi-modal biometrics — explain inline. |
| Lead with | Buyer outcome first. "Processes 40 people per minute" — not "high throughput design." |
| Paragraph length | Max 3 sentences |
| Numbers | Embedded in sentences — never floated as standalone labels |
| Urgency | Never manufactured |
| First person plural | Never "We offer / We believe / We are proud" — write in second or third person |
| Sentence length | Max 25 words. Target: 30% short (5–10), 50% medium (11–20), 20% longer (21–25) |

---

## 2. Buyer Language Reference

| Use this | Not this |
|---|---|
| turnstile gate | access automation barrier |
| face recognition | facial biometric identification system |
| number plate camera | ANPR/LPR imaging device |
| attendance machine | time and attendance biometric terminal |
| OEM order | white-label procurement |
| factory direct | manufacturer-to-buyer supply chain |
| works outdoors | suitable for external deployment |

---

## 3. Prohibited Words & Phrases

Zero tolerance. If found, delete the entire sentence and rewrite with a spec number or outcome.

| Category | Banned |
|---|---|
| AI filler adjectives | cutting-edge, state-of-the-art, world-class, next-generation, innovative, revolutionary, game-changing, industry-leading, advanced (alone), powerful (alone), high quality, premium (alone), robust, seamless, seamlessly |
| Corporate verbs | leverage, elevate, empower, revolutionize, transform, optimize, streamline, unlock, harness, pioneer |
| Vague descriptors | reliable (without a spec number), durable (without a cycle count), versatile, flexible, comprehensive, holistic, end-to-end, tailor-made, bespoke |
| Opening clichés | In today's world, In the modern era, In an ever-changing landscape, In today's fast-paced, As technology evolves |
| Soft openers | Whether you're looking for, Look no further, If you're searching for, The good news is |
| False authority | Our team of experts, Dedicated team, Passionate professionals, Years of experience (without number), Trusted by thousands |
| Weak CTAs | Learn more, Click here, Find out more, Discover more, Read more, See more, Explore our range |
| Filler phrases | Don't hesitate to contact us, Feel free to reach out, We would love to hear from you |
| Brand chest-beating | At EASCO, we believe, We are proud to, We are committed to, Our mission is to |
| Emotional manipulation | Peace of mind, Don't miss out, Act now, Limited time |

---

## 4. Copywriting Framework — FAB Chain

Every sentence must complete the chain. Open with Benefit.

```
Feature:    What the product has
Advantage:  What it does differently
Benefit:    What the buyer's facility / operation gains
```

**Examples:**

| Level | Sentence |
|---|---|
| Feature only (fails) | "The gate uses crank-link transmission." |
| Benefit-first (passes) | "Nobody gets trapped. Crank-link transmission stops the gate the instant it meets resistance — mechanical, not software-dependent." |
| Feature only (fails) | "Iris recognition has a 1-in-10,000,000 FAR." |
| Benefit-first (passes) | "The wrong person cannot get in. Iris recognition misidentifies at a rate of 1 in 10,000,000 — the highest accuracy in commercial biometrics." |

---

## 5. Specificity Ladder

Every factual claim must reach Level 3 minimum. Level 4 is the target.

```
Level 1 (fails):  "Handles high throughput"
Level 2 (fails):  "Handles very high throughput"
Level 3 (passes): "Processes 45 persons per minute"
Level 4 (target): "Processes 45 persons per minute — fast enough to clear a 500-seat auditorium in under 12 minutes"
```

---

## 6. CTA Rules

Three-part test — all three must pass:
1. **Substitution test:** Replace CTA with "Click here." Same meaning = fail.
2. **Value exchange test:** Format — `[Action verb] + [specific thing reader gets]`
3. **Section alignment test:** CTA matches what the section just covered.

**Passing CTAs:**
- "Download the speed gate specification sheet"
- "Request a quote for your project volume and destination"
- "Compare all biometric systems side by side"
- "Send us your gate layout for a configuration recommendation"
- "Get pricing for your order quantity and shipping destination"

**Failing CTAs:**
- "Contact us" (acceptable only on Contact page)
- "Learn more"
- "View our products"
- "Get in touch"

One CTA per section maximum. CTA journey across a full page:
- Early page → orientation (find right product, compare options)
- Mid page → verification (download spec, datasheet, compare)
- End page → conversion (request quote, WhatsApp)

---

## 7. Contact Details (Use on Every Page)

| Channel | Detail |
|---|---|
| WhatsApp | +86 13711422283 |
| Email | hwenyin280@gmail.com |
| Skype | 1662258884@qq.com |
| LinkedIn | https://www.linkedin.com/feed/ |
| Facebook | https://www.facebook.com/turnstilemanufacturer/ |
| Address (EN) | Building 20, 2nd Floor, Dahe Industrial Zone, Huanguan South Road, Guanlan Street, Longhua New District, Shenzhen, Guangdong Province, China |
| Address (CN) | 广东省深圳市龙华新区观澜街道环观南路大和工业区20栋2楼 |

---

---

# QUALITY SYSTEM

---

## TIER 1 — Five Inline Checks (Run After Every Section)

Run all five before presenting a section to the user. Do not skip.

---

### Check 1 — Banned Phrase Scan

Read word by word against the prohibited list in Section 3.

**Pass:** Zero matches
**Fail:** Any match — remove and rewrite the entire sentence with a spec number or outcome.

---

### Check 2 — Claims Verification

Trace every factual claim to `_system/client-data-map.md`.
Every performance claim must reach Level 3 on the Specificity Ladder (Section 5).

**EASCO special rules:**
- Founding year (December 22, 2009) ✅ confirmed — use freely
- Countries served (50+) ✅ confirmed — use freely
- Certifications — use only what's ✅ in client-data-map.md's Certifications table (CE, ISO 9001/14001/45001 confirmed; RoHS/UKCA/EAC not yet)
- Iris FAR (1 in 10,000,000) ✅ — use freely
- Face recognition accuracy (99.98%) ✅ — use freely
- OEM prototype (30–45 days) — use with ⚠️ until client confirms

**Pass:** Every claim traced to client-data-map.md. Every claim at Level 3+.
**Fail:** Any unverified claim — remove or annotate with ⚠️.

---

### Check 3 — B2B Readability Test

**Test A — Technical term rule**
- Allowed without explanation: Wiegand, RS485, TCP/IP, IP65, FAR, FRR, ANPR, LPR
- Must explain inline: liveness detection, multi-modal biometrics, crank-link transmission, MTBF

**Test B — Sentence length**
Max 25 words. Distribution: 30% short / 50% medium / 20% longer.

**Test C — Active voice**
Every passive construction rewritten active.
- Passive: "Anti-crush protection is included."
- Active: "Anti-crush protection stops the gate the instant it meets resistance."

**Test D — Jargon ratio**
Every term that needs explanation explained in the same sentence.

**Pass:** All four tests pass.
**Fail:** Any test fails — fix before moving on.

---

### Check 4 — Benefit-First Test

Every sentence must open with what the buyer's facility gains. See FAB chain in Section 4.

**Pass:** Every sentence opens with buyer outcome.
**Fail:** Any sentence opens with product attribute before buyer benefit.

---

### Check 5 — CTA Specificity Test

Apply the three-part CTA test from Section 6.

**Pass:** All three parts pass. One CTA per section maximum.
**Fail:** Any part fails — rewrite before presenting.

---

## TIER 2 — Five-Pass System (Run After Full Page Compiled)

Tier 1 checks mean the page is already clean. Passes refine, not rescue.

---

### Pass A — Full-Page Quality Audit

Read the full page once. Mark every failure. Score six dimensions.

**Scoring:** 0 failures = 10/10 | 1 = 9/10 | 2–3 = 7–8/10 | 4–6 = 5–6/10 | 7–10 = 3–4/10 | 11+ = 1–2/10

**Six dimensions:**
1. **Clarity** — unexplained terms + sentences over 25 words
2. **Specificity** — unverified claims + Level 1/2 claims
3. **Human Voice** — banned phrases + same-word consecutive openings + assembled-sounding sentences
4. **Buyer Fit** — feature-first sentences + unexplained B2B jargon
5. **Benefit-First** — sentences where product feature appears before buyer benefit
6. **Originality** — repeated phrases + structural repetition clusters

```
PASS A AUDIT — [Page Name]
Clarity: [X]/10 — [note]
Specificity: [X]/10 — [note]
Human Voice: [X]/10 — [note]
Buyer Fit: [X]/10 — [note]
Benefit-First: [X]/10 — [note]
Originality: [X]/10 — [note]
Overall: [average]/10

Failure list for Pass B:
- [Section]: [exact sentence] — [check failed] — [fix instruction]
```

---

### Pass B — Surgical Rewrite

Fix Pass A failure list only. Do not rewrite passing sentences.

**Eight rules:**
1. No two consecutive sentences start with the same word
2. Every vague claim gets exact number from client-data-map.md
3. Sentences over 25 words — split at natural break
4. Every passive → active
5. Two ideas joined by "and" → test as two sentences
6. Read aloud after fixes — vary rhythm
7. Use buyer language, not engineering jargon
8. No urgency triggers — B2B buyers research over weeks

```
PASS B COMPLETE — [Page Name]
Items fixed: [count]
Sections touched: [list]
Items needing client data: [list — removed claim, noted data needed]
```

---

### Pass N — NLP Semantic Coverage (NEW)

Verify that the page contains the full cluster of terms a search engine / AI system associates with the topic. Thin semantic coverage = lower rankings and lower AI citation rate.

**Mandatory access control term clusters by page type:**

| Page Type | Required Terms |
|---|---|
| Turnstile pages | throughput (persons/min), passage width, anti-tailgating, anti-crush, IP rating, Wiegand, RS485, direction (one-way/two-way), flap/arm/cylindrical, opening speed |
| Biometrics pages | FAR (false acceptance rate), FRR (false rejection rate), liveness detection, IR illumination, recognition distance, face capacity, operating temperature, IP65, Android OS |
| LPR/Vehicle pages | ANPR, LPR, plate recognition accuracy, night vision, IP65, MTBF, recognition speed, IR camera, barrier gate |
| Attendance pages | clock-in, enrollment, shift management, buddy punching, cloud sync, biometric, anti-spoofing |
| Airport/Custom | kiosk, self check-in, boarding pass, FIDS, OEM, ODM, SDK, API, custom firmware |

**Process:**
1. List the required terms for the page type
2. Check each term is present at least once
3. For missing terms — add to the most relevant existing section (do not create new sections)

```
PASS N COMPLETE — [Page Name]
Page type: [Turnstile / Biometrics / LPR / Attendance / Airport / General]
Required terms checked: [X/Y present]
Terms added: [list terms and which section they were added to]
Terms not applicable: [list any skipped and why]
```

---

### Pass D — E-E-A-T & GEO Check (NEW)

Verify the page will be cited by AI systems (ChatGPT, Gemini, Perplexity) and pass Google's E-E-A-T signals.

**Six checks:**

**D1 — AI-Quotable Paragraph**
Every page must contain one paragraph in this format:
> "[Brand] [product/service] [capability] — [spec] — [use case] — [differentiator]."

Example:
> "EASCO manufactures face recognition access control terminals with 99.98% accuracy at 200–300ms recognition speed. Storage for 50,000 faces onboard. IP65-rated for outdoor installation. Factory direct from Shenzhen — the same supply chain used by global security integrators."

**D2 — FAQ Coverage**
Minimum 5 Q&As per page. Questions must target long-tail search intent and "People Also Ask" patterns. Answers: max 3 sentences, direct answer first. FAQPage schema applies.

**D3 — Authority Signals**
At least 2 of these per page (only use confirmed items):
- 20 years manufacturing (⚠️ confirm founding year first)
- Factory direct — Shenzhen
- Iris: 1-in-10,000,000 FAR ✅
- Face: 99.98% accuracy ✅
- IP65-rated ✅
- ISO 9001 (⚠️ confirm)
- OEM/ODM available ✅

**D4 — Freshness**
Add `Last Updated: [date]` to page metadata. Only update for substantive content changes.

**D5 — Experience Signals**
Minimum 2 per page:
- Use case scenario ("In a hospital entrance handling 800 staff per shift...")
- Failure mode addressed ("If the gate loses power...")
- Environment context ("In dusty industrial environments...")
- Buyer scenario ("An importer sourcing 200 units for a Middle East distributor...")

**D6 — Entity Consistency**
- Brand name: "EASCO" (all caps) throughout
- Product names: use exact model codes from client-data-map.md
- Company name: "Shenzhen Easco Intelligent Equipment Co., Ltd." on About/Contact/Footer only

```
PASS D COMPLETE — [Page Name]
AI-quotable paragraph: [present / added to Section X]
FAQ count: [X Q&As]
Authority signals: [list 2+ used]
Freshness date: [set to YYYY-MM-DD]
Experience signals: [list 2+ used]
Entity consistency: [checked / issues found]
```

---

### Pass C — Conversion Review

Read as a B2B buyer who has never heard of EASCO and is comparing 3 suppliers.

**Six tests:**

**Test 1 — 3-second headline test**
Each H2: does it state a buyer outcome in 3 seconds?
- Failing: "Our Turnstile Range" / "Product Features"
- Passing: "45 People Per Minute. Zero Tailgating." / "Factory Direct. No Middleman Markup."

**Test 2 — First 10 words test**
First 10 words of every section body: do they state what the buyer gains?
Fail if they introduce the product, company, or feature first.

**Test 3 — Objection coverage test**
Cross-check against `_system/objection-map.md`. Every applicable objection answered.

**Test 4 — CTA journey test**
- Early CTA → orientation
- Mid CTA → verification
- End CTA → conversion
No two CTAs to same destination.

**Test 5 — Differentiation test**
Read as a buyer with ZKTeco and Hikvision tabs open. What does this page say that they cannot?
Minimum 2 differentiators from `_system/differentiator-card.md` must appear explicitly.

**Test 6 — Read-aloud test**
Read full page aloud. Mark every hesitation or phrase that sounds written, not spoken. Every mark = rewrite.

**AI-Written Score — target 15% or below**

Raises score (+5% each): 3+ consecutive same-structure sentences, "not only...but also", "Furthermore/Additionally/Moreover", perfect parallel bullets, generic CTA
Lowers score (−5% each): intentional fragment, sentence starting "And"/"But", non-round specific number, mid-paragraph direct address, unexpected analogy, rhetorical question answered immediately

```
PASS C REVIEW — [Page Name]
3-second headline test: [pass/fail] — [note]
First 10 words test: [pass/fail] — [note]
Objection coverage test: [pass/fail] — [uncovered objections]
CTA journey test: [pass/fail] — [note]
Differentiation test: [pass/fail] — [differentiators present / missing]
Read-aloud test: [pass/fail] — [flagged sentences]
AI-Written Score: [X]%

Final changes made:
- [exact change and location]

Page status: READY FOR DEVELOPMENT / NEEDS FURTHER WORK
```

---

## Pass Log Header Template

Add to top of every completed page file:

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
