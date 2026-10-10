---
name: Go-Live Readiness
description: A botanical editorial command center for calm, consequential launch decisions.
colors:
  alabaster: "#f9f8f4"
  surface: "#ffffff"
  forest: "#2d3a31"
  muted: "#5a655b"
  sage: "#8c9a84"
  sage-deep: "#53624d"
  clay: "#dccfc2"
  stone: "#e6e2da"
  terracotta: "#a95f4e"
  soft: "#f2f0eb"
typography:
  display:
    fontFamily: "Playfair Display, serif"
    fontSize: "clamp(3rem, 6.2vw, 5.8rem)"
    fontWeight: 600
    lineHeight: 0.95
    letterSpacing: "-0.025em"
  body:
    fontFamily: "Source Sans 3, system-ui, sans-serif"
    fontSize: "15px"
    fontWeight: 500
    lineHeight: 1.6
rounded:
  control: "999px"
  panel: "24px"
  arch: "120px 120px 24px 24px"
spacing:
  sm: "8px"
  md: "16px"
  lg: "24px"
components:
  button-primary:
    backgroundColor: "{colors.forest}"
    textColor: "#ffffff"
    rounded: "{rounded.control}"
    padding: "11px 19px"
  panel:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.forest}"
    rounded: "{rounded.panel}"
    padding: "24px"
---

# Design System: Go-Live Readiness

## Overview

**Creative North Star: "The Conservatory Briefing"**

Go-Live Readiness combines the composure of an editorial briefing with the organic restraint of a botanical conservatory. The system is quiet enough for high-stakes operating work but memorable through forest typography, arch silhouettes, sage progress, and warm clay surfaces.

**Key Characteristics:** forest editorial type; alabaster field; sage and clay signals; arch-shaped priority surfaces; measured, low-noise density.

## Colors

Forest anchors text and primary action. Sage communicates progress, terracotta marks risk and attention, while clay and stone provide calm structural layers.

**The Calm Signal Rule.** Status colors remain muted and always appear with explicit language; urgency comes from meaning, not saturation.

## Typography

**Display Font:** Playfair Display (serif)  
**Body Font:** Source Sans 3 (system sans fallback)

Playfair establishes an editorial command voice for major decisions. Source Sans 3 keeps tasks, risks, labels, and owners direct and scannable.

## Layout

The desktop command center pairs a flexible workstream panel with a 300px critical-path rail. At 850px the panels stack; at 600px task pairs become a single list and risk rows become mobile cards. The content container is capped at 1240px.

## Elevation & Depth

Most hierarchy comes from tone, borders, and form. Primary panels use a restrained `0 20px 40px -28px rgba(45,58,49,.35)` shadow; critical items use shallower ambient lift.

## Shapes

Arches are reserved for the readiness indicator, critical-path rail, and quiet hero geometry. Standard working panels use 20–36px corners. Buttons and status chips use pills; tables retain precise alignment.

## Components

- **Buttons:** uppercase tracked pills, forest primary and sage outline secondary.
- **Readiness indicator:** arch-ended progress form with numeric status and plain-language interpretation.
- **Workstreams:** editorial titles, sage bars, and full-width task rows.
- **Risks:** text-backed muted severity tags; resolve and delete remain distinct controls.

## Do's and Don'ts

### Do:
- **Do** pair every color signal with readable status text.
- **Do** use arches sparingly for launch-level emphasis.
- **Do** preserve generous spacing around decision summaries.

### Don't:
- **Don't** add neon status colors, gradient buttons, or playful geometric stickers.
- **Don't** use procedural grain overlays; the palette and arch system carry the organic character.
- **Don't** let editorial styling obscure owners, blockers, or next actions.
