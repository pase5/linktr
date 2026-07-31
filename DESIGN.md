---
name: Neo-Editorial Portfolio
colors:
  surface: '#fcfaeb'
  surface-dim: '#dddacc'
  surface-bright: '#fcfaeb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f7f4e5'
  surface-container: '#f1eee0'
  surface-container-high: '#ebe8da'
  surface-container-highest: '#e5e3d5'
  on-surface: '#1c1c13'
  on-surface-variant: '#474837'
  inverse-surface: '#313127'
  inverse-on-surface: '#f4f1e3'
  outline: '#787865'
  outline-variant: '#c9c8b1'
  surface-tint: '#5e6300'
  primary: '#5e6300'
  on-primary: '#ffffff'
  primary-container: '#e8f06c'
  on-primary-container: '#676d00'
  inverse-primary: '#c6ce4e'
  secondary: '#4d6544'
  on-secondary: '#ffffff'
  secondary-container: '#cce8be'
  on-secondary-container: '#516948'
  tertiary: '#586152'
  on-tertiary: '#ffffff'
  tertiary-container: '#e2ebd8'
  on-tertiary-container: '#626a5b'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2ea67'
  primary-fixed-dim: '#c6ce4e'
  on-primary-fixed: '#1b1d00'
  on-primary-fixed-variant: '#464a00'
  secondary-fixed: '#cfebc1'
  secondary-fixed-dim: '#b3cea6'
  on-secondary-fixed: '#0b2006'
  on-secondary-fixed-variant: '#364d2e'
  tertiary-fixed: '#dde6d3'
  tertiary-fixed-dim: '#c0c9b7'
  on-tertiary-fixed: '#161e12'
  on-tertiary-fixed-variant: '#41493b'
  background: '#fcfaeb'
  on-background: '#1c1c13'
  surface-variant: '#e5e3d5'
typography:
  display:
    fontFamily: Anton
    fontSize: 80px
    fontWeight: '400'
    lineHeight: '1.0'
    letterSpacing: 0.02em
  headline-lg:
    fontFamily: Anton
    fontSize: 48px
    fontWeight: '400'
    lineHeight: '1.1'
    letterSpacing: 0.02em
  headline-lg-mobile:
    fontFamily: Anton
    fontSize: 36px
    fontWeight: '400'
    lineHeight: '1.1'
    letterSpacing: 0.02em
  headline-md:
    fontFamily: Anton
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.2'
    letterSpacing: 0.02em
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '500'
    lineHeight: '1.6'
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-bold:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.2'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 40px
  xl: 64px
  container-max: 640px
  gutter: 16px
---

## Brand & Style

This design system merges the structural impact of **Neo-Brutalism** with the refined spacing of **Editorial Minimalism**. It is designed for creative professionals, developers, and curators who require a high-impact "link-in-bio" or personal portfolio that feels both authoritative and approachable.

The aesthetic relies on "Soft Neo-Brutalism": it utilizes the heavy strokes and bold typography of traditional brutalism but softens the aggression with oversized corner radii, lush organic colors, and sophisticated whitespace. The goal is to evoke a sense of high-end curation and modern technical proficiency.

## Colors

The palette is anchored by a high-visibility **Lime (#E8F06C)** used for primary actions and highlights, contrasted against a deep **Forest Green (#23391C)** for grounding elements and text.

- **Primary Lime**: Used for "Look at Me" moments—buttons, active states, and focus indicators.
- **Primary Green**: Used for primary text and high-contrast containers.
- **Surface Green (#DCE5D2)**: Used for subtle card backgrounds to provide a soft, organic feel that differentiates from pure white.
- **Black/White**: Reserved for absolute clarity and deep shadows.

## Typography

The typographic system relies on a "Loud & Clear" hierarchy. **Anton** provides the brutalist impact for headings, while **Manrope** ensures the body content remains sophisticated and legible.

Headings should always be treated as graphic elements. Use tight line-heights for display text to create a dense, editorial block feel. Body text should maintain generous tracking and leading to balance the visual weight of the headings.

## Layout & Spacing

The design system follows a **Fixed Central Column** layout, optimized for mobile-first consumption (Linktree style) but expanding gracefully for desktop viewing. 

- **Mobile**: Single column with 16px horizontal safe-margins.
- **Desktop**: Content is constrained to a 640px max-width container, centered on the screen to maintain the "card-stack" feel.
- **Rhythm**: Use the `lg` (40px) spacing unit between major card components to create an airy, editorial flow.

## Elevation & Depth

This system eschews traditional soft shadows in favor of **Hard Strokes** and **Tonal Layering**. 

1.  **Level 0 (Background)**: Solid `#F4F7F0` surface.
2.  **Level 1 (Cards)**: White or `#DCE5D2` surfaces with a 2px solid `#23391C` border.
3.  **Level 2 (Interactive)**: Elements use a "Hard Shadow" (Neo-brutalist style)—a 4px or 8px offset shadow with 100% opacity using the Primary Green color. This creates a tactile, "clickable" physical appearance.
4.  **Glass**: Occasional use of backdrop-blur (20px) on navigation headers to maintain the modern editorial edge.

## Shapes

The shape language is defined by **Exaggerated Roundness**. While the borders are brutalist and hard, the corners are extremely soft to make the UI feel friendly and premium.

- **Standard Cards**: 24px corner radius.
- **Buttons & Chips**: 36px (fully pill-shaped) to contrast against the rectangular grid of the cards.
- **Inputs**: 16px corner radius for a slightly more structured feel.

## Components

### Buttons
- **Primary**: Lime (#E8F06C) background, 2px Primary Green border, 8px hard shadow. Text in Anton (Headline-MD).
- **Secondary**: Transparent background, 2px Primary Green border, no shadow until hover.

### Cards (The Core Unit)
- Every "Link" or "Project" is housed in a card. 
- Use a 2px solid Primary Green stroke. 
- Padding should be generous (24px or 32px) to allow typography to breathe.

### Chips / Tags
- Small pill-shaped containers with #DCE5D2 backgrounds.
- Used for categories or skills. Text in Label-Bold.

### Input Fields
- White background, 2px Primary Green stroke.
- On focus, the stroke remains 2px but the card gains the Primary Lime hard shadow.

### Lists
- Items in a list should be separated by 2px horizontal lines. 
- Use "Leading Icons" inside Lime circles for high-visibility navigation.