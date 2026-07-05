---
name: Royal Commerce
colors:
  surface: '#f9f9fc'
  surface-dim: '#dadadc'
  surface-bright: '#f9f9fc'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f6'
  surface-container: '#eeeef0'
  surface-container-high: '#e8e8ea'
  surface-container-highest: '#e2e2e5'
  on-surface: '#1a1c1e'
  on-surface-variant: '#444650'
  inverse-surface: '#2f3133'
  inverse-on-surface: '#f0f0f3'
  outline: '#757682'
  outline-variant: '#c5c6d2'
  surface-tint: '#435b9f'
  primary: '#00113a'
  on-primary: '#ffffff'
  primary-container: '#002366'
  on-primary-container: '#758dd5'
  inverse-primary: '#b3c5ff'
  secondary: '#904d00'
  on-secondary: '#ffffff'
  secondary-container: '#fd8b00'
  on-secondary-container: '#603100'
  tertiary: '#121516'
  on-tertiary: '#ffffff'
  tertiary-container: '#26292a'
  on-tertiary-container: '#8e9091'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b3c5ff'
  on-primary-fixed: '#00174a'
  on-primary-fixed-variant: '#2a4386'
  secondary-fixed: '#ffdcc3'
  secondary-fixed-dim: '#ffb77d'
  on-secondary-fixed: '#2f1500'
  on-secondary-fixed-variant: '#6e3900'
  tertiary-fixed: '#e1e3e4'
  tertiary-fixed-dim: '#c5c7c8'
  on-tertiary-fixed: '#191c1d'
  on-tertiary-fixed-variant: '#454748'
  background: '#f9f9fc'
  on-background: '#1a1c1e'
  surface-variant: '#e2e2e5'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
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
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
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
  base: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 32px
---

## Brand & Style

The brand identity for this design system is built upon the pillars of reliability, premium service, and modern efficiency. Targeting a discerning e-commerce audience, the UI must evoke a sense of established trust (Royal Blue) punctuated by moments of energetic action and discovery (Vibrant Orange).

The design style is **Corporate / Modern** with a focus on high-clarity information architecture. It utilizes a sophisticated balance of ample whitespace, precise alignment, and subtle depth to guide users through the shopping journey without friction. The aesthetic is clean and "un-fussy," ensuring that product photography remains the hero while the interface provides a sturdy, professional framework for transactions.

## Colors

The palette is anchored by **Royal Blue**, which serves as the primary brand identifier, used for navigation, primary headers, and essential structural elements to establish authority. **Vibrant Orange** is reserved strictly for high-priority calls to action (CTAs), such as "Add to Cart" or "Buy Now," ensuring they are immediately discoverable.

Backgrounds utilize a tiered system of whites and extremely light grays to create subtle contrast between different content sections. Semantic colors for success, error, and warning should follow industry standards but be adjusted to match the saturation levels of the primary palette.

## Typography

The typography system relies exclusively on **Inter**, a typeface designed for screen readability and professional clarity. 

- **Headlines:** Use Bold (700) or Semi-Bold (600) weights with slight negative letter spacing to create a compact, premium feel for product titles and section headers.
- **Body:** Standard body text uses a 16px base for optimal legibility. Use the Regular (400) weight for long-form descriptions.
- **Labels:** Small labels, such as category tags or "Sold Out" badges, should use Semi-Bold (600) with increased letter spacing and uppercase styling for distinct visual hierarchy.

## Layout & Spacing

This design system employs a **Fixed Grid** model for desktop, centering content within a 1280px container to maintain readability on ultra-wide monitors. 

- **Grid:** A 12-column system is used for desktop and tablet, collapsing to a 2-column or 1-column system for mobile.
- **Rhythm:** An 8px base spacing unit governs all margins and paddings. Component internal padding should follow the `base * n` rule (e.g., 16px, 24px, 32px).
- **Responsive Behavior:** On mobile devices, the side margins reduce to 16px to maximize screen real estate for product images.

## Elevation & Depth

To maintain a clean and professional look, this design system uses **Tonal Layers** combined with **Low-Contrast Outlines**. 

- **Surface Levels:** The primary background is white (#FFFFFF). Secondary sections or sidebars use a soft gray (#F8F9FA).
- **Shadows:** Avoid heavy, dark shadows. Use a single, highly diffused "Ambient Shadow" for floating elements like carts or modals (0px 4px 20px rgba(0, 35, 102, 0.08)).
- **Borders:** Use 1px solid borders in a light neutral tone (#E2E8F0) to define card boundaries and input fields, ensuring the UI feels structured but not boxed-in.

## Shapes

The shape language is **Soft**, utilizing subtle corner rounding to bridge the gap between corporate rigidity and modern friendliness. 

- **Standard Elements:** Buttons, inputs, and small cards use a 0.25rem (4px) radius.
- **Large Elements:** Product imagery and promotional banners use a 0.5rem (8px) radius to soften the visual impact.
- **Interactive States:** Hovering over a card should slightly increase the elevation shadow rather than changing the shape.

## Components

### Buttons
- **Primary Action:** Solid Royal Blue background with White text. On hover, the blue darkens by 10%.
- **Accent Action:** Solid Vibrant Orange background with White text (used for "Add to Cart"). On hover, it shifts slightly toward red-orange.
- **Ghost/Secondary:** Royal Blue 1px border with Royal Blue text. Clear background.

### Social Login
- **Google/Facebook:** These buttons should maintain their brand-compliant colors but adopt the system's "Soft" roundedness and height (44px) to ensure visual consistency.

### Input Fields
- **Default State:** 1px border (#E2E8F0), 12px horizontal padding.
- **Focus State:** 2px border in Royal Blue with a subtle 4px outer glow in the same color at 10% opacity.
- **Validation:** Error states must use a clear Red (#D32F2F) for both the border and the helper text below.

### Cards
- **Product Card:** White background, 1px border, no shadow by default. On hover, apply the "Ambient Shadow" and a subtle upward translate (-4px) to indicate interactivity.

### Lists & Navigation
- **Navigation:** Top-tier links use Semi-Bold weight. Active states are indicated by a 2px Royal Blue underline rather than a color change of the text itself.