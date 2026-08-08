---
name: Island Velocity
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f4'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#544438'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f0f1f1'
  outline: '#867366'
  outline-variant: '#d9c2b3'
  surface-tint: '#904d00'
  primary: '#904d00'
  on-primary: '#ffffff'
  primary-container: '#f2994a'
  on-primary-container: '#663500'
  inverse-primary: '#ffb77d'
  secondary: '#586062'
  on-secondary: '#ffffff'
  secondary-container: '#dae1e3'
  on-secondary-container: '#5d6466'
  tertiary: '#c00104'
  on-tertiary: '#ffffff'
  tertiary-container: '#ff8e7e'
  on-tertiary-container: '#890002'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdcc3'
  primary-fixed-dim: '#ffb77d'
  on-primary-fixed: '#2f1500'
  on-primary-fixed-variant: '#6e3900'
  secondary-fixed: '#dde4e6'
  secondary-fixed-dim: '#c1c8ca'
  on-secondary-fixed: '#161d1f'
  on-secondary-fixed-variant: '#41484a'
  tertiary-fixed: '#ffdad5'
  tertiary-fixed-dim: '#ffb4a9'
  on-tertiary-fixed: '#410000'
  on-tertiary-fixed-variant: '#930002'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
  warm-gold: '#F2994A'
  deep-slate: '#2D3436'
  island-red: '#EF3124'
  glass-fill: rgba(255, 255, 255, 0.7)
  glass-stroke: rgba(255, 255, 255, 0.4)
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 56px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Montserrat
    fontSize: 36px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-bold:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  button:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
  section-gap: 120px
---

## Brand & Style
The design system is engineered for a premium motorbike and scooter rental experience in Sri Lanka, targeting adventurous international travelers. The personality is a fusion of **high-octane adventure and serene tropical luxury**. 

The chosen style is **Modern Glassmorphism**, emphasizing a "floating" aesthetic. By utilizing deep charcoal backgrounds and vibrant tropical accents against frosted glass layers, the UI evokes the feeling of a high-end dashboard. This approach balances the ruggedness of motorcycling with the sophisticated reliability of a premium service provider. The heavy use of whitespace ensures that the focus remains on high-quality vehicle photography and clear calls to action.

## Colors
This design system utilizes a high-contrast palette to drive hierarchy. 

- **Primary (Warm Gold/Orange):** Used exclusively for primary actions, price highlights, and active states to evoke the warmth of the Sri Lankan sun.
- **Secondary (Deep Charcoal):** Provides the professional grounding. Used for headers, heavy text, and footer sections to imply stability and trust.
- **Accent (Island Red):** Reserved for urgent notifications or specific "Hot Deal" tags, inherited from the brand’s heritage.
- **Neutral (White):** The canvas. Expansive white space is mandatory to prevent the glassmorphism effects from feeling cluttered.

The "Glass" effect is achieved using a 70% opacity white fill with a 40% opacity white stroke, paired with a significant backdrop blur (20px+).

## Typography
The typography strategy pairs the geometric strength of **Montserrat** for headlines with the exceptional legibility of **Inter** for body copy and UI labels.

- **Headlines:** Set in Montserrat with tight letter-spacing for a modern, impactful look. Headlines should primarily use the Deep Charcoal color.
- **Body:** Inter provides a neutral, highly readable experience for technical specs and rental terms.
- **Labels:** Small labels and tags should use Inter at a semi-bold weight with slight tracking (letter-spacing) to improve readability at small scales.
- **Responsive:** Display sizes must scale down by approximately 30-40% on mobile devices to maintain visual balance.

## Layout & Spacing
The design system follows a **12-column fluid grid** for desktop and a **4-column grid** for mobile. 

- **The Floating Aesthetic:** To achieve the "floating" look, elements should never feel cramped. Use generous section gaps (120px+) to separate distinct phases of the user journey (e.g., from Search to Catalog).
- **Glass Overlays:** The search and booking bars should overlap the hero imagery using absolute positioning, creating a sense of physical depth.
- **Alignment:** Content should be centered within the 1280px max-width container, while background elements or decorative images may bleed to the edge of the viewport.

## Elevation & Depth
Depth is the cornerstone of this design system. It is communicated through three specific tiers:

1.  **Base Layer:** Solid white or subtle light gray (#F8F9FA) backgrounds.
2.  **Glass Layer (Mid-tier):** Frosted glass panels used for the Search Bar and Filter controls. These use a `backdrop-filter: blur(24px)` and a thin 1px white border at 40% opacity to define the edge.
3.  **Floating Tier (High-tier):** Vehicle cards and CTA buttons. These use **Ambient Shadows**: soft, large-radius shadows (Blur: 30px, Y: 10px) with very low opacity (8%) using the Deep Charcoal color to make them "pop" off the page without looking heavy.

## Shapes
The shape language is consistently **Rounded**. 

- **Primary Cards:** Use a 1rem (16px) corner radius to feel approachable and modern.
- **CTA Buttons:** Use a 2rem (32px) or "Pill" shape to distinguish them from structural elements and make them highly touch-friendly for mobile users.
- **Input Fields:** Should match the card roundedness (16px) to maintain a cohesive visual rhythm within the booking forms.

## Components
### Buttons
- **Primary:** Warm Gold (#F2994A) background with White text. Rounded-pill shape. High-contrast hover state (slight darken).
- **Secondary:** Deep Charcoal border (2px) with transparent background and charcoal text.

### Glassmorphism Search Bar
- A horizontal container with a high backdrop blur. 
- Divide sections (Location, Date, Vehicle Type) with subtle 1px vertical lines. 
- The search trigger should be a prominent Gold button inside the glass container.

### Vehicle Catalog Cards
- **Image:** High-resolution photo with no background or a very clean environmental shot.
- **Content:** Title in Montserrat, price in Gold bold text. 
- **Specs:** Use small icons (engine size, transmission) with Inter labels.
- **Interactions:** A subtle scale-up effect (1.02x) on hover to signify interactivity.

### Inputs & Checkboxes
- Fields should have a light gray fill (#F1F3F5) and transition to a Gold border on focus.
- Checkboxes for "Insurance" or "Add-ons" should use the Gold color for the checked state to ensure high visibility.