---
name: Kinetic Obsidian
colors:
  surface: '#121317'
  surface-dim: '#121317'
  surface-bright: '#38393d'
  surface-container-lowest: '#0d0e12'
  surface-container-low: '#1a1b20'
  surface-container: '#1f1f24'
  surface-container-high: '#292a2e'
  surface-container-highest: '#343439'
  on-surface: '#e3e2e7'
  on-surface-variant: '#e2bfb0'
  inverse-surface: '#e3e2e7'
  inverse-on-surface: '#2f3035'
  outline: '#a98a7d'
  outline-variant: '#5a4136'
  surface-tint: '#ffb693'
  primary: '#ffb693'
  on-primary: '#561f00'
  primary-container: '#ff6b00'
  on-primary-container: '#572000'
  inverse-primary: '#a04100'
  secondary: '#ffb77c'
  on-secondary: '#4d2700'
  secondary-container: '#d37b22'
  on-secondary-container: '#432100'
  tertiary: '#d0bcff'
  on-tertiary: '#3c0091'
  tertiary-container: '#a783ff'
  on-tertiary-container: '#3c0092'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdbcc'
  primary-fixed-dim: '#ffb693'
  on-primary-fixed: '#351000'
  on-primary-fixed-variant: '#7a3000'
  secondary-fixed: '#ffdcc2'
  secondary-fixed-dim: '#ffb77c'
  on-secondary-fixed: '#2e1500'
  on-secondary-fixed-variant: '#6d3900'
  tertiary-fixed: '#e9ddff'
  tertiary-fixed-dim: '#d0bcff'
  on-tertiary-fixed: '#23005c'
  on-tertiary-fixed-variant: '#5516be'
  background: '#121317'
  on-background: '#e3e2e7'
  surface-variant: '#343439'
typography:
  display-hero:
    fontFamily: Space Grotesk
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Space Grotesk
    fontSize: 38px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 18px
    fontWeight: '500'
    lineHeight: 24px
    letterSpacing: 0em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0.01em
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0.01em
  label-lg:
    fontFamily: Space Grotesk
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-md:
    fontFamily: Space Grotesk
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.06em
  label-sm:
    fontFamily: Space Grotesk
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 12px
    letterSpacing: 0.08em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-lg: 1.5rem
  margin: 1rem
  margin-md: 1.5rem
  margin-lg: 2.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

This design system expresses disciplined vitality, high-performance daily tracking, and sensory clarity. It marries the depth of an obsidian backdrop with luminous, warm ember gradients to transform routine habit logging into a ritualized personal feed. The emotional resonance is focused, premium, and relentlessly momentum-driven—giving users an executive dashboard for their physical life, health metrics, and visual memories.

The visual direction merges **refined dark-mode Glassmorphism** with **high-contrast kinetic accents**:
- Deep, pitch-black canvases softened with radial ambient glows of amber and twilight violet.
- Translucent surface panels that capture background luminance through subtle backdrop-filters and hairline illuminated borders.
- Precision timeline ticks, micro-metric cards, and high-density image grids that evoke precision instruments rather than generic lifestyle apps.

## Colors

The palette balances incendiary solar energy with pitch-dark carbon values to retain eye comfort during late-night reviews while delivering instant dopamine during task completion.

- **Primary (`#FF6B00`):** Pure energetic kinetic orange. Reserved for primary calls to action, timeline current-hour indicators, completed habit triggers, and active visual highlights.
- **Secondary (`#FF9E44`):** Soft ember orange. Used for ambient glow rims, gradient stops, secondary metrics, and active state badges.
- **Tertiary (`#8B5CF6`):** Twilight violet. Serves as a depth undertone across radial page gradients, indicating medical/recovery metrics, cognitive appointments, and calm contrast against workout intensity.
- **Neutral (`#0D0E12`):** Obsidian void base. Tinted with blue-violet micro-undertones to eliminate flat dead blacks.
- **Surface Elevation Hierarchy:**
  - `surface-0` (`#07080A`): True base background.
  - `surface-1` (`rgba(19, 21, 27, 0.75)`): Base glass container for cards and timeline panels.
  - `surface-2` (`rgba(29, 32, 42, 0.85)`): Elevated inputs, popovers, and secondary controls.
  - `border-glass` (`rgba(255, 107, 0, 0.15)`): Default subtle orange edge wireframe.
  - `border-glass-active` (`rgba(255, 107, 0, 0.6)`): Focused/hovered outline glow.

## Typography

The type scale combines the technical precision and geometric structure of **Space Grotesk** with the fluid, highly legible rhythm of **Plus Jakarta Sans**.

- **Space Grotesk** commands all visual signposts: numeric timestamps, calorie/rep totals, section titles, clock ticks, and uppercase data tags. Its slight idiosyncratic angles add high-tech character.
- **Plus Jakarta Sans** provides friction-free readability across micro-notes, food log descriptions, medical prescriptions, and conversational entries.
- All uppercase labels enforce slight tracking expansion (`letter-spacing: 0.04em - 0.08em`) to guarantee quick visual parsing when scanning dense schedules or hourly nodes.

## Layout & Spacing

The layout model uses a dense fluid grid designed to display continuous timelines, multi-slot daily agendas, and photo blocks without cognitive overwhelm.

