---
name: Academic Precision
colors:
  surface: '#f8f9fa'
  surface-dim: '#d9dadb'
  surface-bright: '#f8f9fa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4f5'
  surface-container: '#edeeef'
  surface-container-high: '#e7e8e9'
  surface-container-highest: '#e1e3e4'
  on-surface: '#191c1d'
  on-surface-variant: '#434654'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#737686'
  outline-variant: '#c3c5d7'
  surface-tint: '#1353d8'
  primary: '#003fb1'
  on-primary: '#ffffff'
  primary-container: '#1a56db'
  on-primary-container: '#d4dcff'
  inverse-primary: '#b5c4ff'
  secondary: '#7127e5'
  on-secondary: '#ffffff'
  secondary-container: '#8b4aff'
  on-secondary-container: '#fffbff'
  tertiary: '#852b00'
  on-tertiary: '#ffffff'
  tertiary-container: '#ad3b00'
  on-tertiary-container: '#ffd4c5'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b5c4ff'
  on-primary-fixed: '#00174d'
  on-primary-fixed-variant: '#003dab'
  secondary-fixed: '#eaddff'
  secondary-fixed-dim: '#d2bbff'
  on-secondary-fixed: '#25005a'
  on-secondary-fixed-variant: '#5a00c6'
  tertiary-fixed: '#ffdbcf'
  tertiary-fixed-dim: '#ffb59a'
  on-tertiary-fixed: '#380d00'
  on-tertiary-fixed-variant: '#802a00'
  background: '#f8f9fa'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
typography:
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
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
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
  stats-number:
    fontFamily: Hanken Grotesk
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
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
  max-width: 1200px
---

## Brand & Style

This design system centers on **Corporate Modernism** with a focus on educational efficiency. The brand personality is professional, reliable, and frictionless, specifically tailored for the high-frequency task of student attendance. 

The aesthetic prioritizes clarity over decoration, utilizing generous whitespace and a structured hierarchy to ensure users can process information quickly. The emotional response should be one of "quiet confidence"—the app feels like a dependable tool that stays out of the way while providing high utility.

- **Primary Style:** Corporate / Modern.
- **Visual Tone:** Crisp, methodical, and accessible.
- **Target Audience:** Educators, administrators, and students who require immediate data entry and retrieval.

## Colors

The palette is anchored by a professional "Academic Blue" that signals authority and stability.

- **Primary (#1A56DB):** Used for primary actions, active states, and key navigational elements.
- **Secondary (#7E3AF2):** A muted violet used sparingly for accentuating progress or highlighting secondary categories (e.g., specific course types).
- **Neutral / Background (#F9FAFB):** A very light gray-white used for page backgrounds to reduce eye strain compared to pure white.
- **Borders (#E5E7EB):** Soft gray strokes define structure without creating visual noise.
- **Success/Warning/Error:** Standard semantic greens (#059669) and reds (#DC2626) are used for attendance statuses (Present/Absent).

## Typography

The system uses a pairing of **Hanken Grotesk** for displays and **Inter** for functional UI text. This combination balances contemporary flair with maximum legibility.

- **Headlines:** Use Hanken Grotesk with tighter letter-spacing for a modern, "designed" feel. 
- **Body & Data:** Use Inter for its exceptional readability at small sizes, crucial for scanning long lists of names or timestamps.
- **Numerical Data:** Stats (like attendance percentages) should use the `stats-number` style to emphasize key performance indicators.

## Layout & Spacing

The layout follows a **Fluid Grid** model with a focus on vertical rhythm. 

- **Grid:** A 12-column system for desktop and a 4-column system for mobile.
- **Rhythm:** All margins and paddings are multiples of 4px. Use 16px as the standard "container padding" for cards and list items.
- **Attendance Lists:** For mobile, use full-width rows with 12px vertical gaps to ensure large "tap targets" for attendance marking. On desktop, lists transition into a structured table with 1px soft gray dividers.

## Elevation & Depth

This design system uses **Tonal Layers** and **Low-contrast outlines** rather than heavy shadows to maintain a clean, "flat-plus" appearance.

- **Level 0 (Surface):** Neutral background (#F9FAFB).
- **Level 1 (Cards/Containers):** Pure white (#FFFFFF) with a 1px border (#E5E7EB).
- **Level 2 (Modals/Popovers):** Pure white with a very soft, diffused shadow (0px 10px 15px -3px rgba(0, 0, 0, 0.05)) to suggest interaction.
- **Depth via Color:** Active items should use the Primary Blue as a subtle left-hand border (4px width) to indicate selection without adding physical height.

## Shapes

The shape language is **Soft** and systematic.

- **Standard Elements:** Inputs, buttons, and small cards use a 0.25rem (4px) radius. This reflects professional restraint while avoiding the harshness of sharp corners.
- **Large Containers:** Dashboard widgets or profile cards use `rounded-lg` (0.5rem) to provide a gentle, modern frame.
- **Status Indicators:** Icons and "Present/Absent" chips utilize a circular or high-radius pill shape to differentiate them from functional buttons.

## Components

### Buttons
- **Primary:** Solid Primary Blue with white text. High contrast for the "Submit Attendance" action.
- **Secondary:** White background with 1px Gray border and Blue text.
- **Size:** Minimum touch target of 44px height for mobile efficiency.

### Attendance Chips
- Small, pill-shaped indicators. 
- **Present:** Light green background with dark green text.
- **Absent:** Light red background with dark red text.
- **Excused:** Light gray background with dark gray text.

### Input Fields
- Clean, 1px bordered boxes. On focus, the border color changes to Primary Blue with a 2px outer "halo" (low opacity blue).
- Labels are always positioned above the field using the `label-md` style.

### Attendance Rows (Custom Component)
- A horizontal list item containing: Student Avatar (left), Name/ID (center), and a segmented toggle for status (right).
- Large tap areas are mandatory to prevent "fat-finger" errors during rapid roll-calling.

### Cards
- White background, 1px border, no shadow.
- Used for grouping classes, modules, or daily summaries on the dashboard.