---
name: Majestic Gold & Charcoal
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1b1b1b'
  surface-container: '#1f1f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353535'
  on-surface: '#e2e2e2'
  on-surface-variant: '#d1c5b4'
  inverse-surface: '#e2e2e2'
  inverse-on-surface: '#303030'
  outline: '#9a8f80'
  outline-variant: '#4e4639'
  surface-tint: '#e9c176'
  primary: '#e9c176'
  on-primary: '#412d00'
  primary-container: '#c5a059'
  on-primary-container: '#4e3700'
  inverse-primary: '#775a19'
  secondary: '#c8c6c5'
  on-secondary: '#313030'
  secondary-container: '#474746'
  on-secondary-container: '#b7b5b4'
  tertiary: '#e7c188'
  on-tertiary: '#432c01'
  tertiary-container: '#c3a06a'
  on-tertiary-container: '#4f370a'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdea5'
  primary-fixed-dim: '#e9c176'
  on-primary-fixed: '#261900'
  on-primary-fixed-variant: '#5d4201'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474746'
  tertiary-fixed: '#ffdeae'
  tertiary-fixed-dim: '#e7c188'
  on-tertiary-fixed: '#281800'
  on-tertiary-fixed-variant: '#5c4215'
  background: '#131313'
  on-background: '#e2e2e2'
  surface-variant: '#353535'
  antique-gold: '#C5A059'
  deep-obsidian: '#0A0A0A'
  silk-white: '#F4F4F4'
  muted-gold: '#8E6F3E'
typography:
  display-lg:
    fontFamily: Libre Caslon Text
    fontSize: 64px
    fontWeight: '400'
    lineHeight: 72px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Libre Caslon Text
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 56px
  headline-lg-mobile:
    fontFamily: Libre Caslon Text
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
  headline-md:
    fontFamily: Libre Caslon Text
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
  title-lg:
    fontFamily: Manrope
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: 0.05em
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 20px
    letterSpacing: 0.1em
spacing:
  unit: 8px
  gutter-desktop: 32px
  margin-desktop: 80px
  margin-mobile: 20px
  container-max: 1440px
---

## Brand & Style

The design system for Dubai Fistan Sarayı embodies **Luxury Minimalism** infused with **High-Contrast Boldness**. It is tailored for a high-end boutique clientele who value craftsmanship, heritage, and exclusivity. The visual narrative focuses on the tactile richness of premium fabrics, using deep, void-like blacks to make the metallic gold accents feel luminous and substantial.

The emotional response should be one of "Affluent Serenity"—a digital experience that feels as curated as a private atelier appointment. The UI avoids unnecessary clutter, favoring expansive negative space and precise alignment to emphasize the quality of the content and the products. High-quality photography of fabric textures, embroidery, and boutique interiors serves as the primary visual driver, framed by sharp, sophisticated architectural lines.

## Colors

The palette is rooted in a **Dark Mode** first philosophy to evoke a sense of nocturnal elegance and mystery. 

- **Primary (Antique Gold):** This is the signature brand color, used for primary calls to action, headings, and decorative accents. It should feel metallic rather than flat yellow.
- **Secondary (Charcoal/Obsidian):** Used for surface layers and containers to provide subtle depth against the pure black background.
- **Neutral (Pure Black):** The foundation of the system, used to create a "limitless" backdrop that allows photography to pop.
- **Accents (Silk White):** Used sparingly for body text and utilitarian elements to ensure high legibility against dark backgrounds without competing with the gold.

## Typography

This design system utilizes a **Classical-Modern Hybrid** approach:

- **Headlines (Libre Caslon Text):** A sophisticated serif that provides historical weight and an editorial feel. Used for large displays, section headers, and product names.
- **Body & Labels (Manrope):** A clean, highly legible sans-serif that balances the traditional serif. Its geometric nature provides the "modern" contrast requested.
- **Styling Note:** Large headlines should often use a gold-to-light-gold subtle gradient or remain solid `antique-gold`. All uppercase labels should have generous letter-spacing to enhance the luxury "boutique" aesthetic.

## Layout & Spacing

The layout follows a **Fixed-Width Grid** on desktop (1440px max) to maintain a controlled, cinematic composition.

- **Desktop (12 Columns):** Uses a 32px gutter and wide 80px margins to create a sense of exclusivity and breathing room. Elements should often span 6 or 8 columns to avoid overcrowding.
- **Tablet (8 Columns):** Transitions to a 24px gutter and 40px margins.
- **Mobile (4 Columns):** Uses a 16px gutter and 20px margins. Content reflows vertically, focusing on high-impact full-bleed imagery for product showcases.

Spacing is based on an **8px base unit**, with a preference for "Airy" layouts—using large padding (64px+) between major sections to prevent the dark theme from feeling heavy or cramped.

## Elevation & Depth

Visual hierarchy is established through **Tonal Layers and Low-Contrast Outlines** rather than aggressive shadows.

1. **Base Layer:** Pure Black (`#000000`).
2. **Surface Layer:** Deep Obsidian (`#0A0A0A`).
3. **Interactive Layer:** Subtle Charcoal (`#1A1A1A`) with thin 1px Gold outlines.
4. **Glassmorphism:** Used sparingly for navigation bars and overlaying content on fabric imagery. A 20px backdrop blur with a 10% opacity white or gold tint creates a "frosted glass" effect that feels like high-end boutique display cases.
5. **Shadows:** When used (e.g., for modal windows), shadows are extremely diffused, large-radius, and tinted with the primary gold color at 5% opacity to create a "glow" effect rather than a dark shadow.

## Shapes

The design system utilizes **Sharp (0px)** corners. This reinforces an architectural, high-fashion, and premium feel. Straight edges convey precision, discipline, and the crisp cut of high-quality fabric. This "sharpness" applies to buttons, input fields, and product cards, creating a consistent, formal visual language.

## Components

- **Buttons:** Primary buttons are solid `antique-gold` with black uppercase text. Secondary buttons are transparent with a 1px gold border ("ghost buttons"). All hover states should involve a subtle scale-up (1.02x) or a gold-to-white shimmer effect.
- **Cards:** Product cards should be borderless on the base layer, using large, high-resolution photography. Titles appear in Serif below the image. On hover, a 1px gold border fades in.
- **Inputs:** Underline-only inputs (border-bottom) are preferred over boxed inputs to maintain a minimalist look. Labels should be small, uppercase, and placed above the field.
- **Navigation:** The header is persistent but ultra-thin. Links are in `manrope` uppercase with wide letter spacing. The active state is indicated by a 2px gold underline or a change to the gold primary color.
- **Specialty Component (Fabric Detail View):** A custom component that allows users to toggle a "macro" zoom on fabric textures, emphasizing the "premium kumaş" (premium fabric) aspect of the brand.
- **Icons:** Use thin-stroke, linear icons in gold. Avoid filled or chunky iconography.