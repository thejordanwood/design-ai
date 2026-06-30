---
name: CivicActions Design System
colors:
  surface: "#FFFFFF"                  
  surface-dim: "#F0F4F7"              
  surface-bright: "#FFFFFF"
  surface-container-lowest: "#FFFFFF"
  surface-container-low: "#F8FAFB"
  surface-container: "#F0F4F7"        
  surface-container-high: "#E1E6EB"
  surface-container-highest: "#D1D8E0"
  on-surface: "#1A1C1E"               
  on-surface-variant: "#3D4551"       
  inverse-surface: "#1A1C1E"
  inverse-on-surface: "#FFFFFF"
  outline: "#71767A"                  
  outline-variant: "#A9AEB1"
  surface-tint: "#162E51"             
  primary: "#162E51"                 
  on-primary: "#FFFFFF"              
  primary-container: "#E2E9F3"        
  on-primary-container: "#0B182B"
  inverse-primary: "#73B3E7"
  secondary: "#D83933"               
  on-secondary: "#FFFFFF"            
  secondary-container: "#FCEBEA"     
  on-secondary-container: "#57110E"
  tertiary: "#73B3E7"                 
  on-tertiary: "#000000"              
  tertiary-container: "#EAF3FC"
  on-tertiary-container: "#102638"
  error: "#D9381E"                    
  on-error: "#FFFFFF"
  error-container: "#F7E8E6"
  on-error-container: "#8A1200"
  primary-fixed: "#162E51"
  primary-fixed-dim: "#0E1F36"
  on-primary-fixed: "#FFFFFF"
  on-primary-fixed-variant: "#E2E9F3"
  secondary-fixed: "#D83933"
  secondary-fixed-dim: "#A32520"
  on-secondary-fixed: "#FFFFFF"
  on-secondary-fixed-variant: "#FCEBEA"
  tertiary-fixed: "#73B3E7"
  tertiary-fixed-dim: "#498CC4"
  on-tertiary-fixed: "#000000"
  on-tertiary-fixed-variant: "#EAF3FC"
  background: "#FFFFFF"
  on-background: "#1A1C1E"
  surface-variant: "#F0F4F7"
typography:
  headline-xl:
    fontFamily: Merriweather
    fontSize: 40px                  
    fontWeight: "700"
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Merriweather
    fontSize: 32px
    fontWeight: "700"
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Merriweather
    fontSize: 24px
    fontWeight: "600"
    lineHeight: 32px
    letterSpacing: 0em
  body-lg:
    fontFamily: Nunito
    fontSize: 18px
    fontWeight: "400"
    lineHeight: 28px
    letterSpacing: 0em
  body-md:
    fontFamily: Nunito
    fontSize: 16px
    fontWeight: "400"
    lineHeight: 24px                   
    letterSpacing: 0em
  label-md:
    fontFamily: Nunito
    fontSize: 14px
    fontWeight: "600"                 
    lineHeight: 20px
    letterSpacing: 0.02em
rounded:
  sm: 2px                            
  DEFAULT: 4px
  md: 4px
  lg: 4px                            
  xl: 8px
  full: 9999px
spacing:
  unit: 8px
  container-max: 1040px               
  gutter: 32px
  margin-mobile: 16px
  margin-desktop: 32px
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.label-md}"
    rounded: "{rounded.DEFAULT}"
    padding: 12px 24px
    height: 44px                      
  button-primary-hover:
    backgroundColor: "#00477A"         
  button-secondary:
    backgroundColor: transparent
    textColor: "{colors.primary}"
    typography: "{typography.label-md}"
    rounded: "{rounded.DEFAULT}"
    padding: 12px 24px
    height: 44px
  button-secondary-hover:
    backgroundColor: "rgba(0, 94, 162, 0.08)"
  card-solid-civic:                   
    backgroundColor: "{colors.surface-dim}"
    rounded: "{rounded.xl}"
    padding: "{spacing.gutter}"
    border: "1px solid {colors.outline-variant}"
  card-interactive-hover:
    backgroundColor: "{colors.surface-container-high}"
  input-field:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.on-surface}"
    typography: "{typography.body-md}"
    rounded: "{rounded.sm}"
    padding: 12px
    border: "1px solid {colors.outline}" 
  list-item-hover:
    backgroundColor: "{colors.primary-container}"
    textColor: "{colors.on-primary-container}"
    rounded: "{rounded.sm}"
    padding: 8px
  hero-headline:
    textColor: "{colors.on-surface}"
    typography: "{typography.headline-xl}"
  badge-status:                       
    backgroundColor: "{colors.tertiary-container}"
    textColor: "{colors.on-tertiary-container}"
    typography: "{typography.label-md}"
    rounded: "{rounded.full}"
    padding: 4px 12px
---

## Brand & Style

