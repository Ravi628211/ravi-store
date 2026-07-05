---
name: Ravi Store Design System
colors:
  surface: '#f9f9ff'
  surface-dim: '#cfdaf2'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f3ff'
  surface-container: '#e7eeff'
  surface-container-high: '#dee8ff'
  surface-container-highest: '#d8e3fb'
  on-surface: '#111c2d'
  on-surface-variant: '#434653'
  inverse-surface: '#263143'
  inverse-on-surface: '#ecf1ff'
  outline: '#737784'
  outline-variant: '#c3c6d5'
  surface-tint: '#1d59c1'
  primary: '#003c90'
  on-primary: '#ffffff'
  primary-container: '#0f52ba'
  on-primary-container: '#bcceff'
  inverse-primary: '#b0c6ff'
  secondary: '#a04100'
  on-secondary: '#ffffff'
  secondary-container: '#fe6b00'
  on-secondary-container: '#572000'
  tertiary: '#3d4143'
  on-tertiary: '#ffffff'
  tertiary-container: '#55585a'
  on-tertiary-container: '#ccced0'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d9e2ff'
  primary-fixed-dim: '#b0c6ff'
  on-primary-fixed: '#001945'
  on-primary-fixed-variant: '#00419c'
  secondary-fixed: '#ffdbcc'
  secondary-fixed-dim: '#ffb693'
  on-secondary-fixed: '#351000'
  on-secondary-fixed-variant: '#7a3000'
  tertiary-fixed: '#e0e3e5'
  tertiary-fixed-dim: '#c4c7c9'
  on-tertiary-fixed: '#191c1e'
  on-tertiary-fixed-variant: '#444749'
  background: '#f9f9ff'
  on-background: '#111c2d'
  surface-variant: '#d8e3fb'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Montserrat
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
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
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
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
  margin-desktop: 64px
  margin-mobile: 20px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style

This design system is built to facilitate a premium eCommerce experience tailored for the modern Indian consumer. The brand personality is authoritative yet accessible, combining the trust of traditional commerce with the speed of digital-first retail. 

The aesthetic follows a **Modern Minimalist** approach with subtle **Glassmorphic** accents for high-end product showcases. The interface prioritizes white space to allow product photography to remain the focal point, while utilizing generous rounded corners and layered depth to create an inviting, "touchable" digital environment. The emotional response should be one of reliability, luxury, and effortless navigation.

## Colors

The palette is anchored by **Royal Blue**, a color associated with trust and institutional stability in the Indian market. **Vibrant Orange** serves as the strategic accent color, reserved exclusively for high-priority calls to action (CTAs), price highlights, and limited-time offers to drive urgency without compromising the premium feel.

- **Primary (Royal Blue):** Used for headers, primary buttons, and active states.
- **Secondary (Orange):** Used for "Add to Cart," "Buy Now," and promotional badges.
- **Surface:** Pure White (#FFFFFF) is the primary background to maintain a clean, high-end editorial feel.
- **Neutral:** A range of slate greys is used for secondary text and borders to maintain soft contrast.

## Typography

The system utilizes a dual-font strategy. **Montserrat** provides a bold, geometric presence for headlines and branding, evoking a sense of modern fashion and scale. **Inter** is used for all functional text, product descriptions, and data tables due to its exceptional legibility at small sizes and high x-height.

For mobile screens, display sizes are aggressively stepped down to ensure product titles do not wrap awkwardly, maintaining the "clean" aesthetic even on smaller viewports.

## Layout & Spacing

The design system employs a **12-column fluid grid** for desktop, transitioning to a **4-column grid** for mobile. A base 8px spacing system governs all internal padding and margins to ensure mathematical harmony.

- **Desktop:** 1280px max-width container with 24px gutters. Large horizontal margins (64px) are used to create a "boutique" feel.
- **Tablet:** 8-column grid with 20px gutters.
- **Mobile:** 4-column grid with 16px gutters and 20px side margins to ensure content doesn't feel cramped on narrow devices.

## Elevation & Depth

Hierarchy is established through **Ambient Shadows** and tonal layering rather than harsh borders. 

- **Level 0 (Base):** Pure White (#FFFFFF) background.
- **Level 1 (Cards/Search):** White surface with a very soft, large-radius shadow: `0 10px 30px rgba(15, 82, 186, 0.05)`. Note the subtle blue tint in the shadow to maintain brand harmony.
- **Level 2 (Hover/Modals):** Increased shadow spread and slight lift (y-axis shift).
- **Glassmorphism:** Use a 12px backdrop blur with 80% opacity white for sticky navigation bars and quick-view overlays to maintain context of the underlying content.

## Shapes

The design system uses a **Rounded** shape language to feel modern and friendly. 

- **Buttons & Inputs:** Use the standard `rounded` (0.5rem) setting.
- **Product Cards:** Use `rounded-xl` (1.5rem) to create a soft, premium frame for product imagery.
- **Search Bars:** Use a fully pill-shaped radius (999px) for the mega search bar to differentiate it from other functional elements.

## Components

### Buttons
Primary buttons use the Royal Blue background with white text. The "Add to Cart" and checkout buttons use the Orange accent. All buttons feature a subtle scale transform (98%) on press to provide tactile feedback.

### Product Cards
Cards are the core of the experience. They feature a 1:1 aspect ratio image container, `rounded-xl` corners, and the Level 1 shadow. Information is stacked vertically: Brand (Label-sm), Title (Body-md Bold), Price (Body-lg Bold), and a secondary "Quick Add" ghost button that appears on hover.

### Mega Search Bar
The primary search utility is oversized, positioned centrally in the header. It uses a pill-shape, a subtle 1px border (#E2E8F0), and an active state that triggers a Level 2 shadow with a category dropdown menu.

### Seller Dashboard Components
Data-heavy views use Inter exclusively. Data tables should have "zebra-striping" using the Tertiary color (#F8FAFC) instead of borders. Charts should utilize the Primary Royal Blue for main data lines and the Secondary Orange for comparative metrics or alerts.

### Navigation
The navigation menu uses high-contrast typography (Montserrat, Semi-bold) for top-level categories. Dropdown "Mega-menus" utilize the Glassmorphism effect to overlay the main content without completely obscuring the shopping context.