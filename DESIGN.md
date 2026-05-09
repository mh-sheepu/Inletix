---
name: Inletix
colors:
  surface: '#121317'
  surface-dim: '#121317'
  surface-bright: '#38393e'
  surface-container-lowest: '#0d0e12'
  surface-container-low: '#1a1b20'
  surface-container: '#1f1f24'
  surface-container-high: '#292a2e'
  surface-container-highest: '#343439'
  on-surface: '#e3e2e8'
  on-surface-variant: '#c4c5d9'
  inverse-surface: '#e3e2e8'
  inverse-on-surface: '#2f3035'
  outline: '#8e8fa2'
  outline-variant: '#434656'
  surface-tint: '#b9c3ff'
  primary: '#b9c3ff'
  on-primary: '#00228a'
  primary-container: '#1f51ff'
  on-primary-container: '#e1e4ff'
  inverse-primary: '#0947f7'
  secondary: '#bdf4ff'
  on-secondary: '#00363d'
  secondary-container: '#00e3fd'
  on-secondary-container: '#00616d'
  tertiary: '#c5c6c7'
  on-tertiary: '#2e3132'
  tertiary-container: '#656768'
  on-tertiary-container: '#e5e6e7'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#dde1ff'
  primary-fixed-dim: '#b9c3ff'
  on-primary-fixed: '#001257'
  on-primary-fixed-variant: '#0034c0'
  secondary-fixed: '#9cf0ff'
  secondary-fixed-dim: '#00daf3'
  on-secondary-fixed: '#001f24'
  on-secondary-fixed-variant: '#004f58'
  tertiary-fixed: '#e2e2e3'
  tertiary-fixed-dim: '#c5c6c7'
  on-tertiary-fixed: '#1a1c1d'
  on-tertiary-fixed-variant: '#454748'
  background: '#121317'
  on-background: '#e3e2e8'
  surface-variant: '#343439'
typography:
  display-lg:
    fontFamily: IBM Plex Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: IBM Plex Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: IBM Plex Sans
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-md:
    fontFamily: IBM Plex Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: IBM Plex Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: IBM Plex Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-sm:
    fontFamily: JetBrains Mono
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
  base: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
---

## Brand & Style
The brand identity centers on "Digital Infrastructure Excellence." The design system evokes a sense of architectural stability combined with the speed of modern cloud computing. It targets enterprise decision-makers and technical leads who value precision and reliability.

The aesthetic follows a **Corporate Tech** movement—a hybrid of high-end minimalism and subtle glassmorphism. It utilizes deep, "obsidian" space to represent the core of the data center, while vibrant, light-emitting action colors represent the flow of information. The visual language is intentional, avoiding decorative clutter in favor of high-contrast information density and crisp, geometric alignment.

## Colors
The palette is built on a "Dark Mode First" philosophy to ensure long-term readability and a premium tech feel.

*   **Primary (Electric Blue):** Used for primary calls to action, active states, and critical brand moments. It represents energy and connectivity.
*   **Secondary (Cyan):** Used for accents, data visualization, and secondary interactions. It provides a luminous contrast against dark backgrounds.
*   **Background (Obsidian):** `#0B0C10`. The foundational layer for all pages.
*   **Surface (Slate Gray):** `#1F2833` and `#45A29E`. Used for cards, navigation bars, and structural elements to create depth.
*   **Text (Silver/White):** High-contrast whites (#FFFFFF) for headings and soft silvers (#C5C6C7) for body text to ensure WCAG AA accessibility compliance.

## Typography
This design system utilizes **IBM Plex Sans** for its systematic, corporate, and reliable personality. The typeface strikes a perfect balance between organic humanist details and engineering-grade precision.

*   **Headlines:** Heavy weights (600-700) with slight negative letter-spacing to create a "dense," impactful look on large screens.
*   **Body Text:** Standard weight (400) with generous line heights (1.5x) to optimize legibility against dark backgrounds.
*   **Technical Labels:** **JetBrains Mono** is introduced for small labels, status tags, and metadata to reinforce the IT/Infrastructure context of the company.

## Layout & Spacing
The layout follows a strict **12-column fluid grid** for desktop and a **4-column grid** for mobile. A rhythmic 8px base unit governs all dimensions.

*   **Rhythm:** Vertical spacing should follow increments of 8px (e.g., 16, 24, 32, 64).
*   **Desktop:** Content is housed in a centered 1280px container with 48px side margins. Gutters are fixed at 24px to ensure breathing room between technical data points.
*   **Mobile:** Margins scale down to 16px. Elements like cards should span the full width of the viewport minus the margins to maximize screen real estate.

## Elevation & Depth
Depth is created through **Tonal Layering** and **Subtle Glassmorphism** rather than traditional heavy shadows.

1.  **Level 0 (Background):** Pure Obsidian (#0B0C10).
2.  **Level 1 (Default Surface):** Slate Gray (#1F2833) with a 1px solid border (#45A29E at 20% opacity).
3.  **Level 2 (Floating/Overlays):** Glassmorphic surfaces using a background blur (12px to 20px) and a semi-transparent slate fill (80% opacity).

**Crisp Borders:** Every interactive container must have a 1px border. For inactive states, use a low-contrast gray. For active or focused states, use Electric Blue or Cyan. This "wireframe-plus" look emphasizes technical precision.

## Shapes
The shape language is **"Soft-Tech."** We avoid aggressive roundness to maintain a professional, authoritative feel, but use small radii to keep the interface feeling modern and accessible.

*   **Buttons & Inputs:** 4px (0.25rem) corner radius.
*   **Cards & Modals:** 8px (0.5rem) corner radius.
*   **Outer Containers:** 12px (0.75rem) corner radius.

Iconography should follow this logic—using 1.5pt or 2pt strokes with slightly rounded caps and joins to match the component geometry.

## Components

*   **Buttons:** Primary buttons use a solid Electric Blue fill with white text. Hover states trigger a subtle cyan outer glow (0px 0px 15px rgba(0, 229, 255, 0.3)). Secondary buttons are "Ghost" style with a 1px Cyan border.
*   **Inputs:** Fields use the Obsidian background with a 1px Slate border. On focus, the border transitions to Cyan with a 2px "focus ring" glow. Labels are always placed above the field in JetBrains Mono.
*   **Cards:** Use the Level 1 surface. Content should be padded by 24px. Headers within cards should be separated by a subtle 1px horizontal rule.
*   **Chips/Status Tags:** Small, pill-shaped elements with low-opacity background fills (10%) and high-opacity text (100%) of the same color (e.g., a "System Up" tag has a 10% Cyan background and 100% Cyan text).
*   **Glass Modals:** Use a heavy backdrop-filter (blur 24px) to ensure content remains readable over busy backgrounds. The border should be a gradient stroke from Slate to Cyan to simulate a light-catch effect.