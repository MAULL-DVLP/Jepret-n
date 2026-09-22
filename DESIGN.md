---
name: Whee! Retro Y2K Photobooth
colors:
  surface: '#f0fdf4'
  surface-dim: '#d0ddd5'
  surface-bright: '#f0fdf4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eaf7ee'
  surface-container: '#e4f1e8'
  surface-container-high: '#deebe3'
  surface-container-highest: '#d9e6dd'
  on-surface: '#131e19'
  on-surface-variant: '#5c403c'
  inverse-surface: '#27332d'
  inverse-on-surface: '#e7f4eb'
  outline: '#916f6b'
  outline-variant: '#e6bdb8'
  surface-tint: '#bf0715'
  primary: '#b70011'
  on-primary: '#ffffff'
  primary-container: '#dc2626'
  on-primary-container: '#fff6f5'
  inverse-primary: '#ffb4ab'
  secondary: '#00687a'
  on-secondary: '#ffffff'
  secondary-container: '#57dffe'
  on-secondary-container: '#006172'
  tertiary: '#7f4f00'
  on-tertiary: '#ffffff'
  tertiary-container: '#a06500'
  on-tertiary-container: '#fff7f1'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad6'
  primary-fixed-dim: '#ffb4ab'
  on-primary-fixed: '#410002'
  on-primary-fixed-variant: '#93000b'
  secondary-fixed: '#acedff'
  secondary-fixed-dim: '#4cd7f6'
  on-secondary-fixed: '#001f26'
  on-secondary-fixed-variant: '#004e5c'
  tertiary-fixed: '#ffddb8'
  tertiary-fixed-dim: '#ffb95f'
  on-tertiary-fixed: '#2a1700'
  on-tertiary-fixed-variant: '#653e00'
  background: '#f0fdf4'
  on-background: '#131e19'
  surface-variant: '#d9e6dd'
typography:
  display-lg:
    fontFamily: Rubik
    fontSize: 48px
    fontWeight: '900'
    lineHeight: 52px
    letterSpacing: -0.03em
  display-lg-mobile:
    fontFamily: Rubik
    fontSize: 34px
    fontWeight: '900'
    lineHeight: 38px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Rubik
    fontSize: 28px
    fontWeight: '800'
    lineHeight: 34px
  headline-md:
    fontFamily: Rubik
    fontSize: 22px
    fontWeight: '700'
    lineHeight: 28px
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 18px
    fontWeight: '700'
    lineHeight: 24px
  body-lg:
    fontFamily: Space Grotesk
    fontSize: 16px
    fontWeight: '500'
    lineHeight: 24px
  body-md:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Space Mono
    fontSize: 13px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-md:
    fontFamily: Space Mono
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.06em
  label-sm:
    fontFamily: Space Mono
    fontSize: 9px
    fontWeight: '700'
    lineHeight: 12px
    letterSpacing: 0.08em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-lg: 1.5rem
  margin: 1rem
  margin-md: 1.5rem
  margin-lg: 2.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style
This design system captures an unapologetic, surrealist collision of early-2000s web nostalgia, Frutiger Aero optimism, and weirdcore net-art. Rooted in tactile digital skeuomorphism, CRT scanlines, and glossy bubblegum hardware, it turns taking a photo into a playful, unhinged playground. The aesthetic blends the physical tactility of a molded plastic candy-red CRT television with pixelated OS icons, saturated rolling green hills, swimming goldfish, and glossy soap bubbles. 

The experience targets digital natives, nostalgic Gen Z, and internet culture creators seeking uncurated joy, irony, and tactile delight. The emotional response is immediate dopamine: spontaneous laughter, retro comfort, and an invitation to tinker with tactile buttons that click, bounce, and pop.

## Colors
The palette is hyper-saturated and vibrant, driven by early-2000s desktop OS wallpaper skies and hardware casing tones:

- **Primary (`#DC2626` - Candy CRT Red):** Inspired by molded retro television plastic and high-contrast toy buttons. Used for primary framing, major trigger buttons, and high-impact action elements.
- **Secondary (`#06B6D4` - Cyan Aero Sky):** A bright, electric aqua blue evoking scanline skies, water reflections, and breezy Frutiger Aero desktop motifs. Used for tool selectors, lens borders, and active indicators.
- **Tertiary (`#F59E0B` - Goldfish Orange):** Sourced from playful floating goldfish, bubble glints, and retro warning stickers. Applied to stickers, badge highlights, counter badges, and secondary fun triggers.
- **Neutral (`#F0FDF4` - Bliss Cloud Mint):** An ultra-crisp, tinted off-white recalling rolling grass mist and retro window dialog bodies.
- **Additional Accents:** Windows-inspired system gray (`#C0C0C0`), pitch bezel black (`#111827`), grass neon green (`#4ADE80`), and bubble specular white (`#FFFFFF`).

## Typography
The typography marries bouncy, playful geometry with tech-nostalgic monospace accents.

