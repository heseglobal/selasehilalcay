---
name: Heritage Gold & Forest
colors:
  surface: '#021710'
  surface-dim: '#021710'
  surface-bright: '#283e35'
  surface-container-lowest: '#00120b'
  surface-container-low: '#091f18'
  surface-container: '#0d241c'
  surface-container-high: '#182e26'
  surface-container-highest: '#233930'
  on-surface: '#cfe8dc'
  on-surface-variant: '#c1c8c3'
  inverse-surface: '#cfe8dc'
  inverse-on-surface: '#1f352c'
  outline: '#8b928e'
  outline-variant: '#414844'
  surface-tint: '#abcebd'
  primary: '#abcebd'
  on-primary: '#16362a'
  primary-container: '#1b3b2f'
  on-primary-container: '#83a596'
  inverse-primary: '#456557'
  secondary: '#cbc6bd'
  on-secondary: '#32302a'
  secondary-container: '#4c4942'
  on-secondary-container: '#bdb8af'
  tertiary: '#eebab5'
  on-tertiary: '#482724'
  tertiary-container: '#4e2c29'
  on-tertiary-container: '#c2928e'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#c7ebd9'
  primary-fixed-dim: '#abcebd'
  on-primary-fixed: '#002116'
  on-primary-fixed-variant: '#2d4d40'
  secondary-fixed: '#e7e2d9'
  secondary-fixed-dim: '#cbc6bd'
  on-secondary-fixed: '#1d1b16'
  on-secondary-fixed-variant: '#494640'
  tertiary-fixed: '#ffdad6'
  tertiary-fixed-dim: '#eebab5'
  on-tertiary-fixed: '#301311'
  on-tertiary-fixed-variant: '#623d3a'
  background: '#021710'
  on-background: '#cfe8dc'
  surface-variant: '#233930'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  headline-xl:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
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
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  section-padding: 120px
---

## Brand & Style

This design system embodies the essence of "Selase Hilal Çay" through a lens of **Premium Luxury**. It blends traditional Turkish tea culture with a sophisticated, boutique e-commerce aesthetic. The brand personality is prestigious, authentic, and serene, targeting a discerning audience that values artisanal quality and heritage.

The visual style is a fusion of **Minimalism** and **Tactile Luxury**. It leverages high negative space to allow products to breathe, paired with intricate organic leaf motifs inspired by the gold line-art on the product packaging. The goal is to evoke a sensory response—the warmth of tea, the texture of premium paper, and the precision of gold foil stamping.

- **Emotional Response:** Trust, tranquility, indulgence, and cultural pride.
- **Visual Strategy:** Use of deep, saturated greens against cream tones to create a grounded yet airy experience. Gold is used sparingly as a "finish" to highlight the most important interactions and brand elements.

## Colors

The palette is rooted in the "Deep Forest" of tea plantations and the "Lustrous Gold" of premium tradition.

- **Primary (Forest Green):** Used for immersive backgrounds, navigation bars, and primary brand surfaces. It conveys depth and quality.
- **Secondary (Cream/Beige):** Used for content-heavy sections and product descriptions to ensure maximum readability and a "boutique paper" feel.
- **Accent (Gold/Bronze):** Reserved for call-to-action buttons, thin dividers, and decorative icons. It should be treated like gold leaf—precious and intentional.
- **Neutral:** A darker shade of the forest green for deep shadows or footer backgrounds to maintain a monochromatic harmony.

## Typography

The typographic hierarchy relies on the contrast between the **authoritative elegance of Playfair Display** and the **utilitarian clarity of Inter**.

- **Headlines:** Use Playfair Display for all titles. It provides a literary, high-end feel. For Display and XL sizes, use tighter letter spacing to create a modern editorial look.
- **Body Text:** Inter is utilized for all functional copy, ensuring accessibility and a clean modern balance to the ornate headlines.
- **Labels:** Use Inter in Bold/Semi-bold with increased letter spacing and uppercase styling for "Overlines" or small category labels to create a systematic, organized feel.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy for desktop to maintain the boutique "centered" feel, while transitioning to a fluid model for mobile.

- **Grid:** A 12-column grid with generous 24px gutters.
- **Negative Space:** This is a core component. Use large `section-padding` (120px+) between major content blocks to create a feeling of luxury and exclusivity.
- **Breakpoints:**
  - **Desktop (1280px+):** Centered content with 64px outer margins.
  - **Tablet (768px - 1024px):** 32px margins, 2-column product grids.
  - **Mobile (Under 768px):** 16px margins, single-column stacks, typography scales down (e.g., `headline-lg-mobile`).

## Elevation & Depth

This system avoids heavy drop shadows in favor of **Tonal Layers** and **High-Contrast Outlines**.

- **Flat Depth:** Hierarchy is established through color blocking (Cream surfaces on Forest backgrounds).
- **Thin Gold Borders:** Use 1px Gold (#C9A961) lines to define containers, table rows, and dividers. This mimics the "inlay" look of the product box.
- **Interactive Elevation:** Only on primary cards or buttons, use a very subtle, diffused shadow (0px 4px 20px rgba(0,0,0,0.1)) upon hover to signal interactivity without breaking the flat luxury aesthetic.

## Shapes

The shape language is **Soft and Sophisticated**.

- **Buttons & Inputs:** Use a 0.25rem (4px) corner radius. This provides a "tailored" look that is softer than sharp corners but more professional than fully rounded pills.
- **Product Imagery:** Images should maintain sharp 90-degree corners or very subtle 4px rounding to keep the look clean and architectural.
- **Decorative Elements:** Use the organic leaf pattern as a background mask or a floating element to break the rigidity of the grid.

## Components

### Buttons
- **Primary:** Solid Gold (#C9A961) background with Deep Green (#1B3B2F) text. 4px border radius. No shadow.
- **Secondary:** Transparent background with a 1px Gold border. Text in Gold or Off-white depending on the surface.
- **Tertiary:** Text-only with a thin 1px underline that expands on hover.

### Cards
- Product cards should use the Secondary (Cream) background when placed on Forest Green sections. 
- Use the organic leaf motif as a subtle watermark in the corner of featured cards.
- Pricing should always be in Playfair Display.

### Input Fields
- Underline style preferred for a more "boutique" look. 
- 1px Gold border on the bottom only, with Inter 14px labels floating above.

### Dividers
- Use ultra-thin (0.5pt to 1pt) gold lines. 
- For a premium touch, place the "Hilal" (Crescent/Leaf) logo icon in the center of a horizontal divider.

### Lists & Tables
- Remove all vertical borders. Use thin gold horizontal rules only. 
- Header rows should use `label-md` typography.