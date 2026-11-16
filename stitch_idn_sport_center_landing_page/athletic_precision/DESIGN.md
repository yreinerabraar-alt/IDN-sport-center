---
name: Athletic Precision
colors:
  surface: '#faf8ff'
  surface-dim: '#d2d9f4'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3ff'
  surface-container: '#eaedff'
  surface-container-high: '#e2e7ff'
  surface-container-highest: '#dae2fd'
  on-surface: '#131b2e'
  on-surface-variant: '#434653'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#737785'
  outline-variant: '#c3c6d6'
  surface-tint: '#1357ca'
  primary: '#003f9b'
  on-primary: '#ffffff'
  primary-container: '#0d55c8'
  on-primary-container: '#c7d4ff'
  inverse-primary: '#b1c5ff'
  secondary: '#00668a'
  on-secondary: '#ffffff'
  secondary-container: '#40c2fd'
  on-secondary-container: '#004d6a'
  tertiary: '#00457f'
  on-tertiary: '#ffffff'
  tertiary-container: '#005da8'
  on-tertiary-container: '#bdd6ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2ff'
  primary-fixed-dim: '#b1c5ff'
  on-primary-fixed: '#001847'
  on-primary-fixed-variant: '#00409f'
  secondary-fixed: '#c4e7ff'
  secondary-fixed-dim: '#7bd0ff'
  on-secondary-fixed: '#001e2c'
  on-secondary-fixed-variant: '#004c69'
  tertiary-fixed: '#d4e3ff'
  tertiary-fixed-dim: '#a4c9ff'
  on-tertiary-fixed: '#001c39'
  on-tertiary-fixed-variant: '#004883'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 56px
    fontWeight: '800'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  caption:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.03em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2.5rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system embodies high-energy athleticism, operational excellence, and contemporary sports wellness. Tailored for athletes, students, facility members, and sports program directors, the interface projects dynamism, discipline, and accessibility.

The aesthetic blends **Modern Corporate Clarity** with **Athletic Minimalism**. Crisp structural lines, open whitespace, and fluid curves echo track lanes and court geometry. The interface avoids dense dark-pattern sports betting visuals, opting instead for a bright, motivational, and organized environment. High-contrast typography and vivid electric blue highlights create instantaneous visual hierarchy, driving action whether booking a court, tracking training metrics, or managing tournament brackets.

## Colors

The color architecture directly reflects the brand’s dual-tone athletic identity:

- **Primary (`#0D55C8`)**: Deep athletic royal blue, representing authority, structure, and foundational strength. Used for high-emphasis interactive surfaces, active tab states, key action buttons, and dominant brand headers.
- **Secondary (`#38BDF8`)**: Vibrant cyan blue, representing agility, velocity, and focus. Applied to badges, active indicators, live status pings, progress rings, and key micro-interactions.
- **Tertiary (`#60A5FA`)**: Soft cornflower sky blue derived from the brand logo geometry, ideal for soft tinted chip backgrounds, hovered container fills, and secondary badges.
- **Neutral (`#0F172A`)**: Deep dark slate delivering stark legibility for primary headlines and body copy, avoiding pure black to maintain an elevated, polished finish.
- **Surfaces & Canvases**: The foundational canvas rests on crisp pure white (`#FFFFFF`) with secondary backing surfaces set in ice-tinted blue-gray (`#F8FAFC` to `#F0F7FF`), producing subtle, clean separation between panels without heavy visual clutter.

## Typography

The type system is powered entirely by **Plus Jakarta Sans**, chosen for its geometric foundation, open counters, and energetic athletic curves that match the logo marks. 

- **Display & Headlines**: Tightly tracked (`-0.02em` to `-0.03em`) and heavy weights (`700`–`800`) provide an authoritative, competitive punch across tournament banners, scoreboards, and section titles.
- **Body & Data**: Regular (`400`) and Medium (`500`) weights ensure effortless reading across training logs, schedules, and policy text.
- **Labels & Numbers**: Crisp semi-bold and bold labels maintain clarity at micro scales, especially in court booking grids, jersey numbers, and time slots.

## Layout & Spacing

The layout operates on a standard 12-column responsive fluid grid designed to accommodate dense data (court schedules, member rosters, training timetables) while maintaining ample breathing room.

