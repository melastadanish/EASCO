# Sitemap & Information Architecture — EASCO

> Single source of truth for site structure, URL slugs, and internal linking rules.
> Every page written must match the slug defined here.
> Internal links must use the exact target keyword as anchor text.
> **Last Updated: 2026-07-08**

---

## Confirmed Navigation Structure

```
Home | Products ▼ | About/Why Us | Solutions ▼ | Cases ▼ | FAQ | Gallery | Blog | Contact
```

**Critical rules for agents:**
- Products ▼ is a mega menu showing all 10 category pages directly. There is NO /products/ hub page. Do NOT create or reference products/products-hub.md.
- Solutions ▼ links to each industry sub-page. solutions-hub.md is the /solutions/ landing.
- Cases ▼ links to each venue sub-page. case-studies-hub.md is the /case-studies/ landing.
- FAQ and Gallery are standalone top-level nav items.
- Downloads (/downloads/) exists as a page but is NOT in the nav.
- Request Quote (/quote/) exists as a page but is NOT in the nav.
- There is no Resources section, no Resources Hub, and no other-pages/resources.md. Do NOT create it.

---

## Page Inventory

### Homepage
| URL | File |
|---|---|
| / | other-pages/home.md |

### About / Why Us
| URL | File |
|---|---|
| /why-us/ | other-pages/why-us.md |

### Products — 10 Category Pages (no hub)
Each category is a standalone page. URL structure: `/[category-slug]/`

| Category | URL | File |
|---|---|---|
| Flap Barrier / Speed Gates | /speed-gates/ | products/speed-gates/category.md |
| Tripod Turnstiles | /tripod-turnstiles/ | products/tripod-turnstiles/category.md |
| Cylindrical Turnstiles | /cylindrical-turnstiles/ | products/cylindrical-turnstiles/category.md |
| Android Turnstiles (Face+QR+Card) | /android-turnstiles/ | products/android-turnstiles/category.md |
| Face Recognition Terminals | /face-recognition/ | products/face-recognition/category.md |
| Handheld Face Recognition | /handheld-face-recognition/ | products/handheld-face-recognition/category.md |
| ANPR / LPR Systems | /anpr-systems/ | products/anpr-systems/category.md |
| Palm Vein + Iris Recognition | /palm-vein-iris/ | products/palm-vein-iris/category.md |
| Alcohol Detection Devices | /alcohol-detection/ | products/alcohol-detection/category.md |
| Visitor Registration Machines | /visitor-registration/ | products/visitor-registration/category.md |

### Solutions — by Industry
Landing + sub-pages. URL structure: `/solutions/[industry]/`

| Page | URL | File |
|---|---|---|
| Solutions Hub | /solutions/ | solutions/solutions-hub.md |
| Commercial Buildings | /solutions/commercial-buildings/ | solutions/commercial-buildings.md |
| Smart Campus / Schools | /solutions/smart-campus/ | solutions/smart-campus.md |
| Transportation Hubs | /solutions/transportation/ | solutions/transportation.md |
| Hospitals | /solutions/hospitals/ | solutions/hospitals.md |
| Factories / Warehouses | /solutions/factories/ | solutions/factories.md |
| Government Buildings | /solutions/government/ | solutions/government.md |

### Case Studies — by Venue
Landing + sub-pages. URL structure: `/case-studies/[venue]/`

| Page | URL | File |
|---|---|---|
| Case Studies Hub | /case-studies/ | case-studies/case-studies-hub.md |
| Office Buildings | /case-studies/office-buildings/ | case-studies/office-buildings.md |
| Schools / Universities | /case-studies/schools/ | case-studies/schools.md |
| Factories | /case-studies/factories/ | case-studies/factories.md |
| Metro / Transit | /case-studies/metro/ | case-studies/metro.md |
| Airports | /case-studies/airports/ | case-studies/airports.md |
| Hospitals | /case-studies/hospitals/ | case-studies/hospitals.md |
| Shopping Malls | /case-studies/shopping-malls/ | case-studies/shopping-malls.md |
| Government | /case-studies/government/ | case-studies/government.md |

### FAQ
| URL | File |
|---|---|
| /faq/ | other-pages/faq.md |

### Gallery
| URL | File |
|---|---|
| /gallery/ | other-pages/gallery.md |

