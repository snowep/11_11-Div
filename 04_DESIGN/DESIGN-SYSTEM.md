---
tags: [design, system]
locked: true
locked_date: 2026-01-20
---

# DESIGN SYSTEM — MASTER (includes HERO DESIGN rules)

This is the single source of truth for all visual law. It contains hero design rules (logo family), export rules, relic production constraints, and typography / layout rules.

---

## HERO LOGO FAMILY (LOCKED)
**Canonical set — do not alter without council cycle**
1. **Wordmark:** Söhne Breit (Buch) wordmark — primary (exported in SVG & PDF).  
2. **Typemark:** condensed 11:11 typemark — secondary.  
3. **Symbol:** minimal broken halo ring — tertiary (structural emblem derived from relic geometry).

**Usage rules**
- Export all variants from the same master file (`LOGO_MASTER.ai`).  
- Maintain strict spacing and lock ratios in all uses.  
- Do not add decorative versions or color treatments outside the locked palette without a council vote.

---

## MASTER RELIC VECTOR
- **Canvas:** 2000 × 4000 px artboard for relic master (`MASTER_FULL.ai`).  
- **Metadata:** include `fracture_baseline_px=1940`.  
- **Required layers:** `MASTER_FULL`, `UPPER_EXPORT`, `LOWER_EXPORT`, `SIGIL_LAYER`, `DIAGRAM_LAYER`, `REGISTRATION_MARKS`, `PRINT_SAFE`, `ACCENTS`.  
- **Export formats:** AI, SVG, PDF (vector); PNG (300dpi) for proofs.

---

## TYPOGRAPHY
- **Primary:** Söhne Breit (Buch).  
- **Fallback:** Inter (neutral).  
- **Noise posts & stories:** follow the Top/Mid/Bottom typographic grammar (see [[03_CONTENT/NOISE-STRATEGY]]).

---

## LAYOUT RULES
- Story safe area and feed safe area are defined in `LAYOUT-RULES`. Centered compositions are canonical for the relic visuals. Keep generous negative space.

---

## PRINT RULES (non-negotiable)
- Primary strokes must render to **≥ 0.8 mm** at 300 DPI.  
- Convert hairlines or micro hatching into solid vector shapes on the `PRINT_SAFE` layer.  
- Registration glyphs (two small dots) live in `REGISTRATION_MARKS` with 8% opacity.  
- Spot accents (Blood Oath Red and Halo Ember Gold) must be on their own layers.

---

## FILES TO KEEP IN REPO
- `design/MASTER_FULL.ai` (master relic)  
- `logo/WORDMARK.svg`, `logo/SYMBOL.svg`, `logo/TYPEMARK.svg`  
- `exports/UPPER_TEE_BACK_3600x4800.png` (print safe)  
- `exports/CARD_FRONT_816x1110.pdf` (print safe)  
- `proofs/OVERLAY_PROOF.png`

**See:** [[04_DESIGN/COLOR-PALETTE]] · [[04_DESIGN/RELIC-SWORD]] · [[03_CONTENT/WEEKLY-STORY-TABLE]]

_Signed-off-by: Council — 2026-01-20._
