---
name: Scientific Radiance
colors:
  surface: '#fef8f1'
  surface-dim: '#dfd9d2'
  surface-bright: '#fef8f1'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f9f3ec'
  surface-container: '#f3ede6'
  surface-container-high: '#ede7e0'
  surface-container-highest: '#e7e2db'
  on-surface: '#1d1b17'
  on-surface-variant: '#594041'
  inverse-surface: '#32302c'
  inverse-on-surface: '#f6f0e9'
  outline: '#8d7070'
  outline-variant: '#e1bebe'
  surface-tint: '#b42439'
  primary: '#73001a'
  on-primary: '#ffffff'
  primary-container: '#9b0d2a'
  on-primary-container: '#ffa6a9'
  inverse-primary: '#ffb3b4'
  secondary: '#795900'
  on-secondary: '#ffffff'
  secondary-container: '#fcc74f'
  on-secondary-container: '#715300'
  tertiary: '#735c04'
  on-tertiary: '#ffffff'
  tertiary-container: '#c6a850'
  on-tertiary-container: '#4f3d00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdada'
  primary-fixed-dim: '#ffb3b4'
  on-primary-fixed: '#40000b'
  on-primary-fixed-variant: '#920124'
  secondary-fixed: '#ffdfa0'
  secondary-fixed-dim: '#f3bf48'
  on-secondary-fixed: '#261a00'
  on-secondary-fixed-variant: '#5c4300'
  tertiary-fixed: '#ffe08a'
  tertiary-fixed-dim: '#e3c468'
  on-tertiary-fixed: '#241a00'
  on-tertiary-fixed-variant: '#574400'
  background: '#fef8f1'
  on-background: '#1d1b17'
  surface-variant: '#e7e2db'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-xl:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-xl-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '500'
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
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 32px
  margin-desktop: 80px
  margin-mobile: 20px
  section-padding: 120px
---

## Brand & Style

The brand personality is a synthesis of clinical precision and heritage-inspired wellness. This design system bridges the gap between a high-end medical clinic and a luxury Ayurvedic spa, targeting a discerning clientele that values both advanced technology and traditional care.

The design style is **Editorial Minimalism with Glassmorphism**. It utilizes generous whitespace, high-fashion typography, and translucent layers to evoke a sense of airiness, purity, and "glow." The aesthetic is inspired by premium editorial layouts (Awwwards-style) and Apple’s clean interface, using matte gold accents and soft blurs to create a tactile, premium depth. 

Key attributes:
- **Sophisticated:** Refined visual hierarchy that doesn't shout.
- **Scientific:** Clean lines and functional layouts that build medical trust.
- **Luminous:** Use of gradients and blurs to mimic the "glow" of healthy skin.

## Colors

The palette is rooted in the "Tridha" concept—balancing the intensity of medical science with the warmth of gold.

- **Primary (Deep Ruby Red & Burgundy):** Used for primary calls to action, brand-specific accents, and highlighting key medical expertise. It evokes luxury and vitality.
- **Secondary (Royal & Champagne Gold):** Used for decorative strokes, iconography, and interactive hover states. These are often applied as linear gradients to simulate a matte metallic finish.
- **Base (Warm Ivory & Soft Cream):** These replace pure white to provide a softer, more organic feel that is less clinical and more inviting.
- **Text (Charcoal & Soft Grey):** High-contrast charcoal for legibility in body copy, with soft grey used for metadata and secondary labels.

## Typography

The typography strategy uses a classic "High-Low" pairing. 

**Playfair Display** (Serif) is the voice of the brand. It is used for all headlines and display elements to convey elegance, tradition, and luxury. Tracking should be slightly tightened for large display titles to increase the "editorial" feel.

**Inter** (Sans-Serif) is the functional workhorse. It provides a clean, neutral contrast to the serif headings, ensuring that medical information and treatment descriptions are highly legible and modern. 

- Use **display-lg** for hero sections with generous letter-spacing.
- Use **label-md** in all-caps for categories or small sub-headers to add a "designer brand" aesthetic.

## Layout & Spacing

This design system follows a **Fixed Grid** philosophy to maintain tight control over editorial compositions. 

- **Desktop:** A 12-column grid with a max-width of 1280px. Large margins (80px) are used to push content inward, creating a "boutique" feel.
- **Section Spacing:** Generous vertical padding (120px+) is used between sections to allow the design to "breathe," emphasizing luxury through the luxury of space.
- **Parallax Layers:** Background imagery and decorative gold strokes should move at varying speeds during scroll to create a sense of three-dimensional depth.

## Elevation & Depth

Depth is achieved through **Glassmorphism** and **Light Emission** rather than heavy shadows.

- **Surface Layers:** Containers use a semi-transparent background (Warm Ivory at 70% opacity) with a `backdrop-filter: blur(20px)`. 
- **Gold Glow:** Instead of standard drop shadows, high-priority elements (like active cards or buttons) use a soft "Royal Gold" outer glow (`box-shadow: 0 10px 40px rgba(212, 163, 45, 0.15)`).
- **Subtle Borders:** Use 1px borders with a light gold gradient to define edges without adding visual weight.

## Shapes

The shape language is "Softly Architectural." 

- **Corners:** A base roundedness of 0.5rem (8px) is applied to cards and inputs to keep them feeling modern but approachable. 
- **Decorative Curves:** Large, sweeping organic curves (inspired by Ayurvedic patterns) are used as background masks or subtle gold strokes to break the rigidity of the grid.
- **Buttons:** Use fully pill-shaped (rounded-xl) or sharp-cornered depending on the context: pill-shaped for "Spa/Wellness" and softer-rectangles for "Medical/Clinic" sections.

## Components

### Buttons
- **Primary:** Deep Ruby Red background with white text. High-contrast, no border.
- **Secondary:** Transparent background with a 1px Royal Gold border.
- **Tertiary:** Text-only with a thin gold underline that expands on hover.

### Glassmorphism Cards
- Used for treatment categories. Feature a soft blur, a 1px Champagne Gold border, and a subtle shimmer effect that follows the cursor movement.

### Comparison Sliders
- Used for 'Before & After' results. A vertical handle in Matte Gold separates two high-resolution images. The handle features a small "Tridha" icon.

### Input Fields
- Underlined style (rather than boxed) to maintain a minimalist editorial look. Warm Ivory background with a 1px Charcoal bottom border.

### Navigation Bar
- A fixed glassmorphism bar with a "Frosted Ivory" effect. The logo is centered for desktop layouts to emphasize symmetry and balance.

### Shimmer Effects
- Apply a subtle CSS animation to gold accents to create a "metallic catch" of light as the user scrolls.