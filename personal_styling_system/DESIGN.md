---
name: Personal Styling System
colors:
  surface: '#fbf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fbf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae8e7'
  surface-container-highest: '#e4e2e1'
  on-surface: '#1b1c1c'
  on-surface-variant: '#43474e'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0f0'
  outline: '#74777f'
  outline-variant: '#c4c6cf'
  surface-tint: '#476083'
  primary: '#000613'
  on-primary: '#ffffff'
  primary-container: '#001f3f'
  on-primary-container: '#6f88ad'
  inverse-primary: '#afc8f0'
  secondary: '#5e604d'
  on-secondary: '#ffffff'
  secondary-container: '#e1e1c9'
  on-secondary-container: '#636451'
  tertiary: '#050606'
  on-tertiary: '#ffffff'
  tertiary-container: '#1d1f1f'
  on-tertiary-container: '#858687'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d4e3ff'
  primary-fixed-dim: '#afc8f0'
  on-primary-fixed: '#001c3a'
  on-primary-fixed-variant: '#2f486a'
  secondary-fixed: '#e4e4cc'
  secondary-fixed-dim: '#c8c8b0'
  on-secondary-fixed: '#1b1d0e'
  on-secondary-fixed-variant: '#474836'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c6'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#fbf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e1'
typography:
  headline-xl:
    fontFamily: Bodoni Moda
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Bodoni Moda
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Bodoni Moda
    fontSize: 28px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Bodoni Moda
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-md:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.2'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
  stack-xl: 64px
---

## Brand & Style

The design system is engineered for a premium personal styling service that bridges the gap between high-fashion editorial and advanced technology. The brand personality is **sophisticated, intentional, and expert**, aiming to evoke a sense of personalized luxury through a "Digital Atelier" experience.

The visual direction follows a **Modern Minimalist** aesthetic with a strong emphasis on **Editorial Grid Systems**. By utilizing ample white space and a high-contrast typographic hierarchy, the UI feels breathable and curated. This approach prioritizes the user's wardrobe and style recommendations, ensuring that the interface never competes with the visual content of the clothing. The emotional response should be one of calm confidence and effortless elegance.

## Colors

The color palette is rooted in timeless elegance, utilizing high-contrast neutrals to establish a professional and tech-forward atmosphere.

- **Deep Navy (#001F3F):** Used as the primary brand color for core actions, navigation headers, and primary buttons to convey authority and precision.
- **Beige (#F5F5DC):** The secondary color, serving as a warm, humanizing element. It is used for soft backgrounds, accent containers, and to provide a "canvas" feel that mimics luxury packaging.
- **Soft Gray (#E5E5E5):** A functional tertiary color for borders, subtle dividers, and disabled states.
- **Charcoal (#333333):** The primary neutral for body text and iconography, ensuring high legibility and a grounded feel without the harshness of pure black.

Surfaces should primarily remain white or off-white to maintain the minimalist intent, using the palette to guide the eye toward interactive elements.

## Typography

This design system employs a dual-font strategy to balance fashion heritage with technological clarity.

**Headlines (Bodoni Moda):** A high-contrast serif that evokes the aesthetic of luxury fashion magazines. Use this for large display text and section titles. The verticality of the letterforms provides a sense of stature.

**Body & UI (Hanken Grotesk):** A sharp, contemporary sans-serif used for all functional text. It provides the "tech" vibe—clean, precise, and highly legible at smaller scales.

**Usage Notes:**
- Maintain wide line-heights for body text to improve readability and "breathability."
- Use uppercase styling for `label-md` to create clear architectural markers within the interface.
- Avoid using the serif font for small UI labels or interactive elements (buttons/inputs) to maintain functional clarity.

## Layout & Spacing

The layout is built on a **12-column fixed grid** for desktop, optimized for a max-width of 1440px to ensure a controlled editorial experience. On mobile, it transitions to a **4-column fluid grid**.

**Layout Philosophy:**
- **Asymmetric Balance:** Use whitespace to create focal points. Not every grid column needs to be filled; intentional gaps are encouraged to replicate a boutique look.
- **Consistency:** All spacing is based on a 4px baseline unit.
- **Safe Zones:** Generous margins (64px on desktop) keep the content centered and prevent the UI from feeling cramped.
- **Vertical Rhythm:** Use the `stack` variables to manage vertical distance between elements, ensuring that headlines have significantly more "air" than body paragraphs.

## Elevation & Depth

This design system moves away from heavy shadows in favor of **Tonal Layers and Thin Lines**. Depth is communicated through structural layering rather than physical extrusion.

- **Base Layer:** The standard background (#FFFFFF or #F5F5DC).
- **Surface Layer:** Used for cards and modals, distinguished by a subtle 1px border in Soft Gray (#E5E5E5) or a very light tint shift.
- **Elevation Shadows:** When necessary for high-priority modals, use a "Whisper Shadow"—a highly diffused, low-opacity (4-8%) Deep Navy tint with a 20px blur and 0px spread.
- **Glassmorphism:** Use sparingly for navigation bars or floating action overlays. A 12px backdrop blur with 80% opacity allows the vibrant clothing imagery to bleed through subtly, maintaining a tech-forward feel.

## Shapes

The shape language is characterized by **clean lines and soft precision**. We avoid organic or overly bubbly shapes to maintain a professional, sophisticated tone.

- **Standard Elements:** Buttons and input fields use a "Soft" (0.25rem) radius. This provides just enough friendliness while maintaining a structured, architectural feel.
- **Large Containers:** Cards and image containers use "rounded-lg" (0.5rem) to differentiate them from the smaller interactive elements.
- **Visual Dividers:** Use 1px solid lines in Soft Gray (#E5E5E5) to separate content sections, reinforcing the grid-based editorial feel.

## Components

### Buttons
- **Primary:** Deep Navy background, white Hanken Grotesk text, 0.25rem radius. High-contrast, bold, and authoritative.
- **Secondary:** Transparent background with a 1px Deep Navy border.
- **Tertiary/Ghost:** Text-only with an underline effect on hover, used for less critical actions to keep the UI clean.

### Input Fields
- Structured with a 1px Soft Gray border that transitions to Deep Navy on focus. 
- Labels are always positioned above the field in `label-sm` (uppercase) for clarity.

### Cards
- Minimalist containers with no shadow. 
- Use a 1px Soft Gray border. 
- Images within cards should have a subtle 0.25rem radius to match the component language.

### Chips/Tags
- Used for style categories (e.g., "Minimalist", "Business Casual"). 
- Beige background with Charcoal text. 
- Fully rounded (pill-shaped) to distinguish them from actionable buttons.

### Styling Timeline
- A bespoke component representing the user's "Style Journey." 
- Uses thin vertical lines and small Deep Navy dots to mark milestones, reinforcing the tech-forward, data-driven nature of the service.