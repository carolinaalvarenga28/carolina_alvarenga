---
name: Glacial Press
colors:
  surface: '#f8f9ff'
  surface-dim: '#d5dae5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eef4fe'
  surface-container: '#e9eef9'
  surface-container-high: '#e3e8f3'
  surface-container-highest: '#dde3ed'
  on-surface: '#161c23'
  on-surface-variant: '#42474d'
  inverse-surface: '#2b3139'
  inverse-on-surface: '#ecf1fb'
  outline: '#72777e'
  outline-variant: '#c2c7ce'
  surface-tint: '#3e627f'
  primary: '#3e627f'
  on-primary: '#ffffff'
  primary-container: '#abcff1'
  on-primary-container: '#355976'
  inverse-primary: '#a7caec'
  secondary: '#2d6197'
  on-secondary: '#ffffff'
  secondary-container: '#92c1fe'
  on-secondary-container: '#144f84'
  tertiary: '#005db6'
  on-tertiary: '#ffffff'
  tertiary-container: '#b0ccff'
  on-tertiary-container: '#0054a6'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#cce5ff'
  primary-fixed-dim: '#a7caec'
  on-primary-fixed: '#001e31'
  on-primary-fixed-variant: '#254a66'
  secondary-fixed: '#d2e4ff'
  secondary-fixed-dim: '#a0c9ff'
  on-secondary-fixed: '#001c37'
  on-secondary-fixed-variant: '#07497d'
  tertiary-fixed: '#d6e3ff'
  tertiary-fixed-dim: '#a9c7ff'
  on-tertiary-fixed: '#001b3d'
  on-tertiary-fixed-variant: '#00468b'
  background: '#f8f9ff'
  on-background: '#161c23'
  surface-variant: '#dde3ed'
typography:
  display-hero:
    fontFamily: Anton
    fontSize: 96px
    fontWeight: '400'
    lineHeight: 92px
    letterSpacing: -0.02em
  display-hero-mobile:
    fontFamily: Anton
    fontSize: 52px
    fontWeight: '400'
    lineHeight: 52px
    letterSpacing: -0.01em
  headline-xl:
    fontFamily: Anton
    fontSize: 64px
    fontWeight: '400'
    lineHeight: 64px
    letterSpacing: -0.01em
  headline-xl-mobile:
    fontFamily: Anton
    fontSize: 40px
    fontWeight: '400'
    lineHeight: 42px
    letterSpacing: 0em
  headline-lg:
    fontFamily: Anton
    fontSize: 40px
    fontWeight: '400'
    lineHeight: 44px
    letterSpacing: 0em
  headline-lg-mobile:
    fontFamily: Anton
    fontSize: 30px
    fontWeight: '400'
    lineHeight: 34px
    letterSpacing: 0em
  headline-md:
    fontFamily: Anton
    fontSize: 28px
    fontWeight: '400'
    lineHeight: 32px
    letterSpacing: 0.01em
  headline-sm:
    fontFamily: Anton
    fontSize: 22px
    fontWeight: '400'
    lineHeight: 26px
    letterSpacing: 0.02em
  body-lead:
    fontFamily: Newsreader
    fontSize: 22px
    fontWeight: '400'
    lineHeight: 32px
    letterSpacing: -0.01em
  body-md:
    fontFamily: Newsreader
    fontSize: 17px
    fontWeight: '400'
    lineHeight: 26px
  body-sm:
    fontFamily: Newsreader
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.06em
  label-md:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.08em
  label-sm:
    fontFamily: Space Grotesk
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 12px
    letterSpacing: 0.12em
spacing:
  gutter: 1.5rem
  gutter-mobile: 0.75rem
  margin: 2.5rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system synthesizes Swiss International typography, high-fashion editorial print layouts, and restrained modernist brutalism. It pairs expansive, pale ice paper planes with commanding, condensed ink-black display headers and deliberate structural gridlines.

Targeted at discerning cultural institutions, digital periodicals, contemporary architecture archives, and avant-garde media platforms, the interface evokes an intellectual, precise, and uncompromisingly authoritative mood. It feels like broadsheet journalism re-engineered inside an architectural terminal.

The aesthetic philosophy centers on:
- **Structural Tension:** Heavy vertical condensed display type juxtaposed against delicate hairline rules and airy pale surfaces.
- **Architectural Flatness:** No simulated skeuomorphic depths or soft fuzzy drop-shadows; elevation is communicated through border-enclosed structural scaffolding and layered tint planes.
- **Micro-Cadence:** High-density contextual metadata, indices, folio markers, and coordinate trackers offsetting large editorial display statements.

## Colors

The palette balances frosted atmospheric light with stark lithographic ink values:

- **Primary (`#abcff1` - Ice Sky):** The primary signature tone. Deployed as an intentional high-key accent for highlighted text blocks, focused states, interactive badges, index tabs, and selected state backdrops.
- **Secondary (`#0f4c81` - Deep Sapphire):** Provides deep chromatic weight for hyperlinked editorial markers, secondary actions, and micro-branding elements.
- **Tertiary (`#2a75d3` - Vivid Cobalt):** Used sparingly as an electric signal accent—active indicators, live broadcasts, and dynamic notification pings.
- **Neutral Base (`#0b1118` - Slate Midnight):** The foundational ink tone. Used for headers, structural 1px borders, high-contrast buttons, and heavy horizontal separators.
- **Surface Roles:**
  - `surface-canvas`: `#f4f8fc` (Frosted off-white paper canvas)
  - `surface-panel`: `#ffffff` (Crisp container background)
  - `surface-tint`: `#e8f1f9` (Subtle structural panel fill)
  - `border-structural`: `#0b1118` (High-contrast structural framing)
  - `border-subtle`: `#cbdbe8` (Hairline field division)

## Typography

The typographic hierarchy establishes deliberate friction between three distinct typographic voices:

1. **The Cry (Anton):** Condensed, towering, and bold sans-serif display headers. Rendered primarily in uppercase with compact leading, transforming primary editorial titles into architectural monoliths.
2. **The Narrative (Newsreader):** Literary, authoritative serif text for body copy, article extracts, and long-form commentary, echoing traditional broadsheet press craftsmanship.
3. **The Index (Space Grotesk):** Precise, geometric, monospaced-adjacent grotesque for metadata, dates, issue tags, captions, form fields, and navigation coordinates. Always crisp, spaced, and methodical.

## Layout & Spacing

Layouts conform to a visible, strict 12-column modular grid on desktop and tablet, collapsing to a single or 2-column register on mobile viewports.

- **Desktop (1024px+):** 12 columns, 1.5rem gutters, 2.5rem outer canvas margin. Elements explicitly lock to column boundaries, separated by visible hairline borders.
- **Tablet (768px - 1023px):** 6 columns, 1rem gutters, 1.5rem outer margin.
- **Mobile (Below 768px):** 2 columns or continuous stacked grid blocks, 0.75rem gutters, 1rem margin.

Panels and cards abut directly against one another using continuous interior borders rather than floating margins, simulating the paneled columns of physical newspapers.

## Elevation & Depth

This design system rejects diffuse drop shadows and blurred skeuomorphism. Depth is achieved via **structural stratification, crisp offsets, and border mechanics**:

- **Level 0 (Base Canvas):** Pale ice-tinted backdrop (`#f4f8fc`).
- **Level 1 (Card & Module Layer):** Crisp pure white panels (`#ffffff`) bounded by either subtle steel borders (`#cbdbe8`) or midnight structural framing (`#0b1118`).
- **Level 2 (Active & Accent Planes):** Tinted Ice Sky fields (`#abcff1`) shifting upward into focus.
- **Level 3 (Brutalist Hard Shadows):** When spatial separation is needed (e.g., interactive dialogs, floating toolbars, elevated buttons), elements use solid-color, non-blurred offset projections: `box-shadow: 4px 4px 0px 0px #0b1118`.

## Shapes

Every element is completely unrounded (`roundedness: 0`). 

Corners are 0px throughout the entire interface—from interactive buttons, inputs, and flyout menus down to badges and alert bars. This uncompromising geometric edge reinforces the physical newspaper print aesthetic, ensuring that dividing hairlines cleanly meet without border-radius distortion.

## Components

### Buttons
- **Primary:** Background `#0b1118`, text `#ffffff`, border 1px solid `#0b1118`, uppercase `label-md`. On hover: background `#abcff1`, text `#0b1118`, box-shadow `3px 3px 0px 0px #0b1118`.
- **Secondary:** Background `#ffffff`, text `#0b1118`, border 1px solid `#0b1118`. On hover: background `#f4f8fc`, box-shadow `2px 2px 0px 0px #0b1118`.
- **Ghost Editorial:** Text `#0f4c81`, border-bottom 2px solid `#0f4c81`, zero background padding.

### Chips & Metadata Badges
- Sharp rectangular containers (`roundedness: 0`). Background `#e8f1f9`, border 1px solid `#cbdbe8`, text `#0b1118`, font `label-sm`, uppercase. Active state switches background to `#abcff1` with a 1px solid `#0b1118` border.

### Editorial Cards & Content Blocks
- White backgrounds encased in 1px solid `#cbdbe8` borders.
- Top card meta-band contains issue number, date, and category in `label-sm` font, separated by an explicit horizontal rule.
- Anton headline followed by Newsreader excerpt.

### Form Inputs
- Background `#ffffff`, 1px solid `#0b1118`, padding `space-sm` `space-md`, font `Space Grotesk`. Focus state displays a 2px solid `#0b1118` outline with an `#abcff1` soft focus backdrop wash.

### Checkboxes & Radios
- Strict square perimeters, 0px border-radius, 1.5px solid `#0b1118`. Selected state fills the square completely with `#0b1118`, revealing an inverted `#f4f8fc` tick mark.

### Data Ticker & Edition Banners
- Full-width band spanning the canvas edge-to-edge. Background `#abcff1`, top and bottom bordered by 1px solid `#0b1118`. Contents render monospaced updates and volume indices in `label-md`.