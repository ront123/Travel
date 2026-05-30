---
name: Horizon Voyager
colors:
  surface: '#fcf9f4'
  surface-dim: '#dcdad5'
  surface-bright: '#fcf9f4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3ee'
  surface-container: '#f0ede9'
  surface-container-high: '#ebe8e3'
  surface-container-highest: '#e5e2dd'
  on-surface: '#1c1c19'
  on-surface-variant: '#564239'
  inverse-surface: '#31302d'
  inverse-on-surface: '#f3f0eb'
  outline: '#8a7267'
  outline-variant: '#ddc1b4'
  surface-tint: '#9e4200'
  primary: '#9b4100'
  on-primary: '#ffffff'
  primary-container: '#bc5717'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb691'
  secondary: '#476647'
  on-secondary: '#ffffff'
  secondary-container: '#c6e9c2'
  on-secondary-container: '#4b6a4b'
  tertiary: '#34607f'
  on-tertiary: '#ffffff'
  tertiary-container: '#4e7999'
  on-tertiary-container: '#fcfcff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbcb'
  primary-fixed-dim: '#ffb691'
  on-primary-fixed: '#341100'
  on-primary-fixed-variant: '#793100'
  secondary-fixed: '#c9ecc5'
  secondary-fixed-dim: '#adcfaa'
  on-secondary-fixed: '#042109'
  on-secondary-fixed-variant: '#304e31'
  tertiary-fixed: '#cae6ff'
  tertiary-fixed-dim: '#a0ccef'
  on-tertiary-fixed: '#001e2f'
  on-tertiary-fixed-variant: '#1b4b69'
  background: '#fcf9f4'
  on-background: '#1c1c19'
  surface-variant: '#e5e2dd'
typography:
  display-lg:
    fontFamily: Noto Serif
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Noto Serif
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-md:
    fontFamily: Noto Serif
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-sm:
    fontFamily: Noto Serif
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Libre Franklin
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Libre Franklin
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Montserrat
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  container-max: 1120px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  unit: 8px
---

## Brand & Style

The design system is crafted to evoke the feeling of a premium, curated journey. It blends the warmth of a personal connection with the polished authority of a high-end travel publication. The aesthetic sits at the intersection of **Minimalism** and **Editorial Design**, utilizing generous whitespace and a sophisticated grid to let photography breathe.

The target audience seeks exclusivity, authenticity, and a seamless experience. The UI should feel like a "living brochure"—tactile, inviting, and deeply organized. It avoids the coldness of many modern SaaS platforms in favor of a "human-centered" luxury, where every interaction feels like a guided recommendation from a trusted friend.

## Colors

The palette is derived directly from the transition of a coastal sunset into the lush landscape of a vineyard.

*   **Primary (Sunset Orange):** Used for primary actions, calls to motion, and highlighting key itinerary highlights. It provides a warm, energetic glow.
*   **Secondary (Vineyard Green):** An earthy, grounded tone used for secondary buttons, success states, and elements related to nature or sustainability.
*   **Tertiary (Ocean Deep Blue):** A stable, professional blue used for headers, navigation, and grounding structural elements.
*   **Neutral (Parchment):** An off-white, warm background that prevents the interface from feeling clinical. It mimics the texture of high-quality paper.
*   **Text & Accents:** Deep charcoal is used for primary text to ensure high legibility against the parchment background, while subtle gold accents can be used for "premium" tier badges or dividers.

## Typography

This design system employs a classic serif/sans-serif pairing to achieve an editorial look. 

**Noto Serif** is the cornerstone for all headlines and display text, providing the "authoritative" and "classic" feel required for a premium guide. It handles Hebrew glyphs with exceptional elegance, maintaining a traditional yet clean appearance.

**Libre Franklin** is used for body copy. It is a versatile, dependable sans-serif that remains highly legible at small sizes, perfect for long-form itinerary descriptions.

**Montserrat** is reserved for labels, navigation items, and small metadata. Its geometric nature adds a touch of modernism and "adventure" to the system, especially when used in all-caps with light tracking.

## Layout & Spacing

The layout philosophy follows a **Fixed Grid** model on desktop to simulate the structured feel of a printed A4 travel flyer or brochure. 

*   **Desktop:** A 12-column grid centered on the page with 24px gutters. Content should be grouped into clear vertical sections with generous "white-air" (64px+) between major thematic blocks.
*   **Editorial Breaks:** Occasionally use "Full-Bleed" imagery that breaks the grid to create visual impact, specifically for sunset or landscape photography.
*   **Mobile:** Shifts to a single-column fluid layout with 20px side margins. Horizontal scrolling "cards" are used for browsing different travel packages or gallery images to maintain a compact vertical footprint.
*   **Spacing Rhythm:** Use a base unit of 8px. Internal component padding should be generous (e.g., 24px or 32px inside cards) to convey a sense of luxury and lack of clutter.

## Elevation & Depth

Visual hierarchy is achieved primarily through **Tonal Layers** rather than heavy shadows.

*   **Surface Hierarchy:** The base layer is the Neutral Parchment. Primary content blocks (cards) use a pure white background with a very subtle, thin border (1px) in a slightly darker parchment tone.
*   **Depth:** Use low-contrast outlines for most containers. For interactive elements that require "lift," use an extremely diffused, low-opacity shadow tinted with the Secondary (Green) or Tertiary (Blue) colors to maintain a natural, non-digital appearance.
*   **Photography as Depth:** Deep background blurs are used only behind modal overlays to maintain focus on the "guide" content.

## Shapes

The shape language is **Soft (0.25rem)**. 

This minimal rounding provides a modern touch while maintaining the structural integrity of the "brochure" feel. Sharp corners feel too aggressive, while pill-shapes feel too casual/tech-oriented. The subtle 4px radius on buttons and cards offers a hint of approachability without sacrificing the "premium" professional aesthetic. Photo containers should follow this same 4px radius to ensure a consistent, framed look.

## Components

*   **Buttons:** Primary buttons use the Sunset Orange background with White text. Secondary buttons use the Vineyard Green with an outline or ghost style. Use the Label-MD typography for button text.
*   **Cards:** Use White backgrounds on the Parchment surface. Include a top-aligned image with a fixed aspect ratio (3:2). Text within cards should be left-aligned for Western languages and right-aligned for Hebrew, maintaining high editorial standards.
*   **Input Fields:** Minimalist design with a bottom-border only or a light parchment-toned fill. Labels should use Montserrat in uppercase above the field.
*   **Chips:** Used for "tags" like 'Luxury', 'Adventure', or 'Family-Friendly'. These should be Vineyard Green or Ocean Blue with low-opacity fills and high-contrast text.
*   **Itinerary Lists:** A specialized component featuring a vertical "path" line connecting sunset-orange dots, representing different stops or days in a journey.
*   **Quotes:** Large-scale Noto Serif italics for personal testimonials from Ron, centered and highlighted with a subtle Sunset Orange quote mark icon.