---
name: Solaris
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1b1c1c'
  on-surface-variant: '#424843'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0ef'
  outline: '#727972'
  outline-variant: '#c2c8c1'
  surface-tint: '#466550'
  primary: '#264431'
  on-primary: '#ffffff'
  primary-container: '#3d5c47'
  on-primary-container: '#b0d3b8'
  inverse-primary: '#accfb5'
  secondary: '#994618'
  on-secondary: '#ffffff'
  secondary-container: '#ff9560'
  on-secondary-container: '#752d00'
  tertiary: '#304329'
  on-tertiary: '#ffffff'
  tertiary-container: '#465b3f'
  on-tertiary-container: '#bad1ae'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c8ebd0'
  primary-fixed-dim: '#accfb5'
  on-primary-fixed: '#022110'
  on-primary-fixed-variant: '#2f4d39'
  secondary-fixed: '#ffdbcc'
  secondary-fixed-dim: '#ffb694'
  on-secondary-fixed: '#351000'
  on-secondary-fixed-variant: '#7a3000'
  tertiary-fixed: '#d2eac5'
  tertiary-fixed-dim: '#b6cdaa'
  on-tertiary-fixed: '#0e2009'
  on-tertiary-fixed-variant: '#384c31'
  background: '#fcf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e5e2e1'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 64px
    fontWeight: '600'
    lineHeight: 72px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-xl:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-xl-mobile:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.03em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  container-max: 1280px
  gutter: 24px
---

## Brand & Style

The design system embodies a "High-Tech Organic" philosophy, specifically tailored for the sophisticated urban environment of Monterrey. It blends the precision of premium consumer electronics with the warmth of natural materials. The visual language is deeply rooted in **Minimalism** and **Glassmorphism**, creating an interface that feels as light and breathable as a well-ventilated sustainable structure.

The target audience consists of discerning homeowners and eco-conscious tech enthusiasts. The UI evokes a sense of calm, reliability, and innovative luxury. Every interaction should feel intentional and frictionless, utilizing expansive whitespace to reduce cognitive load and emphasize the premium nature of the products.

Key stylistic pillars include:
- **Luminous Transparency:** Using backdrop blurs to simulate frosted glass, suggesting heat-reflective technology.
- **Architectural Precision:** A strict adherence to grid systems balanced by organic, soft-touch surfaces.
- **Extreme Contrast:** Pairing soft desert tones with deep, authoritative greens to represent the intersection of arid climate and resilient life.

## Colors

The palette is inspired by the rugged beauty of the Sierra Madre and the relentless sun of Northern Mexico.

- **Primary (Deep Green):** Represents the core of the brand—stability, sustainability, and technological density. Used for primary actions and brand-heavy elements.
- **Secondary (Solaris Orange):** An energetic accent reflecting solar power and warmth. Used sparingly for critical CTAs and success states.
- **Tertiary (Leaf Green):** A softer, supportive green used for secondary indicators and lifestyle elements.
- **Neutrals (Arena & Beige):** These form the "canvas" of the design system, replacing pure white to reduce eye strain and provide a sophisticated, tactile feel.
- **Elegant Black:** Used exclusively for high-contrast typography and iconography to ensure peak legibility.

## Typography

This design system utilizes **Inter** for its systematic, utilitarian precision that mirrors the brand's tech-forward identity. 

- **Weight Strategy:** Use `600` (Semi-Bold) for headlines to provide a confident anchor on the page. Body text stays at `400` to maintain a light, airy feel.
- **Tracking:** Headlines use slightly negative letter-spacing (`-0.01em` to `-0.02em`) to mimic the premium feel of high-end editorial layouts. Labels use slightly increased tracking for clarity at small sizes.
- **Hierarchy:** Maintain large vertical gaps between display type and body copy to emphasize the minimalist aesthetic.

## Layout & Spacing

The design system employs a **Fluid Grid** model based on an 8px spatial rhythm. 

- **Desktop (1440px+):** A 12-column grid with 24px gutters and 80px margins. Content is often centered with significant "breathing room" on the flanks.
- **Tablet (768px - 1024px):** An 8-column grid with 20px gutters and 40px margins.
- **Mobile (Under 768px):** A 4-column grid with 16px gutters and 16px margins.

Spacing should be generous. When in doubt, increase the `padding-bottom` or `margin-bottom` to the next scale level. Group related items with `md` (24px) spacing and separate distinct sections with `xl` (80px) spacing to maintain the minimalist narrative.

## Elevation & Depth

Visual hierarchy is achieved through a combination of **Glassmorphism** and **Ambient Shadows**. 

1. **Surface Layers:** The base layer is `Arena` (#EFE6DA). Secondary surfaces (cards, modals) use `White` (#FFFFFF) with a 70-80% opacity and a `20px` backdrop blur.
2. **Shadows:** Avoid harsh, dark shadows. Use long, diffused "Ambient Shadows" with a slight tint of `Deep Green` at very low opacity (e.g., `box-shadow: 0 20px 40px rgba(61, 92, 71, 0.08)`).
3. **Outlines:** Glass elements should have a 1px inner border in semi-transparent white to simulate the "edge" of a glass pane, enhancing the tactile feel.
4. **Interactive Depth:** On hover, elements should slightly lift (increase shadow spread) and increase opacity, suggesting they are moving closer to the user.

## Shapes

The shape language is consistently **Rounded**, reflecting the organic side of the brand. 

- **Standard Radius:** 0.5rem (8px) for buttons and small input fields.
- **Container Radius:** 1rem (16px) for cards, modals, and featured sections.
- **Extreme Radius:** 1.5rem (24px) for hero elements or large image containers.

Avoid sharp 90-degree angles as they feel too industrial and aggressive for the "nature-meets-tech" aesthetic. Circles are reserved for icon backgrounds and avatar containers.

## Components

- **Buttons:** 
  - **Primary:** `Deep Green` background, `White` text, 8px radius. High-gloss finish on hover.
  - **Secondary:** Glass-style (White 20% opacity) with a 1px border.
- **Cards:** White semi-transparent background with 20px backdrop-blur. 16px rounded corners. Use "Ambient Shadows" for depth.
- **Input Fields:** Soft `Beige` background with a 1px `Arena` border. On focus, the border transitions to `Deep Green` with a subtle outer glow.
- **Chips/Badges:** Small, pill-shaped elements using `Leaf Green` for positive status and `Arena` for neutral categories.
- **Glass Navigation:** A fixed top-navigation bar with a heavy backdrop-blur and a subtle bottom border in `White` (10% opacity).
- **Micro-animations:** All transitions (hover, toggle, modal entry) should use a `cubic-bezier(0.4, 0, 0.2, 1)` timing function for a sophisticated, "weighted" feel.