- **Headline & Display (Rubik):** Rounded, punchy, and friendly. Heavy font weights (700–900) replicate toy branding, bubble gum stickers, and vintage software banner graphics.
- **Body Text (Space Grotesk):** Clean, geometric, and quirky sans-serif with subtle early-digital eccentricities that keep reading legible and grounded.
- **Microcopy & UI System Labels (Space Mono):** Used for countdown timers, camera specs, pixel speech bubbles (e.g., `#@%&!`), and toolbar telemetry, establishing the authentic early Web / retro-PC aesthetic.

## Layout & Spacing
The layout follows a centered stage presentation reminiscent of 2000s Flash web toys and desktop window frames. 

- **Desktop & Large Displays:** A fixed-aspect CRT frame (4:3 or 1:1 camera viewport) anchors the screen center, floating above rolling wallpaper grass and sky scanlines. Floating sticker widgets (curious cow, swimming goldfish, pixel recycle bin) overlap boundaries dynamically via relative positioning and safe margin zones.
- **Mobile & Small Screens:** Content condenses into a single stacked column with the camera view filling the top 60vh inside a reduced-radius CRT shell, while physical glossy control buttons arrange across an elevated bottom dock.
- **Rhythm:** Spacing follows an 8px modular baseline (`0.5rem` / `1rem`), preserving tight, tactile cluster groupings for photobooth switches and sticker drawers.

## Elevation & Depth
Depth is explicitly tactile, skeuomorphic, and neo-vintage:

- **Layer 0 (Background Canvas):** Vivid cyan scanline skies and saturated green pasture gradients with horizontal 1px line overlays.
- **Layer 1 (The CRT Housing):** Deep, extruded glossy plastic casing. Rendered with dual-bevel drop shadows (`0 20px 40px rgba(0,0,0,0.35)`), thick inner white specular highlights (`inset 0 3px 6px rgba(255,255,255,0.7)`), and dark inset camera borders (`inset 0 6px 12px rgba(0,0,0,0.8)`).
- **Layer 2 (Viewport Overlay):** Ultra-gloss glass reflections across the screen corners and CRT curve distortion.
- **Layer 3 (Floating Parallax Sprites):** Cutout cows, swimming goldfish, and soap bubbles utilize soft 3D directional drop shadows (`0 8px 16px rgba(0,0,0,0.25)`) to appear suspended mid-air.
- **Layer 4 (Tactile Controls & System Modals):** Classic 90s dual-tone bevel borders (`border-t: white`, `border-l: white`, `border-b: #555`, `border-r: #555`) for system windows, contrasted with pillowy gel buttons sporting radial gloss gradients.

## Shapes
The shape system revolves around bubbly, curved industrial hardware (`rounded-xl` to pill shapes) balanced against strict 0px pixel-art accessory stickers. 

- **CRT & Casing:** Heavily bulbous outer corners with smooth convex radii (`rounded-2xl` to `rounded-3xl`) replicating late-90s rounded tube TVs.
- **Interactive Controls:** Pill-shaped (`rounded-full`) jelly buttons and pill switches.
- **Retro OS Accents:** Strict sharp (`0px`) corners reserved exclusively for retro OS title bars, pixel art dialog speech bubbles, and system error notices to reinforce the hybrid digital/analog collision.

## Components

### Shutter & Action Buttons
- **Primary Shutter Button:** Oversized circular or bulbous pill candy-red button. Features a high-gloss top glass sheen gradient (`white 0%` to `transparent 60%`), thick bottom depth shadow (`0 6px 0 #991B1B`), and an active press state that translates downward 4px while diminishing the shadow.
- **Secondary Bubble Actions:** Translucent cyan/amber gel pills with high-contrast Space Mono bold text and subtle white outlines.

### CRT Photobooth Monitor Frame
- Molded red glossy outer bezel containing power indicator LEDs, speaker vents, and simulated physical knob selectors for filters (Sepia, Fish-Eye, Pixelate, Vapor Glow). The viewport maintains rounded inner corners with a subtle black bezel tube effect.

### Chips & Filter Tags
- Styled like 2000s candy stickers or Web 1.0 badges. Pastel yellow or electric cyan backgrounds, 1.5px solid black borders, drop shadows offset by 2px (`box-shadow: 2px 2px 0px #000`), utilizing `Space Mono` uppercase typography.

### Input Controls & Sliders
- Retro OS sliders with chunky gray block thumbs and ridged texture lines, navigating across a recessed groove (`inset 1px 1px 2px rgba(0,0,0,0.6)`). Checkboxes mimic pixelated Windows 98 bevel boxes with green check marks.

### Cards & Dialog Windows
- Replicates classic vintage desktop utility prompts: a classic blue-to-navy gradient title bar, pixelated window close icons, gray container canvas (`#C0C0C0`), and physical beveled edges.

### Floating Stickers & Web Toys
- Draggable, interactive sticker overlays including swimming goldfish, floating glossy bubbles with realistic transparency reflections, an 8-bit recycling bin icon, and pixel speech bubbles displaying nostalgic emoticons and sound-effect glyphs.