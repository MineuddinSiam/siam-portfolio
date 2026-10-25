---
version: alpha
name: Agentsure
description: |
  Agentsure's design system evokes a premium, technical-forward aesthetic rooted
  in the DevOps and incident response space. The visual language balances
  professional seriousness with subtle warmth, employing a tight, high-contrast
  typographic hierarchy and minimal ornamentation. The palette grounds itself in
  deep forest green (#005032) for trust and control, punctuated by warm earth
  tones (#E68846) used sparingly in prose highlights and decorative accents.
  Terminal-inspired code blocks rendered in dark containers (#1A1A1A backgrounds
  with monospace type) reinforce the engineering-native positioning. The overall
  mood is authoritative yet approachable—a team-centric tool for production
  incidents, not a vendor portal.
source:
  url: "http://agentsure.us/"
  pagesAnalyzed: 1
  extractedAt: 2026-10-14
  tokensMeasured: true
colors:
  primary: "#005032"
  link: "#0000EE"
  canvas: "#FFFFFF"
  on-primary: "#FFFFFF"
  ink: "#000000"
  body: "#0D1016"
  muted: "#1A1A1A"
  faint: "#68655E"
  hairline: "#E6E6E6"
  accent-1: "#E68846"
  accent-2: "#C0392B"
  accent-3: "#C9BBA3"
  neutral-1: "#F2E9DA"
  neutral-2: "#888888"
typography:
  display-xl:
    fontFamily: "Inter Tight"
    fontSize: 72px
    fontWeight: 400
    lineHeight: 1.04
    letterSpacing: -1.8px
  display-xl-strong:
    fontFamily: "Inter Tight"
    fontSize: 72px
    fontWeight: 500
    lineHeight: 1.04
    letterSpacing: -1.8px
  display-lg:
    fontFamily: "Inter Tight"
    fontSize: 48px
    fontWeight: 400
    lineHeight: 1.08
    letterSpacing: -1.06px
  display-lg-strong:
    fontFamily: "Inter Tight"
    fontSize: 48px
    fontWeight: 500
    lineHeight: 1.08
    letterSpacing: -1.06px
  heading-md:
    fontFamily: "Inter Tight"
    fontSize: 28px
    fontWeight: 500
    lineHeight: 1.2
    letterSpacing: -0.5px
  heading-sm:
    fontFamily: "Inter Tight"
    fontSize: 24px
    fontWeight: 500
    lineHeight: 1.18
    letterSpacing: -0.29px
  heading-xs:
    fontFamily: "Inter Tight"
    fontSize: 22px
    fontWeight: 500
    lineHeight: 1.22
    letterSpacing: -0.26px
  heading-xs-loose:
    fontFamily: "Inter Tight"
    fontSize: 22px
    fontWeight: 500
    lineHeight: 1.25
    letterSpacing: -0.26px
  quote:
    fontFamily: "Inter Tight"
    fontSize: 15.5px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0px
  body-lg:
    fontFamily: "Inter Tight"
    fontSize: 18px
    fontWeight: 500
    lineHeight: 1.55
    letterSpacing: -0.18px
  body-lg-tight:
    fontFamily: "Inter Tight"
    fontSize: 18px
    fontWeight: 500
    lineHeight: 1.55
    letterSpacing: -0.22px
  body-md:
    fontFamily: "Inter Tight"
    fontSize: 15.5px
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: 0px
  body-md-loose:
    fontFamily: "Inter Tight"
    fontSize: 15.5px
    fontWeight: 400
    lineHeight: 1.65
    letterSpacing: 0px
  body-sm:
    fontFamily: "Inter Tight"
    fontSize: 15px
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: 0px
  body-xs:
    fontFamily: "Inter Tight"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0px
  nav:
    fontFamily: "Inter Tight"
    fontSize: 13px
    fontWeight: 400
    lineHeight: 1.55
    letterSpacing: 0px
  button:
    fontFamily: "Inter Tight"
    fontSize: 14px
    fontWeight: 500
    lineHeight: 1
    letterSpacing: 0px
  label:
    fontFamily: "Inter Tight"
    fontSize: 14.5px
    fontWeight: 400
    lineHeight: 1.4
    letterSpacing: 0px
  code-xl:
    fontFamily: "JetBrains Mono"
    fontSize: 13px
    fontWeight: 400
    lineHeight: 1.55
    letterSpacing: 0px
  code-lg:
    fontFamily: "JetBrains Mono"
    fontSize: 12.5px
    fontWeight: 400
    lineHeight: 1.7
    letterSpacing: 0px
  code-md:
    fontFamily: "JetBrains Mono"
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.7
    letterSpacing: 0.48px
  code-sm:
    fontFamily: "JetBrains Mono"
    fontSize: 11px
    fontWeight: 400
    lineHeight: 1.7
    letterSpacing: 0.44px
  code-sm-strong:
    fontFamily: "JetBrains Mono"
    fontSize: 11px
    fontWeight: 500
    lineHeight: 1.7
    letterSpacing: 1.54px
    textTransform: uppercase
  code-xs:
    fontFamily: "JetBrains Mono"
    fontSize: 10.5px
    fontWeight: 500
    lineHeight: 1.55
    letterSpacing: 1.26px
    textTransform: uppercase
rounded:
  none: 0px
  xs: 6px
  sm: 8px
  full: 9999px
spacing:
  xxs: 4px
  xs: 8px
  sm: 12px
  md: 16px
  lg: 20px
  xl: 24px
  xxl: 28px
  xxxl: 32px
  section: 36px
  band: 40px
borderWidths:
  thin: 1px
elevationStrategy: color-blocking
themes:
  derived: dark   # the other theme is the site's measured palette
  light:
    bg: "#FFFFFF"
    surface: "#F7F7F7"
    surfaceRaised: "#EDEDED"
    text: "#000000"
    textMuted: "#0D1016"
    border: "#E6E6E6"
    accent: "#005032"
    accentFg: "#FFFFFF"
    focusRing: "#005032"
    elevation: shadow
  dark:
    bg: "#0C1211"
    surface: "#1B201F"
    surfaceRaised: "#272C2B"
    text: "#F5F8F7"
    textMuted: "#9CA1A0"
    border: "#333837"
    accent: "#00A265"
    accentFg: "#0B0B0C"
    focusRing: "#00794C"
    elevation: "border+surface"
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    fontSize: 13px
    fontWeight: 500
    fontFamily: "Inter Tight"
    padding: "13px 16px 13px 16px"
    rounded: 24px
    border: "1px solid {colors.primary}"
    height: 41px
    lineHeight: 1
  button-primary-lg:
    typography: "{typography.button}"
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    padding: "14px 14px 14px 14px"
    rounded: 24px
    height: 42px
  button-outline:
    typography: "{typography.button}"
    textColor: "{colors.body}"
    padding: "13px 20px 13px 20px"
    rounded: 24px
    border: "1px solid {colors.hairline}"
    height: 42px
  button-outline-sm:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.body}"
    fontSize: 13px
    fontWeight: 500
    fontFamily: "Inter Tight"
    padding: "13px 16px 13px 16px"
    rounded: 24px
    border: "1px solid {colors.hairline}"
    height: 41px
    lineHeight: 1
  card:
    textColor: "{colors.body}"
    fontSize: 15px
    fontWeight: 400
    fontFamily: "Inter Tight"
    padding: "36px 32px 36px 32px"
    lineHeight: 1.55
  card-lg:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.body}"
    fontSize: 15px
    fontWeight: 400
    fontFamily: "Inter Tight"
    padding: "32px 32px 32px 32px"
    rounded: "{rounded.sm}"
    lineHeight: 1.55
  navigation:
    backgroundColor: "rgba(255, 255, 255, 0.92)"
    textColor: "{colors.body}"
    fontSize: 15px
    fontWeight: 400
    fontFamily: "Inter Tight"
    padding: "14px 32px 14px 32px"
    height: 64px
    lineHeight: 1.55
  footer:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.faint}"
    fontSize: 15px
    fontWeight: 400
    fontFamily: "Inter Tight"
    padding: "40px 32px 40px 32px"
    border: "1px solid {colors.hairline}"
    lineHeight: 1.55
  link:
    typography: "{typography.body-lg}"
    textColor: "{colors.body}"
    padding: "14px 0px 14px 0px"
  link-2:
    typography: "{typography.nav}"
    textColor: "{colors.faint}"
