---
name: Trazo Mental
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
  on-surface-variant: '#e0c0b1'
  inverse-surface: '#e3e2e6'
  inverse-on-surface: '#2f3034'
  outline: '#a78b7d'
  outline-variant: '#584236'
  surface-tint: '#ffb68e'
  primary: '#ffb68e'
  on-primary: '#542200'
  primary-container: '#ff7a1a'
  on-primary-container: '#5e2700'
  inverse-primary: '#9c4500'
  secondary: '#ffd799'
  on-secondary: '#432c00'
  secondary-container: '#feb300'
  on-secondary-container: '#6a4800'
  tertiary: '#26dcdd'
  on-tertiary: '#003737'
  tertiary-container: '#00b2b3'
  on-tertiary-container: '#003e3e'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdbca'
  primary-fixed-dim: '#ffb68e'
  on-primary-fixed: '#331200'
  on-primary-fixed-variant: '#773300'
  secondary-fixed: '#ffdeac'
  secondary-fixed-dim: '#ffba38'
  on-secondary-fixed: '#281900'
  on-secondary-fixed-variant: '#604100'
  tertiary-fixed: '#56f9f9'
  tertiary-fixed-dim: '#26dcdd'
  on-tertiary-fixed: '#002020'
  on-tertiary-fixed-variant: '#004f50'
  background: '#121316'
  on-background: '#e3e2e6'
  surface-variant: '#343538'
typography:
  display-xl:
    fontFamily: Space Grotesk
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-xl-mobile:
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
    fontSize: 22px
    fontWeight: '500'
    lineHeight: 30px
    letterSpacing: 0em
  title-md:
    fontFamily: Space Grotesk
    fontSize: 18px
    fontWeight: '500'
    lineHeight: 26px
    letterSpacing: 0em
  title-sm:
    fontFamily: Space Grotesk
    fontSize: 15px
    fontWeight: '600'
    lineHeight: 22px
    letterSpacing: 0.01em
  body-lg:
    fontFamily: Space Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
    letterSpacing: 0em
  body-md:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: 0em
  body-sm:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-metric:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-code:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '400'
    lineHeight: 14px
    letterSpacing: 0.04em
  caption:
    fontFamily: Space Grotesk
    fontSize: 11px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0.02em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.25rem
  gutter-mobile: 0.75rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

### Brand Personality & Audience
The brand represents high-precision architectural design, environmental computing, and climatic simulation. It merges the analytical rigor of computational engineering with the intuitive, tactile craft of architectural sketching. 

The target audience comprises bioclimatic architects, urban environmental engineers, passive-house consultants, and computational designers who navigate complex volumetric simulations, thermal envelopes, and aerodynamic studies.

The interface evokes technical precision, solar radiance, environmental mastery, and generative dynamism. It avoids frivolous ornamentation in favor of metric clarity, structural rhythm, and radiant contrast.

### Design Movement & Aesthetic Expression
The design system operates at the intersection of **Technical Modernism** and **Atmospheric Glassmorphism**:
- **Monolithic Technical Dark Mode**: Grounded in deep graphite and obsidian charcoal canvas tones that simulate architectural CAD/BIM environments while maintaining long-session optical comfort.
- **Radiant Energy System**: High-chroma solar accents (architectural orange and radiant amber) juxtaposed with aerodynamic cyan vector paths, mimicking physical simulation models (solar azimuths, thermal mass, CFD airflow currents).
- **Metric Rigor**: Visible alignment axes, subtle datum lines, micro-data indicators, and coordinate readouts, establishing an undeniable instrument-grade tool feel.

## Colors

### Color Strategy
The chromatic hierarchy simulates environmental thermodynamics directly on the display surface:
- **Primary (`#FF7A1A` - Architectural Orange)**: Represents focused radiation, thermal intervention points, primary interactive states, and focal building geometry.
- **Secondary (`#FFB300` - Solar Amber)**: Conveys solar exposure analysis, daylight factor vectors, warning thresholds, and peak thermal gain markers.
- **Tertiary (`#00D2D3` - Aerodynamic Breeze / Cyan)**: Utilized exclusively for climatic airflow trajectories, passive ventilation channels, cooling loads, and convective vector paths.
- **Neutral Canvas (`#121316` to `#252830`)**: Obsidian graphite base with cool undertones engineered to recede, offering infinite perceived viewport depth for volumetric renders.

### Functional Surfaces & Tokens
- **Canvas Base**: `#121316`
- **Surface Elevation 1 (Panels & Toolbars)**: `#1A1C22`
- **Surface Elevation 2 (Cards & Inspectors)**: `#252830`
- **Surface Overlay / Active Container**: `#2E333D`
- **Ghost Outlines / Datum Borders**: `rgba(255, 255, 255, 0.08)`
- **Hover/Selected Borders**: `rgba(255, 122, 26, 0.4)`
- **Text Primary**: `#F8FAFC`
- **Text Secondary (Technical Metadata)**: `#94A3B8`
- **Text Muted (Grid Axis/Units)**: `#64748B`

## Typography

### Structural Approach
Typography reinforces geometric precision and architectural documentation clarity:
- **Headings & Body (`Space Grotesk`)**: Anchors visual balance with its deliberate ink-traps, modernist geometric skeleton, and industrial Scandinavian character. It scales effortlessly from commanding hero headlines down to contextual UI documentation.
- **Data & Measurement Tokens (`JetBrains Mono`)**: Powers numeric metrics, solar angles, CFD velocities (m/s), geographic coordinates, volumetric ratios, and simulation timelines.
- **Rhythm**: All line-height values snap strictly to 2px/4px vertical increments to sustain spatial balance against technical HUD overlays.

## Layout & Spacing

