---
name: run-it-back-brand
description: The Run it Back visual brand system — colors, typography, logo, dual-accent rule, and post templates. Use whenever creating or styling any Run it Back visual asset: short-form video frames, thumbnails, quote/stat cards, carousels, covers, the website, or any graphic that should look on-brand. Keywords: run it back brand, brand colors, brand guidelines, visual identity, post template, thumbnail, on-brand, style this.
---

# Run it Back — Brand System (v1: "Blueprint × Concrete")

Apply this to every Run it Back visual. The look = **technical dark base + heavy condensed
type + a dual accent** (blue = science, orange = push). Credible enough to sell products,
hard enough for the male-discipline core, and unlike the teal-hype and vintage-quote competitors.

## Colors

| Role | Name | Hex | Use |
|---|---|---|---|
| Base | **Ink** | `#0A0E14` | primary background |
| Surface | **Surface** | `#131C26` | cards, panels, secondary bg |
| Accent 1 | **Signal (blue)** | `#3B82F6` | *science / teaching / mechanism* — the differentiator |
| Accent 2 | **Blaze (orange)** | `#FF4A1C` | *push / comeback / action / CTA* |
| Neutral | **Steel** | `#8A9AAC` | secondary text, captions |
| Light | **Bone** | `#F4F7FB` | primary text on dark |

**The dual-accent rule (important):** use **one accent per composition**, chosen by tone.
- **Blue** → teaching/science posts (The Discipline Lab, "why it works," data, protocols).
- **Orange** → push/comeback posts (Never Miss Twice, resilience, imperatives, CTAs).
- The **logo** may carry both (blue loop + orange arrowhead). Individual posts pick one. Never split a headline across both accents.

Backgrounds are almost always dark. Bone text on Ink. Keep it high-contrast and clean —
lots of negative space; the type does the work.

## Typography

- **Display (headlines):** heavy **condensed** grotesque, uppercase, tight tracking.
  Production font: **Big Shoulders Display** (bundled in `canvas-design/canvas-fonts/`) or
  Boldonse. Fallback stack: `Impact, Haettenschweiler, 'Arial Narrow', sans-serif`.
- **Labels / data / series tags:** **monospace**, letter-spaced, uppercase (e.g. `THE DISCIPLINE LAB`).
  Production: a mono (JetBrains/IBM Plex Mono, bundled). Fallback: `'Courier New', monospace`.
- **Body / sublines:** clean sans. Fallback: `Helvetica, Arial, sans-serif`.

Headlines are big and multi-line; break lines for punch, not grammar. One idea per frame.

## Logo (v1 — ADOPTED 2026-07-06)

- **The mark = the comeback monogram:** an angular Blaze-orange stroke that runs a top bar,
  falls to a sharp vertex, then rises past its start into a **white escape arrowhead**; a
  crossbar butts into the rise (abstract R read); a short **dashed gray baseline** ("rock
  bottom") sits beneath. Slight italic lean (skewX −8°).
- Master vector: `content/visual-identity/logo-final/rib-logo-lockup.svg` (lockup) and
  `rib-logo-mark.svg` (mark-only, avatar-safe). Colors: stroke `#FF4A1C`, arrowhead `#F4F7FB`,
  baseline `#5B6672`, on Ink `#0A0E14`.
- Lockups: stacked (mark over wordmark) for hero/cards; mark-only for avatars/watermarks; the
  old ↻ loop glyph remains ONLY inside the text sign-off "↻ run it back." (typographic, not the logo).
- Sign-off (every piece): **`↻ run it back.`** — small, bottom-left, Steel text with the
  loop glyph in the post's active accent. This is the verbal + visual signature and CTA.

## Post templates (short-form 1080×1920)

Standard structure top→bottom:
1. **Brand bar** (top-left): small loop mark + `RUN IT BACK`.
2. **Series tag** (mono, in the active accent) + a short accent underline. e.g. `THE DISCIPLINE LAB`.
3. **Headline** (condensed display, huge, multi-line). Accent the payoff word/line only.
4. **Subline** (sans, Steel/Bone) — the "why" or the tool, 1–2 lines.
5. **Sign-off** `↻ run it back.` + optional micro-CTA (Steel, small): "save this…".

Two modes, by series:
- **Blue mode** — The Discipline Lab / Proof(science) / teaching. Blue accents, grid texture ok.
- **Orange mode** — Never Miss Twice / Run It Back / push. Orange accents, optional top orange rule bar.

Reference renders live in `content/visual-identity/` (`run-it-back-v1`, `post-1/2/3`).

## Do / Don't
- **Do:** dark bg, one accent per frame, huge condensed headline, tons of contrast, the sign-off.
- **Do:** proof on-screen text for typos (muted viewers read captions).
- **Don't:** use both accents loud in one composition; use pastels/grad's-everywhere; center-justify long body; add drop-shadows/glows except the subtle comeback radial on Run It Back pieces.
- **Don't:** slip into generic-gym clichés (flames, chrome, fake-deep quotes). We win on *method*; the look stays disciplined and clean.

## Production notes
- Build frames as SVG for control, or in the editor of choice using these exact values.
- Swap the fallback fonts for the bundled production fonts before publishing.
- When the **Higgsfield character persona** is added, keep every other element constant so it drops in cleanly.
