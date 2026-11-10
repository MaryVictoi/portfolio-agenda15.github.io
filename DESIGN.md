---
name: MV Portfolio System
colors:
  surface: '#111319'
  surface-dim: '#111319'
  surface-bright: '#373940'
  surface-container-lowest: '#0c0e14'
  surface-container-low: '#191b22'
  surface-container: '#1e1f26'
  surface-container-high: '#282a30'
  surface-container-highest: '#33343b'
  on-surface: '#e2e2eb'
  on-surface-variant: '#ccc3d8'
  inverse-surface: '#e2e2eb'
  inverse-on-surface: '#2e3037'
  outline: '#958da1'
  outline-variant: '#4a4455'
  surface-tint: '#d2bbff'
  primary: '#d2bbff'
  on-primary: '#3f008e'
  primary-container: '#7c3aed'
  on-primary-container: '#ede0ff'
  inverse-primary: '#732ee4'
  secondary: '#d0bcff'
  on-secondary: '#3c0091'
  secondary-container: '#571bc1'
  on-secondary-container: '#c4abff'
  tertiary: '#b9c8de'
  on-tertiary: '#233143'
  tertiary-container: '#59687b'
  on-tertiary-container: '#d8e7fe'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#eaddff'
  primary-fixed-dim: '#d2bbff'
  on-primary-fixed: '#25005a'
  on-primary-fixed-variant: '#5a00c6'
  secondary-fixed: '#e9ddff'
  secondary-fixed-dim: '#d0bcff'
  on-secondary-fixed: '#23005c'
  on-secondary-fixed-variant: '#5516be'
  tertiary-fixed: '#d4e4fa'
  tertiary-fixed-dim: '#b9c8de'
  on-tertiary-fixed: '#0d1c2d'
  on-tertiary-fixed-variant: '#39485a'
  background: '#111319'
  on-background: '#e2e2eb'
  surface-variant: '#33343b'
typography:
  display-hero:
    fontFamily: Space Grotesk
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Space Grotesk
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: 0em
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: Hanken Grotesk
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-code:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-tagline:
    fontFamily: Hanken Grotesk
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.18em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  margin: 3rem
  margin-sm: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

The design system projects an authoritative, high-tier technical persona tailored for enterprise clients, engineering leads, and technology executives. The visual character reflects precision, computational elegance, and deep mastery over Data Engineering, Scaled Automation, and Artificial Intelligence.

### Identity Core
- **Monogram:** `MV` — geometric, modern, high-precision typographic lockup utilizing clean apexes and structural line-weights.
- **Signature Motto:** *Analisar • Automatizar • Evoluir* — formatted in tracked uppercase, treated as a subtle architectural cadence across headers and hero footers.
- **Design Style:** Modern Dark Slate & Precision Computational. Combines deep midnight graphite canvases, luminous violet optical energy, structural low-contrast borders, and controlled glass-like surface diffusion.

### Visual Principles
- **Engineering Precision:** Layouts emphasize structure, tabular fidelity, and intentional white/dark space over arbitrary decorative graphics.
- **Luminescent Accentuation:** The vibrant violet spectrum is reserved for active states, high-value outcomes, model convergence points, and high-impact calls to action.
- **Data Clarity:** Complex concepts are translated into digestible visual tiers using modular surface containers and crisp slate contrasts.

## Colors

The palette leverages an obsidian foundation contrasted with an electric violet signal and muted engineering slates.

### Palette Architecture
- **Canvas Base (`#0B0D13`):** Ultimate background base; maintains deep OLED contrast without the harshness of pure black.
- **Surface Elevation Tiers:**
  - *Layer 1 (Card/Section):* `#121520` (Midnight Slate)
  - *Layer 2 (Interactive/Floating):* `#1E2333` (Graphite Surface)
  - *Layer 3 (Hover/Overlays):* `#282F45` (Illuminated Edge)
- **Primary Violet Accent (`#7C3AED` to `#8B5CF6`):** Represents AI computation, active execution, and high-priority directional cues. Used with controlled restraint.
- **Structural Slates:**
  - *Muted Text / Technical Details:* `#64748B`
  - *Secondary Content & Borders:* `#94A3B8`
- **Pure Contrast (`#FFFFFF`):** Reserved for primary editorial headings, core data figures, and crisp vector iconography.

## Typography

Typography establishes an engineering hierarchy: **Space Grotesk** delivers sharp, modern geometric headlines with technological grit; **Hanken Grotesk** balances legibility and neutrality for continuous reading; **JetBrains Mono** surfaces parameters, metrics, system statuses, and terminal data.

