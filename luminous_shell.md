---
name: Luminous Shell
colors:
  surface: '#13131b'
  surface-dim: '#13131b'
  surface-bright: '#393841'
  surface-container-lowest: '#0d0d15'
  surface-container-low: '#1b1b23'
  surface-container: '#1f1f27'
  surface-container-high: '#292932'
  surface-container-highest: '#34343d'
  on-surface: '#e4e1ed'
  on-surface-variant: '#c7c4d7'
  inverse-surface: '#e4e1ed'
  inverse-on-surface: '#303038'
  outline: '#908fa0'
  outline-variant: '#464554'
  surface-tint: '#c0c1ff'
  primary: '#c0c1ff'
  on-primary: '#1000a9'
  primary-container: '#8083ff'
  on-primary-container: '#0d0096'
  inverse-primary: '#494bd6'
  secondary: '#ddb7ff'
  on-secondary: '#490080'
  secondary-container: '#6f00be'
  on-secondary-container: '#d6a9ff'
  tertiary: '#ffb783'
  on-tertiary: '#4f2500'
  tertiary-container: '#d97721'
  on-tertiary-container: '#452000'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e1e0ff'
  primary-fixed-dim: '#c0c1ff'
  on-primary-fixed: '#07006c'
  on-primary-fixed-variant: '#2f2ebe'
  secondary-fixed: '#f0dbff'
  secondary-fixed-dim: '#ddb7ff'
  on-secondary-fixed: '#2c0051'
  on-secondary-fixed-variant: '#6900b3'
  tertiary-fixed: '#ffdcc5'
  tertiary-fixed-dim: '#ffb783'
  on-tertiary-fixed: '#301400'
  on-tertiary-fixed-variant: '#703700'
  background: '#13131b'
  on-background: '#e4e1ed'
  surface-variant: '#34343d'
typography:
  display-lg:
    fontFamily: Hanken Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-sm:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
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
  container-max-width: 1440px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 40px
---

## Brand & Style

The design system is defined by a "Digital Luminescence" aesthetic—fusing high-tech precision with an approachable, airy atmosphere. It is designed for a tech-forward client portal that prioritizes clarity and sophisticated data visualization.

The style leverages **Minimalism** as its structural foundation, utilizing expansive whitespace (or "darkspace") to ensure the interface never feels cluttered. This is layered with **Glassmorphism** to create a sense of depth and hierarchy without relying on heavy shadows. Drawing inspiration from low-poly geometry, the visual language incorporates crystalline patterns and tessellated accents that evoke a sense of structure, resilience, and digital craftsmanship. The emotional response is one of calm confidence, professional reliability, and cutting-edge innovation.

## Colors

The palette is anchored in a deep, obsidian-toned background (#0a0a0f) that provides a high-contrast stage for the vibrant primary accents. 

- **Primary & Secondary:** A core gradient ranging from Indigo (#6366f1) to Magenta-Purple (#a855f7). This gradient is used sparingly for high-impact moments like primary actions, progress indicators, and active states.
- **Neutrals:** The system uses a scale of cool grays. Surfaces sit at #16161e to create subtle separation from the background.
- **Accents:** Derived from the low-poly reference, subtle hints of teal and lime-green can be used in data visualization to provide functional contrast against the purple primary tones.

## Typography

This design system employs **Hanken Grotesk** for its primary personality—a sharp, contemporary sans-serif that maintains high legibility while feeling distinctly modern. For technical data and UI labels, **Geist** is used to provide a "developer-friendly" precision.

- **Scale:** Headlines utilize tight letter spacing and bold weights to command attention.
- **Hierarchy:** Use secondary text colors (#94a3b8) for body copy to ensure the primary headlines remain the focal point.
- **Labels:** Small labels and metadata should use Geist with slightly increased letter spacing and uppercase styling to evoke a technical, "shell-like" terminal aesthetic.

## Layout & Spacing

The layout philosophy follows a **Fixed Grid** model for desktop to maintain a premium, editorial feel, transitioning to a fluid model for smaller breakpoints.

- **Grid:** A 12-column system with a 24px gutter. On desktop, the content is centered with generous margins to prevent eye-strain across ultra-wide monitors.
- **Rhythm:** All spacing is derived from an 8px base unit. Component internal padding should favor "spaciousness"—use 16px or 24px as the default padding for containers to reinforce the minimal aesthetic.
- **Mobile:** Elements reflow to a single column with 16px side margins. Large display type scales down to `headline-lg-mobile` to ensure fit.

## Elevation & Depth

Hierarchy is achieved through **Tonal Layers** and **Glassmorphism** rather than traditional drop shadows.

- **Z-Axis:** The background is the lowest layer (#0a0a0f). Cards and primary containers sit on the second layer (#16161e).
- **Glass Effects:** Floating panels (like modals or dropdowns) utilize a background blur (12px to 20px) and a semi-transparent surface (#16161e at 80% opacity).
- **Outlines:** Instead of shadows, use "Ghost Borders"—1px solid strokes at 10% white opacity—to define element boundaries. This maintains a crisp, technical look.
- **Glow:** Primary action elements (buttons) may feature a soft, tinted outer glow using the primary purple color to indicate interactivity and "power."

## Shapes

The shape language is "Soft-Geometric." While the low-poly inspiration suggests sharp triangles, the UI elements themselves use a subtle 0.25rem (4px) corner radius to ensure the interface feels approachable and professional.

- **Component Radius:** Buttons and input fields use a consistent 4px radius. 
- **Large Surfaces:** Large cards or sections can use `rounded-lg` (8px) to soften the layout.
- **Visual Accents:** Use non-rounded, sharp-edged triangles and poly-patterns as background watermarks or decorative masks to contrast with the functional, rounded UI elements.

## Components

- **Buttons:** Primary buttons use the full purple-to-magenta gradient with white text. Secondary buttons use the "Ghost" style: a 1px border with no fill, or a subtle semi-transparent fill.
- **Inputs:** Fields are dark (#0a0a0f) with a 1px border. On focus, the border transitions to the primary purple with a very subtle inner glow.
- **Cards:** Cards should be flat with a 1px "Ghost Border." Use low-poly geometric patterns as subtle background masks (5% opacity) within cards to add texture.
- **Chips/Tags:** Use Geist for tag typography. Chips should have a light tinted background (10% opacity of the primary color) to make them pop against dark surfaces.
- **Data Viz:** Charts should utilize the crystalline aesthetic. Use area charts with gradient fills and sharp, angular line points rather than smooth curves.
- **Geometric Masks:** Instead of photos, use abstract containers filled with tessellated triangular patterns that mirror the low-poly turtle reference.