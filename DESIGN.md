---
name: Terrane Professional
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e4e2e1'
  on-surface: '#1b1c1c'
  on-surface-variant: '#414844'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0f0'
  outline: '#717973'
  outline-variant: '#c1c8c2'
  surface-tint: '#3f6653'
  primary: '#012d1d'
  on-primary: '#ffffff'
  primary-container: '#1b4332'
  on-primary-container: '#86af99'
  inverse-primary: '#a5d0b9'
  secondary: '#79564c'
  on-secondary: '#ffffff'
  secondary-container: '#fed0c3'
  on-secondary-container: '#79574d'
  tertiary: '#262624'
  on-tertiary: '#ffffff'
  tertiary-container: '#3c3c39'
  on-tertiary-container: '#a8a6a3'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c1ecd4'
  primary-fixed-dim: '#a5d0b9'
  on-primary-fixed: '#002114'
  on-primary-fixed-variant: '#274e3d'
  secondary-fixed: '#ffdbd1'
  secondary-fixed-dim: '#e9bcb0'
  on-secondary-fixed: '#2d150e'
  on-secondary-fixed-variant: '#5f3f36'
  tertiary-fixed: '#e5e2de'
  tertiary-fixed-dim: '#c8c6c2'
  on-tertiary-fixed: '#1c1c19'
  on-tertiary-fixed-variant: '#474744'
  background: '#fcf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e1'
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
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-md-mobile:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  title-lg:
    fontFamily: Montserrat
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Source Sans 3
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Source Sans 3
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Source Sans 3
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  caption:
    fontFamily: Source Sans 3
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
  section-gap: 80px
---

## Brand & Style

The design system is built upon the pillars of stability, transparency, and local heritage. Designed for a real estate leader with a decade of presence in Kushinagar, the aesthetic reflects the literal meaning of "Bhumi" (Earth) through a grounded, **Corporate Modern** approach. 

The visual language avoids fleeting trends in favor of a timeless, architectural structure. It utilizes generous whitespace to signify transparency and high-quality photography to build aspiration. The interface should feel established and unshakable, evoking a sense of "permanent residence" rather than a digital storefront.

- **Primary Motif:** Grid-based layouts and structural alignment.
- **Atmosphere:** Solid, dependable, and quietly premium.
- **Target Audience:** High-intent property buyers, investors, and local families seeking trusted land development.

## Colors

The palette is derived from the natural elements of land development: deep forest greens representing growth and stability, and earthy browns representing the foundation of the soil.

- **Primary (Forest Green):** Used for primary brand actions, headers, and signifying established authority.
- **Secondary (Silt Brown):** Used for accents, secondary buttons, and decorative elements that require a "human" or "earthy" touch.
- **Tertiary (Sand):** A warm off-white used for section backgrounds to soften the UI and prevent the clinical feel of pure white.
- **Neutral (Slate):** A range of grays used for high-legibility typography and UI borders.

Functional colors (Success, Warning, Error) should be slightly desaturated to maintain the professional, earth-toned harmony of the system.

## Typography

This design system uses a pairing of **Montserrat** for headlines and **Source Sans 3** for body text. 

- **Montserrat** provides an authoritative, geometric structure that mirrors architectural blueprints. It should be used for all major headings and price points to convey strength.
- **Source Sans 3** was selected for its exceptional legibility in data-heavy property listings and legal disclosures. Its humanist qualities ensure the brand remains approachable despite its corporate stature.

Apply `display-lg` sparingly for hero sections. Use `label-md` for metadata like "Property Type" or "Construction Status" to create a clear information hierarchy.

## Layout & Spacing

The layout philosophy follows a **Fixed Grid** model on desktop to maintain a sense of containment and order. 

- **Grid:** A 12-column system with a 24px gutter. Content should be centered within a 1280px container.
- **Vertical Rhythm:** Use increments of 8px for internal component spacing. Section-to-section spacing is generous (80px+) to allow the "Bhumi" (land) imagery to breathe.
- **Mobile:** Transition to a single-column fluid layout with 20px side margins. Property cards should stack vertically, while feature icons may use a horizontal scroll (carousel) to save vertical real estate.

## Elevation & Depth

To maintain a "stable" and "grounded" brand feel, this design system avoids floating elements or heavy shadows. Depth is communicated through **Tonal Layers** and crisp, low-contrast outlines.

- **Surface Tiers:** Use the Tertiary (Sand) color to define the background, with white cards sitting on top to signify importance.
- **Borders:** Use 1px borders in a soft neutral (#E0E0E0) for input fields and property cards instead of drop shadows.
- **Interactive States:** Only use subtle, soft-blur shadows (e.g., `box-shadow: 0 4px 12px rgba(0,0,0,0.05)`) when a user hovers over a property listing card to indicate interactivity without breaking the flat, professional aesthetic.

## Shapes

The shape language is **Soft (Level 1)**. 

While the brand is professional, pure sharp corners can feel overly aggressive or dated. A minimal radius of 4px (`rounded-sm`) to 8px (`rounded-md`) is used to modernize the interface while retaining the rigid, structural feel of a development firm. 

- **Buttons & Inputs:** 4px radius.
- **Cards & Large Containers:** 8px radius.
- **Icons:** Should follow a "solid" or "duotone" style with square terminals to match the font's geometric nature.

## Components

### Buttons
Primary buttons use the Forest Green background with white text. Secondary buttons use the Silt Brown or a ghost-style outline. Button labels must be in Montserrat SemiBold.

### Property Listing Cards
Cards must prioritize high-resolution imagery at the top. The "Metadata Bar" below the image should clearly display "Area", "Type", and "Location" using `label-md` and small earthy icons. The price should always be the most prominent typographic element in the card footer.

### Trust Badges
Given the 10-year industry presence, trust badges (e.g., "RERA Approved", "10 Years Excellence") should be rendered in a monochromatic Slate or Silt Brown to appear as "seals" rather than advertisements.

### Input Fields
Fields should be structured with a subtle 1px border. Focus states transition the border to Forest Green. Use clear labels above the field rather than relying solely on placeholder text to ensure transparency and ease of use for all age groups.

### Lists & Tables
For plot dimensions or project milestones, use clean rows with alternating Tertiary (Sand) backgrounds. This "Zebra-striping" enhances readability for technical specifications.