The design system captures the trust and clarity of high-impact public sector modernization. It targets an audience of government agencies, civic technologists, and the millions of diverse citizens navigating critical public services. The aesthetic is "Civic Authority," blending the absolute reliability of democratic institutions with the streamlined efficiency of modern human-centered product design.

To achieve this, the design system utilizes flat design and structural grids. Surfaces appear as clean, crisp layout configurations anchored by intentional whitespace, maximizing cognitive focus and ensuring uncompromised reading widths. High-contrast visual accents and strict typography systems represent democratic accessibility, ensuring that while the interface is highly professional, it feels inviting, transparent, and universally usable rather than rigid or bureaucratic

## Colors

The palette is anchored in the transition from institutional stability to accessible clarity.

- **Primary (Dark Blue):** Represents the unwavering foundation of democratic institutions. Used for bold structural layout elements, core typography, and primary landmarks.
- **Secondary (Red):** Represents civic authority and trusted digital interaction. Used for critical CTAs, active states, and high-importance highlights to anchor the user's focus.
- **Tertiary (Light Blue):** Represents transparent communication and modern civic innovation. Used for secondary informational emphasis, supportive status badges, and subtle callouts.
- **Neutral (White):** A crisp, ultra-high-contrast foundation that ensures absolute readability, maximizing visual comfort and scanning speed across diverse screen viewports.

Gradient usage is strictly prohibited: use solid, flat color fields for backgrounds and layout structures to eliminate unnecessary visual noise, guaranteeing full adherence to WCAG 2.2 AA contrast rules and maintaining structural clarity.

## Typography

This design system uses a dual-font strategy to balance democratic authority with modern utility [14].

- **Merriweather** is the voice of the institution. Its elegant, traditional serifs project editorial credibility, warmth, and the historical weight of civic structures. It should be used exclusively for headlines to establish clear information hierarchies. Large headings should use slightly compact line heights to feel unified, grounded, and monumental.
- **Nunito** provides an approachable, highly legible counterpoint for long-form content, data panels, and form descriptions. Its rounded, friendly sans-serif terminals soften the institutional layout, ensuring that dense policy documentation or complex transactional fields remain comfortable to scan and universally accessible across various viewport dimensions.

To maintain strict compliance and federal readability metrics, typography must never utilize text-shadows, blurs, or glow effects; always keep characters sharp, flat, and distinct against their backgrounds to guarantee uncompromised clarity and edge contrast [14].

## Layout & Spacing

The layout philosophy follows a **Fixed Grid** model for desktop to maintain a prestigious, editorial feel, while transitioning to a fluid model for mobile.

A 12-column grid is used for desktop layouts, with generous outer margins to simulate the isolation of a celestial body in the void. Spacing is governed by an 8px base unit, but "negative space" is prioritized—elements should be allowed to breathe, echoing the vastness of space. Component groups should use tight internal spacing (e.g., 8px or 16px) but wide external margins (e.g., 64px or 80px) to create distinct "islands" of content.

## Elevation & Depth

Depth in this design system is achieved through **Glassmorphism** and light-based layering rather than traditional drop shadows.

- **Level 1 (Base):** Deep obsidian/neutral background.
- **Level 2 (Panels):** Semi-transparent surfaces (10-20% opacity) with a `20px` backdrop blur. These layers should have a `1px` inner stroke of white at 10% opacity to define the edge, simulating a glass refraction.
- **Level 3 (Interactive):** Elements that are hovered or active should emit an "Ambient Glow." This is a soft, diffused shadow tinted with the `Secondary` or `Primary` color, creating the effect of light bleeding from behind the object.

## Shapes

The shape language is "Soft-Technical." While the overall feel is geometric, a small corner radius is applied to all components to prevent the UI from feeling too aggressive or "sharp."

Buttons and input fields should utilize the `rounded-lg` (8px) setting for a modern feel. For specific decorative elements, such as image containers or featured cards, the `rounded-xl` (12px) setting can be used to soften the composition. Circles and perfect arcs are encouraged as supporting graphic elements to mirror the orbital theme of the festival.

## Components

### Action Elements

Buttons utilize `Space Grotesk` for a technical, high-impact feel; the Primary button mimics the "diamond ring" flash with a luminous amber glow on hover. Secondary buttons remain ethereal with a cyan outline, suggesting the sky's transition during totality.

### Containers & Surfaces

Cards implement level-2 glassmorphism using a semi-transparent `surface-variant` fill and a fine 1px inner stroke to simulate light refraction on glass edges. For interactive states, cards should expand their "Ambient Glow" using the Secondary Cyan color to indicate focus.

### Inputs & Selection

Input fields are anchored in the deepest `surface-container-lowest` to provide maximum contrast for entered text. Focus states use the Secondary Cyan border to maintain the cosmic color story without distracting from content.

### Typography Application

`headline-xl` should always be paired with a subtle primary-colored glow when placed on dark backgrounds to ensure it feels "radiant" rather than static. List items use a tighter `rounded-md` corner to differentiate them from larger, more prominent layout containers.
