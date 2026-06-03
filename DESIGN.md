---
name: Executive Engineering & Valuation
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f3'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#44474b'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f0f1f1'
  outline: '#74777c'
  outline-variant: '#c4c6cb'
  surface-tint: '#555f6a'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#131d26'
  on-primary-container: '#7b8590'
  inverse-primary: '#bdc8d4'
  secondary: '#775a19'
  on-secondary: '#ffffff'
  secondary-container: '#fed488'
  on-secondary-container: '#785a1a'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#141d23'
  on-tertiary-container: '#7c858d'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d9e3f0'
  primary-fixed-dim: '#bdc8d4'
  on-primary-fixed: '#131d26'
  on-primary-fixed-variant: '#3e4852'
  secondary-fixed: '#ffdea5'
  secondary-fixed-dim: '#e9c176'
  on-secondary-fixed: '#261900'
  on-secondary-fixed-variant: '#5d4201'
  tertiary-fixed: '#dbe4ed'
  tertiary-fixed-dim: '#bfc8d0'
  on-tertiary-fixed: '#141d23'
  on-tertiary-fixed-variant: '#3f484f'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '700'
    lineHeight: '1.3'
    letterSpacing: 0.05em
  headline-sm:
    fontFamily: Montserrat
    fontSize: 18px
    fontWeight: '600'
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
    lineHeight: '1.5'
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.1em
  technical-mono:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.02em
spacing:
  unit: 8px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
  max-width: 1280px
---

## Brand & Style

The design system is engineered to project **Technical Authority**, **Legal Security**, and **Sophisticated Precision**. It caters to a high-end clientele including law firms, real estate investors, and institutional developers who require absolute trust in property valuation and civil engineering expertise.

The aesthetic follows a **Modern Corporate** direction with a focus on high-contrast minimalism. It utilizes a "Structural Luxury" approach: combining the rigid, grid-based logic of engineering with the refined materials of executive branding. Every interface element should feel calculated, intentional, and premium.

## Colors

The palette is restricted to three core pillars to maintain an executive atmosphere:

*   **Deep Corporate Blue (#111B24):** Used for typography, primary backgrounds, and surfaces requiring maximum visual weight. It represents stability and professional rigor.
*   **Matte Gold (#C5A059):** Reserved for surgical precision—accents, thin structural lines, primary action states, and technical iconography. It evokes the quality and high value of the properties being evaluated.
*   **Ultra-Clean Off-White (#FAFAFA):** The foundation of the system. This provides a clean, expansive canvas that mimics high-grade architectural paper.

Secondary neutrals in mid-tone grays should be used sparingly for metadata and deactivated states.

## Typography

Typography balances the bold impact of **Montserrat** for headings with the systematic clarity of **Inter** for technical data.

*   **Headlines:** Use Montserrat in Bold or Semi-Bold. Larger displays should utilize slight negative letter-spacing to feel more "imposing," while smaller subheaders should use increased letter-spacing and uppercase styling for a more architectural, labeled feel.
*   **Body:** Inter provides the necessary legibility for dense valuation reports and legal descriptions.
*   **Alignment:** Stick to structured, left-aligned layouts. Justified text may be used for formal report summaries to mimic legal documentation.

## Layout & Spacing

This design system employs a **Fixed Grid** philosophy. Content is contained within a 1280px max-width container to ensure readability of technical reports.

*   **Rhythm:** A 8px base unit drives all spacing. 
*   **Grid:** Use a 12-column grid for desktop with 24px gutters. Elements should align strictly to the grid to reflect engineering precision.
*   **Whitespace:** Generous top and bottom margins (80px–120px) between sections are mandatory to allow the technical content to "breathe" and feel premium.
*   **Technical Breaks:** Horizontal rules should be 1px solid Matte Gold (#C5A059), occasionally interrupted by a centralized "Compass" or "Bússola" icon to symbolize direction and accuracy.

## Elevation & Depth

To maintain a "technical paper" feel, the system avoids heavy shadows. Instead, it uses **Tonal Layering** and **Fine Outlines**:

*   **Surfaces:** Most content sits flat on the Off-White background. 
*   **Layers:** High-priority cards use a 1px solid border in the Primary Blue or Matte Gold rather than a shadow.
*   **Subtle Depth:** Where depth is required (e.g., modals), use a 1px Gold border with a very soft, neutralized drop shadow (Color: #111B24, Opacity: 5%, Blur: 20px).
*   **Glassmorphism:** Use only for mobile navigation bars—highly blurred (32px) and slightly tinted with the Primary Blue at 90% opacity.

## Shapes

The shape language is **Sharp (0px)**. 

In engineering and valuation, precision is represented by hard edges and defined corners. Rounded corners are avoided to distance the brand from "friendly" consumer apps and lean into an "institutional" and "authoritative" aesthetic. All buttons, input fields, and containers must have 90-degree angles.

## Components

*   **Buttons:** Rectangular with no radius. Primary buttons are solid Deep Blue with White text. "Action" buttons are Matte Gold with Deep Blue text. 
*   **Input Fields:** Bottom-border only (1px) in Deep Blue, moving to Matte Gold on focus. This mimics architectural drafting lines.
*   **Icons:** Minimalist, thin-line (1px or 1.5px) icons in Matte Gold. Avoid filled icons.
*   **Cards:** 1px solid Blue or Gold border. No fill (transparent) or solid Off-White fill.
*   **Section Dividers:** A thin 1px Gold line with a Compass icon centered. The line should fade out toward the margins.
*   **Data Tables:** High-density, technical tables with Matte Gold headers and subtle 0.5px Blue horizontal separators. No vertical lines.
*   **Valuation Chips:** Small, square-edged labels with Gold backgrounds used to highlight property "Status" or "Technical Rating."