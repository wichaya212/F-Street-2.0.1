---
name: F STREET
colors:
  surface: '#121316'
  surface-dim: '#121316'
  surface-bright: '#38393c'
  surface-container-lowest: '#0d0e11'
  surface-container-low: '#1b1b1f'
  surface-container: '#1f1f23'
  surface-container-high: '#292a2d'
  surface-container-highest: '#343538'
  on-surface: '#e3e2e6'
  on-surface-variant: '#c3c6d7'
  inverse-surface: '#e3e2e6'
  inverse-on-surface: '#303034'
  outline: '#8d90a0'
  outline-variant: '#434655'
  surface-tint: '#b4c5ff'
  primary: '#b4c5ff'
  on-primary: '#002a78'
  primary-container: '#2563eb'
  on-primary-container: '#eeefff'
  inverse-primary: '#0053db'
  secondary: '#7bd0ff'
  on-secondary: '#00354a'
  secondary-container: '#00a6e0'
  on-secondary-container: '#00374d'
  tertiary: '#bac6e7'
  on-tertiary: '#24304a'
  tertiary-container: '#616d8a'
  on-tertiary-container: '#edf0ff'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b4c5ff'
  on-primary-fixed: '#00174b'
  on-primary-fixed-variant: '#003ea8'
  secondary-fixed: '#c4e7ff'
  secondary-fixed-dim: '#7bd0ff'
  on-secondary-fixed: '#001e2c'
  on-secondary-fixed-variant: '#004c69'
  tertiary-fixed: '#d9e2ff'
  tertiary-fixed-dim: '#bac6e7'
  on-tertiary-fixed: '#0f1b34'
  on-tertiary-fixed-variant: '#3b4662'
  background: '#121316'
  on-background: '#e3e2e6'
  surface-variant: '#343538'
typography:
  display-hero:
    fontFamily: Syne
    fontSize: 72px
    fontWeight: '800'
    lineHeight: 76px
    letterSpacing: -0.04em
  display-hero-mobile:
    fontFamily: Syne
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.03em
  headline-xl:
    fontFamily: Syne
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 52px
    letterSpacing: -0.03em
  headline-xl-mobile:
    fontFamily: Syne
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Syne
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Syne
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 30px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Syne
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: 0em
  body-lg:
    fontFamily: Space Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-md:
    fontFamily: Space Grotesk
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: 0em
  body-sm:
    fontFamily: Space Grotesk
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-caps:
    fontFamily: Space Mono
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.12em
  label-code:
    fontFamily: Space Mono
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0.04em
spacing:
  space-3xs: 0.125rem
  space-2xs: 0.25rem
  space-xs: 0.5rem
  space-sm: 0.75rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 3rem
  space-3xl: 4rem
  space-4xl: 6rem
  gutter-mobile: 1rem
  gutter-desktop: 2rem
  margin-mobile: 1rem
  margin-desktop: 3rem
---

## Brand & Style
The design system embodies the intersection of Bangkok night-culture edge and Seoul high-fashion streetwear precision. It targets fashion-forward global youth and metropolitan streetwear collectors who demand exclusivity, structural edge, and refined underground aesthetics. The interface evokes hyper-modern confidence, raw urban tension, and luxury exclusivity.

The visual style blends **High-Contrast Editorial Brutalism** with **Dark Technical Glassmorphism**. Layouts leverage stark monolithic typographic scale, razor-sharp architectural grids, and atmospheric deep slate undercurrents illuminated by electric cobalt and icy cyan accents. Surfaces feel metallic, dense, and tactile, using razor-thin borders and luminous edge highlights to carve out modular containers in low-light environments.

## Colors
The palette is rooted in an abyss of ultra-deep blacks and slate midnight blues, contrasted by hyper-saturated electric blue energy.

- **Base Void (`#0a0b0e`)**: The foundational canvas for the entire store experience, deep enough to maximize OLED black contrast while maintaining subtle cool undertones.
- **Midnight Slate Navy (`#0d1527` base, `#131f38` elevated)**: Applied to cards, navigation panels, floating sheets, and micro-surfaces to create volumetric structure without washing out darkness.
- **Electric Cobalt (`#2563eb`)**: Primary interactive color for high-intent actions, active indicator bars, key interactive badges, and brand punchlines.
- **Cyan Blue Flare (`#38bdf8`)**: Secondary tactical accent used for critical drop countdowns, rarity badges, low-stock alerts, and micro-glow highlights.
- **Crisp White (`#ffffff`)**: High-contrast editorial display headlines, hero copy, and pure-contrast icons.
- **Muted Cool Grey (`#94a3b8`)**: Secondary typography, technical specs, SKU metadata, and inactive state architecture.

## Typography
Typographic rhythm sets an uncompromising, avant-garde tone.

