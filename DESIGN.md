---
name: Gaúcha Heritage Modern
colors:
  surface: '#f8f9ff'
  surface-dim: '#d0dbed'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e6eeff'
  surface-container-high: '#dee9fc'
  surface-container-highest: '#d9e3f6'
  on-surface: '#121c2a'
  on-surface-variant: '#5b403d'
  inverse-surface: '#27313f'
  inverse-on-surface: '#eaf1ff'
  outline: '#8f6f6c'
  outline-variant: '#e4beb9'
  surface-tint: '#b91c1c'
  primary: '#93000b'
  on-primary: '#ffffff'
  primary-container: '#b91c1c'
  on-primary-container: '#ffcdc7'
  inverse-primary: '#ffb4ab'
  secondary: '#486458'
  on-secondary: '#ffffff'
  secondary-container: '#c7e7d7'
  on-secondary-container: '#4c695c'
  tertiary: '#4b463c'
  on-tertiary: '#ffffff'
  tertiary-container: '#645d52'
  on-tertiary-container: '#e0d7c9'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad6'
  primary-fixed-dim: '#ffb4ab'
  on-primary-fixed: '#410002'
  on-primary-fixed-variant: '#93000b'
  secondary-fixed: '#caeada'
  secondary-fixed-dim: '#aecebe'
  on-secondary-fixed: '#032017'
  on-secondary-fixed-variant: '#304c41'
  tertiary-fixed: '#ebe1d3'
  tertiary-fixed-dim: '#cec5b8'
  on-tertiary-fixed: '#1f1b13'
  on-tertiary-fixed-variant: '#4c463c'
  background: '#f8f9ff'
  on-background: '#121c2a'
  surface-variant: '#d9e3f6'
typography:
  display-lg:
    fontFamily: Manrope
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Manrope
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-md:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
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
  container-max: 1200px
  gutter: 20px
  margin-mobile: 16px
---

## Brand & Style

The brand personality for the design system is rooted in the rich culinary tradition of the Brazilian churrascaria, reinterpreted through a contemporary, high-end lens. It balances the rustic warmth of open-fire cooking with the clinical precision of a modern professional service. The target audience seeks an authentic but elevated dining experience, expecting a digital interface that feels as inviting as a warm hearth but as efficient as a five-star kitchen.

The visual style is **Corporate / Modern** with a **Tactile** edge. It utilizes a sophisticated "light and airy" foundation to ensure legibility and a sense of cleanliness, punctuated by deep, traditional colors that evoke heritage. The emotional response is one of trust, appetite, and comfort. We avoid the cluttered "budget" look of typical fast-food apps, opting instead for generous whitespace, refined typography, and subtle depth to convey a premium positioning.

## Colors

The palette is anchored by a high-energy **Primary Red (#B91C1C)**, used strategically for calls to action and to stimulate appetite. This is balanced by a **Dark Green (#1E3A2F)**, which provides a grounding, natural contrast and references the traditional "Gaúcho" flag colors seen in the logo.

The UI background uses a **Light Beige (#F8F4EF)** instead of a sterile white to maintain a "warm" hospitality feel. **Warm Cream (#F0E6D8)** is reserved for secondary containers, card backgrounds, and section dividers to create soft tonal layering. All primary text is rendered in **Charcoal (#1F2937)** to ensure maximum readability and a professional, modern finish.

## Typography

This design system uses a dual-sans-serif pairing to achieve a "modern-premium" look. **Manrope** is used for headlines; its geometric but slightly condensed nature feels structural and authoritative. **Plus Jakarta Sans** is used for body text and labels; its wider apertures and friendly terminals ensure high legibility and a welcoming tone during long-form reading (like menu descriptions).

For mobile devices, headlines scale down to prevent awkward word-breaks, while body text maintains a minimum 16px size for accessibility in high-glare environments (e.g., a customer checking the menu while walking).

## Layout & Spacing

The layout follows a **fluid grid** philosophy with a focus on a mobile-first hierarchy. On mobile, we use a single-column stack with 16px side margins. On tablet and desktop, the system expands into a 12-column grid with 24px gutters.

Spacing is generous to evoke a "fine dining" feel. High-value content—like signature meat cuts or pizzas—should be surrounded by significant whitespace (the `lg` or `xl` tokens) to draw the eye. We use an 8px base grid to ensure all vertical rhythm is mathematically consistent.

## Elevation & Depth

We utilize **Tonal Layers** combined with **Ambient Shadows** to create a sense of organized hierarchy. Surfaces are never pure white; they sit on the light beige background. 

1.  **Level 0 (Base):** Light Beige (#F8F4EF) - The main canvas.
2.  **Level 1 (Cards/Containers):** Warm Cream (#F0E6D8) or White (#FFFFFF) with a very soft, diffused shadow (Blur: 15px, Y: 4px, Opacity: 4% Charcoal).
3.  **Level 2 (Interaction/Popovers):** White (#FFFFFF) with a more defined shadow (Blur: 25px, Y: 8px, Opacity: 8% Charcoal).

Avoid harsh black shadows; instead, tint shadows with a hint of the primary red or dark green to keep the interface feeling "warm" and integrated.

## Shapes

The shape language is defined by **Rounded (Level 2)** corners. While the logo is circular, the UI elements use soft, large-radius corners to feel approachable and modern without being overly "bubbly."

-   **Standard Elements:** (Buttons, Inputs) use `rounded-lg` (16px).
-   **Containers:** (Product Cards, Section Blocks) use `rounded-xl` (24px).
-   **Featured Elements:** Promotional banners or the logo container may use "Full" roundedness (pill-shaped) to echo the circular logo identity.

## Components

### Buttons
-   **Primary:** Solid Primary Red (#B91C1C) with White text. Bold, 16px rounded corners.
-   **Secondary:** Solid Dark Green (#1E3A2F) with White text.
-   **Tertiary:** Transparent background with Primary Red text and a 1px border of the same color.

### Cards (Menu Items)
Cards should feature high-quality imagery at the top. The bottom section uses the Warm Cream background with Charcoal text. Use `rounded-xl` for the card itself and `rounded-lg` for any internal "Add to Cart" buttons.

### Inputs & Selects
Form fields use a White background with a 1px border in Warm Cream. On focus, the border transitions to Dark Green. Labels sit above the field in `label-lg` typography.

### Chips (Categories)
Used for menu filtering (e.g., "Beef", "Pizzas", "Drinks"). These are pill-shaped. Inactive chips use a Warm Cream background; active chips use Dark Green with White text.

### Lists
Order history or menu lists use subtle 1px dividers in the Warm Cream color. List items should have a minimum height of 56px to remain touch-friendly on mobile devices.