states:
  button-hover:
    target: button
    state: hover
    transform: "translateY(-1px)"
  nav-hover:
    target: nav
    state: hover
    transform: "translateY(-1px)"
  other-hover:
    target: other
    state: hover
    boxShadow: "rgba(0, 0, 0, 0.18) 0px 8px 28px -16px"
    transform: "translateY(-2px)"
  input-focus:
    target: input
    state: focus
    boxShadow: "rgba(0, 0, 238, 0.1) 0px 0px 0px 3px"
  other-disabled:
    target: other
    state: disabled
    opacity: 0.6
    transform: none
breakpoints:
  - width: 375
    containerWidth: 335
    gridColumns: 1
    navLinksVisible: 2
    menuToggleVisible: true
    headingPx: 40
    bodyPx: 15
    sectionPaddingX: 20
  - width: 768
    containerWidth: 704
    gridColumns: 1
    navLinksVisible: 2
    menuToggleVisible: true
    headingPx: 41
    bodyPx: 15
    sectionPaddingX: 32
  - width: 1024
    containerWidth: 960
    gridColumns: 3
    navLinksVisible: 7
    menuToggleVisible: false
    headingPx: 55
    bodyPx: 15
    sectionPaddingX: 32
  - width: 1280
    containerWidth: 1180
    gridColumns: 3
    navLinksVisible: 7
    menuToggleVisible: false
    headingPx: 69
    bodyPx: 15
    sectionPaddingX: 32
  - width: 1440
    containerWidth: 1180
    gridColumns: 3
    navLinksVisible: 7
    menuToggleVisible: false
    headingPx: 72
    bodyPx: 15
    sectionPaddingX: 32
