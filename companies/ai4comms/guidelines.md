# AI4comms Brand Guidelines

**Direction:** Practical AI enablement partner · **Archetype:** Sage (primary) + Caregiver (secondary)
**Locale:** Dutch (NL-NL) primary, English secondary
**Refreshed:** 2026-05-18 — realigned to deployed identity at ai4-comms.com

AI4comms helps communications professionals make AI usable in daily practice. The identity is grounded, accessible, and serviceable — closer to a trusted colleague than a premium consultancy. This refresh replaces the earlier aspirational "Signal Authority" system (archived at `.build-history/aspirational-2026-04-05/`) with a brand that matches what is actually deployed at ai4-comms.com.

---

## 1. Brand Foundation

### Essence
AI4comms turns AI from abstract hype into usable operating practice for communications teams — in Dutch, on the ground, one routekaart at a time.

### Positioning
For Dutch-speaking communications professionals under pressure to adopt AI responsibly, AI4comms is the enablement partner that translates AI tooling into practical routines — so teams gain impact without losing their craft or their judgment.

### Tagline
- **Primary (NL):** Kies voor AI als partner, niet als vervanger
- **English equivalent:** Choose AI as a partner, not a replacement

### Personality
- **Practical** — outcomes over theory, every concept has a hands-on next step
- **Approachable** — explains rather than impresses
- **Grounded** — senior judgment, no hype, no jargon for jargon's sake
- **Patient** — meets teams where they are; trusts the routekaart
- **Trustworthy** — calm, clear, accountable

### Archetype
- **Primary — Sage:** we understand AI and translate it honestly; mastery in service of understanding
- **Secondary — Caregiver:** we make adoption feel safe and supported; we protect the team's craft and time

---

## 2. Voice & Tone

