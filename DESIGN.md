---
name: Kinetic Portfolio
colors:
  surface: '#0b1326'
  surface-dim: '#0b1326'
  surface-bright: '#31394d'
  surface-container-lowest: '#060e20'
  surface-container-low: '#131b2e'
  surface-container: '#171f33'
  surface-container-high: '#222a3d'
  surface-container-highest: '#2d3449'
  on-surface: '#dae2fd'
  on-surface-variant: '#c7c4d7'
  inverse-surface: '#dae2fd'
  inverse-on-surface: '#283044'
  outline: '#908fa0'
  outline-variant: '#464554'
  surface-tint: '#c0c1ff'
  primary: '#c0c1ff'
  on-primary: '#1000a9'
  primary-container: '#8083ff'
  on-primary-container: '#0d0096'
  inverse-primary: '#494bd6'
  secondary: '#44e2cd'
  on-secondary: '#003731'
  secondary-container: '#03c6b2'
  on-secondary-container: '#004d44'
  tertiary: '#ffafd3'
  on-tertiary: '#620040'
  tertiary-container: '#e364a7'
  on-tertiary-container: '#560038'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e1e0ff'
  primary-fixed-dim: '#c0c1ff'
  on-primary-fixed: '#07006c'
  on-primary-fixed-variant: '#2f2ebe'
  secondary-fixed: '#62fae3'
  secondary-fixed-dim: '#3cddc7'
  on-secondary-fixed: '#00201c'
  on-secondary-fixed-variant: '#005047'
  tertiary-fixed: '#ffd8e7'
  tertiary-fixed-dim: '#ffafd3'
  on-tertiary-fixed: '#3d0026'
  on-tertiary-fixed-variant: '#85145a'
  background: '#0b1326'
  on-background: '#dae2fd'
  surface-variant: '#2d3449'
typography:
  display-lg:
    fontFamily: Hanken Grotesk
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 42px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-sm:
    fontFamily: Hanken Grotesk
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
  label-mono:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  section-gap: 120px
  section-gap-mobile: 64px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 20px
---

## Brand & Style

This design system is engineered to transform a standard developer resume into a high-end digital experience. The brand personality is **technical, precise, and sophisticated**, moving away from the static nature of the reference image toward a dynamic, professional identity.

The design style is **Corporate Modern with a Minimalist lean**. It prioritizes high-quality typography and generous whitespace to ensure the developer's projects are the primary focus. Subtle use of glassmorphism and ambient shadows provides depth without clutter, creating a "premium software" feel that resonates with tech recruiters and engineering managers. On mobile, the experience shifts to a content-first approach, using vertical rhythm to maintain readability.

## Colors

The palette is anchored in a **Deep Indigo and Charcoal** dark mode to provide a modern, "IDE-inspired" backdrop that reduces eye strain and feels inherently technical.

*   **Primary (Indigo):** Used for primary actions, active states, and brand-defining accents.
*   **Secondary (Teal):** Used for "Success" states, code-related accents, and highlighting technical skills.
*   **Tertiary (Pink/Violet):** Used sparingly for interactive highlights or to differentiate categories in project cards.
*   **Neutrals:** A range of cool grays (slates) are used to establish hierarchy in text and container surfaces.

The background uses a near-black navy to allow vibrant accents to "pop" with high legibility.

## Typography

This system utilizes a trio of typefaces to balance character with utility:
1.  **Hanken Grotesk** for headlines: Sharp, contemporary, and highly legible at large scales.
2.  **Inter** for body text: The industry standard for UI clarity and readability.
3.  **JetBrains Mono** for labels and tags: A nod to the developer's craft, used for tech stacks, dates, and metadata.

Hierarchy is established through weight and color rather than just size. Headlines should use the primary neutral-white, while body text uses a slightly dimmed slate to create a natural visual flow.

## Layout & Spacing

The layout follows a **Fluid Grid** model with a maximum container width of 1200px. 

*   **Desktop:** A 12-column grid with 24px gutters. Use asymmetrical layouts (e.g., a 4-column sidebar for contact info and an 8-column main area for projects) to create visual interest.
*   **Mobile:** A single-column flow with 20px side margins. 
*   **Vertical Rhythm:** Use a strict 8px baseline. Sections are separated by significant "breathing room" (120px) to give each part of the portfolio (Skills, Projects, Education) its own stage.

Elements like project cards should use internal padding of 32px (4x the base unit) to maintain a spacious, high-end feel.

## Elevation & Depth

Visual hierarchy is achieved through **Tonal Layers** and **Ambient Shadows**. 

1.  **Level 0 (Background):** The base dark navy.
2.  **Level 1 (Cards/Sections):** A slightly lighter slate surface with a subtle 1px border (`rgba(255,255,255,0.1)`) to define edges without high-contrast lines.
3.  **Level 2 (Hover/Active):** Surfaces lift using a soft, diffused shadow: `0 20px 25px -5px rgba(0, 0, 0, 0.3)`.

For high-priority items, use a **Backdrop Blur** (glassmorphism) on navigation bars and floating action buttons to maintain context of the content underneath while providing a clear interactive layer.

## Shapes

The design system uses a **Rounded** shape language (`0.5rem` or `8px` base) to appear approachable yet professional. 

*   **Project Cards:** Use `rounded-xl` (24px) to create a soft, containerized look.
*   **Buttons & Inputs:** Use the standard `rounded` (8px).
*   **Tags/Pills:** Use full-radius (pill-shaped) for technology tags (e.g., "React", "Python") to distinguish them from functional buttons.

## Components

*   **Buttons:** Primary buttons use a solid Indigo fill. Secondary buttons use a ghost style with a subtle Indigo border. Always include a hover state that slightly increases the shadow depth.
*   **Project Cards:** These are the centerpiece. Use a Level 1 surface, 32px padding, and clear separation between the project title (Headline-sm) and the description (Body-md). Tech stacks should be displayed as a row of mono-font pills at the bottom.
*   **Skill Chips:** Use a subtle background tint (Indigo at 10% opacity) with the primary Indigo text to create a soft, non-intrusive tag.
*   **Input Fields:** Used for contact forms. Deep charcoal background, 1px border that glows Indigo on focus. Labels should use `label-mono` for a technical touch.
*   **Code Snippets:** Occasionally used for "About Me" or "Experience" sections. Use a true black background with syntax highlighting consistent with the Teal and Pink accent colors.