---
name: Bio-Technical Synthesis
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#3d4947'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#6d7a77'
  outline-variant: '#bcc9c6'
  surface-tint: '#006a61'
  primary: '#00685f'
  on-primary: '#ffffff'
  primary-container: '#008378'
  on-primary-container: '#f4fffc'
  inverse-primary: '#6bd8cb'
  secondary: '#545f73'
  on-secondary: '#ffffff'
  secondary-container: '#d5e0f8'
  on-secondary-container: '#586377'
  tertiary: '#00685d'
  on-tertiary: '#ffffff'
  tertiary-container: '#008376'
  on-tertiary-container: '#f4fffb'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#89f5e7'
  primary-fixed-dim: '#6bd8cb'
  on-primary-fixed: '#00201d'
  on-primary-fixed-variant: '#005049'
  secondary-fixed: '#d8e3fb'
  secondary-fixed-dim: '#bcc7de'
  on-secondary-fixed: '#111c2d'
  on-secondary-fixed-variant: '#3c475a'
  tertiary-fixed: '#71f8e4'
  tertiary-fixed-dim: '#4fdbc8'
  on-tertiary-fixed: '#00201c'
  on-tertiary-fixed-variant: '#005048'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  display-lg:
    fontFamily: Hanken Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Hanken Grotesk
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
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.05em
  headline-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 4px
  xs: 0.5rem
  sm: 1rem
  md: 1.5rem
  lg: 2.5rem
  xl: 4rem
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style
The design system focuses on the intersection of biological sciences and advanced computation. The aesthetic is a fusion of **Modern Corporate** and **Technical Minimalism**, aiming to evoke a sense of clinical precision alongside environmental stewardship. 

The target audience consists of B2B stakeholders, researchers, and policy-makers who require high-density data presented with clarity and authority. The visual narrative balances the "warmth" of sustainable technology with the "cool" rigor of laboratory environments. High-quality whitespace is used to reduce cognitive load, while precise technical details (thin lines, monospaced accents) reinforce the innovative nature of the product.

## Colors
The palette is anchored by "Bio-Teal" primaries, representing growth and environmental health. These are balanced by "Deep Slate" tech-accents that provide a professional, grounded structure.

- **Primary (#0D9488):** Used for main actions, active states, and success indicators.
- **Secondary (#1E293B):** Reserved for navigation headers, primary text, and structural high-contrast elements.
- **Tertiary (#14B8A6):** A lighter teal for data visualization, hover states, and supporting illustrations.
- **Surface:** The background remains a clean, medical-grade white (#FFFFFF) with neutral-toned containers (#F8FAFC) to create subtle separation.

## Typography
The typography system uses a tiered approach to distinguish between technical data and narrative content. 

- **Headlines:** Hanken Grotesk provides a sharp, contemporary look that feels engineered yet accessible.
- **Body:** Inter is utilized for its exceptional legibility in data-heavy B2B contexts.
- **Labels/Data:** JetBrains Mono is used sparingly for technical metadata, ID strings, and scientific units to lean into the "high-tech" laboratory feel. 

All headings should favor a tight tracking (-0.01em to -0.02em) to maintain a premium, editorial appearance.

## Layout & Spacing
The spacing rhythm is based on a 4px baseline grid, ensuring mathematical alignment across all technical components. 

The layout utilizes a **12-column fluid grid** for desktop with wide margins (64px) to promote a feeling of openness and high-end positioning. On mobile, the system transitions to a 4-column grid with 16px margins. 

Large-scale sections should be separated by "xl" spacing (4rem) to maintain the minimalist, breathable aesthetic. Content containers should use "md" (1.5rem) padding internally to ensure data feels organized and uncrowded.

## Elevation & Depth
Depth is achieved through a combination of **Tonal Layers** and **Ambient Shadows**. This design system avoids heavy shadows, opting instead for "Scientific Elevation":

1.  **Level 0 (Base):** White (#FFFFFF) – The primary canvas.
2.  **Level 1 (Surface):** Neutral Off-white (#F8FAFC) – Used for grouping secondary content areas or sidebar backgrounds.
3.  **Level 2 (Cards):** White surface with a 1px border (#E2E8F0) and a subtle, ultra-diffused shadow (0px 4px 20px rgba(30, 41, 59, 0.05)).
4.  **Level 3 (Interactive):** When hovering over interactive cards, the shadow deepens slightly and the border color shifts to the Primary teal.

Glassmorphism is used exclusively for sticky navigation headers (Backdrop blur: 12px, Opacity: 80% white) to maintain context while scrolling through long technical reports.

## Shapes
The shape language is **Soft** and restrained. While consumer apps might use hyper-rounded corners, this design system uses a 0.25rem (4px) base radius to maintain a sense of structural engineering and precision.

- **Standard Elements (Inputs, Small Buttons):** 4px radius.
- **Containers & Cards (rounded-lg):** 8px radius.
- **Search Bars & Badges (rounded-xl):** 12px radius.

The goal is to avoid "childlike" roundness, favoring a "precision-molded" look similar to laboratory equipment.

## Components
- **Buttons:** Primary buttons use a solid #0D9488 fill with white text. Secondary buttons use a 1px border of #1E293B with a subtle 5% fill on hover. Text is always semi-bold.
- **Input Fields:** Use a 1px border (#E2E8F0). On focus, the border transitions to Primary Teal with a 2px outer glow (ring) of the same color at 20% opacity.
- **Cards:** White backgrounds, 1px light gray borders, and "Level 2" elevation. Use a top-accent bar (2px thick) in Teal or Navy to categorize different types of data.
- **Chips/Badges:** Small, caps-locked JetBrains Mono text. Use low-saturation backgrounds (e.g., Teal at 10% opacity) to ensure they don't distract from the primary CTA.
- **Lists:** Data rows should be separated by thin 1px horizontal lines (#F1F5F9). Avoid alternating row colors; use whitespace to define hierarchy instead.
- **Icons:** Use 1.5pt stroke weight icons. Avoid filled shapes. Icons should be technical—using crosshairs, chevrons, and geometric representations of biological markers.
- **Status Indicators:** Use "Pulse" animations for live data feeds, using a small circular dot in Teal (Active) or Slate (Inactive).