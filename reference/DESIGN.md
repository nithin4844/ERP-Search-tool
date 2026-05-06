---
name: Analyst Standard
colors:
  surface: '#f9f9ff'
  surface-dim: '#d3daef'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f3ff'
  surface-container: '#e9edff'
  surface-container-high: '#e1e8fd'
  surface-container-highest: '#dce2f7'
  on-surface: '#141b2b'
  on-surface-variant: '#424655'
  inverse-surface: '#293040'
  inverse-on-surface: '#edf0ff'
  outline: '#727687'
  outline-variant: '#c2c6d8'
  surface-tint: '#0055d5'
  primary: '#0051cb'
  on-primary: '#ffffff'
  primary-container: '#0067ff'
  on-primary-container: '#faf8ff'
  inverse-primary: '#b3c5ff'
  secondary: '#3c6a00'
  on-secondary: '#ffffff'
  secondary-container: '#abf45f'
  on-secondary-container: '#3f6f00'
  tertiary: '#a23400'
  on-tertiary: '#ffffff'
  tertiary-container: '#cc4400'
  on-tertiary-container: '#fff8f6'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2ff'
  primary-fixed-dim: '#b3c5ff'
  on-primary-fixed: '#001849'
  on-primary-fixed-variant: '#003fa3'
  secondary-fixed: '#aef762'
  secondary-fixed-dim: '#93da48'
  on-secondary-fixed: '#0e2000'
  on-secondary-fixed-variant: '#2c5000'
  tertiary-fixed: '#ffdbcf'
  tertiary-fixed-dim: '#ffb59b'
  on-tertiary-fixed: '#380d00'
  on-tertiary-fixed-variant: '#822800'
  background: '#f9f9ff'
  on-background: '#141b2b'
  surface-variant: '#dce2f7'
typography:
  headline-lg:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Inter
    fontSize: 16px
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
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 1.5rem
  section-gap: 2rem
  card-padding: 1.25rem
  stack-tight: 0.5rem
  stack-default: 1rem
---

## Brand & Style

This design system is engineered for high-utility financial analysis, blending the structured efficiency of a professional terminal with the clean, rhythmic minimalism of a modern workspace. The brand personality is authoritative, precise, and unobtrusive, designed to fade into the background so that complex data remains the primary focus. 

The aesthetic direction follows a **Corporate Minimalist** approach. It utilizes a predominantly grayscale canvas to signify seriousness and objectivity, punctuated by high-fidelity brand colors for functional signaling (actions and trends). The UI evokes a sense of "quiet intelligence," where premium quality is communicated through perfect alignment, subtle borders, and a disciplined use of whitespace.

## Colors

The color palette is anchored in a neutral "Workspace Gray" to reduce eye strain during prolonged analytical sessions. 

- **Primary Action:** A vibrant blue (#0067FF) is reserved strictly for primary calls-to-action, navigation states, and interactive data points.
- **Success/Growth:** A specialized green (#8ED443) is used for positive financial indicators, ensuring high legibility against the grayscale background.
- **Grayscale Spectrum:** We utilize #F1F5F9 for the page background to differentiate the "canvas" from the "content." Surfaces (cards) are pure #FFFFFF. 
- **Borders:** A consistent #E5E7EB is used for all structural containment, providing definition without adding visual noise.

## Typography

This design system utilizes **Inter** exclusively to maintain a systematic, utilitarian feel. The typographic scale is deliberately compact to accommodate the high information density required by financial dashboards.

- **Data Readability:** Body sizes are centered around 13px and 14px for maximum efficiency in data tables and lists.
- **Hierarchy:** We use font weight (Semi-bold 600) rather than excessive size increases to denote hierarchy, maintaining a level visual plane.
- **Labels:** Small, uppercase labels with increased letter spacing are used for table headers and category descriptors to differentiate metadata from primary data.

## Layout & Spacing

The layout employs a **Fixed Grid** philosophy for dashboard views, ensuring that complex data tables and charts remain in a predictable, stable position. 

- **Grid:** A 12-column system with a 24px gutter. 
- **Density:** We utilize a "Compact-First" spacing rhythm. Internal card padding is set to 20px (1.25rem) to balance information density with a premium, breathable feel. 
- **Alignment:** All elements must align to a 4px baseline grid to ensure mathematical precision in the UI, reflecting the precision of the financial data it displays.

## Elevation & Depth

Depth in this design system is achieved through **Tonal Layering** and **Low-Contrast Outlines** rather than aggressive shadows. 

- **Surface Levels:** The base background is #F1F5F9. Content sits on #FFFFFF cards.
- **Outlines:** Every card and interactive element features a 1px border of #E5E7EB. 
- **Shadows:** We use a single "Ambient" shadow style for elevated cards: `0 1px 3px 0 rgba(0, 0, 0, 0.05), 0 1px 2px 0 rgba(0, 0, 0, 0.03)`. This provides just enough lift to suggest interactability without breaking the minimalist aesthetic.
- **Hover States:** Interactive surfaces transition from a flat state to a subtle shadow on hover, accompanied by a 1px border color shift to a slightly darker gray.

## Shapes

The shape language is **Soft** and disciplined. 

- **Corners:** A base radius of 4px (0.25rem) is used for buttons and inputs. Larger containers and cards use a 8px (0.5rem) radius to create a nesting effect that feels organized.
- **Dividers:** Thin, 1px horizontal and vertical lines (#E5E7EB) are used within cards to separate data groups without the need for additional whitespace.
- **Data Points:** Graphs and charts should utilize slightly rounded stroke caps to maintain consistency with the UI's geometry.

## Components

- **Buttons:** Primary buttons use #0067FF with white text. Secondary buttons are white with #E5E7EB borders and dark text. All buttons feature a subtle 4px corner radius.
- **Cards:** The foundational unit of the design system. Cards must have a white background, a 1px border (#E5E7EB), and the "Ambient" shadow on hover.
- **Data Tables:** Headers should use `label-md` typography with a light gray background (#F8FAFC). Row heights should be compact (36px-40px) with thin dividers between rows.
- **Input Fields:** Minimalist design with a 1px border. On focus, the border color changes to #0067FF with a subtle 2px glow.
- **Chips/Badges:** Used for status or categories. They feature a soft background tint of the primary or secondary color (at 10% opacity) with high-contrast text.
- **Metric Tiles:** Dedicated components for "Big Numbers" that highlight a single financial metric with a corresponding trend indicator (using the secondary green color).