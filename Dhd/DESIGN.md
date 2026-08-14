---
name: Precision & Void
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f3'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#424656'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f0f1f1'
  outline: '#727687'
  outline-variant: '#c2c6d8'
  surface-tint: '#0054d6'
  primary: '#0050cb'
  on-primary: '#ffffff'
  primary-container: '#0066ff'
  on-primary-container: '#f8f7ff'
  inverse-primary: '#b3c5ff'
  secondary: '#5f5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e2dfde'
  on-secondary-container: '#636262'
  tertiary: '#a33200'
  on-tertiary: '#ffffff'
  tertiary-container: '#cc4204'
  on-tertiary-container: '#fff6f4'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae1ff'
  primary-fixed-dim: '#b3c5ff'
  on-primary-fixed: '#001849'
  on-primary-fixed-variant: '#003fa4'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474746'
  tertiary-fixed: '#ffdbd0'
  tertiary-fixed-dim: '#ffb59d'
  on-tertiary-fixed: '#390c00'
  on-tertiary-fixed-variant: '#832600'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  display:
    fontFamily: Inter
    fontSize: 72px
    fontWeight: '600'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.03em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
    letterSpacing: -0.02em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: -0.01em
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: '0'
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.0'
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
  section-gap: 128px
---

## Brand & Style
The design system is rooted in the principles of industrial precision and high-end minimalism. It targets professionals and enthusiasts in the 3D printing and manufacturing space who value clarity, technical accuracy, and sophisticated aesthetics. 

The visual language draws heavily from Neo-Minimalism, emphasizing:
- **Spatial Intent:** Massive amounts of white space to isolate technical subjects and elevate them to "art objects."
- **Geometric Rigor:** A strictly aligned grid that mirrors the Cartesian coordinates of 3D printing hardware.
- **Architectural Clarity:** Layouts are built using structural hierarchy rather than decorative elements.
- **Technological Premium:** A cold, clean atmosphere that suggests high-performance machinery and cutting-edge material science.

## Colors
The palette is intentionally restrained to maintain focus on high-fidelity product imagery and technical data.

- **Background (#FAFAFA):** A slightly off-white base that prevents screen glare and provides a premium, "gallery" feel.
- **Typography (#1A1A1A):** A deep, graphite black for high legibility and a grounded, authoritative presence.
- **Accent (#0066FF):** A precision tech-blue used sparingly for interactive elements, progress indicators, and focal points.
- **Surface (#FFFFFF):** Pure white is reserved for cards and containers to create a subtle lift from the background.
- **Borders (#E5E5E5):** Hairline strokes used for structural definition without adding visual weight.

## Typography
The system uses **Inter** for its neutral, systematic clarity and excellent legibility across all scales. To reinforce the technical nature of 3D printing, **JetBrains Mono** is introduced for labels and data points.

- **Display & Headlines:** Utilize tight letter-spacing and heavy weights to create a sense of solid, manufactured objects.
- **Body Text:** Generous line-height ensures readability of technical specifications.
- **Data Labels:** Always in monospaced font to evoke the feel of G-code, measurements, and engineering parameters.

## Layout & Spacing
The layout follows a 12-column fixed-width grid for desktop to ensure content remains centered and easy to scan.

- **Rhythm:** All spacing is derived from an 8px base unit. 
- **Section Gaps:** Large vertical gaps (128px+) are used to separate different modules, allowing each product feature to breathe.
- **Alignment:** Content should strictly follow the grid lines. Text blocks should generally be left-aligned to mirror the precision of technical blueprints.
- **Mobile:** On mobile, the 12-column grid collapses to a 4-column fluid layout with reduced margins.

## Elevation & Depth
In alignment with the Apple-like aesthetic, depth is communicated through **tonal layers** and **translucency** rather than heavy shadows.

- **Surface Tiers:** Background (#FAFAFA) is level 0. Cards and Modals use Surface (#FFFFFF) at level 1.
- **Hairline Outlines:** Use 1px solid borders (#E5E5E5) instead of shadows to define containers.
- **Soft Shadows:** Only used for floating elements (like dropdowns) to provide context. Shadows should be ultra-diffused: `0px 10px 30px rgba(0, 0, 0, 0.04)`.
- **Glassmorphism:** Navigation bars use a backdrop blur (20px) with 80% opacity Surface color to maintain a sense of space as the user scrolls.

## Shapes
The shape language is "Soft-Tech." It avoids the extreme roundness of consumer apps in favor of a more professional, "machined" look.

- **Small Components:** (Buttons, Inputs) use a 0.25rem (4px) radius.
- **Large Components:** (Cards, Images) use a 0.5rem (8px) radius.
- **Icons:** Use thin 1.5pt strokes with square caps to match the geometric theme.

## Components

- **Buttons:** 
  - *Primary:* Solid Black (#1A1A1A) with white text. No rounded-pill shapes; use 4px radius. 
  - *Ghost:* 1px border (#E5E5E5) with blue text on hover.
- **Inputs:** Minimalist bottom-border only or a very light 1px surrounding border. Labels should use the monospaced font.
- **Cards:** White background, 1px border (#E5E5E5). No shadow. On hover, the border color changes to the Primary Blue (#0066FF).
- **Status Indicators:** Small geometric shapes (squares or circles) using the accent color for active states.
- **Progress Bars:** Thin 2px lines. The "filled" portion uses the tech-blue accent.
- **Breadcrumbs & Meta:** Use JetBrains Mono at 12px for all metadata, including printer temperatures, filament types, and print times.