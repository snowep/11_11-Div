---
tags: [design, relic]
locked: true
locked_date: 2026-01-20
---

# RELIC 001 — SPECIFICATION & INTENT (LOCKED)

**Canonical object:** a straight, archetypal sacred longsword (Type XV–inspired silhouette) — intentionally culturally ambiguous.

**Fracture baseline (locked):** 48.5% of full master height.  
(Master canvas height = 4000 px → baseline = **1940 px**; set `fracture_baseline_px=1940` in master file metadata.)

## Distribution & meaning (locked)
- **Upper half** (handle → fracture) → garment print (TEE) — general edition.  
- **Lower half** (fracture → point) → collectible card / relic token — PO-only collectible, numbered, and archival.

**What owning Relic 001 implies (locked):**
- You are recorded as a **Witness** in the Book (waitlist/ledger).  
- You receive **ritual access**: priority PO invitation + limited listening-room invite.

## Visual rules
- Blade: restrained, symmetrical silhouette with a minimal crown motif integrated into the guard/pommel (partially broken).  
- Fracture: a single clean diagonal cut at the baseline. It is geometric and controlled — no ragged forms.  
- Sigil: geometric derivative of fracture geometry. Small, tone-on-tone; one sigil per drop.

## Production requirements
- Provide `MASTER_FULL` AI/SVG vector & `PRINT_SAFE` variants.  
- Generate `UPPER_EXPORT` (for TEE) and `LOWER_EXPORT` (for CARD) assets.  
- **Overlay proof** (`OVERLAY_PROOF.png`) must demonstrate pixel-perfect seam alignment and be signed by the production sign-off panel before any run.

**See:** [[04_DESIGN/DESIGN-SYSTEM]] · [[06_OPERATIONS/MERCH-LOGIC]] · [[05_DECISIONS/PRODUCTION-SIGNOFF]]

_Signed-off-by: Council — 2026-01-20._