Write like a senior adviser who is a peer, not a guru. In Dutch, default to professional but not stiff (`u`/`je` follows the client's own usage — the live site uses `je`/`jullie`).

**Core rules:**
- Lead with the point, then explain
- Short, scannable sentences
- Use the team's language ("communicatieprofessionals", "communicatieteam", "routekaart")
- Concrete examples beat abstractions
- Ask honest rhetorical questions; answer them plainly
- Never oversell AI; never undersell the team's existing craft

**Do:**
- "AI-oplossingen op maat voor communicatieprofessionals"
- "Onze werkwijze: de AI-routekaart"
- "Resultaat: een communicatieteam met meer impact"

**Don't:**
- "Signal through the noise" — too abstract for the deployed audience
- "Transform your communications" — empty buzz
- "Disrupt", "revolutionize", "leverage" — wrong register

---

## 3. Logo

The mark is **one wordmark** — the rounded "AI4comms" panel. It never changes shape. What changes is **colour**, so it sits correctly on any background. Refresh 2026-07-22 added a background-adaptive variant set + a favicon system; the wordmark geometry is untouched (a `protected` asset).

### Colour variants (pick by background)

| Variant | File | Use it on |
|---|---|---|
| **Primary** | `logos/ai4comms-logo-primary.svg` (`.png`) | White / paper / any **light** surface — the default |
| **Reversed** | `logos/ai4comms-logo-reversed.svg` (`.png`) | Solid **canopy / pine / dark** sections (light paper chip, canopy letters, sage 4) |
| **Knockout** | `logos/ai4comms-logo-knockout.svg` (`.png`) | **Photos** & immersive dark (transparent, white outline + letters, sage 4) — this is the `logo.white` slot |
| **Mono canopy** | `logos/ai4comms-logo-mono-canopy.svg` (`.png`) | **One-colour** print on light (stamps, emboss) |
| **Mono white** | `logos/ai4comms-logo-mono-white.svg` (`.png`) | **One-colour reversed** print / watermark on dark |

The background→variant mapping is machine-readable in `charter.logo.usage` and `charter.logo.variants`, and `images.logoVariantOnImage = "white"` so every render surface auto-selects the knockout over imagery. **Never place the primary dark panel on a dark surface — reach for reversed or knockout.**

### Favicon

`AI4` in a rounded square tile (built from the logo's own A/I/4 glyphs — legible to 16px, unlike the old shrunk panel). Multiple tints for different chrome, mapped in `charter.logo.favicons`:

| Tile | Files | Use |
|---|---|---|
| **Canopy** (default) | `logos/favicons/ai4comms-favicon-canopy-{16,32,180,192}.png` (`.svg`) | Default — dark tab bars, app tile, document headers |
| **Sage** | `logos/favicons/ai4comms-favicon-sage-{32,180}.png` | Bright accent — busy/light chrome where it should pop |
| **Paper** | `logos/favicons/ai4comms-favicon-paper-{32,180}.png` | Quiet, light-mode-native |
| **Outline** | `logos/favicons/ai4comms-favicon-outline-{32,180}.png` | Transparent — blends on any light surface |

**Clear space:** at least the height of the "A" on all sides.
**Minimum size:** wordmark 96px wide on screen (knockout 110px), 24mm in print; favicon down to 16px.

*Icon-only / abstract symbol mark — still not part of the system; a distinctive graphical mark is the next refresh step (see BUILD_LOG). Until then the favicon tile is the sub-32px mark.*

---

## 4. Color Palette

| Token | Hex | Role |
|---|---|---|
| Canopy | `#15311A` | Primary — logo, headings on light, primary CTA |
| Pine | `#214C28` | Secondary — gradient depth, hover states, secondary CTA |
| Sage | `#9EC187` | Accent — highlights, rules, active indicators, sparing use |
| White | `#FFFFFF` | Primary surface |
| Paper | `#F8FAFC` | Secondary surface (section bands, cards) |
| Mist | `#ECECEC` | Tertiary surface (gradient end, table headers) |
| Ink | `#1F1F1F` | Body text |
| Ink-light | `#4E4E4E` | Muted text, captions |

**Header gradient** (matches deployed): `linear-gradient(135deg, #F8FAFC 0%, #ECECEC 100%)`.

**Mode:** light-first. Dark sections are allowed but should be the exception, not the rule — and they MUST use `#15311A` (canopy) as the background, never near-black.

**Semantic colors:** `success #3B7A4E`, `warning #C89B3E`, `error #B85648`, `info #4F6F3D`.

---

## 5. Typography

**Typeface:** Montserrat for everything (heading + body), matching the deployed Divi global font settings. JetBrains Mono is retained for code blocks (not used on the deployed site, but reserved for technical deliverables).

| Use | Family | Weight | Size | Line-height |
|---|---|---|---|---|
| Display | Montserrat | 700 | 56–72px | 1.2 |
| H1 | Montserrat | 700 | 44px | 1.2 |
| H2 | Montserrat | 700 | 34px | 1.25 |
| H3 | Montserrat | 600 | 22px | 1.3 |
| Body | Montserrat | 400 | 14px | 1.7 |
| Caption | Montserrat | 400 | 12–13px | 1.5 |
| Overline | Montserrat | 600 | 12px | 1.3, tracked 0.12em uppercase |

Body size 14px and line-height 1.7 are the deployed Divi defaults — preserve them in web/document templates so on-screen output matches the live site.

---

## 6. Motif System

The deployed site has **no decorative motif system** — it relies on whitespace, a header gradient, and the sage accent rule for visual rhythm. Phase 3 motif SVGs from the previous aspirational brand (dark dividers, hatched pattern tile) have been archived; they encode a darker, more authoritative system than what is deployed.

**Acceptable design-system motifs for this refresh** (to be regenerated in a follow-up Phase 3 step):
- **Sage hairline rule** — 1px sage line, 64px wide, paired under section overlines
- **Header gradient** — `linear-gradient(135deg, #F8FAFC → #ECECEC)`, reserved for page/section headers
- **Pine wedge** — a single 8px-tall canopy band used as a section opener at the top of dark callout boxes

That is the full motif vocabulary until a richer system is commissioned. Do not invent decorative shapes that aren't deployed.

### Distinctive mark family (added 2026-07-22)

The brand now has a **graphical mark** — and deliberately, **not one mark but a small family of four**, so brand signalling can rotate instead of repeating (the same idea as the rotating image library). All share the language: canopy line + soft sage fill, rounded, 2px stroke — never neon, never cold. Each ships a light version (`assets/svg/marks/mark-<id>.svg`, canopy+sage) and a knockout (`-knockout.svg`, white+sage for dark/photo).

| Pref | Mark | Says | Reach for it when |
|---|---|---|---|
| 1 | **Routekaart** (`mark-routekaart`) | the guided path to a goal — their method word | process, approach, how-we-work, onboarding |
| 2 | **The "4" badge** (`mark-four-badge`) | the sage 4 as a badge — ties to logo equity | small/compact, favicon, avatar, app icon, stamp |
| 3 | **Partner network** (`mark-network`) | AI woven into the team | AI, product, integration, platform |
| 4 | **Partner leaves** (`mark-partner-leaves`) | human + AI, partner not replacement (the tagline) | partnership, people, collaboration, care |

**How a deliverable picks one** — machine-readable in `charter.symbol.selection`: match the surface/topic against each mark's `contextTags`; when several fit (or none), follow `preferenceOrder` **with seeded variance** so consecutive documents rotate marks. Deterministic single-pick surfaces use `selection.default` (Routekaart). Never invent a mark outside the set. This is a **multi-version brand item** (`symbol.kind: "multi-version"`) — the same pattern as the logo variants, but the logo picks *deterministically by background* while the mark picks *by context with variance*.

---

## 7. Imagery

The deployed site uses **minimal photography**. The previous brand's 140-image library (architectural / signal / data-texture themes) is archived but no longer canonical — it was built for the dark-mode aspirational identity and does not match the deployed light, typographic feel.

**Imagery posture for this refresh:**
- Default to **no hero photography**. Type and whitespace carry the page.
- When photography is required (case studies, team page), use **bright, natural, human-scale** images (workplaces, conversations, screens being used by real hands).
- Avoid: dark architectural shots, abstract data textures, neon-lit interiors, monochrome industrial scenes.
- Treatment: keep originals largely untouched. Overlay only with `--overlay-canopy-55` if text needs to sit on the image.

A new image library will be sourced in a follow-up Phase 4 pass.

---

## 8. Templates

The existing `templates/` directory contains dark-mode artifacts that no longer match the brand:

| Template | Status | Action |
|---|---|---|
| `templates/docx/styles.docx` + `letterhead.docx` | ✅ light-mode | Materialised from specs via `render-anchors.js` (ORG-PLAN-149); stale `default.docx` removed |
| `templates/html/business-cards.html` | dark-mode | Regenerate in light mode |
| `templates/html/email-signature.html` | dark-mode | Regenerate in light mode |

This refresh updates the **charter, tokens, guidelines, and logos only**. Template regeneration is a separate Phase 5 pass (flagged in BUILD_LOG.md as the next-action item).

---

## 9. What changed in this refresh

| Dimension | Before (aspirational) | After (deployed) |
|---|---|---|
| Mode | dark-mode-native | light-mode-first |
| Tagline | "Signal through the noise." (EN) | "Kies voor AI als partner, niet als vervanger" (NL) |
| Archetype | Magician + Ruler | Sage + Caregiver |
| Accent | `#44E88A` neon phosphor | `#9EC187` sage |
| Heading font | Syne | Montserrat |
| Body font | Inter | Montserrat |
| Logo | 489-byte stand-in wordmark | 8.4 KB designed Affinity artwork (live) |
| Logo variants | 8 (primary/white/icon/mark × svg/png) | 4 (primary svg/png + 2 favicons) |
| Imagery | 140-image dark library | Minimal — text-first |
| Primary green | `#15311A` ✓ | `#15311A` ✓ (unchanged) |

The primary brand green is the one thing that survived the refresh. Everything else was realigned to what the client actually ships.
