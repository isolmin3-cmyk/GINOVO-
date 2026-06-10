---
name: JINOVER Precision
colors:
  surface: '#121318'
  surface-dim: '#121318'
  surface-bright: '#38393e'
  surface-container-lowest: '#0d0e13'
  surface-container-low: '#1a1b20'
  surface-container: '#1e1f25'
  surface-container-high: '#292a2f'
  surface-container-highest: '#34343a'
  on-surface: '#e3e1e9'
  on-surface-variant: '#c3caaf'
  inverse-surface: '#e3e1e9'
  inverse-on-surface: '#2f3036'
  outline: '#8d947b'
  outline-variant: '#434935'
  surface-tint: '#9dd912'
  primary: '#b2f032'
  on-primary: '#243600'
  primary-container: '#97d303'
  on-primary-container: '#3c5700'
  inverse-primary: '#496800'
  secondary: '#bec6e0'
  on-secondary: '#283044'
  secondary-container: '#3e465c'
  on-secondary-container: '#adb5ce'
  tertiary: '#ddddde'
  on-tertiary: '#2f3132'
  tertiary-container: '#c1c1c2'
  on-tertiary-container: '#4d4f50'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#b7f638'
  primary-fixed-dim: '#9dd912'
  on-primary-fixed: '#131f00'
  on-primary-fixed-variant: '#364e00'
  secondary-fixed: '#dae2fd'
  secondary-fixed-dim: '#bec6e0'
  on-secondary-fixed: '#131b2e'
  on-secondary-fixed-variant: '#3e465c'
  tertiary-fixed: '#e2e2e3'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1d'
  on-tertiary-fixed-variant: '#454748'
  background: '#121318'
  on-background: '#e3e1e9'
  surface-variant: '#34343a'
typography:
  display-xl:
    fontFamily: Hanken Grotesk
    fontSize: 80px
    fontWeight: '800'
    lineHeight: 90px
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 20px
    fontWeight: '400'
    lineHeight: 32px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  label-mono:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.1em
  label-xs:
    fontFamily: Geist
    fontSize: 10px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.15em
spacing:
  container-max: 1280px
  section-gap: 160px
  margin-lg: 64px
  gutter: 32px
  stack-md: 24px
  stack-sm: 8px
---

## Brand & Style
JINOVER embodies **Precision Engineered Performance**. The brand personality is technical, elite, and futuristic, targeting serious golfers and tech-focused strategists who value data-driven improvement. 

The visual style is a hybrid of **Minimalist Industrial** and **Glassmorphism**. It utilizes a deep "Pitch Black" foundation to establish a premium, high-stakes atmosphere, punctuated by high-visibility "Cyber Lime" accents that signal advanced technology and digital integration. The interface feels like a high-end laboratory or a professional telemetry dashboard—precise, clean, and uncompromising.

## Colors
The palette is dominated by a dark-mode architecture. 
- **Primary (Cyber Lime):** Used exclusively for high-priority actions, data highlights, and technical indicators. It should "glow" against the dark background.
- **Backgrounds:** A tiered system of near-blacks (`#121318`) and pure blacks (`#000000`) creates depth.
- **Typography:** Uses high-contrast off-whites for readability and muted grays for secondary technical metadata.
- **Glass Effects:** Semi-transparent surfaces use a desaturated navy/gray base to maintain a "cool" temperature.

## Typography
The system uses a pairing of **Hanken Grotesk** for emotive, high-impact messaging and **Geist** for technical data and labels.
- **Display & Headlines:** Heavy weights (700-800) with tight letter spacing create a sense of authority and precision.
- **Body:** Generous line heights ensure readability in low-light environments.
- **Technical Labels:** Geist is used for "monospaced-feel" labels, lending a developer/engineer aesthetic to specs and tracking numbers. Use uppercase and wide letter spacing for these roles.

## Layout & Spacing
The layout follows a **Fixed-Width Centered** model for desktop, transitioning to a fluid single-column for mobile. 
- **Sectioning:** Large vertical gaps (160px) separate major content blocks to prevent visual clutter and emphasize the premium nature of the products.
- **Grids:** A standard 12-column grid is used for marketing content, while data tables and comparison charts use condensed internal spacing to reflect technical efficiency.
- **Margins:** Desktop uses 64px horizontal margins; Mobile drops to 24px.

## Elevation & Depth
Depth is achieved through **Glassmorphism** and **Primary Glows**:
- **Glass Cards:** Surfaces like navigation dropdowns and feature cards use `rgba(30, 31, 37, 0.7)` with a `12px` backdrop blur. Borders are ultra-thin (`1px`) and low-opacity (`white/5`).
- **Glow Effects:** Interactive elements (buttons, active sensors) utilize a soft `0 0 15px` outer glow in the primary color to simulate light emission.
- **Tiered Surfaces:** The background is the lowest level (`#121318`), while containers use slightly lighter shades (`#1e1f25`) to lift content without needing heavy shadows.

## Shapes
The shape language is primarily **Sharp and Geometric**, emphasizing industrial engineering. 
- **Buttons & Large Containers:** Use 0px (sharp) corners to maintain a "pro" look.
- **Utility Elements:** Smaller cards or "light" cards may use a micro-radius (2px-4px) to soften the UI just enough for touch ergonomics, but the overall system should feel rectangular and rigid.
- **Specialty Shapes:** Use horizontal "tech lines" (2px tall) and monospaced boxes to frame content sections.

## Components
- **Primary Button:** Square corners, solid Cyber Lime background, black label (Geist font, uppercase). Features a "primary-glow" on hover.
- **Ghost Button:** Square corners, thin border (`white/20`), white or lime label. Hover state adds a subtle background fill.
- **Technical Tables:** Dark backgrounds (`#1a1b21`) with thin divider lines (`white/5`). Active or "Winner" columns should have a subtle tint of the primary color.
- **Feature Tiles:** Large image-based tiles with a bottom-up black gradient overlay. Headlines within tiles use Cyber Lime.
- **Spec Chips:** Small rectangular boxes with uppercase Geist labels, used for showing technical metrics like "90°" or "Direct".
- **Glass Header:** Sticky header with `90%` opacity and heavy backdrop blur, featuring a thin bottom border to separate it from the scrolling content.

This website must use a single global Header and Footer across all pages.

Header Rules

Keep the exact same header design, layout, spacing, colors, typography, logo position, navigation structure, button styles, and interactions on every page.
Do not redesign, rearrange, resize, simplify, or enhance the header.
The header acts as a global component and must remain identical throughout the entire website.
Only the active menu state may change according to the current page.

Footer Rules

Keep the exact same footer design, layout, colors, spacing, typography, social icons, contact information, and link structure on every page.
Do not redesign or modify the footer under any circumstances.
The footer acts as a global component and must remain identical throughout the entire website.

Consistency Requirements

Treat Header and Footer as locked master components.
Any future page generation or design updates must preserve the Header and Footer exactly as originally created.
Changes are allowed only in the main content area between the Header and Footer.
Never create alternative versions of the Header or Footer.
Maintain pixel-perfect consistency across all pages.