- **Mobile Viewports (<768px):** Single-column stream with vertical timeline ticks anchored to the left. Outer edge margin sits at `1rem` to maximize photography viewing space. Habit checks and meal thumbnails stack in dual-column inline blocks (`gap: space-sm`).
- **Tablet Viewports (768px - 1024px):** 6-column fluid structure. Left rail holds the daily overview summary and calendar heat-map; the remaining columns house the dual-feed hourly journal and photo roll.
- **Desktop Viewports (>1024px):** 12-column fixed-max layout (max-width: 1440px) centered with `margin-lg` padding. 3 columns dedicated to navigation and life stats, 6 columns for the visual timeline log, and 3 columns for day/month calendar widgets and upcoming medical/chore checklists.

## Elevation & Depth

Visual hierarchy does not rely on heavy drop shadows, which can muddy dark UI. Depth is generated through **luminous translucency and spectral backdrops**:

- **Layer 0 (Canvas):** Deepest charcoal background `#07080A` with fixed ambient radial gradients:
  - Top-left glow: `radial-gradient(circle at 10% 20%, rgba(255, 107, 0, 0.08) 0%, transparent 60%)`.
  - Bottom-right accent: `radial-gradient(circle at 90% 80%, rgba(139, 92, 246, 0.06) 0%, transparent 50%)`.
- **Layer 1 (Cards & Feed Panels):** Translucent obsidian `rgba(17, 19, 24, 0.72)` supported by a `backdrop-filter: blur(16px)` and a crisp outer border `1px solid rgba(255, 107, 0, 0.12)`.
- **Layer 2 (Interactive Floating Elements & Flyouts):** `rgba(26, 29, 38, 0.88)` with `backdrop-filter: blur(24px)`, framed by `1px solid rgba(255, 158, 68, 0.35)` and cast with an ambient orange-tinted shadow: `0 12px 32px -4px rgba(255, 107, 0, 0.15)`.
- **Layer 3 (Modals & Full Overlays):** Pitch black glass with `backdrop-filter: blur(32px)` and edge-lit top boundaries resembling light falling across beveled glass.

## Shapes

The interface embraces a **Rounded (Level 2)** shape profile:
- Primary UI elements, input bars, standard grid cells, and routine card frames carry `0.5rem` (`8px`) radiuses.
- Larger media-rich container cards, life feed groupings, and calendar grid blocks leverage `rounded-lg` (`1rem` / `16px`).
- Deep modal takeovers, photo zoom drawers, and main dashboards implement `rounded-xl` (`1.5rem` / `24px`).
- Tightly grouped atomic badges, category pills, and quick-add indicators utilize continuous full-pill geometry (`rounded-full`) to immediately signal interactive affordance.

## Components

### Buttons & Interactive Controls
- **Primary Kinetic Action:** Solid vibrant orange (`#FF6B00`) texturing into `#FF7A00` with dark contrast typography (`#07080A`, weight 700). On hover, fires a focused halo glow (`box-shadow: 0 0 20px rgba(255, 107, 0, 0.45)`).
- **Secondary Ghost Glass:** Obsidian glass with `border: 1px solid rgba(255, 107, 0, 0.25)` and crisp white text. Hovering expands the border opacity to `0.8` with a subtle orange text shift.
- **Micro-Add Triggers:** Circular pill buttons pinned along hourly timeline marks for rapid 1-tap logging.

### Glassmorphism Cards & Visual Media Blocks
- **Photo Progress Cards:** Aspect ratio 4:5 or 1:1. The media is recessed with an inner gradient overlay that fades into base card obsidian at the bottom edge. Includes a top-right translucent time stamp chip and bottom overlay labels for workout loads or meal calories.
- **Hourly Timeline Modules:** Continuous hairline vertical trace on the left edge (`rgba(255, 255, 255, 0.08)`). Active/current time nodes illuminate with a solid orange ring, pulsating slightly (`rgba(255, 107, 0, 0.2)`).

### Status Chips & Category Indicators
- Height of 24px, uppercase `label-sm` font.
- **Gym/Workout:** Deep rust background (`rgba(255, 107, 0, 0.12)`), text `#FF7A00`, hairline border `rgba(255, 107, 0, 0.3)`.
- **Nutrition/Meals:** Emerald smoke tint (`rgba(34, 197, 94, 0.12)`), text `#4ADE80`.
- **Medical/Appointments:** Violet mist (`rgba(139, 92, 246, 0.12)`), text `#C084FC`.
- **Chores/Habits:** Neutral glass (`rgba(255, 255, 255, 0.06)`), text `#E2E8F0`.

### Form Inputs & Checkboxes
- **Text & Metric Fields:** Background `rgba(13, 14, 18, 0.6)`, recessed inner shadow, `1px` border `rgba(255, 255, 255, 0.1)`. Focus state illuminates the border to vibrant orange with zero layout shift.
- **Habit Checkboxes:** Custom rounded squircle (`6px`). Unchecked state has a faint translucent boundary; checking animates a spring-physics orange fill with a sharp obsidian checkmark icon.

### Calendar Grid Widget
- Micro 7-column matrix. Each day square is styled as a mini heat-cell:
  - Low completion: Charcoal cell with muted dot.
  - Full completion: Glowing amber core with a `1px` solid primary border.
  - Selected day: Distinct high-contrast orange background with black typography.