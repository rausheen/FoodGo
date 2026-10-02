---
name: Modern Epicurean
colors:
  surface: '#f9f9ff'
  surface-dim: '#d3daef'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f3ff'
  surface-container: '#e9edff'
  surface-container-high: '#e1e8fd'
  surface-container-highest: '#dce2f7'
  on-surface: '#141b2b'
  on-surface-variant: '#5c403a'
  inverse-surface: '#293040'
  inverse-on-surface: '#edf0ff'
  outline: '#916f68'
  outline-variant: '#e6bdb5'
  surface-tint: '#ba1c00'
  primary: '#b51b00'
  on-primary: '#ffffff'
  primary-container: '#de2e0f'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb4a5'
  secondary: '#505f76'
  on-secondary: '#ffffff'
  secondary-container: '#d0e1fb'
  on-secondary-container: '#54647a'
  tertiary: '#006947'
  on-tertiary: '#ffffff'
  tertiary-container: '#00855b'
  on-tertiary-container: '#f5fff6'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad3'
  primary-fixed-dim: '#ffb4a5'
  on-primary-fixed: '#3f0400'
  on-primary-fixed-variant: '#8e1300'
  secondary-fixed: '#d3e4fe'
  secondary-fixed-dim: '#b7c8e1'
  on-secondary-fixed: '#0b1c30'
  on-secondary-fixed-variant: '#38485d'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#f9f9ff'
  on-background: '#141b2b'
  surface-variant: '#dce2f7'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 56px
    fontWeight: '800'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.025em
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.025em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.005em
  title-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 22px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  margin: 2rem
  margin-sm: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style
The design system balances the high-octane speed of on-demand food delivery with the refined aesthetics of contemporary culinary curation. It conveys warmth, appetite appeal, instant gratification, and uncompromising quality. Designed for discerning urbanites, culinary explorers, and time-conscious food lovers, the system delivers an effortless, mouth-watering experience.

The visual style blends modern tactile minimalism with delicate atmospheric depth:
- **Warm Culinary Energy:** A vibrant, fiery-warm signature red-orange anchors user actions, sparking appetite without overwhelming.
- **Pristine Canvas:** Generous white space and soft, warm-tinted light neutral backgrounds allow high-resolution culinary photography to take center stage.
- **Refined Micro-Interactions:** Subtle floating cards, tactile pill toggles, and delicate hairline boundaries replace dense UI chrome to keep the ordering experience light, fluid, and delightful.

## Colors
The color architecture relies on a purposeful hierarchy to highlight food artistry, direct ordering actions, and convey diet and status indicators clearly.

- **Primary (`#FF4626`):** The signature warm orange/red. Reserved for primary conversion points (Add to Cart, Checkout, Primary Filters) and active navigation cues. Interacts with hover variant `#E03517` and bright accent `#FF5E3A`.
- **Secondary (`#64748B`):** Cool slate. Drives secondary metadata, structural icons, unselected states, and structural dividers.
- **Tertiary (`#10B981`):** Crisp emerald green. Denotes dietary assurance (Pure Vegetarian badges), successful transactional states, and promotional savings.
- **Neutral (`#111827`):** Deep charcoal. Provides contrast for headlines, restaurant titles, and prices, pairing with a soft canvas backdrop (`#F8F9FA` to `#FFFFFF`) rather than cold, stark monochrome.
- **Specialized Tokens:** Star rating gold (`#F59E0B`) for reviews, and non-veg marker ruby (`#DC2626`).

## Typography
The system pairs **Plus Jakarta Sans** for headlines with **Inter** for UI, technical body copy, and transactional microcopy.

- **Display & Headlines:** Plus Jakarta Sans offers geometric geometric precision with warm, contemporary curves that echo culinary indulgence while retaining structural authority.
- **Body & Controls:** Inter ensures maximum readability across variable nutritional labels, recipe descriptions, customizable add-on lists, and order checkout matrices.
- **Tabular Numerics:** Prices and countdown trackers must always apply font feature setting `"tnum"` to avoid visual jitter during live basket calculations and ETA updates.

## Layout & Spacing
The layout follows an 8pt spatial baseline with a responsive 12-column fluid grid on desktop, 8 columns on tablet, and 4 columns on mobile devices.