### Blog
| URL | File |
|---|---|
| /blog/ | blogs/blog-hub.md |
| /blog/what-is-a-turnstile-gate/ | blogs/what-is-a-turnstile-gate.md |
| /blog/biometric-access-control-explained/ | blogs/biometric-access-control-explained.md |
| /blog/how-to-choose-turnstile-gate/ | blogs/how-to-choose-turnstile-gate.md |
| /blog/face-recognition-vs-fingerprint/ | blogs/face-recognition-vs-fingerprint.md |
| /blog/access-control-for-construction-sites/ | blogs/access-control-for-construction-sites.md |
| /blog/oem-vs-odm/ | blogs/oem-vs-odm.md |
| /blog/how-does-anpr-work/ | blogs/how-does-anpr-work.md |
| /blog/what-is-liveness-detection/ | blogs/what-is-liveness-detection.md |

### Contact
| URL | File |
|---|---|
| /contact/ | other-pages/contact.md |

### Supporting Pages (not in main nav)
| Page | URL | File |
|---|---|---|
| Request Quote | /quote/ | other-pages/request-quote.md |
| Downloads | /downloads/ | other-pages/downloads.md |
| Factory Tour | /factory/ | other-pages/factory.md |
| Certifications | /certifications/ | other-pages/certifications.md |
| OEM/ODM Services | /oem-odm/ | other-pages/oem-odm.md |
| Partners & Distributors | /partners/ | other-pages/partners.md |
| Trade Shows & Events | /events/ | other-pages/events.md |
| Privacy Policy | /privacy/ | other-pages/privacy-policy.md |
| Terms of Service | /terms/ | other-pages/terms.md |
| Cookie Policy | /cookies/ | other-pages/cookies.md |

### Competitor / Alternative Pages (SEO)
| Page | URL | File |
|---|---|---|
| EASCO vs ZKTeco | /vs/zkteco/ | alternatives/easco-vs-zkteco.md |
| EASCO vs Hikvision | /vs/hikvision/ | alternatives/easco-vs-hikvision.md |
| ZKTeco Alternative | /zkteco-alternative/ | alternatives/zkteco-alternative.md |
| Hikvision Alternative | /hikvision-alternative/ | alternatives/hikvision-alternative.md |

---

## SEO Meta Titles & Descriptions (Core Pages)

| Page | Title Tag (≤60 chars) | Meta Description (≤160 chars) |
|---|---|---|
| Homepage | EASCO — Turnstile Gate & Face Recognition Manufacturer \| Shenzhen | EASCO manufactures turnstile gates, face recognition terminals, and biometric access control devices. 20 years experience, 63 patents, OEM/ODM available. Export to 50+ countries. |
| Why Us | Why Choose EASCO \| Turnstile & Biometric Manufacturer Since 2009 | Since 2009, EASCO has delivered intelligent security hardware to clients worldwide. ISO certified, 63 patents, 3,000m² factory in Shenzhen. OEM/ODM services available. |
| Solutions | Access Control Solutions by Industry \| EASCO | EASCO delivers tailored access control solutions for commercial buildings, schools, airports, hospitals, factories and more. |
| Case Studies | Installation Case Studies \| EASCO Projects Worldwide | Explore real EASCO installations: office buildings, schools, airports, banks, malls, government facilities. |
| FAQ | Access Control FAQs \| EASCO Turnstile & Biometric Systems | Answers to the most common questions about EASCO turnstile gates, face recognition terminals, biometrics, ANPR, and OEM/ODM services. |
| Gallery | Installation Photo Gallery \| EASCO Access Control Projects | Browse EASCO installation photos from offices, campuses, factories, airports, and more. |
| Blog | Access Control & Biometrics Blog \| EASCO | Industry insights, product guides, and technical articles on turnstile gates, face recognition, biometrics, and smart access control. |
| Contact | Contact EASCO \| Get a Quote for Turnstile & Biometric Systems | Contact EASCO for quotes on turnstile gates, face recognition terminals, and access control systems. Reply within 1 hour. WhatsApp: +86 13711422283 |

---

## Internal Linking Rules

1. Anchor text — always use the target keyword of the destination page. Never "click here" or "read more."
2. Product pages → relevant solution pages
3. Solution pages → 3–4 recommended product category pages
4. Case study pages → relevant solution and product pages
5. Blog posts → relevant product category pages
6. Homepage → all core nav pages
7. Footer links — all 10 product categories, Solutions, Cases, Why Us, FAQ, Gallery, Contact, Request Quote

---

## Visual Content Requirements

| Page | Assets Needed |
|---|---|
| Homepage | Hero video, product category images, solution industry images, world map, cert badges |
| Why Us | Factory photos, team photo, exhibition booth photos, cert scans |
| All product pages | White-background product photos, dimension diagrams, demo video links |
| Solutions | Industry context photos (office, campus, airport, factory) |
| Case Studies | Real project photos with location — confirmed unavailable from client |
| Gallery | All installation photos — pending client upload |

---

## End of Sitemap