### Layout Architecture
The layout uses a **fluid-modular CAD shell system**:
- **Application Shell**: Operates via persistent docked side rails (tools, viewport inspector, environmental timeline, sunpath controller) enclosing a responsive central 3D/isometric viewport.
- **Content Dashboard**: Implements a 12-column dynamic grid on desktop, scaling to 8 columns on tablet and 4 columns on mobile.
- **Datum Anchors**: Section boundaries utilize hair-thin technical datum rules (`1px` width with `space-sm` notch marks) rather than thick dividers, keeping the workspace uncluttered.

### Breakpoint Matrix
- **Mobile (< 768px)**: Stacked viewport with collapsible bottom-sheet inspectors. Margins snap to `margin-mobile` (1rem), with single-column analytical modules.
- **Tablet (768px - 1199px)**: Floating transparent utility palettes; two-column analytical breakdowns.
- **Desktop (>= 1200px)**: Multi-panel continuous workspace; three-column metric inspector with split-pane solar/wind visualizers.

## Elevation & Depth

### Atmospheric Volumetric Hierarchy
Elevation relies on tonal stacking and calibrated ghost outlines instead of conventional heavy drop shadows:
- **Level 0 (Simulation Canvas)**: Pitch background `#121316` with a low-opacity orthographic micro-grid (`rgba(255, 255, 255, 0.03)`).
- **Level 1 (Docked Structural Toolbars)**: `#1A1C22` with a `1px` solid border of `rgba(255, 255, 255, 0.06)`. No shadow.
- **Level 2 (Floating Analysis Cards & HUD Overlays)**: `#252830` with `backdrop-filter: blur(16px)` and an ambient, low-profile rim lighting: `0 8px 32px -4px rgba(0, 0, 0, 0.65), inset 0 1px 0 rgba(255, 255, 255, 0.08)`.
- **Level 3 (Focused Modal / Active Vector Gizmos)**: `#2E333D` enclosed by an illuminated focus state: `0 0 24px -2px rgba(255, 122, 26, 0.25), 0 12px 40px rgba(0, 0, 0, 0.8)`.

### Chromatic Glows
Simulations harness calibrated luminescent accents:
- **Thermal Hotspots**: Subtle radial gradients in `#FF7A1A` with 15% opacity to visualize high radiation values.
- **Ventilation Trails**: Linear gradient lines blending from transparent to `#00D2D3` with an outer soft glow `box-shadow: 0 0 8px rgba(0, 210, 211, 0.5)`.

## Shapes

### Architectural Precision
Roundedness is set to `1` (Soft - subtle corner softening):
- Standard interactive elements (buttons, inputs, status pills) feature a sharp `0.25rem` (4px) corner radius, preserving the feel of milled aluminum instruments and drafting devices.
- Flyout panels, dialogs, and large view cards maintain `0.5rem` (8px) radius to prevent harsh corner artifacts over complex visual simulations.
- Avoid large organic bubbles or circular pill geometries; structural corners must remain disciplined, architectural, and grounded.

## Components

### Buttons
- **Primary (Solar Vector Action)**: Solid `#FF7A1A` background with `#121316` high-contrast bold typography. On hover, shifts to `#FF8A33` with an ambient glow (`0 0 16px rgba(255, 122, 26, 0.4)`).
- **Secondary (Aerodynamic Trigger)**: Transparent base with `#00D2D3` border (1px) and `#00D2D3` typography. Hover initiates `rgba(0, 210, 211, 0.12)` fill.
- **Tertiary / Utility**: Ghost button with `#252830` fill, `rgba(255, 255, 255, 0.08)` border, and `#F8FAFC` label.

### Chips & Badges
- Compact `JetBrains Mono` text in uppercase.
- Solar chips utilize `rgba(255, 179, 0, 0.12)` background with `#FFB300` border and text.
- Aerodynamic/airflow chips utilize `rgba(0, 210, 211, 0.12)` background with `#00D2D3` border and text.
- Height standard is fixed at `22px` with `6px` horizontal padding.

### Lists & Metric Rows
- Borderless list rows separated by `1px` subtle rules (`rgba(255, 255, 255, 0.04)`).
- Left-aligned parameter name (`Space Grotesk`, 13px) matched with right-aligned numeric data (`JetBrains Mono`, 13px) accompanied by physical units (`m³`, `kWh/m²`, `m/s`).

### Checkboxes & Radio Controls
- Sharp `3px` corners for checkboxes; strict geometric rings for radios.
- Inactive state: `rgba(255, 255, 255, 0.15)` border on `#1A1C22`.
- Active state: Solid `#FF7A1A` fill with dark contrasting inner micro-glyph.

### Input Fields & Scrubbers
- Dark recessed background `#16181D` with inset shadow `inset 0 2px 4px rgba(0, 0, 0, 0.5)`.
- Numeric inputs integrate direct drag-to-scrub handles and inline unit suffixes.
- Active focus displays a `1px` solid ring of `#FF7A1A`.

### Cards & Analytical Modules
- Multi-tier surface structure (`#1A1C22` base with `#252830` header bars).
- Integrated metric headers with status indicators (e.g., active sun simulation, wind tunnel load).
- Structural micro-dividers with subtle visual reference crosshairs in panel corners.

### Domain-Specific Components
- **Sunpath Scrubber**: Circular or horizontal solar slider showing elevation (0°-90°) and azimuth angles with dynamic solar amber gradient fills.
- **Wind Rose HUD**: Polar coordinate overlay rendered with `#00D2D3` vector ticks and speed scales.
- **Thermal Gradient Legend**: Linear ribbon detailing surface temperatures from `#00D2D3` (cooling) through `#FFB300` to `#FF7A1A` (radiation peak).