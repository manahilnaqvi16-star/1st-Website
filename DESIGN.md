---
name: Epicurean Nocturne
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#d8c3ad'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#a08e7a'
  outline-variant: '#534434'
  surface-tint: '#ffb95f'
  primary: '#ffc174'
  on-primary: '#472a00'
  primary-container: '#f59e0b'
  on-primary-container: '#613b00'
  inverse-primary: '#855300'
  secondary: '#e9c349'
  on-secondary: '#3c2f00'
  secondary-container: '#af8d11'
  on-secondary-container: '#342800'
  tertiary: '#cecccb'
  on-tertiary: '#313030'
  tertiary-container: '#b2b0b0'
  on-tertiary-container: '#444343'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffddb8'
  primary-fixed-dim: '#ffb95f'
  on-primary-fixed: '#2a1700'
  on-primary-fixed-variant: '#653e00'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#e5e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1c1b1b'
  on-tertiary-fixed-variant: '#474746'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.1em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 24px
  margin-mobile: 20px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
  section-padding: 100px
---

## Brand & Style
The design system embodies a premium, "dark-luxe" dining experience. It targets a sophisticated audience seeking culinary excellence in an atmosphere that feels both intimate and high-end. 

The aesthetic is a fusion of **Modern Minimalism** and **Glassmorphism**. By using deep, layered blacks and charcoals as a canvas, the UI allows the photography of food to remain the focal point. Atmosphere is created through refined gradients that mimic low-light restaurant environments, while frosted glass surfaces add a sense of modern depth. The emotional response is one of exclusivity, warmth, and professional reliability.

## Colors
The palette is rooted in a "Noir" foundation. The primary background is a rich, near-black neutral (`#0A0A0A`), while elevated surfaces use a deep charcoal (`#1A1A1A`). 

**Warm Orange (#F59E0B)** serves as the primary action color, used for high-priority CTAs and interactive highlights to stimulate appetite and energy. **Gold (#D4AF37)** is reserved for decorative elements, iconography, and luxury accents, often applied as a subtle gradient to denote premium status. Backgrounds should occasionally utilize a very soft radial gradient of the primary color at 5% opacity to prevent the dark mode from feeling "flat" or "cold."

## Typography
This design system utilizes a high-contrast typographic pairing. **Playfair Display** provides an authoritative, editorial feel for headlines, reflecting the craftsmanship of the kitchen. 

**Inter** is used for all functional and body text to ensure maximum legibility against dark backgrounds. Use "Body-LG" for menu descriptions and intro paragraphs. "Label-caps" should be used for category headers (e.g., "APPETIZERS") and small metadata. All serif headings should maintain tight tracking to feel cohesive, while sans-serif labels should have increased letter-spacing for a modern, architectural look.

## Layout & Spacing
The layout follows a **Fixed Grid** approach for desktop, centering content within a 1280px container to maintain an intimate, controlled reading experience. 

On mobile, the layout transitions to a single-column fluid flow with generous 20px side margins. Horizontal spacing between menu items in a grid should remain consistent at 24px. Section breathing room is critical; use 100px of vertical padding between major content blocks to evoke a sense of "fine dining" space and luxury.

## Elevation & Depth
Depth is achieved through **Glassmorphism** and **Tonal Layering**. Instead of traditional drop shadows, which can look muddy on black backgrounds, we use:

1.  **Backdrop Blurs:** High-level containers (like navigation bars or modal overlays) use a 20px blur with a 10% white tint.
2.  **Inner Glows:** To make cards pop, use a subtle 1px top-border or "inner stroke" in a semi-transparent white (5-10% opacity).
3.  **Soft Ambient Glows:** For primary cards, a very faint outer glow using the primary orange color (`#F59E0B`) at 15% opacity and 30px blur creates a "lit from within" effect.

## Shapes
The design system uses a **Rounded** (Level 2) logic. Standard components like buttons and input fields feature an 8px (0.5rem) corner radius. 

Larger containers, such as menu cards and gallery images, should use `rounded-xl` (24px / 1.5rem) to soften the overall aesthetic and feel more welcoming. This balance of structured layouts with rounded corners prevents the professional dark theme from feeling too "tech" or clinical.

## Components

### Buttons
Primary buttons use the `accent_gradient` with white or dark-charcoal text depending on legibility. Secondary buttons are "Ghost" style with a 1px Gold (`#D4AF37`) border and no fill.

### Menu Cards
Cards use the `#1A1A1A` charcoal background with a `rounded-xl` radius. Images should be top-aligned with no padding, while text content should have 24px of internal padding. Price tags should be set in Gold.

### Input Fields
Forms should feature a dark-filled background (darker than the card surface) with a 1px border that glows Primary Orange (`#F59E0B`) upon focus.

### Gallery
A masonry or strict 3-column grid. Images should have a subtle scale-up transform on hover (1.05x) with a smooth 300ms transition to create an interactive, tactile feel.

### Chips/Tags
Used for dietary requirements (e.g., "Vegan", "Gluten-Free"). These should be small, pill-shaped, with a subtle 10% opacity fill of the Primary color and matching text color.