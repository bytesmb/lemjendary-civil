---
name: Botanical Heritage
colors:
  surface: '#fafaf4'
  surface-dim: '#dadad5'
  surface-bright: '#fafaf4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f4ee'
  surface-container: '#eeeee8'
  surface-container-high: '#e9e8e3'
  surface-container-highest: '#e3e3dd'
  on-surface: '#1a1c19'
  on-surface-variant: '#434840'
  inverse-surface: '#2f312d'
  inverse-on-surface: '#f1f1eb'
  outline: '#73796f'
  outline-variant: '#c3c8bd'
  surface-tint: '#496640'
  primary: '#334f2b'
  on-primary: '#ffffff'
  primary-container: '#4a6741'
  on-primary-container: '#c2e4b4'
  inverse-primary: '#afd0a1'
  secondary: '#795830'
  on-secondary: '#ffffff'
  secondary-container: '#fdcf9d'
  on-secondary-container: '#78572f'
  tertiary: '#663a4e'
  on-tertiary: '#ffffff'
  tertiary-container: '#815166'
  on-tertiary-container: '#ffcde0'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#caecbc'
  primary-fixed-dim: '#afd0a1'
  on-primary-fixed: '#062104'
  on-primary-fixed-variant: '#324e2a'
  secondary-fixed: '#ffddb9'
  secondary-fixed-dim: '#ebbf8e'
  on-secondary-fixed: '#2b1700'
  on-secondary-fixed-variant: '#5f411a'
  tertiary-fixed: '#ffd8e6'
  tertiary-fixed-dim: '#f2b6ce'
  on-tertiary-fixed: '#330e21'
  on-tertiary-fixed-variant: '#65394d'
  background: '#fafaf4'
  on-background: '#1a1c19'
  surface-variant: '#e3e3dd'
typography:
  display-names:
    fontFamily: Playfair Display
    fontSize: 42px
    fontWeight: '300'
    lineHeight: '1.2'
    letterSpacing: 0.1em
  display-names-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '300'
    lineHeight: '1.2'
    letterSpacing: 0.08em
  headline-section:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '400'
    lineHeight: '1.4'
    letterSpacing: 0.05em
  body-invitation:
    fontFamily: EB Garamond
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Montserrat
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.5'
    letterSpacing: 0.2em
  button-text:
    fontFamily: Montserrat
    fontSize: 13px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.15em
spacing:
  page-margin: 2rem
  section-gap: 4rem
  element-gap: 1.5rem
  inline-padding: 1rem
---

## Brand & Style
The brand personality is sophisticated, timeless, and deeply rooted in organic elegance. Targeted at high-end, curated wedding experiences, the UI evokes a sense of calm, prestige, and intimate celebration. 

The design style is a blend of **Minimalism** and **Tactile** aesthetics. It utilizes heavy whitespace to create an "airy" feel, reminiscent of high-quality physical stationery. The interface should feel less like a digital app and more like a hand-pressed parchment invitation. Key visual signatures include generous margins, subtle paper textures, and the use of fine-line botanical illustrations to frame content.

## Colors
The palette is centered on a deep **Forest Green** primary, symbolizing growth and tradition. This is set against a **Parchment** background which must be implemented with a subtle noise/grain texture overlay (2-3% opacity) to mimic paper stock.

- **Primary (#4A6741):** Used for headings, primary buttons, and intricate monogram assets.
- **Secondary/Gold Accent (#C2996B):** A muted metallic used sparingly for dividers or special decorative elements.
- **Background (#F5F0E8):** The foundational "paper" of the interface.
- **Neutral/Charcoal (#2D2D2D):** Used for body text to ensure high legibility against the off-white background.

## Typography
The typography system is the core of this design system’s elegance. 

- **Display (Playfair Display):** Should be used for the names of the couple. It is intentionally thin and wide-spaced to evoke luxury editorial design.
- **Body (EB Garamond):** Used exclusively in italics for invitation copy, RSVP details, and personal notes to simulate the flow of traditional calligraphy without sacrificing readability.
- **Accent (Montserrat):** A clean, geometric sans-serif used for utilitarian data like dates, times, and navigation. It must always be presented in uppercase with generous letter spacing to provide a modern "anchor" to the classic serifs.

## Layout & Spacing
The layout follows a **Fixed Grid** philosophy centered within the viewport. On mobile, the side margins are unusually wide (32px) to frame the content like a card.

- **Verticality:** Sections are separated by significant vertical gaps (64px+) to allow the botanical assets and typography "room to breathe."
- **Alignment:** Central alignment is the default for all primary invitation elements. Left-aligned layouts are reserved for dense information like hotel lists or registries.
- **Mobile Reflow:** For mobile, the display typography scales down to prevent awkward line breaks, while the body text remains large for accessibility.

## Elevation & Depth
This design system avoids traditional box-shadows. Instead, it uses **Tonal Layers** and **Low-Contrast Outlines**.

- **Surfaces:** Depth is achieved by placing a secondary surface (a slightly lighter parchment or a very thin Forest Green border) on top of the textured background.
- **Interactive Elements:** Buttons do not "float"; they are flat fills or ghost borders.
- **Dividers:** Use thin (0.5px) Forest Green lines or small botanical ornaments to separate sections rather than shadow-based containers.

## Shapes
The shape language is **Sharp (0)**. Square corners are used for buttons, input fields, and image containers to mimic the precision of custom-cut cardstock and high-end stationery. Rounded corners are strictly prohibited except for circular monogram frames or specific decorative botanical masks.

## Components
- **Buttons:** Primary buttons are solid Forest Green with white or parchment uppercase text. Secondary buttons are "Ghost" style with a 1px Forest Green border and no fill.
- **Input Fields:** Minimalist design—bottom-border only (1px Forest Green) with `label-caps` typography floating above.
- **Cards:** Content blocks for "Schedule" or "Travel" should not have backgrounds. They are defined by generous padding and thin horizontal separators.
- **Chips/Labels:** Used for dietary requirements or attendance status, these should be small, centered text with a very light Forest Green tint background (10% opacity).
- **Monograms:** A signature component. A central circular or shield-shaped vector asset using the primary color, placed at the top of the landing experience.
- **Botanical Dividers:** Decorative SVGs (vines, leaves) used as section breaks to reinforce the forest theme.