### Formatting Rules
- **Monogram & Signature:** The tagline *Analisar • Automatizar • Evoluir* strictly applies `label-tagline` in all caps with `0.18em` letter tracking to emulate architectural technical drawings.
- **Metrics and KPI Numbers:** Large data outcomes utilize `headline-lg` paired with a trailing `label-code` unit suffix in `#94A3B8`.
- **System Tags:** Always set in `label-code` to emphasize the algorithmic, deterministic nature of the portfolio artifacts.

## Layout & Spacing

The layout is structured around an adaptive 12-column grid system bounded inside a maximum width of `1280px`.

### Responsive Breakpoints
- **Mobile (< 768px):** 4-column layout, `margin-sm` (1.25rem), `gutter-sm` (1rem). Hero metrics stack vertically; navigation switches to a compact floating action drawer.
- **Tablet (768px - 1024px):** 8-column layout, `margin` (2rem), `gutter` (1.5rem). Case studies transition to 2-column alternating blocks.
- **Desktop (> 1024px):** 12-column layout, `margin` (3rem), `gutter` (1.5rem). Enables side-by-side data visualization and narrative architecture.

### Grid Rhythm & Component Flow
Vertical rhythm follows strict multiples of `8px` (`0.5rem`). Section separators rely on empty space (`space-xl` * 2) combined with 1px hairline dividers rather than heavy graphics.

## Elevation & Depth

Visual depth is achieved through ambient light diffusion and layered dark surfaces rather than high-contrast dropshadows.

### Layering Hierarchy
1. **Canvas Level (0):** `#0B0D13` base background.
2. **Surface Level (1):** `#121520` background with a subtle, crisp 1px perimeter border of `rgba(148, 163, 184, 0.08)`.
3. **Elevated Component Level (2):** `#1E2333` background with dual-tone depth:
   - *Outer Halo:* `0 12px 32px -8px rgba(0, 0, 0, 0.65)`
   - *Violet Resonance:* `0 0 24px -4px rgba(124, 58, 237, 0.12)` (applied exclusively on active or hovered states)
4. **Overlay / Drawer Level (3):** `rgba(18, 21, 32, 0.85)` surface with `backdrop-filter: blur(16px)` and perimeter border `rgba(124, 58, 237, 0.25)`.

## Shapes

The design system adopts a controlled, semi-industrial soft curvature (`roundedness: 1`). 

- Standard components (buttons, text inputs, code boxes) use `0.25rem` (4px).
- Containers, modal sheets, and case study cards use `rounded-lg` (`0.5rem` / 8px).
- Large showcase canvases use `rounded-xl` (`0.75rem` / 12px).
- Pill shapes are strictly prohibited except for status indicator dots (e.g., active pipeline health lights). Sharp corners are preferred for data grids to preserve technological rigor.

## Components

### Buttons
- **Primary:** Solid `#7C3AED` background, `#FFFFFF` text, `4px` radius, typography `label-code` in bold or `body-sm`. Hover transitions to `#8B5CF6` with a soft violet shadow (`0 0 16px rgba(124, 58, 237, 0.4)`).
- **Secondary / Outline:** Background `transparent`, 1px border `#64748B`, text `#FFFFFF`. Hover transitions border to `#8B5CF6` and background to `rgba(124, 58, 237, 0.08)`.
- **Tertiary / Ghost:** Text `#94A3B8`, no border. Hover shifts text to `#FFFFFF`.

### Chips & Badges
- **Technical Tags (e.g., PyTorch, Snowflake, Kafka):** Background `#1E2333`, text `#94A3B8`, border `1px solid rgba(148, 163, 184, 0.12)`, font `label-code`.
- **Active State Badges:** Background `rgba(124, 58, 237, 0.15)`, text `#8B5CF6`, border `1px solid rgba(124, 58, 237, 0.3)`.

### Cards & Project Showcases
- Background `#121520`, border `1px solid rgba(148, 163, 184, 0.08)`.
- Hover state raises card subtly via `transform: translateY(-2px)`, border shifts to `rgba(124, 58, 237, 0.35)`, with subtle illumination (`0 8px 32px rgba(124, 58, 237, 0.08)`).

### Input Fields & Terminal Controls
- Background `#0B0D13`, border `1px solid #1E2333`, typography `label-code`, text `#FFFFFF`, placeholder `#64748B`.
- Focus state applies a 1px border of `#7C3AED` and a glow of `0 0 0 2px rgba(124, 58, 237, 0.2)`.

### Architecture Pipeline Diagrams & Metric Callouts
- Interactive pipeline blocks rendered on `#1E2333` tiles, linked with 1.5px dotted paths in `#64748B` that animate to solid `#8B5CF6` when hovered or processing.