coverage:
  stylesheetsBlocked: true
  responsiveMeasured: true
  archetypesDetected: 0
  archetypesUnnamed: 0
  statesFound: 16
  gradientsFound: 0
  semanticRampDeclared: false
  rolesUnassigned: 5
---

# Design System Inspired by Agentsure

## 1. Visual Theme & Atmosphere

Agentsure's design system evokes a premium, technical-forward aesthetic rooted in the DevOps and incident response space. The visual language balances professional seriousness with subtle warmth, employing a tight, high-contrast typographic hierarchy and minimal ornamentation. The palette grounds itself in deep forest green (`{colors.primary}` — `#005032`) for trust and control, punctuated by warm earth tones (`{colors.accent-1}` — `#E68846`) used sparingly in prose highlights and decorative accents. Terminal-inspired code blocks rendered in dark containers (`#1A1A1A` backgrounds with monospace type) reinforce the engineering-native positioning. The overall mood is authoritative yet approachable—a team-centric tool for production incidents, not a vendor portal.

**Key Characteristics**

- High-contrast, minimal palette anchored in deep green and neutral blacks
- Tight, negative letter-spacing on display sizes for technical precision
- Pill-shaped button geometry (full border-radius) for modern softness
- Monospace code typography (JetBrains Mono) for incident logs and terminal UI metaphor
- Flat surfaces with no multi-layer shadows; depth via color blocking only
- Warm accent (`#E68846`) used as italic highlight text, never as UI fills
- Clean whitespace; typography-driven hierarchy over visual chrome

## 2. Color Palette & Roles

### Primary
- **Primary / Brand** (`{colors.primary}` — `#005032`): Primary CTA fills, active states, brand accent in navigation and core UI. Deep forest green conveying trust and operational control.

### Interactive
- **Link** (`{colors.link}` — `#0000EE`): Inline hyperlink text colour. Standard web blue, used sparingly on the page.

### Decorative / Unassigned
- **Accent 1** (`{colors.accent-1}` — `#E68846`): Warm burnt orange used for italic text highlights and decorative prose emphasis. No structural role in UI components.
- **Accent 2** (`{colors.accent-2}` — `#C0392B`): Deep red; present in the palette but unmeasured in active use.
- **Accent 3** (`{colors.accent-3}` — `#C9BBA3`): Muted tan; present in the palette but unmeasured in active use.

### Neutral Scale
- **Canvas** (`{colors.canvas}` — `#FFFFFF`): Default page background, card surfaces, and label text on brand-colored backgrounds.
- **Ink** (`{colors.ink}` — `#000000`): Headings and primary text. Maximum contrast, used for the strongest visual hierarchy.
- **Body** (`{colors.body}` — `#0D1016`): Body copy text. Very dark near-black, indistinguishable from ink in most contexts.
- **Muted** (`{colors.muted}` — `#1A1A1A`): Captions and secondary text; also the background of code/incident log containers.
- **Faint** (`{colors.faint}` — `#68655E`): Tertiary text and placeholder content. Reduced contrast for de-emphasized information.
- **Neutral 1** (`{colors.neutral-1}` — `#F2E9DA`): Light cream tone, unassigned role but present in palette.
- **Neutral 2** (`{colors.neutral-2}` — `#888888`): Mid-gray, unassigned role but present in palette.

### Surface & Borders
- **Hairline** (`{colors.hairline}` — `#E6E6E6`): 1px dividers, borders, and edge strokes. Minimal visual weight.

## 3. Typography Rules

### Font Family

