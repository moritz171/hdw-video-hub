---
name: Industrial Grit
colors:
  surface: '#0c141e'
  surface-dim: '#0c141e'
  surface-bright: '#323a45'
  surface-container-lowest: '#070f19'
  surface-container-low: '#141c27'
  surface-container: '#18202b'
  surface-container-high: '#232b36'
  surface-container-highest: '#2d3541'
  on-surface: '#dbe3f2'
  on-surface-variant: '#e3bfb1'
  inverse-surface: '#dbe3f2'
  inverse-on-surface: '#29313c'
  outline: '#aa8a7d'
  outline-variant: '#5a4136'
  surface-tint: '#ffb596'
  primary: '#ffb596'
  on-primary: '#581e00'
  primary-container: '#ff6600'
  on-primary-container: '#561d00'
  inverse-primary: '#a33e00'
  secondary: '#c6c6c7'
  on-secondary: '#2f3131'
  secondary-container: '#454747'
  on-secondary-container: '#b4b5b5'
  tertiary: '#9ccaff'
  on-tertiary: '#003256'
  tertiary-container: '#009cfc'
  on-tertiary-container: '#003155'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdbcd'
  primary-fixed-dim: '#ffb596'
  on-primary-fixed: '#360f00'
  on-primary-fixed-variant: '#7c2e00'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#d0e4ff'
  tertiary-fixed-dim: '#9ccaff'
  on-tertiary-fixed: '#001d35'
  on-tertiary-fixed-variant: '#00497b'
  background: '#0c141e'
  on-background: '#dbe3f2'
  surface-variant: '#2d3541'
  deep-obsidian: '#000000'
  slate-steel: '#2C3746'
  caution-orange: '#E65C00'
typography:
  headline-xl:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '900'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '800'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 28px
    fontWeight: '800'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '700'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-bold:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: JetBrains Mono
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
  base: 8px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  max-width: 1280px
---

## Brand & Style

This design system embodies a "hands-on" industrial aesthetic, tailored for a professional workshop environment where durability meets precision. The brand personality is rugged, masculine, and unapologetically bold, designed to resonate with makers and craftsmen.

The visual style is **Industrial Modern**, characterized by a dark, high-contrast environment that mimics the feel of a premium tool chest or a modern workshop. It prioritizes clarity and impact, using heavy borders, structural grids, and high-energy accent colors to drive action. The emotional response is one of reliability and expertise—evoking the feeling of a well-engineered tool that is built to last.

## Colors

The palette is anchored by a deep **Slate/Anthracite (#212934)** base, creating a sophisticated dark mode that reduces glare and emphasizes content. **Deep Obsidian (#000000)** is used for structural grounding and backgrounds of high-intensity components.

The primary brand driver is **Caution Orange (#FF6600)**, used exclusively for primary Calls to Action (CTAs), critical status indicators, and brand highlights. This color is designed to "pop" aggressively against the dark backgrounds. **White (#FFFFFF)** is reserved for high-contrast typography and essential icons, ensuring maximum legibility in a low-light UI environment.

## Typography

The typography system is engineered for power and readability. **Montserrat** is the primary display face, utilized in heavy weights (ExtraBold to Black) and uppercase styling to create an authoritative, masculine presence for headings.

**Hanken Grotesk** serves as the body typeface, offering a clean, contemporary sans-serif feel that balances the aggression of the headlines with professional clarity. For technical details, measurements, and metadata, **JetBrains Mono** is introduced to provide a "blueprinted" or technical documentation feel, reinforcing the industrial narrative. Use tighter tracking on headlines and wider tracking on labels for a refined, engineered look.

## Layout & Spacing

This design system utilizes a **fixed-grid** model for desktop and a **fluid-grid** for mobile. The layout is built on a strict 8px baseline grid to ensure mathematical precision between elements.

On desktop, the content is contained within a 1280px max-width 12-column grid. Margins are generous to allow the dark interface to "breathe." On mobile, the 4-column grid uses condensed gutters (16px) to maximize screen real estate for high-impact imagery and bold typography. Section vertical padding should be substantial (80px - 120px) to maintain a premium, modern feel.

## Elevation & Depth

In this dark-themed system, depth is communicated through **Tonal Layers** rather than traditional soft shadows. 

1.  **Base Layer:** The deepest level (#000000) used for the main background.
2.  **Surface Layer:** A slightly lighter neutral (#212934) used for cards, sections, and containers.
3.  **Accent Layer:** Subtitle or interactive elements use a "Slate Steel" tint (#2C3746).

For borders, use high-contrast **low-opacity outlines** (1px solid white at 10% opacity) to define edges without adding visual clutter. When an element requires "lift," use a subtle, sharp 4px shadow with 40% opacity of the background color to keep the look crisp and grounded.

## Shapes

The shape language is **Soft (0.25rem)**. This slight rounding takes the edge off the industrial aesthetic, making it feel modern and "manufactured" rather than raw and sharp. 

Primary buttons and input fields should utilize this consistent 4px radius. Smaller components like chips or tags can use the `rounded-lg` (8px) setting for visual variety, but never exceed this to maintain the masculine, structured feel of the brand.

## Components

**Buttons:** 
- **Primary:** Bold Orange (#FF6600) background with Black (#000000) text, Montserrat Bold, Uppercase. High impact.
- **Secondary:** Transparent with a 2px White border, White text.
- **Hover States:** Primary buttons should shift to a deeper orange (#E65C00); Secondary buttons should gain a subtle white fill at 10% opacity.

**Input Fields:**
- Dark Obsidian background, Slate Steel border (1px), White text. Focus state triggers a 1px Caution Orange border. Use JetBrains Mono for placeholder text to emphasize the "spec-sheet" feel.

**Cards:**
- Solid Slate (#212934) background. No shadows. Use 1px borders (#FFFFFF at 10% opacity) to separate them from the background. 

**Chips/Tags:**
- Small, uppercase JetBrains Mono text. Used for "In Stock," "New," or "Professional Grade" indicators.

**Lists:**
- Bullet points should be replaced with small Orange squares or "plus" icons to reinforce the construction/assembly metaphor.

**Progress Bars:**
- Thick, 8px bars using a Slate Steel track and Caution Orange fill, emphasizing the "work in progress" or "performance" aspect of the brand.