---
name: Editorial Prime
colors:
  surface: '#fcf9f4'
  surface-dim: '#dcdad5'
  surface-bright: '#fcf9f4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3ee'
  surface-container: '#f1ede8'
  surface-container-high: '#ebe8e3'
  surface-container-highest: '#e5e2dd'
  on-surface: '#1c1c19'
  on-surface-variant: '#4c4546'
  inverse-surface: '#31302d'
  inverse-on-surface: '#f3f0eb'
  outline: '#7e7576'
  outline-variant: '#cfc4c5'
  surface-tint: '#5e5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1b1b1b'
  on-primary-container: '#848484'
  inverse-primary: '#c6c6c6'
  secondary: '#5e5e5c'
  on-secondary: '#ffffff'
  secondary-container: '#e1dfdc'
  on-secondary-container: '#636360'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#1b1c1c'
  on-tertiary-container: '#848484'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2e2e2'
  primary-fixed-dim: '#c6c6c6'
  on-primary-fixed: '#1b1b1b'
  on-primary-fixed-variant: '#474747'
  secondary-fixed: '#e4e2de'
  secondary-fixed-dim: '#c8c6c3'
  on-secondary-fixed: '#1b1c1a'
  on-secondary-fixed-variant: '#474744'
  tertiary-fixed: '#e4e2e2'
  tertiary-fixed-dim: '#c7c6c6'
  on-tertiary-fixed: '#1b1c1c'
  on-tertiary-fixed-variant: '#464747'
  background: '#fcf9f4'
  on-background: '#1c1c19'
  surface-variant: '#e5e2dd'
typography:
  display:
    fontFamily: DM Sans
    fontSize: 72px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: DM Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: DM Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: DM Sans
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Source Serif 4
    fontSize: 20px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Source Serif 4
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
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
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
  stack-sm: 16px
  stack-md: 32px
  stack-lg: 64px
---

## Brand & Style

The design system is built for high-end digital publishing, focusing on clarity, authority, and a premium reading experience. It targets creators, journalists, and professional curators who value content over decoration. 

The aesthetic is **Sophisticated Minimalism** with an **Editorial** edge. It mimics the tactile quality of high-fashion print magazines and broadsheet newspapers, translated into a modern digital interface. The emotional response should be one of calm focus, reliability, and timelessness. 

Key stylistic pillars:
- **High Contrast:** A binary color relationship that emphasizes readability.
- **Structured White Space:** Generous "air" around elements to prevent cognitive overload.
- **Precision:** Perfect alignment and purposeful use of scale to establish hierarchy without the need for decorative flourishes.

## Colors

The palette is strictly limited to ensure a cohesive editorial feel. 

- **Primary Background:** A rich, warm cream (`#FDFBF7`) serves as the canvas, reducing the eye strain associated with pure white backgrounds while maintaining a "paper" quality.
- **Primary Elements:** Solid black (`#000000`) is used for all primary text, icons, and high-emphasis UI components.
- **Secondary/Supporting:** A mid-tone grey (`#707070`) is used for metadata and secondary labels to create a subtle hierarchy.
- **Accents/Dividers:** A muted neutral (`#E5E2DD`) is used for thin borders and dividers to separate content sections without introducing heavy visual weight.

Interaction states:
- **Hover:** Solid black elements transition to a 90% opacity or a dark grey if depth is required.
- **Selection:** High-contrast inverse (Black background with Cream text).

## Typography

This design system utilizes a trio of typefaces to achieve a balanced editorial hierarchy:

1.  **Headlines (DM Sans):** A geometric sans-serif that provides a modern, clean, and bold structure for titles.
2.  **Body (Source Serif 4):** A highly legible serif font designed for long-form reading. It provides the "literary" feel essential for a newsletter platform.
3.  **Labels (Hanken Grotesk):** A sharp, contemporary sans-serif used for navigation, metadata, and buttons. 

**Usage Guidelines:**
- Maintain wide line-height (1.6x) for body text to ensure maximum readability.
- Use uppercase for labels and small metadata to create visual distinction from the body text.
- Headlines should use tight letter spacing for a more "locked-in" professional look.

## Layout & Spacing

The layout philosophy follows a **fixed-grid system** centered on the screen, with an emphasis on vertical rhythm.

- **Grid:** A 12-column grid for desktop with 24px gutters. For the reading experience, content is constrained to a 1-column central well (max 720px) to optimize line length.
- **Rhythm:** Spacing is based on an 8px base unit. Vertical stacks should be generous—use 64px (stack-lg) between major sections to emphasize the minimal, airy aesthetic.
- **Responsive:** 
    - **Desktop:** Wide margins (64px) and centered content.
    - **Tablet:** Margins reduce to 32px; 8-column grid.
    - **Mobile:** Margins reduce to 20px; 4-column grid. All typography scales down to maintain the viewport balance.

## Elevation & Depth

This design system avoids traditional shadows to maintain a flat, print-inspired aesthetic. 

- **Low-Contrast Outlines:** Instead of shadows, use 1px solid borders (`#E5E2DD`) to define card boundaries or input fields.
- **Tonal Layering:** Depth is communicated through color blocking rather than light and shadow. Elements "lifted" into focus should use a solid black background with cream text to stand out immediately against the cream canvas.
- **Z-Index:** Content layers are strictly flat. Modal overlays should use a semi-transparent cream backdrop blur to maintain the color story while directing focus.

## Shapes

The shape language is primarily **sharp and architectural**. 

- **Standard Radius:** 0.25rem (4px) is the maximum roundedness used for buttons and inputs. This provides a "softened sharp" feel that feels modern without being overly technical or "bubbly."
- **Editorial Cards:** Should remain perfectly sharp (0px) to mimic the edges of a page or newspaper column.
- **Interactive Elements:** Buttons utilize the 4px radius to provide a subtle tactile cue that they are "objects" separate from the static text content.

## Components

### Buttons
- **Primary:** Solid black background, cream text (`#FDFBF7`), 4px corner radius. No border. Text is set in Hanken Grotesk, Semi-Bold, Uppercase.
- **Secondary:** Transparent background, 1px solid black border, black text.
- **Hover State:** Primary buttons shift to 85% opacity. Secondary buttons fill solid black with cream text.

### Input Fields
- **Default:** Transparent background with a 1px solid black bottom border only (editorial style).
- **Active/Focus:** A full 1px solid black box with 4px corner radius.
- **Placeholder:** Mid-grey (`#707070`) serif text to contrast with user input.

### Cards
- **Newsletter Card:** No background or shadow. Defined by a 1px top-border (`#E5E2DD`) and generous vertical padding. 
- **Featured Card:** Solid cream background with a 1px solid black border to differentiate from the page surface.

### Chips & Tags
- Small, uppercase labels with a cream background and a 1px solid black border. No rounded corners (0px) to maintain the "tag" aesthetic.

### Lists
- Use thin (`1px`) dividers in `#E5E2DD`. Each list item should have a minimum height of 64px to maintain the airy layout.

### Newsletter Specifics
- **Subscription Bar:** A sticky element at the bottom or top of the viewport. Solid black background, cream input field with 4px radius, and a cream "Submit" button for maximum contrast inversion.