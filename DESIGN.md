---
name: Cinematic Orthopedic
colors:
  surface: '#111415'
  surface-dim: '#111415'
  surface-bright: '#373a3b'
  surface-container-lowest: '#0c0f10'
  surface-container-low: '#191c1d'
  surface-container: '#1d2021'
  surface-container-high: '#282a2b'
  surface-container-highest: '#323536'
  on-surface: '#e1e3e4'
  on-surface-variant: '#c4c6cf'
  inverse-surface: '#e1e3e4'
  inverse-on-surface: '#2e3132'
  outline: '#8e9099'
  outline-variant: '#44474e'
  surface-tint: '#b2c7f5'
  primary: '#b2c7f5'
  on-primary: '#1a3055'
  primary-container: '#001a3f'
  on-primary-container: '#6f84ae'
  inverse-primary: '#4a5e87'
  secondary: '#adc6ff'
  on-secondary: '#002e69'
  secondary-container: '#0158bc'
  on-secondary-container: '#c3d5ff'
  tertiary: '#ffb780'
  on-tertiary: '#4e2600'
  tertiary-container: '#2f1400'
  on-tertiary-container: '#ba7236'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d7e2ff'
  primary-fixed-dim: '#b2c7f5'
  on-primary-fixed: '#001a3f'
  on-primary-fixed-variant: '#32476d'
  secondary-fixed: '#d8e2ff'
  secondary-fixed-dim: '#adc6ff'
  on-secondary-fixed: '#001a41'
  on-secondary-fixed-variant: '#004494'
  tertiary-fixed: '#ffdcc4'
  tertiary-fixed-dim: '#ffb780'
  on-tertiary-fixed: '#2f1400'
  on-tertiary-fixed-variant: '#6f3800'
  background: '#111415'
  on-background: '#e1e3e4'
  surface-variant: '#323536'
  divider-gold: '#f4a261'
  clinical-white: '#ffffff'
  surface-dark: '#000a18'
  glass-border: rgba(255, 255, 255, 0.1)
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 64px
    fontWeight: '800'
    lineHeight: 72px
    letterSpacing: 0.05em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: 0.05em
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 42px
  headline-md:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: 0.05em
  body-lg:
    fontFamily: Montserrat
    fontSize: 20px
    fontWeight: '300'
    lineHeight: 32px
  body-md:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Montserrat
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.2em
  label-sm:
    fontFamily: Montserrat
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.1em
spacing:
  unit: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  gutter-desktop: 24px
  margin-mobile: 20px
  margin-desktop: 64px
---

## Brand & Style
The brand identity is rooted in **Elite Clinical Expertise**, blending the precision of high-end medical care with a "luxury performance" aesthetic. The style is a sophisticated mix of **Glassmorphism** and **High-Contrast Minimalism**, utilizing a dark, cinematic atmosphere to evoke trust, authority, and modernism.

The visual narrative focuses on "Restored Movement" through dramatic lighting, deep shadows, and sharp, gold-accented focal points. It targets a discerning audience seeking specialized therapy, moving away from sterile medical tropes toward a premium, athletic, and results-oriented environment.

## Colors
The palette is dominated by a **Deep Midnight Base** (#001a3f to black), providing a high-contrast foundation for content. 

- **Primary & Secondary:** Utilize deep blues and vibrant electric blues to maintain a professional, clinical "tech" feel.
- **Accent (Gold):** The "Divider Gold" (#f4a261) is used sparingly for critical actions, status indicators, and highlights, symbolizing precision and high value.
- **Backgrounds:** A mix of true black and near-black gradients creates a sense of infinite depth.
- **Glass Effects:** Semi-transparent whites and blues are used for floating elements to maintain legibility without breaking the background immersion.

## Typography
The system uses **Montserrat** exclusively to achieve a clean, geometric, and authoritative look. 

- **Headlines:** Use heavy weights (700-800) and uppercase styling to create a bold "editorial" impact. High letter spacing is applied to maintain clarity and premium feel.
- **Body:** Uses lighter weights (300-400) to contrast against the heavy headers, ensuring the text feels breathable and modern.
- **Labels:** Heavily tracked (letter-spaced) and uppercase, used for navigation and small metadata to reinforce the technical/precise nature of the brand.

## Layout & Spacing
The layout follows a **Fluid Grid** with generous vertical rhythm to emphasize the premium nature of the content.

- **Grid:** A 12-column desktop grid with 24px gutters. Content is often placed asymmetrically to create a dynamic, modern feel (e.g., 7-column vs 5-column splits).
- **Safe Areas:** Large side margins (64px desktop) ensure the content feels centered and focused.
- **Vertical Rhythm:** Sections are separated by significant "breathing room" (80px to 128px) to prevent the dark UI from feeling cramped.
- **Mobile Adaptivity:** Breakpoints at 768px and 1024px. On mobile, margins reduce to 20px and asymmetric grids collapse into a single vertical stack.

## Elevation & Depth
Depth is created through **Atmospheric Layering** rather than traditional shadows:

- **Glassmorphism:** Navigation and badges use `backdrop-filter: blur(20px)` combined with a low-opacity white border (10%) to sit "above" the background imagery.
- **Glows:** Instead of drop shadows, "Gold" elements use subtle outer glows (`box-shadow: 0 0 20px #F4A261`) to suggest light emission in the dark environment.
- **Gradient Overlays:** Images are anchored into the layout using multi-directional gradients (Dark blue to Black) to ensure text legibility and visual integration.
- **Tonal Separation:** Cards use a subtle `white/5` or `primary/30` background to distinguish themselves from the absolute black page background.

## Shapes
The shape language is primarily **Sharp and Architectural**, utilizing 0px radius for most structural elements (cards, large buttons, image containers) to convey precision and clinical rigor.

- **Exceptions:** Pill shapes (fully rounded) are reserved strictly for small "status" badges and secondary "chip" style indicators to provide a visual break from the otherwise rigid grid.
- **Borders:** Thin (1px) borders are used extensively on cards and buttons to define shape within the dark environment.

## Components

### Buttons
- **Primary:** Background in `divider-gold`, text in black, sharp corners. Features a hover effect that shifts to white with a significant gold glow.
- **Secondary/Ghost:** Transparent background with a `divider-gold` border. Text in gold.
- **Action Links:** Label-sm typography with a small `arrow_outward` icon and a gold hover state.

### Cards
- **Service Cards:** Semi-transparent (`white/5`) background with a thin `white/10` border. Sharp corners. Content is heavily padded (40px).
- **Asymmetric Image Cards:** Use a grayscale/high-contrast filter on images with a gradient overlay that reveals text on hover.

### Navigation
- **Floating Header:** 30% black background with high blur. 1px bottom border. Links use `label-md` uppercase typography.

### Input Fields & Controls
- **Style:** Underlined or minimally bordered (1px) with high-contrast text. Focus states should utilize the `divider-gold` for the border color to maintain consistency.

### Badges
- **Expertise Chips:** Pill-shaped, semi-transparent background with a gold "live" dot indicator. Used to categorize content or highlight specialties.