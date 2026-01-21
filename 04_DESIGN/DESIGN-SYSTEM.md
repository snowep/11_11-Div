---
tags: [design, system]
locked: true
locked_date: 2026-01-20
---

# DESIGN SYSTEM — MASTER (includes HERO DESIGN rules)

This is the single source of truth for all visual law. It contains the hero design rules (logo family), export rules, and the production constraints for the relic system.

---

## Logo family (HERO DESIGN — locked)
**Responsive logo family (locked)**  
1. **Wordmark** — Söhne Breit (Buch) wordmark — primary.  
2. **Typemark** — condensed 11:11 typemark — secondary.  
3. **Symbol** — minimal broken halo ring (structural) — tertiary.

**Usage rules**  
- All three are canonical and must be exported from the same master source file.  
- Don’t invent new mark variants without a council cycle.  
- Keep wordmark and typemark ratio consistent across applications.

---

## Master vector & export rules
- **MASTER_FULL**: single-source vector (AI/SVG) of the Relic and logo family. Size: 2000×4000 px vector artboard for relics (metadata: `fracture_baseline_px=1940`).  
- Layers that must exist: `MASTER_FULL`, `UPPER_EXPORT`, `LOWER_EXPORT`, `SIGIL_LAYER`, `DIAGRAM_LAYER`, `REGISTRATION_MARKS`, `PRINT_SAFE`, `ACCENTS`.  
- Export formats required for production: AI, SVG, PDF (vector), PNG 300dpi for proofs.

---

## Typography
- Primary: **Söhne Breit** (Buch).  
- Fallback: **Inter** or **Montserrat** for system use only if Söhne unavailable.

---

## Layout & grid principles
- Generous negative space. Favor centered alignment for canonical artifacts, left alignment for noise (where specified).  
- Use the same vertical rhythm across digital and print; preserve the canonical fracture baseline for relic assets.

---

## Print constraints (non-negotiable)
- **Primary strokes** must render to **≥0.8 mm** at 300dpi.  
- No hairlines in print; convert fine detail to solid shapes on `PRINT_SAFE` layer.  
- Registration glyphs (two dots) stored in `REGISTRATION_MARKS` (opacity 8%).  
- All spot colors and accents must be on separate layers.

---

## Files & exports to maintain in repo
- `1111_MASTER_FULL.ai` (master vector)  
- `1111_UPPER_TEE_BACK.pdf/png` (tee upper half export)  
- `1111_CARD_FRONT.pdf/png` (card lower half export)  
- `LOGO_WORDMARK.svg` / `LOGO_SYMBOL.svg` / `LOGO_TYPEMARK.svg`  
- `OVERLAY_PROOF.png` (pixel-perfect seam proof — required before production)

**See:** [[04_DESIGN/RELIC-SWORD]] | [[04_DESIGN/COLOR-PALETTE]] | [[05_DECISIONS/PRODUCTION-SIGNOFF]]

_Signed-off-by: Steve Jobs (persona), Dieter Rams, Hiroshi Fujiwara — 2026-01-20._