**Primary:** Inter Tight (https://fonts.googleapis.com/) — a tight, modern geometric sans-serif with negative tracking built into display sizes.

**Secondary / Code:** JetBrains Mono (https://fonts.googleapis.com/) — monospace typeface for incident logs, terminal UI, and code snippets.

Fallback stack (not extracted, but standard):
```
Inter Tight, system-ui, -apple-system, sans-serif
JetBrains Mono, "Courier New", monospace
```

### Hierarchy

| Role | Font | Size | Weight | Line Height | Letter Spacing | Notes |
|---|---|---|---|---|---|---|
| Display XL | Inter Tight | 72px | 400 | 1.04 | -1.8px | Hero headline; maximum impact; light weight with tight tracking |
| Display XL Strong | Inter Tight | 72px | 500 | 1.04 | -1.8px | Hero headline; bold variant |
| Display LG | Inter Tight | 48px | 400 | 1.08 | -1.06px | Section headlines; relaxed weight |
| Display LG Strong | Inter Tight | 48px | 500 | 1.08 | -1.06px | Section headlines; bold variant |
| Heading MD | Inter Tight | 28px | 500 | 1.2 | -0.5px | Subsection headers |
| Heading SM | Inter Tight | 24px | 500 | 1.18 | -0.29px | Block headers |
| Heading XS | Inter Tight | 22px | 500 | 1.22 | -0.26px | Card titles |
| Heading XS Loose | Inter Tight | 22px | 500 | 1.25 | -0.26px | Card titles with relaxed line height |
| Body LG | Inter Tight | 18px | 500 | 1.55 | -0.18px | Large body text; medium weight |
| Body LG Tight | Inter Tight | 18px | 500 | 1.55 | -0.22px | Large body text; tighter tracking |
| Body MD | Inter Tight | 15.5px | 400 | 1.6 | 0px | Primary body copy |
| Body MD Loose | Inter Tight | 15.5px | 400 | 1.65 | 0px | Body copy with generous line height |
| Body SM | Inter Tight | 15px | 400 | 1.6 | 0px | Reduced body text |
| Body XS | Inter Tight | 14px | 400 | 1.5 | 0px | List items and smaller secondary text |
| Quote | Inter Tight | 15.5px | 400 | 1.5 | 0px | Block quotes |
| Button | Inter Tight | 14px | 500 | 1 | 0px | CTA text; tight line height |
| Label | Inter Tight | 14.5px | 400 | 1.4 | 0px | Form labels and input captions |
| Navigation | Inter Tight | 13px | 400 | 1.55 | 0px | Nav links and breadcrumbs |
| Code XL | JetBrains Mono | 13px | 400 | 1.55 | 0px | Incident ID headers in logs |
| Code LG | JetBrains Mono | 12.5px | 400 | 1.7 | 0px | Code blocks and terminal output |
| Code MD | JetBrains Mono | 12px | 400 | 1.7 | 0.48px | Inline code snippets |
| Code SM | JetBrains Mono | 11px | 400 | 1.7 | 0.44px | Small code references |
| Code SM Strong | JetBrains Mono | 11px | 500 | 1.7 | 1.54px | Small code headings; uppercase, bold |
| Code XS | JetBrains Mono | 10.5px | 500 | 1.55 | 1.26px | Uppercase code labels; maximum density |

### Principles

- **Negative tracking on display:** Sizes 48px and above employ negative letter-spacing (from `-1.8px` to `-0.5px`) to compress and tighten headlines, reinforcing a technical, high-precision aesthetic.
- **Weight hierarchy:** Body text defaults to 400 (regular); headings and CTAs use 500 (medium); code labels optionally 500 for emphasis.
- **Monospace as metaphor:** JetBrains Mono reserves itself for incident logs and code examples, signaling technical authenticity and production context.
- **Line height for rhythm:** Body text uses 1.6× to 1.65× for readability; headings use 1.04× to 1.2× to compress vertical space.
- **Loose vs. tight variants:** The system provides both relaxed and tight versions of body and heading sizes to permit flexible editorial control.

## 4. Component Stylings

### Buttons

#### Primary
- **Background:** `{colors.primary}` (`#005032`)
- **Text Color:** `{colors.canvas}` (`#FFFFFF`)
- **Padding:** `{spacing.md}` (`16px`) horizontal, `{spacing.md}` (`16px`) vertical (13px 16px 13px 16px as measured)
- **Border Radius:** `{rounded.full}` (`9999px`)
- **Border:** `1px solid {colors.primary}` (`#005032`)
- **Font:** `{typography.button}` (14px, weight 500, line-height 1)
- **Height:** 42px (lg variant); 41px (standard)
- **Hover:** Translate Y -1px; text color remains white

#### Primary Large
- **Background:** `{colors.primary}` (`#005032`)
- **Text Color:** `{colors.canvas}` (`#FFFFFF`)
- **Padding:** `{spacing.md}` (`14px`) all sides
- **Border Radius:** `{rounded.full}` (`9999px`)
- **Border:** None
- **Font:** `{typography.button}` (14px, weight 500, line-height 1)
- **Height:** 42px

#### Outline
- **Background:** Transparent
- **Text Color:** `{colors.body}` (`#0D1016`)
- **Padding:** `{spacing.md}` (`20px`) horizontal, `{spacing.md}` (`13px`) vertical
- **Border Radius:** `{rounded.full}` (`9999px`)
- **Border:** `1px solid {colors.hairline}` (`#E6E6E6`)
- **Font:** `{typography.button}` (14px, weight 500, line-height 1)
- **Height:** 42px
- **Hover:** Border color shifts to `{colors.ink}` (`#000000`), text color to `{colors.ink}`

#### Outline Small
- **Background:** `{colors.canvas}` (`#FFFFFF`)
- **Text Color:** `{colors.body}` (`#0D1016`)
- **Padding:** `{spacing.md}` (`16px`) horizontal, `{spacing.md}` (`13px`) vertical
- **Border Radius:** `{rounded.full}` (`9999px`)
- **Border:** `1px solid {colors.hairline}` (`#E6E6E6`)
- **Font:** `{typography.button}` (13px, weight 500, line-height 1)
- **Height:** 41px

### Cards & Containers

#### Card Default
- **Background:** Transparent
- **Text Color:** `{colors.body}` (`#0D1016`)
- **Padding:** `{spacing.band}` (`40px`) horizontal and vertical (36px 32px as measured)
- **Border Radius:** `{rounded.none}` (`0px`)
- **Border:** None
- **Font:** `{typography.body-md}` (15.5px, weight 400, line-height 1.6)
- **Box Shadow:** None

#### Card Default Large
- **Background:** `{colors.canvas}` (`#FFFFFF`)
- **Text Color:** `{colors.body}` (`#0D1016`)
- **Padding:** `{spacing.xxxl}` (`32px`) all sides
- **Border Radius:** `{rounded.sm}` (`8px`)
- **Border:** None
- **Font:** `{typography.body-md}` (15.5px, weight 400, line-height 1.6)
- **Box Shadow:** None

#### Code Block / Incident Log Container
- **Background:** `{colors.muted}` (`#1A1A1A`)
- **Text Color:** `{colors.accent-1}` (`#E68846`) for incident IDs; `{colors.canvas}` (`#FFFFFF`) for log text
- **Padding:** `{spacing.band}` (`40px`) horizontal and vertical
- **Border Radius:** `{rounded.none}` (`0px`)
- **Font:** `{typography.code-lg}` or `{typography.code-xl}` (12.5px–13px monospace)
- **Border:** None
- **Box Shadow:** None

### Navigation

#### Header Navigation
- **Background:** `{colors.canvas}` with 0.92 opacity (`rgba(255, 255, 255, 0.92)`)
- **Text Color:** `{colors.body}` (`#0D1016`)
- **Padding:** `{spacing.md}` (`32px`) horizontal, `{spacing.md}` (`14px`) vertical
- **Border Radius:** `{rounded.none}` (`0px`)
- **Border:** None
- **Font:** `{typography.nav}` (13px, weight 400, line-height 1.55)
- **Height:** 64px
- **Hover:** Text color to `{colors.ink}` (`#000000`), translate Y -1px
- **Visible Links:** 7 on desktop (1024px+); collapses to menu toggle on tablet/mobile

### Footer

#### Footer Default
- **Background:** `{colors.canvas}` (`#FFFFFF`)
- **Text Color:** `{colors.faint}` (`#68655E`)
- **Padding:** `{spacing.band}` (`40px`) horizontal and vertical
- **Border Radius:** `{rounded.none}` (`0px`)
- **Border:** `1px solid {colors.hairline}` (`#E6E6E6`)
- **Font:** `{typography.body-md}` (15px, weight 400, line-height 1.6)
- **Box Shadow:** None

### Links

#### Link Default
- **Background:** Transparent
- **Text Color:** `{colors.body}` (`#0D1016`)
- **Font:** `{typography.body-lg}` (18px, weight 500, line-height 1.55)
- **Padding:** `0px` horizontal, `{spacing.md}` (`14px`) vertical
- **Border:** None
- **Hover:** Text color to `{colors.ink}` (`#000000`)

#### Link Small
- **Background:** Transparent
- **Text Color:** `{colors.faint}` (`#68655E`)
- **Font:** `{typography.nav}` (13px, weight 400, line-height 1.55)
- **Padding:** None
- **Border:** None
- **Hover:** Color shifts to `{colors.body}` (`#0D1016`)

### Inputs & Forms

#### Input Field (inferred from label measurements)
- **Background:** `{colors.canvas}` (`#FFFFFF`)
- **Text Color:** `{colors.body}` (`#0D1016`)
- **Border Radius:** `{rounded.xs}` (`6px`)
- **Border:** `1px solid {colors.hairline}` (`#E6E6E6`)
- **Font:** `{typography.label}` (14.5px, weight 400, line-height 1.4)
- **Focus:** Border color `{colors.link}` (`#0000EE`), box-shadow `rgba(0, 0, 238, 0.1) 0px 0px 0px 3px`

## 5. Layout Principles

### Spacing System

**Base Unit:** `{spacing.xxs}` = 4px

**Scale:**
- `{spacing.xxs}` = 4px — Micro gaps between related elements
- `{spacing.xs}` = 8px — Tight padding within small components
- `{spacing.sm}` = 12px — Standard internal spacing for compact layouts
- `{spacing.md}` = 16px — Default padding for buttons, cards, and form elements
- `{spacing.lg}` = 20px — Generous spacing between medium blocks
- `{spacing.xl}` = 24px — Section-level vertical spacing
- `{spacing.xxl}` = 28px — Large vertical separation
- `{spacing.xxxl}` = 32px — Padding within large containers and cards
- `{spacing.section}` = 36px — Major section padding and gaps
- `{spacing.band}` = 40px — Full-width band and hero section padding

**Usage Context:**
- Micro (4–8px): Line-height adjustments, icon-text gaps
- Compact (12–16px): Button padding, form field spacing, list item margins
- Default (20–24px): Card padding, section headers, block separation
- Generous (28–40px): Hero sections, full-width bands, major layout divisions

### Grid & Container

- **Mobile (375px):** Single column, max-width 335px, section padding-x = `{spacing.lg}` (`20px`)
- **Tablet (768px):** Single column, max-width 704px, section padding-x = `{spacing.xxxl}` (`32px`)
- **Desktop (1024px+):** Three-column grid available, max-width 1180px (fixed), section padding-x = `{spacing.xxxl}` (`32px`)

The grid uses a 3-column structure on desktop but most layouts revert to single-column text-driven design. The max-width caps at 1180px on desktop and remains constant from 1024px onward.

### Whitespace Philosophy

Agentsure employs generous negative space and typography-driven composition. Cards and hero sections use vertical rhythm governed by the heading and body line heights, with `{spacing.band}` (`40px`) between major sections. Padding inside containers follows the scale (32–40px), and gaps between distinct content blocks range from 20–36px. The design resists visual chrome; depth and separation are achieved through color blocking (white backgrounds on light gray pages) and generous breathing room rather than borders or shadows.

### Border Radius Scale

- `{rounded.none}` = 0px — Cards, hero sections, footers, navigation bar; the default for full-width or block-level elements
- `{rounded.xs}` = 6px — Input fields, smaller contained components
- `{rounded.sm}` = 8px — Large cards and secondary containers
- `{rounded.full}` = 9999px — Buttons and pill-shaped interactive elements; the signature for CTAs

### Border Widths

- **Thin:** 1px — Used on buttons (outline variants), input fields (focus), and footer dividers. Hairline borders convey a light touch and modern minimalism.

## 6. Depth & Elevation

**Elevation Strategy:** Color-blocking — depth comes from surface colour changes, not shadows.

| Level | Treatment | Use |
|---|---|---|
| Flat | No shadow, transparent or canvas background | Default body text, hero text overlays, most prose |
| Raised | No shadow; white background on light canvas | Cards, contained sections, code log containers with dark background |
| Interactive Lift | Translate Y -1px on hover; no shadow | Buttons, nav links, interactive text; micro-elevation via transform |
| Deep Hover | Box-shadow `rgba(0, 0, 0, 0.18) 0px 8px 28px -16px`; transform: translateY(-2px) | Other interactive elements (not buttons/nav) on hover; rare, reserved for special interactive cards |

The system eschews traditional multi-layer shadows in favor of color contrast and subtle transforms. The one observed shadow (`rgba(0, 0, 0, 0.18) 0px 8px 28px -16px`) appears only on hover of specific interactive elements and is not part of the base elevation table. This keeps the design flat and technically oriented.

### Opacity Levels

- **Full:** 1.0 (default)
- **Disabled:** 0.6 — Applied to disabled buttons and form elements; combined with `transform: none` to suppress hover effects
- **Hover muted:** 0.7 — Reduced opacity for certain interactive elements on hover; signals a secondary action state

### Z-index / Layering

- **Default:** 0 (not specified; implicit)
- **Dropdown (tier 1):** z-index 50
- **Dropdown (tier 2):** z-index 55
- **Dropdown (tier 3):** z-index 60

The z-index scale suggests a shallow layering model with increments of 5 for dropdown/overlay management. No modal, toast, or sticky layer values were extracted.

## 7. Do's and Don'ts

### Do

- **Use the pill-shaped button** (`{rounded.full}` / 9999px) for all primary and secondary CTAs. This is the signature interactive element and conveys modernity.
- **Employ tight letter-spacing** on display sizes (48px and above). Negative tracking is a defining characteristic of the brand typographic voice.
- **Apply generous padding** to large content blocks (32–40px) and section separations (20–36px). Whitespace is a design material, not a mistake.
- **Stack colors for depth.** Use white backgrounds (`{colors.canvas}`) on light gray page backgrounds to create visual separation without shadows or borders.
- **Use monospace type** (JetBrains Mono) exclusively for incident logs, IDs, and code examples. This signals technical authenticity.
- **Leverage the warm accent** (`{colors.accent-1}` / `#E68846`) sparingly—only as italic highlight text in prose, never as a UI fill or button background.
- **Respect the 3-column grid on desktop,** but default most content to single-column center-aligned layouts with max-width constraints.
- **Apply the primary green** (`{colors.primary}` / `#005032`) to CTAs, active states, and brand moments. It is the only chromatic color in the system.

### Don't

- **Do NOT use shadows for depth.** Rely on color blocking and transforms instead. The system has no multi-layer shadow ladder.
- **Do NOT add unnecessary borders or lines.** Hairline dividers are reserved for footer and input focus states; most UI elements sit flush against backgrounds.
- **Do NOT over-tighten or loosen line heights** on body text. The measured 1.6× baseline is optimized for readability; deviations should be rare.
- **Do NOT apply border-radius to full-width containers.** Hero sections, cards with 0px radius, and navigation bars remain sharp; only interactive elements (buttons, inputs, smaller cards) soften their corners.
- **Do NOT mix primary green with secondary UI elements.** The brand green is reserved for CTAs and active states; secondary actions use outline variants.
- **Do NOT use the unused accent colors** (`{colors.accent-2}`, `{colors.accent-3}`) in UI. They are decorative palette members present for future extensibility only.
- **Do NOT reduce letter-spacing on headings below the measured values.** Tight tracking is intentional and reinforces technical precision.
- **Do NOT create multi-tier shadow systems.** The design is flat; use transform (translateY) for micro-elevation on hover instead.
- **Do NOT disable interaction states without explicit UX requirements.** The system provides only observed hover/focus/disabled states; do not invent others.

## 8. Responsive Behavior

### Breakpoints

| Viewport | Content Width | Grid Columns | Visible Nav Links | Menu Toggle | Display Heading | Body Text | Section Padding X |
|---|---|---|---|---|---|---|---|
| 375px (mobile) | 335px | 1 | 2 (primary nav compacts) | Yes | 40px | 15px | `{spacing.lg}` (20px) |
| 768px (tablet) | 704px | 1 | 2 (nav remains compact) | Yes | 41px | 15px | `{spacing.xxxl}` (32px) |
| 1024px (desktop) | 960px | 3 (available) | 7 (full nav visible) | No | 55px | 15px | `{spacing.xxxl}` (32px) |
| 1280px | 1180px (max-width) | 3 | 7 | No | 69px | 15px | `{spacing.xxxl}` (32px) |
| 1440px | 1180px (max-width, fixed) | 3 | 7 | No | 72px | 15px | `{spacing.xxxl}` (32px) |

**Key Breakpoints:**
- **Mobile < 1024px:** Single-column layout, compact nav with menu toggle below ~1000px
- **Desktop ≥ 1024px:** Multi-column grid available, full navigation visible, max-width container (1180px) enforced

Display heading sizes scale from 40px on mobile to 72px on large desktop; body text remains stable at 15px across all viewports.

### Touch Targets

- **Minimum interactive size:** 42px height (observed on buttons)
- **Button padding:** `{spacing.md}` (`16px`) horizontal minimum ensures adequate tap area on small screens
- **Navigation links:** `{typography.nav}` (13px) with `{spacing.md}` (14px) vertical padding for 42px total height
- **Form inputs:** `{rounded.xs}` (6px) border radius with `{spacing.md}` (16px) padding, total height 42px

All interactive elements meet or exceed 42px in height, suitable for finger interaction on touch devices.

### Collapsing Strategy

1. **Headings scale down:** Display XL drops from 72px (1440px+) to 40px (375px); heading sizing scales across breakpoints to maintain visual rhythm within narrower viewports.
2. **Content width constrains:** Maximum width reduces from 1180px (desktop) to 960px (1024px), 704px (768px), and 335px (375px); no horizontal scroll.
3. **Navigation collapses:** Full nav (7 links visible at 1024px+) compacts to 2 visible links with a menu toggle below ~1000px.
4. **Padding adjusts:** Section padding-x reduces from `{spacing.xxxl}` (32px) on tablet/desktop to `{spacing.lg}` (20px) on mobile, freeing horizontal real estate.
5. **Grid reverts to single column:** The 3-column grid layout is available but not forced; most content remains single-column text-driven across all breakpoints.
6. **Code blocks and images:** Remain full-width within their container bounds; no special responsive shrinkage applied.

## 9. Agent Prompt Guide

### Quick Color Reference

When implementing UI components, refer to these primary colors:

- **Primary CTA & Brand Accent:** Primary (`#005032`) — use for button fills, active states, and brand moments
- **Page Background:** Canvas (`#FFFFFF`) — default surface color for cards and containers
- **Heading & Primary Text:** Ink (`#000000`) — maximum contrast for headlines
- **Body Copy:** Body (`#0D1016`) — near-black for paragraph text
- **Secondary/Muted Text:** Faint (`#68655E`) — reduced contrast for captions and placeholders
- **Hairline Borders & Dividers:** Hairline (`#E6E6E6`) — light 1px strokes
- **Code/Terminal Background:** Muted (`#1A1A1A`) — dark container for incident logs
- **Accent Highlight (prose only):** Accent 1 (`#E68846`) — warm orange for italic text emphasis, never UI fills
- **Link Text (rare):** Link (`#0000EE`) — standard web blue for hyperlinks

### Iteration Guide

1. **All buttons are pill-shaped** (`{rounded.full}` / 9999px). Use primary green (`#005032`) for CTAs; outline variants use transparent background with hairline border.

2. **Display type is tightly tracked.** Sizes 48px and above carry negative letter-spacing from -1.06px to -1.8px. This is not a mistake; it is intentional compression for technical precision.

3. **Body text uses 1.6× line-height and 15.5px base size.** Never tighten or loosen this; it is optimized for readability across all viewports.

4. **Monospace (JetBrains Mono) is reserved for code blocks and incident IDs.** Do not use it for body text or UI labels.

5. **Cards and full-width sections have 0px border-radius.** Only interactive elements (buttons, inputs, small secondary cards) get rounded corners.

6. **Whitespace is intentional.** Padding inside containers: 32–40px. Gaps between sections: 20–36px. Do not compress spacing without explicit UX rationale.

7. **No shadows; use color blocking.** Depth comes from white backgrounds on light canvases and subtle Y-axis transforms on hover (translateY -1px), not box-shadow.

8. **Hover state for buttons: translateY(-1px).** Rare interactive elements use translateY(-2px) with a soft shadow (`rgba(0, 0, 0, 0.18) 0px 8px 28px -16px`).

9. **Responsive breakpoint at 1024px:** Below this, navigation compacts to menu toggle; layout remains single-column until desktop. Max-width is 1180px and fixed from 1024px onward.

10. **Warm accent (`#E68846`) appears only as italic text highlights in prose.** Do not use it for button fills, status states, or UI components.

## 10. Known Gaps

- **Interaction states for disabled inputs, error/warning states:** The extraction captured disabled button opacity (0.6) and some hover transforms, but did not observe error, success, or warning color states. These do not appear in the site's live stylesheets; assume the system has no semantic status ramp.

- **Gradients or decorative meshes:** No gradients, meshes, or blend modes were extracted. The design is a flat color-block system.

- **Multi-layer shadow elevation table:** Only one observed shadow (`rgba(0, 0, 0, 0.18) 0px 8px 28px -16px`) was recorded, appearing on rare interactive hover states. The system does not publish a traditional multi-tier elevation ladder; use color blocking and micro-transforms instead.

- **Unused accent colors in UI:** Five colors (`{colors.accent-1}`, `{colors.accent-2}`, `{colors.accent-3}`, `{colors.neutral-1}`, `{colors.neutral-2}`) were extracted from the palette but have no measurable roles in components. Accent 1 appears only as italic prose highlight; the rest remain unassigned. They are likely palette reserves for future expansion.

- **Dark mode or theme variants:** The extraction captured one theme (light background). No dark mode, high-contrast, or alternate color scheme was observed or analyzed. If the site ships a dark mode, this document does not cover it.

- **Light/dark mode toggle:** No theme-switching UI or stylesheet variants were found.

- **Animations beyond hover transforms:** The extraction noted only hover `transform` values (translateY, translate X/Y). No animation durations, easing functions, transitions, or keyframe sequences were captured.

- **Advanced form states (focus, invalid, success, loading):** Only the input focus state (border color to blue, outline shadow) was observed. Placeholder text styling, validation messaging, and loading states were not measured.

- **Surfaces behind authentication:** The analyzed page is public-facing. Any authenticated dashboards, user panels, or gated features were not captured.

- **Responsive image behavior:** Images observed do not have explicit srcset, picture elements, or aspect-ratio rules in the extracted data.

- **Opacity on interactive elements:** The system uses 0.6 opacity for disabled state and 0.7 for certain hover states. No other opacity ramps (e.g., hover, focus) for enabled interactive elements were extracted.

- **Z-index values beyond dropdowns:** Only z-index 50, 55, 60 were captured (dropdown tiers). Modal, toast, sticky header, and other layering contexts were not measured.