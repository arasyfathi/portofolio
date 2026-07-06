---
name: Luminous Developer Portfolio
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#c5c9ac'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#8f9378'
  outline-variant: '#444932'
  surface-tint: '#b0d500'
  primary: '#ffffff'
  on-primary: '#2a3400'
  primary-container: '#caf300'
  on-primary-container: '#596c00'
  inverse-primary: '#536600'
  secondary: '#c8c6c5'
  on-secondary: '#303030'
  secondary-container: '#474746'
  on-secondary-container: '#b7b5b4'
  tertiary: '#ffffff'
  on-tertiary: '#1b343d'
  tertiary-container: '#cde7f3'
  on-tertiary-container: '#506873'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#caf300'
  primary-fixed-dim: '#b0d500'
  on-primary-fixed: '#171e00'
  on-primary-fixed-variant: '#3e4c00'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1b1b1c'
  on-secondary-fixed-variant: '#474746'
  tertiary-fixed: '#cde7f3'
  tertiary-fixed-dim: '#b1cad7'
  on-tertiary-fixed: '#041e28'
  on-tertiary-fixed-variant: '#324a54'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
  pure-white: '#FFFFFF'
  surface-border: rgba(255, 255, 255, 0.1)
  lime-glow: rgba(212, 255, 0, 0.25)
  text-muted: '#A1A1AA'
typography:
  display-xl:
    fontFamily: Hanken Grotesk
    fontSize: 72px
    fontWeight: '800'
    lineHeight: 80px
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
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
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
  label-mono:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 24px
  section-gap: 120px
  element-gap: 16px
---

## Brand & Style
The design system is engineered for a high-end Full-stack and Mobile Developer portfolio, targeting tech recruiters, potential clients, and the developer community. The brand personality is **technical, precise, and visionary**, projecting an image of an engineer who masters both the deep logic of the backend and the polished aesthetics of the frontend.

The visual style is **Modern Tech-Noir**, blending high-contrast minimalism with glassmorphism and subtle neon accents. It utilizes a sophisticated dark theme to reduce eye strain during technical reviews while using vibrant lime green highlights to guide the user's eye to key achievements and calls to action. The aesthetic is intentionally "bleeding-edge," reflecting a mastery of modern web technologies.

## Colors
The palette is built on a foundation of deep, layered blacks to create a sense of infinite depth.
- **Primary (#D4FF00):** A vivid lime green used exclusively for highlights, interactive states, and critical information.
- **Background (#121212):** A deep charcoal that provides a more sophisticated backdrop than pure black, allowing for subtle shadow play.
- **Surface (#1E1E1E):** Used for cards and elevated elements to create a hierarchical distinction from the background.
- **Text:** Pure white (#FFFFFF) is reserved for headings and primary content to ensure maximum readability. Secondary text uses a muted gray to maintain visual balance.

## Typography
The typography system uses a tri-font approach to balance impact with technical clarity:
- **Headings:** Hanken Grotesk provides a sharp, contemporary feel with tight tracking for a premium "editorial" look in large displays.
- **Body:** Inter is used for its exceptional legibility in dark mode, ensuring that project descriptions and technical details are easy to digest.
- **Technical/Labels:** JetBrains Mono is utilized for tags, code snippets, and metadata to reinforce the developer-centric nature of the portfolio.

All large display text should utilize "optical sizing" where available, and headings should lean towards heavier weights to contrast against the dark background.

## Layout & Spacing
The design system employs a **fixed-center grid** for desktop (12 columns) and a **fluid layout** for mobile (4 columns). 

- **Whitespace:** Use aggressive vertical spacing (`section-gap`) to allow each portfolio piece or service to breathe. This prevents the "cluttered" look common in developer sites.
- **Margins:** 24px margins on mobile, scaling to 80px+ on desktop to create a focused, centered content column.
- **Alignment:** Strict adherence to a 8px baseline grid to ensure all components, icons, and text blocks feel structurally sound.

## Elevation & Depth
In this design system, depth is conveyed through **Glassmorphism** and **Tonal Layering** rather than traditional heavy shadows.

- **Base Layer:** Background (#121212).
- **Secondary Layer:** Surface (#1E1E1E) with a subtle 1px border of `surface-border`.
- **Interactive Layer:** Glassmorphic elements using a backdrop-blur (12px to 20px) and a very low opacity white fill (4-8%).
- **Accent Elevation:** Use a "Lime Glow" (a soft, diffused outer glow using the primary color) for active states or highlighted project cards. Shadows should be tinted with the background color (not pure black) to maintain a soft, modern transition.

## Shapes
The shape language is **Soft (0.25rem - 0.75rem)**. This provides a precise, engineered look that isn't as aggressive as sharp corners, nor as "friendly" as highly rounded pill shapes. 

- **Small Components:** (Buttons, Inputs) use a 4px (0.25rem) radius.
- **Large Components:** (Cards, Modals) use a 12px (0.75rem) radius.
- **Icons:** Should follow a linear, 2px stroke weight to match the refined aesthetic.

## Components
- **Buttons:**
    - *Primary:* Solid Lime Green (#D4FF00) with Black text. No shadow, but a subtle "bloom" effect on hover.
    - *Secondary:* Ghost style with a 1px white border and a 5% white hover fill.
- **Cards:** Use a glassmorphic background with a 12px blur. Include a 1px top-left highlight border to simulate a light source. Hover states should trigger a subtle primary-colored border glow.
- **Inputs:** Dark backgrounds (#1E1E1E) with a subtle bottom-border only. On focus, the border transitions to Lime Green with a small external glow.
- **Chips/Tags:** Monospaced font (JetBrains Mono), all-caps, with a low-opacity lime green background and a 1px primary border.
- **Lists:** Bullet points should be replaced with small, glowing lime-green squares or custom SVG tech icons.
- **Scrollbar:** Custom-styled to be ultra-thin, charcoal-colored, with a lime green thumb.