- **Desktop (>= 1024px):** Max container width `1280px` centered with `margin: 2rem` and `gutter: 1.5rem`. Enables 3-to-4 card restaurant grid arrays and persistent floating cart drawers.
- **Tablet (768px - 1023px):** 8-column layout with `gutter: 1rem` and `margin: 1.5rem`. Card grids collapse cleanly to 2 columns.
- **Mobile (< 768px):** 4-column layout with `margin-sm: 1rem` and `gutter-sm: 1rem`. Culinary dish cards shift to single-column or horizontal stacked cards with fixed media dimensions to facilitate easy one-handed thumbs-only interaction.

## Elevation & Depth
Depth conveys appetite focus and tactile response through clean floating surfaces and ambient, warm-tinted shadows:

- **Surface Neutral Layering:** The viewport ground rests at `#F8F9FA`. Cards, menu sheets, and contextual panels rise with crisp `#FFFFFF` backgrounds bordered by subtle, low-opacity outlines (`rgba(17, 24, 39, 0.06)`).
- **Resting Cards:** Low-elevation components use a soft, ambient drop: `0px 2px 8px -2px rgba(17, 24, 39, 0.04), 0px 1px 4px -1px rgba(17, 24, 39, 0.02)`.
- **Interactive / Hover Elevation:** Elevated cards lift using smooth CSS transitions: `0px 12px 24px -6px rgba(255, 70, 38, 0.08), 0px 4px 12px -2px rgba(17, 24, 39, 0.05)`. The warm primary tint in the shadow evokes lighting from the focal cuisine.
- **Floating Controls & Cart Bar:** Floating bottom sheets, persistent navigation, and sticky checkout summaries leverage: `0px 16px 36px -4px rgba(17, 24, 39, 0.12), 0px 0px 0px 1px rgba(17, 24, 39, 0.04)`.

## Shapes
A roundedness level of `2` provides an approachable, ergonomic geometry across all surfaces.

- **Cards & Dialogs (`rounded-xl` / 1.5rem / 24px):** Applied to restaurant showcase cards, dish detail sheets, and modal bottom containers.
- **Interactive Controls (`rounded-lg` / 1rem / 16px):** Standard text inputs, quantity pickers, and modifier groups.
- **Micro-Elements & Badges (Pill / Full-Radius):** Category filter chips, dietary tags (Veg/Non-Veg), promotional badges, and primary action buttons utilize pill contours (`9999px`) to create smooth finger-friendly touch targets.

## Components

### Buttons
- **Primary:** Full-pill silhouette, solid `#FF4626` background, `#FFFFFF` text (`label-lg`), with subtle inner highlight. On hover, smooth shift to `#E03517`. Focus states apply a 3px ring of `rgba(255, 70, 38, 0.3)`.
- **Secondary:** Surface `#FFFFFF`, border `1px solid rgba(17, 24, 39, 0.12)`, text `#111827`. Hover applies a `#F8F9FA` background.
- **Floating Cart / Action Trigger:** Sticky pill bar with saturated accent, price summary on the left, action cue on the right, floating above content with elevated ambient shadow.

### Chips & Category Filters
- Full pill form. Inactive state: `#FFFFFF` background, `1px solid rgba(17, 24, 39, 0.08)`, secondary icon, and `#64748B` typography.
- Active state: `#111827` dark fill with `#FFFFFF` text or `#FF4626` soft-wash fill (`rgba(255, 70, 38, 0.1)`) with `#FF4626` bold text.

### Dietary & Rating Badges
- **Veg Indicator:** Square container with a green outer outline (`1.5px solid #10B981`) encasing a solid green center circle (`#10B981`, 8px).
- **Non-Veg Indicator:** Square container with a ruby outer outline (`1.5px solid #DC2626`) encasing a solid ruby triangle (`#DC2626`).
- **Rating Chip:** Soft yellow/amber background (`rgba(245, 158, 11, 0.12)`), solid gold star icon (`#F59E0B`), and `#111827` bold rating value.

### Restaurant & Menu Cards
- Clean `#FFFFFF` base with `16px - 20px` corner radius.
- Imagery fills the top perimeter edge-to-edge or rests in an inner rounded canvas with 1:1 or 16:9 aspect ratios.
- Overlay badges (ETA, Discount Tags) sit float-pinned 12px from card edges with a frosted glass backing (`backdrop-filter: blur(8px)`, `background: rgba(255, 255, 255, 0.85)`).

### Input Fields & Steppers
- Form inputs feature an inset background `#F8F9FA`, border `1px solid rgba(17, 24, 39, 0.08)`, transition to `#FFFFFF` with primary border `#FF4626` on focus.
- Add-to-cart quantity stepper: Pill-shaped segmented control with decrement (`-`), bold quantity digit, and increment (`+`), styled in high-contrast primary orange.