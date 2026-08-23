---
name: Cinematic Commerce
colors:
  surface: '#0f141b'
  surface-dim: '#0f141b'
  surface-bright: '#343941'
  surface-container-lowest: '#090f15'
  surface-container-low: '#171c23'
  surface-container: '#1b2027'
  surface-container-high: '#252a32'
  surface-container-highest: '#30353d'
  on-surface: '#dee2ec'
  on-surface-variant: '#c6c6cb'
  inverse-surface: '#dee2ec'
  inverse-on-surface: '#2c3138'
  outline: '#909095'
  outline-variant: '#45474b'
  surface-tint: '#c4c6cf'
  primary: '#c4c6cf'
  on-primary: '#2e3037'
  primary-container: '#0b0e14'
  on-primary-container: '#797b83'
  inverse-primary: '#5c5e66'
  secondary: '#98cbff'
  on-secondary: '#003354'
  secondary-container: '#00a2fd'
  on-secondary-container: '#003558'
  tertiary: '#bfc7d3'
  on-tertiary: '#29313a'
  tertiary-container: '#070f17'
  on-tertiary-container: '#747c87'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e1e2eb'
  primary-fixed-dim: '#c4c6cf'
  on-primary-fixed: '#191c22'
  on-primary-fixed-variant: '#44474e'
  secondary-fixed: '#cfe5ff'
  secondary-fixed-dim: '#98cbff'
  on-secondary-fixed: '#001d33'
  on-secondary-fixed-variant: '#004a77'
  tertiary-fixed: '#dbe3ef'
  tertiary-fixed-dim: '#bfc7d3'
  on-tertiary-fixed: '#141c25'
  on-tertiary-fixed-variant: '#404751'
  background: '#0f141b'
  on-background: '#dee2ec'
  surface-variant: '#30353d'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
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
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 4px
  xs: 8px
  sm: 16px
  md: 24px
  lg: 40px
  xl: 64px
  gutter: 20px
  margin-mobile: 16px
  margin-desktop: 48px
---

## Brand & Style

The design system is a high-octane, cinematic e-commerce framework inspired by premium content streaming platforms. It targets a tech-savvy audience that values discovery, visual fidelity, and a seamless "infinite scroll" experience. The aesthetic is anchored in a dark, immersive atmosphere where products are treated like featured titles.

The visual style is **Corporate / Modern** with a **Minimalist** lean. It utilizes deep canvas depth to allow vibrant product imagery and Electric Blue accents to pop. The emotional response should be one of "exclusive access" and "technical precision," maintaining a high-contrast environment that reduces eye strain while emphasizing premium value.

## Colors

The palette is strictly dark-mode first. The **Primary** color (#0B0E14) acts as the infinite void of the canvas, ensuring that product photography with alpha channels or high-key lighting remains the focal point. 

The **Secondary** Electric Blue (#00A3FF) is reserved for high-priority actions, active states, and critical navigational cues. **Slate Grays** serve as tonal separators, creating hierarchy between the background and container surfaces without the need for harsh lines. Use white (#FFFFFF) for primary headers and a muted slate (#94A3B8) for secondary metadata to maintain a clear information hierarchy.

## Typography

This design system utilizes **Inter** for its systematic, utilitarian, and highly legible characteristics in dark environments. The type scale is optimized for readability against high-contrast backgrounds.

Headlines should use tighter letter spacing and heavy weights to command attention, mimicking a theatrical poster style. Labels for categories and filters use a semi-bold weight and occasional uppercase transformations to differentiate them from body content. For mobile devices, headlines scale down to prevent excessive word-breaking while maintaining the bold, impactful character of the brand.

## Layout & Spacing

The design system employs a **Fluid Grid** model. On desktop, it utilizes a 12-column grid with generous 24px gutters to allow the product cards room to breathe. 

- **Desktop (1280px+):** Max-width container of 1440px. Sidebars are fixed at 280px, with the main product grid expanding to fill the remaining space.
- **Tablet (768px - 1279px):** Sidebars collapse into a horizontal filter bar or a drawer. Gutters reduce to 16px.
- **Mobile (<768px):** A single or double-column card layout with 16px side margins. 

The spacing rhythm follows a 4px base unit. Vertical rhythm between sections should be 40px or 64px to create a distinct "content block" feel, reminiscent of streaming service categories.

## Elevation & Depth

Visual hierarchy is achieved through **Tonal Layers** and **Subtle Shadows**. Since the primary background is near-black, traditional shadows are replaced by "glow" effects or subtle lightening of the surface hex code.

1.  **Level 0 (Canvas):** #0B0E14 - The lowest base.
2.  **Level 1 (Cards/Sidebar):** #161B22 - Surfaces that sit directly on the canvas. These use a 1px border (#1F2937) instead of a shadow for definition.
3.  **Level 2 (Dropdowns/Modals):** #1F2937 - Elevated elements. These use a soft, diffused shadow with 20% opacity and 16px blur to create separation.
4.  **Interactive Glow:** Primary buttons and active states use a subtle Electric Blue outer glow (4px blur) to simulate an emissive light source.

## Shapes

The shape language is consistently **Rounded**, using a 12px (0.75rem) corner radius as the standard for product cards and main containers. This softening of the geometry contrasts with the "technical" dark theme to make the interface feel approachable and modern.

- **Small elements (Checkboxes, Tags):** 4px radius.
- **Standard elements (Cards, Input fields):** 12px radius.
- **Large elements (Modals, Feature Banners):** 24px radius.
- **Search bars:** Fully pill-shaped to denote a distinct functional area.

## Components

### Navigation & Sidebars
- **Global Nav:** Sticky top bar with a glassmorphic blur (12px backdrop-filter) and 70% opacity #0B0E14 background.
- **Category Sidebar:** Minimalist text links with 8px vertical spacing. Active states feature an Electric Blue left-accent border (2px wide).

### Buttons & Inputs
- **Primary Button:** Solid Electric Blue (#00A3FF) with White text. High-contrast and vibrant.
- **Secondary Button:** Ghost style with a 1px #1F2937 border.
- **Input Fields:** Deep Slate background (#161B22) with 12px padding. Focus state triggers an Electric Blue border glow.

### Product Grid & Cards
- **Product Cards:** Aspect ratio of 3:4 for a "poster" feel. 12px border radius. Titles appear in `label-md` below the image or as an overlay on hover.
- **Hover States:** Cards should scale slightly (1.02x) and increase border brightness when hovered.

### Filters & Chips
- **Category Chips:** Rounded-pill shapes with #1F2937 background. Active chips switch to Electric Blue text with a subtle background tint.