- **Headlines & Editorial Titles (`Syne`)**: Dynamic, sculptural, and expressive. Used in tight leading formats (`-0.04em` tracking on displays) to evoke heavy streetwear poster layouts and modern zine covers.
- **Interface & Product Body (`Space Grotesk`)**: Clean, geometric, and functional. Delivers high legibility across product specifications, sizing guides, and long-form collection background stories.
- **Data, Labels, and Specs (`Space Mono`)**: Technical and industrial. Applied to SKUs, drop timers, inventory tallies, currency displays, and size matrices in all-caps formatting with elevated letter spacing.

## Layout & Spacing
The layout follows a modular 12-column dynamic grid on desktop and a compact 4-column structure on mobile devices.

- **Grid Architecture**: 
  - **Desktop (1280px+)**: 12 columns with 32px gutters and 48px outer margins. Max content container width is locked at 1440px to preserve strict editorial proportions.
  - **Tablet (768px - 1279px)**: 8 columns with 24px gutters and 32px margins.
  - **Mobile (< 767px)**: 4 columns with 16px gutters and 16px margins, allowing zero-margin bleed for full-width lookbook imagery.
- **Section Rhythm**: Heavy vertical pacing. Editorial collection drops transition through generous vertical leaps (`space-3xl` to `space-4xl`), while product data grids collapse into dense, pressurized technical groupings using `space-xs` and `space-sm`.

## Elevation & Depth
Depth is constructed through atmospheric translucency and sharp luminous outlines rather than soft generic drop shadows.

- **Surface Level 0 (Base)**: `#0a0b0e` solid background canvas.
- **Surface Level 1 (Card & Module)**: `#0d1527` with a 1px border of `rgba(148, 163, 184, 0.12)`.
- **Surface Level 2 (Flyouts & Dropdowns)**: `#131f38` backdrop with `backdrop-filter: blur(16px)` and border `rgba(56, 189, 248, 0.2)`.
- **Surface Level 3 (Sticky Bar & Modals)**: Solid `#0d1527` overlaid with `rgba(10, 11, 14, 0.75)` backdrop blur, framed by top-edge highlight lines of `#2563eb`.
- **Glow Signatures**: Functional accents utilize an electric cyan outer glow: `box-shadow: 0 0 24px rgba(56, 189, 248, 0.25)` on primary active states, exclusive drop tags, and checkout CTAs.

## Shapes
The shape language is strictly **Sharp (`0`)**. Every container, product preview tile, CTA, badge, and input field utilizes unrounded 0px borders. This architectural brutalism emphasizes the tailored cuts, structural silhouettes, and street-ready industrial hardware found in contemporary Bangkok and Seoul designer apparel. 

Accents may feature chamfered 45-degree angled corner cuts on technical labels, drop badges, and hero tags to reinforce an engineering-grade aesthetic.

## Components

- **Buttons**:
  - *Primary*: Solid `#ffffff` background with `#0a0b0e` bold uppercase text, 0px radius, 1px border `#ffffff`. Hover: Instant transition to `#2563eb` background with white text and cyan glow highlight.
  - *Secondary / Outline*: Transparent surface, 1px border `#94a3b8`, `#ffffff` text. Hover: Border color `#38bdf8`, background `rgba(56, 189, 248, 0.08)`.
  - *Drop/Alert*: Solid `#2563eb` with all-caps monospaced status indicator icon.
- **Product Cards**:
  - Sharp 0px containers with `#0d1527` surfaces and subtle `rgba(148, 163, 184, 0.12)` borders.
  - Image frame maintains a high-fashion 3:4 aspect ratio with hover zoom effect and quick-add overlay bar sliding up from the bottom edge.
  - Top corner reserved for monospaced stock status tags (e.g., `[EDITION OF 50]`, `[SOLD OUT]`).
- **Input Fields**:
  - Background `#0d1527`, 0px border `rgba(148, 163, 184, 0.25)`, monospace placeholder text in `#94a3b8`.
  - Focus state: Border transitions to `#38bdf8` with an interior 1px cyan stroke, removing standard browser outlines.
- **Chips & Filters**:
  - Low-profile rectangular chips with monospaced text. Unselected: Dark background `#0a0b0e`, 1px border `rgba(148, 163, 184, 0.2)`. Selected: Inverted `#ffffff` surface with `#0a0b0e` text and sharp micro-cross indicator.
- **Checkboxes & Radios**:
  - Pure geometric 16px square boxes. Checkboxes fill with solid `#2563eb` with crisp white checkmark vector; Radio controls utilize an inner solid sharp square instead of circular dots.
- **Editorial Drop Banners & Lookbook Sliders**:
  - Full-width hero carousels with translucent blurred floating specs cards, featuring electric cobalt navigation indicators and live UTC release countdown timers.