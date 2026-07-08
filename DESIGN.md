---
name: Hydro-Technical Precision
colors:
  surface: '#f8fafb'
  surface-dim: '#d8dadb'
  surface-bright: '#f8fafb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f5'
  surface-container: '#eceeef'
  surface-container-high: '#e6e8e9'
  surface-container-highest: '#e1e3e4'
  on-surface: '#191c1d'
  on-surface-variant: '#40484c'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#eff1f2'
  outline: '#71787d'
  outline-variant: '#c0c7cd'
  surface-tint: '#2a657e'
  primary: '#003345'
  on-primary: '#ffffff'
  primary-container: '#004b63'
  on-primary-container: '#83bad6'
  inverse-primary: '#96ceeb'
  secondary: '#02677f'
  on-secondary: '#ffffff'
  secondary-container: '#98e2fd'
  on-secondary-container: '#00667e'
  tertiary: '#203500'
  on-tertiary: '#ffffff'
  tertiary-container: '#314d00'
  on-tertiary-container: '#95c057'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#bfe8ff'
  primary-fixed-dim: '#96ceeb'
  on-primary-fixed: '#001f2b'
  on-primary-fixed-variant: '#044d65'
  secondary-fixed: '#b7eaff'
  secondary-fixed-dim: '#87d1ec'
  on-secondary-fixed: '#001f28'
  on-secondary-fixed-variant: '#004e60'
  tertiary-fixed: '#c3f181'
  tertiary-fixed-dim: '#a8d469'
  on-tertiary-fixed: '#111f00'
  on-tertiary-fixed-variant: '#324f00'
  background: '#f8fafb'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
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
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base-unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style
The design system is engineered to project technical mastery, reliability, and environmental stewardship. It targets agricultural, industrial, and high-end residential clients who require long-term infrastructure solutions rather than quick fixes.

The aesthetic follows a **Corporate / Modern** style with a focus on "Engineering Clarity." This is achieved through high-quality whitespace, a systematic grid, and a disciplined use of color that avoids decorative excess. The UI should feel as precise and well-constructed as a mechanical blueprint, balanced by the fluidity of its water-inspired palette.

## Colors
The palette is grounded in the "Petróleo" Navy Blue to establish authority and the literal depth of artesian exploration.

- **Primary (Navy Blue):** Used for headers, primary actions, and deep structural elements. Represents the expertise of the "Sul" region.
- **Secondary (Light Blue):** Used for interactive states, iconography, and progress indicators. Represents water purity.
- **Accent (Soft Green):** Used sparingly for environmental certifications, "Sustainability" sections, and success states.
- **Background:** A crisp Off-white (#F8FAFB) is used to reduce eye strain compared to pure white, maintaining a technical, laboratory-clean feel.
- **Surface:** Pure white (#FFFFFF) is reserved for cards and elevated components to create clear separation.

## Typography
The typography strategy pairs **Montserrat** for headlines to provide a bold, geometric, and modern structural feel, with **Inter** for body text to ensure maximum legibility for technical data and service descriptions.

Headlines should use a tighter letter-spacing to feel more "engineered." Body text remains neutral and systematic. Use `label-caps` for technical specifications or small sub-headers to maintain a disciplined, professional hierarchy.

## Layout & Spacing
The design system utilizes a **12-column fluid grid** for desktop and a **4-column grid** for mobile. A strict 8px spacing scale ensures consistency across all components.

- **Desktop:** 64px outer margins to provide "breathing room" that reflects the openness of the Southern landscape.
- **Vertical Rhythm:** Sections are separated by large 80px - 120px gaps to prevent the information from feeling cluttered.
- **Alignment:** All technical data points and lists should be left-aligned to a vertical axis to reinforce the feeling of a structured report or manual.

## Elevation & Depth
To maintain a discreet and technical appearance, this design system avoids heavy shadows. Instead, it uses **Low-contrast outlines** and **Tonal layers**.

- **Depth Level 1 (Default):** Flat background in Off-white.
- **Depth Level 2 (Cards):** Pure white surface with a 1px border in a very light grey (#E2E8F0). No shadow.
- **Depth Level 3 (Interactive):** When hovered, cards or buttons gain a subtle, ultra-diffused shadow (0px 4px 20px rgba(0, 75, 99, 0.08)) to suggest a soft lift without breaking the clean aesthetic.

## Shapes
A **Soft (0.25rem)** roundedness is applied to standard elements like input fields and small buttons. This provides a modern touch without appearing overly "bubbly" or consumer-grade.

- **Standard Radius:** 4px (Soft) for buttons and inputs.
- **Large Radius:** 8px (Rounded-lg) for service cards and containers.
- **Interactive Elements:** Buttons and CTA blocks maintain these subtle corners to reflect precision machining and professional hardware.

## Components
- **Primary Buttons:** Solid Navy Blue with white text. High contrast, 4px corner radius.
- **WhatsApp CTA:** A specialized "Floating Action Button" (FAB) or prominent section footer using a slightly more vibrant green than the Soft Green accent, paired with a clear "Falar com Especialista" (Speak with a Specialist) label.
- **Technical Cards:** White background, 1px border, 8px radius. Used for "Service Packages" or "Drilling Specifications." Icons should be stroke-based (2pt weight) in Navy Blue.
- **Data Lists:** For maintenance logs or depth specs, use clean rows with alternating subtle grey backgrounds (zebra striping) and Inter 14px text.
- **Input Fields:** Minimalist design with a 1px border that turns Light Blue on focus. Labels are always placed above the field in `label-caps` style.
- **Status Badges:** Small, 2px radius chips for "Active," "Maintained," or "Pure Water" indicators, using the Soft Green or Light Blue palette.