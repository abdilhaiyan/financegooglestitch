---
name: Technical Precision
colors:
  surface: '#101416'
  surface-dim: '#101416'
  surface-bright: '#363a3c'
  surface-container-lowest: '#0b0f11'
  surface-container-low: '#181c1e'
  surface-container: '#1c2023'
  surface-container-high: '#262b2d'
  surface-container-highest: '#313538'
  on-surface: '#e0e3e6'
  on-surface-variant: '#c7c4d8'
  inverse-surface: '#e0e3e6'
  inverse-on-surface: '#2d3133'
  outline: '#918fa1'
  outline-variant: '#464555'
  surface-tint: '#c3c0ff'
  primary: '#c3c0ff'
  on-primary: '#1d00a5'
  primary-container: '#635bff'
  on-primary-container: '#fefaff'
  inverse-primary: '#4c42e9'
  secondary: '#b0c8eb'
  on-secondary: '#19324d'
  secondary-container: '#314865'
  on-secondary-container: '#9fb7d9'
  tertiary: '#ffb68f'
  on-tertiary: '#542100'
  tertiary-container: '#be5400'
  on-tertiary-container: '#fffaf9'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e2dfff'
  primary-fixed-dim: '#c3c0ff'
  on-primary-fixed: '#0f0069'
  on-primary-fixed-variant: '#321ed2'
  secondary-fixed: '#d2e4ff'
  secondary-fixed-dim: '#b0c8eb'
  on-secondary-fixed: '#001c37'
  on-secondary-fixed-variant: '#314865'
  tertiary-fixed: '#ffdbca'
  tertiary-fixed-dim: '#ffb68f'
  on-tertiary-fixed: '#331100'
  on-tertiary-fixed-variant: '#773200'
  background: '#101416'
  on-background: '#e0e3e6'
  surface-variant: '#313538'
  status-income: '#10B981'
  status-expense: '#EF4444'
  status-info: '#0EA5E9'
  surface-slate: '#1E293B'
  border-low-contrast: '#334155'
typography:
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 10px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.04em
  data-display:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: -0.01em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  gutter: 16px
  margin-mobile: 16px
  margin-desktop: 32px
  table-row-height: 32px
  compact-padding: 8px
---

## Brand & Style

This design system is engineered for high-performance financial environments where data density and technical clarity are paramount. The brand personality is authoritative, systematic, and transparent, catering to analysts and financial controllers who require immediate access to complex information without visual fatigue.

The design style follows a **Corporate / Modern** aesthetic with elements of **Minimalism**. It prioritizes function over form, utilizing heavy whitespace within components to maintain legibility while keeping the overall layout extremely compact. The visual language is defined by sharp execution, subtle tonal layering, and a rigorous adherence to a logic-driven grid system.

## Colors

The palette is optimized for long-session endurance. The primary color (Royal Blue) is reserved for high-intent actions and primary focus states. The background architecture utilizes deep navy and slate grays to reduce eye strain in high-density data views.

In **Dark Mode** (default), surfaces use tiered slate grays to establish hierarchy. In **Light Mode**, the system shifts to a clean, high-contrast white and off-white (`#F6F9FC`) foundation. Functional colors are used with clinical precision: Emerald specifically denotes positive financial flow, while Crimson marks expenses or negative deltas. These are used sparingly to ensure they remain effective as cognitive signals.

## Typography

The system utilizes **Inter** for all UI copy due to its exceptional legibility at small sizes and its neutral, professional tone. For tabular data and numerical figures, **JetBrains Mono** is employed to ensure character alignment and rapid scanning of financial values.

Typography levels are intentionally constrained to maintain a tight visual hierarchy. Mobile adjustments are minimal, focusing on reducing headline scales (e.g., `headline-lg` reduces to 24px) while preserving the body and data scales for functional parity across devices.

## Layout & Spacing

This design system employs a **Fixed Grid** model for desktop dashboards to ensure data visualizations remain predictable and comparable across sessions. The system is built on a strict 4px baseline grid.

- **Desktop (1440px+):** 12-column grid with 16px gutters.
- **Tablet (768px - 1439px):** 8-column grid with 16px gutters.
- **Mobile (<767px):** 4-column grid with 12px gutters.

The spacing rhythm is aggressive. Vertical spacing in data tables is minimized (32px row heights) to maximize the amount of information visible "above the fold." Components use a "compact" internal padding of 8px to keep control clusters tight and efficient.

## Elevation & Depth

Visual hierarchy is achieved through **Tonal Layers** and **Low-contrast Outlines** rather than heavy shadows. In the dark theme, the base background is the darkest surface, with interactive components (cards, inputs) appearing one shade lighter.

- **Level 0 (Background):** Deepest navy. Used for the main canvas.
- **Level 1 (Cards/Sidebar):** Slate gray. Used to group related data points.
- **Level 2 (Hover/Active):** Slightly lighter slate or subtle primary tint.
- **Borders:** 1px solid borders using `border-low-contrast` are the primary separator, ensuring clear structural definition without adding visual weight. Shadows are only used on floating elements (modals, dropdowns) and are kept sharp with low diffusion (0px 4px 12px, 20% opacity).

## Shapes

The shape language is **Soft** but leaning toward sharp. A 4px (`0.25rem`) corner radius is the standard for almost all elements—buttons, inputs, and cards. This slight rounding provides a hint of modernity without sacrificing the "serious" architectural feel of the dashboard. Large containers like main content panels use an 8px radius to subtly distinguish them from the internal components.

## Components

### Buttons
Buttons use high-saturation fills for primary actions (`#635BFF`) and ghost/outline styles for secondary filters. The height is fixed at 32px for standard and 28px for compact data-view controls.

### Data Tables
Tables are the core component. Use zebra-striping with extremely low contrast. Hover states must highlight the entire row with a subtle slate tint. Column headers use `label-sm` with a distinct border-bottom.

### Input Fields
Inputs are "low-profile." They feature a 1px border and use the `surface-slate` color as their background. The focus state is indicated by a primary-colored 1px ring, avoiding any "glow" effects to keep the UI crisp.

### Chips & Badges
Status badges for "Income" and "Expense" use a "soft-fill" approach: a low-opacity background of the status color with high-contrast text on top. They should be compact, using `label-sm` typography.

### Integrated Filter Bars
Filter bars are pinned to the top of data containers. They use a unified horizontal layout with 8px spacing between dropdowns, allowing for rapid parameter adjustment without entering sub-menus.