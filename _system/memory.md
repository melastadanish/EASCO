# Memory — EASCO Content Repository

> Session-persistent memory. **Read at the start of every session. Update at the end of every session.**
> Newest entries on top. Prune items once resolved and reflected in the system files.

---

## Current State

- **Complete (five-pass):** `other-pages/home.md` · `other-pages/why-us.md` · `other-pages/faq.md` + 4 legacy silo pillars (reuse as source copy only)
- **Everything else:** frontmatter stubs — the stub's frontmatter is the page brief
- **Next task:** `_system/execution-plan.md` Phase 1 → `products/speed-gates/category.md`
- **System:** weldocnc-style — fixed-section templates, Tier 1 checks per section, five passes (A→B→N→D→C) on compiled page

---

## Standing Decisions (do not re-litigate)

1. `_system/sitemap.md` is the single source of truth for URL slugs and folder structure
2. Data Source Hierarchy: `_system/product-specs/` → `_system/VERIFIED-COMPANY-DATA.md` → `_system/client-data-map.md` → raw manuals (verify first) — product-specs wins conflicts
3. Authority claims: verbatim strings only (WritingSystem § Verbatim Authority Statements)
4. Banned until client confirms: "20+ years" (use 16+) · ROHS badge · IP54 company badge · production capacity · warranty periods · UKCA/EAC
5. Legacy `silos/` pages: source copy for product archives — never develop as-is
6. Archive pages use `templates/product-archive-template.md` (12 sections); detail pages use `templates/product-page-template.md` (11 sections)
7. Visual/design direction lives in `_system/design.md` — content files stay copy-only

---

## Open Questions (blocked on user/client)

- [ ] Keyword list vs sitemap category conflict: `seo/keyword-master-list.md` has scenic-spots / banks / stadiums-gyms; `_system/sitemap.md` has government / metro / hospitals. Which set is final?
- [ ] Gate openers + handheld parking devices: raw manuals exist, but no category in the 10-category plan. On the site or not?
- [ ] Case studies: all 8 blocked — client must supply project data + photos
- [ ] Spec sheets pending from client: MTH8, JF1–JF5, J3/J4, 锋影, 168 stainless, single-arm, parking toll, handheld parking, MTFKS01/02
- [ ] Top 3 SEO-priority product lines not yet confirmed by client

---

## Session Log

**2026-07-06 — System build session**
- Audited repo + weldocnc reference; adopted weldocnc writing system for EASCO
- WritingSystem.md extended: Data Source Hierarchy, Verbatim Authority Statements, Pass N Term Lists per category
- Templates rebuilt: product-archive (12 fixed sections), product-page (11 fixed sections)
- execution-plan.md rephased into 9 ordered checkbox phases; progress.md reconciled (home/why-us/faq were wrongly 🔲)
- Folders aligned to sitemap: `solutions/`, case-studies stubs (all BLOCKED), `products/` tree with 11 frontmatter briefs
- memory.md + design.md created; CLAUDE.md slimmed to ≤21 lines
- Branch: `claude/repo-audit-6onxl6` · PR #3 (draft)

**Earlier (from git history)**
- 2026-07-02 — faq.md five-pass complete (A:10.0, 47 Q&As) · company data verified (founded Dec 22 2009, 63 patents, 3,000m², 80,000+ installs)
- 2026-06-2x — why-us.md (A:10.0), home.md (A:9.8) five-pass complete · redesign per Ayesha's plan committed
- 2026-06-21 — product-specs/ extracted from catalogue · 4 silo pillars completed under old structure

---

## End of Memory
