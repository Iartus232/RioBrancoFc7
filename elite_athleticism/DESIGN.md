---
name: Elite Athleticism
colors:
  surface: '#f8f9fa'
  surface-dim: '#d9dadb'
  surface-bright: '#f8f9fa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4f5'
  surface-container: '#edeeef'
  surface-container-high: '#e7e8e9'
  surface-container-highest: '#e1e3e4'
  on-surface: '#191c1d'
  on-surface-variant: '#43474e'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#74777f'
  outline-variant: '#c4c6cf'
  surface-tint: '#476083'
  primary: '#000613'
  on-primary: '#ffffff'
  primary-container: '#001f3f'
  on-primary-container: '#6f88ad'
  inverse-primary: '#afc8f0'
  secondary: '#3a5f94'
  on-secondary: '#ffffff'
  secondary-container: '#9fc2fe'
  on-secondary-container: '#294f83'
  tertiary: '#705d00'
  on-tertiary: '#ffffff'
  tertiary-container: '#c9a900'
  on-tertiary-container: '#4c3f00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d4e3ff'
  primary-fixed-dim: '#afc8f0'
  on-primary-fixed: '#001c3a'
  on-primary-fixed-variant: '#2f486a'
  secondary-fixed: '#d5e3ff'
  secondary-fixed-dim: '#a7c8ff'
  on-secondary-fixed: '#001b3c'
  on-secondary-fixed-variant: '#1f477b'
  tertiary-fixed: '#ffe16d'
  tertiary-fixed-dim: '#e9c400'
  on-tertiary-fixed: '#221b00'
  on-tertiary-fixed-variant: '#544600'
  background: '#f8f9fa'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 64px
    fontWeight: '900'
    lineHeight: 72px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '700'
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
  label-bold:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  button:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '700'
    lineHeight: 16px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style

The design system is engineered for the Rio Branco FC7 Football Academy, capturing the prestige of elite European football clubs while maintaining the high-energy pulse of a modern sports training facility. The brand personality is **authoritative, aspirational, and disciplined.** It speaks to both the young athlete dreaming of professional play and the parent seeking a structured, high-quality environment.

The visual style is **Corporate / Modern with a Sport Edge**, characterized by high-contrast typography, a deep "stadium-lights" color palette, and a sophisticated use of depth. It avoids the cluttered "noisy" look of amateur sports sites in favor of a clean, structured layout that exudes professionalism and trust. 

Key visual drivers:
- **Kinetic Energy:** Use of subtle diagonal accents and italicized display type.
- **Prestige:** Gold accents used sparingly to signify "gold-standard" training.
- **Clarity:** Heavy use of white space and crisp borders to ensure information is easily digestible.

## Colors

The color palette is derived directly from the Rio Branco FC7 crest, utilizing deep blues to establish institutional authority.

- **Navy Base (#001F3F):** The primary color for headers, footers, and deep backgrounds. It provides a more sophisticated foundation than pure black.
- **Royal Blue (#003366):** Used for interactive elements, secondary containers, and sport-related iconography.
- **Championship Gold (#FFD700):** Reserved exclusively for high-impact Call to Action (CTA) buttons, membership highlights, and "Winner" states.
- **Depth Black (#000000):** Used primarily for typography in light modes and for deep gradient overlays on photography to ensure text legibility.
- **Contrast White (#FFFFFF):** The primary background color for content areas to ensure maximum readability and a clean, modern feel.

## Typography

The typography strategy pairs **Montserrat** for its geometric, athletic strength and **Inter** for its unparalleled legibility in functional UI.

- **Headlines:** Use Montserrat in Bold or Black weights. For hero sections, use `display-lg` with tight letter spacing. Headers should always feel structural and "solid."
- **Body:** Inter is used for all long-form text. Its neutral tone allows the brand-heavy headlines to stand out without competing for attention.
- **Labels:** Small labels, such as "Upcoming Match" or "Age Group," should use `label-bold` with uppercase styling to mimic the "player name" aesthetic on jerseys.
- **Italics:** Use italics sparingly in Montserrat headlines to denote speed or action.

## Layout & Spacing

This design system utilizes a **12-column fluid grid** for desktop and a **4-column grid** for mobile. The spacing rhythm is built on an 8px baseline to ensure mathematical consistency.

- **Desktop:** 12 columns, 24px gutters, and 64px side margins. Content should be centered with a max-width of 1280px for optimal readability.
- **Mobile:** 4 columns, 16px gutters, and 16px side margins.
- **Sectioning:** Use large vertical padding (`xl`) between major sections to emphasize the premium, spacious feel of an elite club site.
- **Reflow:** Cards should transition from 3 or 4 columns on desktop to 1 column on mobile to ensure tap targets remain large and images remain impactful.

## Elevation & Depth

Visual hierarchy is managed through **Tonal Layers** and **Ambient Shadows**.

- **Surfaces:** The primary background is White. Secondary containers (like schedules or stats tables) use a very light grey (#F1F3F5) to create subtle separation.
- **Shadows:** Use a "Stadium Shadow" style—extremely soft, large-radius blurs with a low opacity (4-8%). This makes cards look like they are floating just above the pitch rather than being glued to it.
- **Active States:** When a component is interactive (hovered), it should slightly lift via a more pronounced shadow and a 2px vertical translation (upwards) to provide tactile feedback.
- **Overlays:** Dark Navy gradients should be applied to the bottom 40% of hero images to ensure white typography remains accessible.

## Shapes

The shape language is **Soft (0.25rem / 4px)**. This choice balances the aggressive nature of competitive sports with the approachability of an educational academy.

- **Standard Elements:** Inputs, buttons, and small tags use a 4px radius.
- **Containers:** Large cards and modal windows use `rounded-lg` (8px) for a smoother appearance.
- **Action Elements:** CTA buttons are strictly rectangular with the 4px radius to maintain a "blocky," strong appearance reminiscent of jersey numbers and field markings.

## Components

### Buttons
- **Primary:** Gold (#FFD700) background with Navy text. Bold Montserrat. This is for "Register Now" or "Join the Team."
- **Secondary:** Navy (#001F3F) background with White text.
- **Ghost:** Royal Blue border and text, transparent background.

### Input Fields
- White background with a 1px border (#DEE2E6). Focus state uses a 2px Royal Blue border and a soft blue outer glow.

### Cards
- White background, 8px corner radius, and the "Stadium Shadow." 
- **Sport-Specific Detail:** A 4px Gold top-border can be used on "Featured" or "Elite" category cards to distinguish them.

### Chips/Tags
- Small, uppercase labels used for age groups (e.g., "SUB-15"). Navy background with White text or Gold background for "MVP/Featured."

### Progress Bars
- Used for player stats or enrollment capacity. Royal Blue fill on a Light Grey track.

### Lists
- Used for match schedules. Alternating light grey/white background rows with Navy text and a Royal Blue chevron for drill-down actions.