- **Desktop (1024px+)**: 12 columns with `2.5rem` outer margins and `1.5rem` gutters. Maximum content width locks at `1280px` for optimal readability and balanced composition.
- **Tablet (768px – 1023px)**: 8 columns with `1.5rem` outer margins and `1.25rem` gutters. Multi-column cards compress to 2-up configurations.
- **Mobile (Below 768px)**: 4 columns with `1rem` outer margins and `1rem` gutters. Multi-column metric sets collapse into fluid 1-column stacks or horizontal scrollable carousels.

Spacing rhythm relies strictly on the 4px/8px incremental scale (`0.25rem` to `2.5rem`), ensuring uniform alignment across cards, stats counters, and navigation bars.

## Elevation & Depth

Depth is established through crisp surface layering, low-contrast ghost borders, and soft atmospheric blue-tinted shadows, rather than muddy dark drop-shadows.

- **Level 0 (Flat Canvas)**: Neutral surface (`#FFFFFF` or `#F8FAFC`). No shadow. Delimited where necessary by crisp 1px borders in cool slate tint (`rgba(15, 23, 42, 0.08)` or `#E2E8F0`).
- **Level 1 (Cards & Standard Panels)**: `0 2px 8px -2px rgba(13, 85, 200, 0.06), 0 1px 3px 0 rgba(15, 23, 42, 0.04)`. Accompanied by a 1px solid border (`#E2E8F0`).
- **Level 2 (Interactive Hover & Dropdowns)**: `0 10px 24px -4px rgba(13, 85, 200, 0.10), 0 4px 8px -2px rgba(15, 23, 42, 0.04)`. Card borders shift to `#CBD5E1`.
- **Level 3 (Modals, Overlays & Sticky Nav)**: `0 20px 32px -8px rgba(15, 23, 42, 0.14), 0 8px 16px -4px rgba(13, 85, 200, 0.08)`. Navigation headers apply a 12px blur backdrop over semi-transparent `#FFFFFF` (`rgba(255, 255, 255, 0.85)`).

## Shapes

The geometric architecture uses `roundedness: 2`, providing smooth, friendly, and energetic contours that echo sports balls, running track apexes, and the fluid loops of the brand monogram.

- **Inputs, Buttons, and Selectors**: `0.75rem` (`rounded-xl`) corner radius.
- **Cards and Data Containers**: `1rem` to `1.25rem` (`rounded-2xl`) corner radius, creating distinct modular panels.
- **Badges, Tags, and Pill Tabs**: Fully pill-shaped (`9999px`) for agility and clear distinction from functional containers.

## Components

### Buttons
- **Primary**: Solid athletic royal blue (`#0D55C8`) background, pure white text, bold weight (`600`), `0.75rem` radius. Subtle hover lift with background transition to `#0A44A1`.
- **Secondary / Accent**: Soft cyan tint fill (`#F0F7FF`) with royal blue text (`#0D55C8`) and a 1px border (`#BAE6FD`). Hover state transitions to `#E0F2FE`.
- **Ghost / Tertiary**: Transparent background, slate text (`#0F172A`), hover background `#F1F5F9`.

### Chips & Filter Pills
- Fully rounded (`rounded-full`), height of 32px, padding of `0 14px`.
- Unselected: Cool gray fill (`#F8FAFC`), border in `#E2E8F0`, neutral text (`#475569`).
- Selected: Primary royal blue fill (`#0D55C8`) or vibrant sky tint (`#E0F2FE` with `#0369A1` text), conveying active category or selected court facility.

### Cards & Schedules
- Built with pure white surfaces, `1rem` corner radiuses, and crisp `1px` borders (`#E2E8F0`).
- Headers feature title-level typography paired with secondary accent badges (e.g., "Available", "Full", "Live Match").
- Schedule grids use clean horizontal dividers and alternating subtle row states (`#F8FAFC`) to maximize readability of complex time matrices.

### Form Inputs
- Height of 44px, bordered in `#CBD5E1` with a `0.75rem` radius.
- Focus state activates a 2px primary ring in `#0D55C8` with a soft outer glow (`rgba(56, 189, 248, 0.25)`).
- Clear placeholder hierarchy using `#94A3B8`.

### Specialized Sports Components
- **Court / Facility Availability Bar**: Segmented horizontal timeline using `#38BDF8` (booked), `#10B981` (open), and `#CBD5E1` (maintenance).
- **Match / Score Indicator**: High-contrast score blocks with bold tabular numeric styling, framed inside a dual-bordered container displaying team flags/monograms.