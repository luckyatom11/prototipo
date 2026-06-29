---
name: Sandoichi POS
colors:
  surface: '#fbfbe2'
  surface-dim: '#dbdcc3'
  surface-bright: '#fbfbe2'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f5dc'
  surface-container: '#efefd7'
  surface-container-high: '#eaead1'
  surface-container-highest: '#e4e4cc'
  on-surface: '#1b1d0e'
  on-surface-variant: '#46483b'
  inverse-surface: '#303221'
  inverse-on-surface: '#f2f2d9'
  outline: '#767869'
  outline-variant: '#c6c8b6'
  surface-tint: '#54651e'
  primary: '#52621c'
  on-primary: '#ffffff'
  primary-container: '#6a7c32'
  on-primary-container: '#fbffe4'
  inverse-primary: '#bbcf7c'
  secondary: '#775a00'
  on-secondary: '#ffffff'
  secondary-container: '#fec72c'
  on-secondary-container: '#6f5400'
  tertiary: '#76553d'
  on-tertiary: '#ffffff'
  tertiary-container: '#926d54'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d7ec95'
  primary-fixed-dim: '#bbcf7c'
  on-primary-fixed: '#161e00'
  on-primary-fixed-variant: '#3d4c05'
  secondary-fixed: '#ffdf98'
  secondary-fixed-dim: '#f5bf22'
  on-secondary-fixed: '#251a00'
  on-secondary-fixed-variant: '#5a4300'
  tertiary-fixed: '#ffdcc6'
  tertiary-fixed-dim: '#eabda0'
  on-tertiary-fixed: '#2d1604'
  on-tertiary-fixed-variant: '#5f402a'
  background: '#fbfbe2'
  on-background: '#1b1d0e'
  surface-variant: '#e4e4cc'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Work Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Work Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-lg:
    fontFamily: Work Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-md:
    fontFamily: Work Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
  headline-md-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  gutter: 16px
  margin-mobile: 16px
  margin-desktop: 24px
  container-padding: 20px
---

## Brand & Style
The brand personality is friendly, warm, and clean, inspired by Japanese-style sandwich shops. It balances the efficiency of a Point-of-Sale (POS) system with an approachable, artisanal aesthetic. 

The design style is a blend of **Modern Minimalism** and **Tactile Design**. It utilizes high-quality typography and generous whitespace for legibility in fast-paced environments, while employing subtle borders and structured rectangular elements to evoke a sense of physical order and reliability. The goal is to create an emotional response of comfort and professional clarity.

## Colors
The palette is derived from natural, culinary tones. 
- **Olive Green (#708238)**: Used for primary actions, success states, and brand highlights.
- **Mustard Yellow (#E1AD01)**: Used for secondary actions, warnings, or highlighting specific order status modifiers.
- **Coffee Brown (#6F4E37)**: The primary color for text, iconography, and structural borders, providing a softer alternative to pure black.
- **Cream Background (#F5F5DC)**: The foundation of the UI, creating a warm, paper-like feel that reduces eye strain compared to stark white.

## Typography
Typography is optimized for rapid scanning. **Plus Jakarta Sans** provides a friendly, contemporary feel for headlines and totals. **Work Sans** is used for tabular data (the order list) and labels due to its professional, grounded character and excellent legibility at smaller sizes.

Numerical values (prices and quantities) should always use a medium or bold weight to ensure they stand out within the grid layout.

## Layout & Spacing
The layout uses a **Fluid Grid** system to maximize the utility of tablet and desktop screens used in POS environments. 

- **Grid Model**: A 12-column grid for desktop/tablet landscapes.
- **Order List**: Occupies the central top area (6-8 columns) as shown in the sketch, utilizing a structured table format.
- **Action Zone**: The bottom area is reserved for high-frequency rectangular buttons (e.g., Cancel, Multi-pay), grouped logically by function.
- **Rhythm**: An 8px baseline grid ensures consistent vertical alignment. Large touch targets are prioritized, with minimum button heights of 56px to accommodate rapid tactile input.

## Elevation & Depth
This design system uses **Tonal Layers** and **Low-contrast outlines** rather than heavy shadows to maintain a clean, "Japanese stationery" aesthetic.

- **Primary Surface**: The Cream background.
- **Secondary Surface (Order List/Inputs)**: White containers with a 1px solid Coffee Brown border (#6F4E37 at 20% opacity).
- **Interactive Elements**: Buttons use solid color fills. High-priority items (like the Total amount) may use a subtle 2px border to emphasize importance without adding visual noise.

## Shapes
Following the sketch's visual language, the system uses **Soft (1)** roundedness. Rectangular buttons and containers feature a 0.25rem (4px) corner radius. This creates a clean, architectural look that feels "friendly" without becoming too playful or bubbly, maintaining the professional requirement of a POS tool.

## Components
- **Buttons**: Strict rectangular shapes. Primary buttons (Pay, Complete) use Olive Green with white text. Destructive actions (Cancel) use a Coffee Brown outline. Auxiliary actions use Mustard Yellow.
- **Order Table**: Rows should have a minimum height of 48px. Use alternating row tints or subtle dividers in Coffee Brown (10% opacity) to guide the eye.
- **Input Fields (ID de Producto)**: Rectangular fields with a 1px Coffee Brown border. Labels sit above the input in `label-md`.
- **Total Display**: A large, prominent rectangular box (as seen in the sketch) using `headline-lg` typography to ensure the final price is the most visible element on the screen.
- **Chips/Status**: Small rectangular tags with Mustard Yellow backgrounds to denote "Pendientes" (Pending) items.