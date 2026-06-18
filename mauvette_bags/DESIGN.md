---
name: Mauvette BAGS
colors:
  surface: '#fbf9f5'
  surface-dim: '#dbdad6'
  surface-bright: '#fbf9f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3ef'
  surface-container: '#efeeea'
  surface-container-high: '#eae8e4'
  surface-container-highest: '#e4e2de'
  on-surface: '#1b1c1a'
  on-surface-variant: '#4f453f'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f0ed'
  outline: '#81756e'
  outline-variant: '#d2c4bc'
  surface-tint: '#705a4c'
  primary: '#26170c'
  on-primary: '#ffffff'
  primary-container: '#3d2b1f'
  on-primary-container: '#ac9181'
  inverse-primary: '#dec1af'
  secondary: '#775a19'
  on-secondary: '#ffffff'
  secondary-container: '#fed488'
  on-secondary-container: '#785a1a'
  tertiary: '#211910'
  on-tertiary: '#ffffff'
  tertiary-container: '#372d24'
  on-tertiary-container: '#a39487'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#fbddca'
  primary-fixed-dim: '#dec1af'
  on-primary-fixed: '#28180d'
  on-primary-fixed-variant: '#574335'
  secondary-fixed: '#ffdea5'
  secondary-fixed-dim: '#e9c176'
  on-secondary-fixed: '#261900'
  on-secondary-fixed-variant: '#5d4201'
  tertiary-fixed: '#f1dfd1'
  tertiary-fixed-dim: '#d4c4b6'
  on-tertiary-fixed: '#231a11'
  on-tertiary-fixed-variant: '#50453a'
  background: '#fbf9f5'
  on-background: '#1b1c1a'
  surface-variant: '#e4e2de'
typography:
  display-lg:
    fontFamily: Bodoni Moda
    fontSize: 64px
    fontWeight: '400'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Bodoni Moda
    fontSize: 40px
    fontWeight: '400'
    lineHeight: '1.2'
  headline-lg:
    fontFamily: Bodoni Moda
    fontSize: 40px
    fontWeight: '400'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Bodoni Moda
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Bodoni Moda
    fontSize: 28px
    fontWeight: '400'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Montserrat
    fontSize: 18px
    fontWeight: '300'
    lineHeight: '1.6'
    letterSpacing: 0.01em
  body-md:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Montserrat
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.1em
  caption:
    fontFamily: Montserrat
    fontSize: 11px
    fontWeight: '400'
    lineHeight: '1.4'
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
  section-gap: 120px
---

## Brand & Style

The design system embodies the essence of "Lujo Silencioso" (Quiet Luxury)—an artisanal approach to digital retail that prioritizes restraint over excess. The target audience is the discerning collector who values craftsmanship, provenance, and the intimate story of a small leather atelier.

The aesthetic is a sophisticated blend of **Minimalism** and **Editorial Design**. It draws inspiration from high-end print magazines, utilizing expansive whitespace to create a "gallery" atmosphere where the products are treated as art pieces. The interface should feel tactile and breathable, evoking the sensory experience of running a hand over premium grain leather. The emotional response is one of calm, exclusivity, and enduring quality.

## Colors

The palette is rooted in organic, earthy tones that mirror the raw materials of the atelier. 

- **Primary (Espresso):** Used for primary text and high-importance UI elements to provide depth.
- **Secondary (Brushed Gold):** Reserved for subtle highlights, interactive states, and "hardware-inspired" accents.
- **Backgrounds (Cream & Bone):** These two shades should be layered to create subtle distinction between sections without using harsh dividers. Use Cream for the main canvas and Bone for container backgrounds or secondary sections.
- **Accents (Taupe & Sand):** Used for secondary UI elements, borders, and disabled states.
- **Text (Near Black):** Used sparingly for maximum legibility on high-contrast editorial blocks.

## Typography

Typography is the primary vehicle for the brand’s editorial voice. 

- **Bodoni Moda** provides a high-contrast, vertical stress that communicates luxury and history. Use this for all major headings and "moment" text.
- **Montserrat** is utilized for its clean, geometric qualities. To maintain the premium feel, use lighter weights (300/400) for body copy and medium/semibold for functional labels.
- **Hierarchy:** Ensure generous leading (line height) for body text to improve readability and perceived value. Use uppercase styling with wide letter-spacing for navigation and buttons to evoke the feeling of a fashion house logotype.

## Layout & Spacing

The layout follows a **Fixed Grid** approach on desktop to maintain the integrity of editorial compositions, shifting to a fluid model for smaller viewports.

- **Grid:** A 12-column grid is used for the shop and gallery layouts. Large-scale imagery should often break the grid or occupy significant real estate (e.g., 8 columns for an image, 4 for description).
- **Whitespace:** Emphasize "Aire" (Air). Sections should be separated by significant vertical gaps (`section-gap`) to allow the user to focus on one product story at a time.
- **Dividers:** When necessary, use 1px horizontal lines in `#D2B48C` (Sand) with 50% opacity. Avoid boxing content; prefer open-sided layouts.

## Elevation & Depth

To maintain a "Quiet Elegance," depth is created through **Tonal Layers** rather than heavy shadows.

- **Surfaces:** Use subtle shifts between `#FDFBF7` and `#F9F6F2` to define hierarchy. 
- **Shadows:** Use only one type of shadow—an "Ambient Glow." It should be extremely soft, using the Espresso color at 5-8% opacity with a large blur (20-30px) and 0 offset. This makes elements like "Carrito" (Cart) drawers feel like they are gently resting on the surface.
- **Glass:** A light backdrop blur (4px) can be used on the navigation header when scrolling to maintain a sense of layered transparency without looking overly "techy."

## Shapes

The shape language is refined and soft. Sharp edges are avoided to reflect the supple nature of leather, yet perfectly circular corners are avoided to keep the look "Atelier-made" rather than "App-like."

- **Base Radius:** 4px to 8px for buttons and input fields.
- **Product Cards:** Should have no border, using a subtle background color shift to define their area.
- **Icons:** Use thin-stroke (1px or 1.5px) line icons with slightly rounded caps to match the typography.

## Components

- **Botones (Buttons):** 
    - *Primario:* Espresso background, White text, uppercase, 8px radius. High-width padding.
    - *Secundario:* Transparent background, 1px Espresso border.
    - *Hardware:* Tiny Brushed Gold accents for "Añadir al Carrito" buttons.
- **Campos de Entrada (Inputs):** Minimalist style. Only a bottom border (1px) in Taupe, which turns to Espresso on focus. Labels sit above in uppercase Montserrat 12px.
- **Fichas de Producto (Product Cards):** Large photography is the hero. The price and title should be center-aligned below the image in Bodoni Moda.
- **Selector de Color (Chips):** Small circular swatches with a 2px offset border when selected to indicate the specific leather hide.
- **Navegación:** A centered logo with links split to the left and right. Use a "hover" effect that displays a simple thin underline in Gold.
- **Boutique Elements:** Include a "Certificado de Autenticidad" badge component and "Detalles del Artesano" expandable lists.