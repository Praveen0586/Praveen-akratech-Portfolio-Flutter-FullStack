---
name: Obsidian Engineering
colors:
  surface: '#0f131d'
  surface-dim: '#0f131d'
  surface-bright: '#353944'
  surface-container-lowest: '#0a0e18'
  surface-container-low: '#171b26'
  surface-container: '#1c1f2a'
  surface-container-high: '#262a35'
  surface-container-highest: '#313540'
  on-surface: '#dfe2f1'
  on-surface-variant: '#bcc9cd'
  inverse-surface: '#dfe2f1'
  inverse-on-surface: '#2c303b'
  outline: '#869397'
  outline-variant: '#3d494c'
  surface-tint: '#4cd7f6'
  primary: '#4cd7f6'
  on-primary: '#003640'
  primary-container: '#06b6d4'
  on-primary-container: '#00424f'
  inverse-primary: '#00687a'
  secondary: '#4edea3'
  on-secondary: '#003824'
  secondary-container: '#00a572'
  on-secondary-container: '#00311f'
  tertiary: '#c0c1ff'
  on-tertiary: '#1000a9'
  tertiary-container: '#9a9dff'
  on-tertiary-container: '#211cb4'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#acedff'
  primary-fixed-dim: '#4cd7f6'
  on-primary-fixed: '#001f26'
  on-primary-fixed-variant: '#004e5c'
  secondary-fixed: '#6ffbbe'
  secondary-fixed-dim: '#4edea3'
  on-secondary-fixed: '#002113'
  on-secondary-fixed-variant: '#005236'
  tertiary-fixed: '#e1e0ff'
  tertiary-fixed-dim: '#c0c1ff'
  on-tertiary-fixed: '#07006c'
  on-tertiary-fixed-variant: '#2f2ebe'
  background: '#0f131d'
  on-background: '#dfe2f1'
  surface-variant: '#313540'
typography:
  display-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 56px
    fontWeight: '800'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  code-snippet:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 22px
  label-mono:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.06em
  label-ui:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 4rem
  margin-tablet: 2rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system crafts an elite, high-velocity identity for a modern mobile and systems architect specializing in Flutter and AI-assisted workflows. Rooted in an aesthetic of precision engineering, the system balances technical depth with refined product design polish. 

### Brand Character & Aesthetic
- **Atmosphere:** Dark-mode primary, architectonic, computational, and immaculate. It channels the precision of high-end developer runtimes combined with the bespoke clarity of a boutique digital product lab.
- **Design Movement:** Glassmorphic High-Tech Minimal. Translucent dark planes, hair-thin chromatic borders, diffused structural glows, and terminal-grade monospaced accents.
- **Emotional Response:** Confidence, rigor, and cutting-edge fluidity. Visitors should perceive an engineer who operates at the intersection of robust mobile architecture (Flutter/Dart) and next-generation autonomous toolchains (Claude, Copilot, Gemini).

## Colors

The palette leverages a deep, void-like canvas offset by electric algorithmic accents to signify compiled efficiency, active state transitions, and neural computation.

- **Background & Canvas (`#0B0F19`):** Deep Obsidian Slate. Provides infinite contrast for neon syntax tokens and translucent card substrates without the eye fatigue of pure `#000000`.
- **Primary Accent (`#06B6D4` - Cyber Cyan):** Represents interface velocity, active execution states, dynamic mobile viewports, and primary interactive surfaces.
- **Secondary Accent (`#10B981` - Compiler Emerald):** Denotes production stability, live status indicators, clean metrics, and AI workflow telemetry.
- **Tertiary Accent (`#6366F1` - Synapse Indigo):** Reserved for generative AI indicators, metadata tags, and semantic pipeline highlights.
- **Surface Roles:**
  - `surface-base`: `#0B0F19` (Root background canvas)
  - `surface-elevated`: `rgba(15, 23, 42, 0.65)` (Glassmorphic cards with frosted blur)
  - `surface-overlay`: `rgba(30, 41, 59, 0.50)` (Hover states, elevated popovers, terminal code blocks)
  - `border-hairline`: `rgba(255, 255, 255, 0.08)` (Subtle separation)
  - `border-active`: `rgba(6, 182, 212, 0.35)` (Focus rings, featured case studies)

## Typography

The typographic hierarchy establishes distinct semantic layers:
- **Headings (Plus Jakarta Sans):** Geometric, contemporary, and assertive. Tight letter-spacing reinforces clean, architectural tension across project titles and section headers.
- **Narrative & UI (Inter):** Highly legible, neutral workhorse engineered for complex digital interfaces, reading comfort, and case study documentation.
- **Technical Telemetry & Code (JetBrains Mono):** Monospaced precision for file structures, API endpoints, runtime metrics, and AI workflow metadata tags. Always typeset in upper or micro-case with deliberate tracking.

## Layout & Spacing

The layout is constructed on a 12-column fluid grid system pinned to a maximum container width of `1280px` for desktop screens, collapsing cleanly to 8 columns on tablets and 4 columns on mobile viewports.

### Rhythm & Responsive Rules
- **Desktop (1024px+):** Outer canvas margins set to `margin` (`4rem`). Gutters are `1.5rem`. Case studies split comfortably into asymmetrical 7/5 or 8/4 grid compositions (interactive prototype alongside technical deep dive).
- **Tablet (768px - 1023px):** Margins reduce to `margin-tablet` (`2rem`). Split cards consolidate to 8 columns with stacked preview viewports.
- **Mobile (<768px):** Margins tighten to `margin-mobile` (`1.25rem`). Grids collapse into a singular 4-column flow. Code snippets horizontally scroll with sticky line-number gutters.
- **Spacing Scale Application:**
  - `space-xs` (4px): Tag padding, dot-indicator spacing.
  - `space-sm` (8px): Icon-to-label inline offsets, chip gaps.
  - `space-md` (16px): Input padding, inside element grouping, compact card padding.
  - `space-lg` (24px): Standard card interior breathing room, modular stack gaps.
  - `space-xl` (40px): Section subdivisions and case study phase milestones.

## Elevation & Depth

Visual hierarchy uses frosted glassmorphism anchored on layered darkness rather than drop shadows.

- **Substrate Tiers:**
  - **Tier 0 (Canvas):** Pure `#0B0F19`. Zero blur. Optional subtle background matrix grid pattern composed of `rgba(255, 255, 255, 0.02)` 32px raster squares.
  - **Tier 1 (Base Cards & Modules):** `rgba(15, 23, 42, 0.65)` with `backdrop-filter: blur(16px)` and a `1px` continuous border in `rgba(255, 255, 255, 0.07)`.
  - **Tier 2 (Interactive Floating Elements / Flyouts):** `rgba(30, 41, 59, 0.75)` with `backdrop-filter: blur(24px)`, framed by `1px` border of `rgba(6, 182, 212, 0.2)`.
- **Glow & Atmosphere:** High-blur radial gradients placed behind focal elements (e.g., a cyan/emerald conic blur with 120px diffusion at 10% opacity behind primary mobile mockups).
- **Interaction Depth:** On hover, surfaces do not lift mechanically along the Z-axis. Instead, their border transitions to `rgba(6, 182, 212, 0.45)`, accompanied by an inner hairline highlight (`inset 0 1px 0 0 rgba(255, 255, 255, 0.15)`).

## Shapes

The design uses a balanced rounded architecture (Level 2: `0.5rem` / 8px default, `1rem` / 16px for cards, `1.5rem` / 24px for large viewports). 

- **Cards & Case Study Frames:** 16px corner radius (`rounded-lg`), mimicking modern iOS and Android device contours.
- **Buttons & System Pills:** 8px corner radius (`rounded`) for compact tools; full pill radii strictly for contextual metadata badges and status pills.
- **Code Terminals & Syntax Insets:** 8px corner radius (`rounded`) with square interior dividers for tab headers and status lines.

## Components

### 1. Interactive Case Study Cards (Offer Mela, Polymer Market, Relexwise, Avora Markets)
- **Structure:** Frosted 16px rounded surface featuring a split-pane layout: architecture specs and technical impact on the left, an embedded interactive mobile device canvas on the right.
- **Header:** Features the project codename in `headline-md`, flanked by monospaced platform tags (`FLUTTER`, `DART`, `OFFLINE-FIRST`).
- **Telemetry Bar:** Mini stat grid displaying quantified milestones (e.g., `45% Latency Drop`, `100k+ MAU`) using `JetBrains Mono` values capped with subtle emerald glows.

### 2. Buttons & CTAs
- **Primary (Action):** Solid fill with gradient blend from Cyan (`#06B6D4`) to Emerald (`#10B981`), black `Inter` semi-bold text, no border. Hover triggers a subtle external cyan luminescent sheen.
- **Secondary (Terminal/Source):** Deep glass background (`rgba(15, 23, 42, 0.8)`), white text, `1px` hairline border `rgba(255, 255, 255, 0.12)`.
- **Ghost/Icon Button:** Zero background; cyan accent on hover with a 4px circular pulse indicator.

### 3. Interactive AI Badges & Tech Chips
- **Design:** Monospaced label pills (`label-mono`) with a dual-layer treatment. A subtle dark base with a 1px border matching the accent color at 20% opacity.
- **AI Indicator Variants:**
  - *Claude*: Indigo accent badge with a spark glyph.
  - *Gemini*: Cyan accent badge with a dual-ring glyph.
  - *Copilot*: Emerald accent badge with a branch icon.
- **State:** Active badges emit a gentle 4px ambient halo in their signature color.

### 4. Code Snippets & Terminal Windows
- **Frame:** Window header containing three 10px circular dots (soft slate, non-distracting) and an embedded file path indicator (e.g., `lib/features/engine/bloc.dart`).
- **Body:** `JetBrains Mono` with custom dark-palette syntax highlighting: constants in Cyan, types in Emerald, keywords in Indigo, muted comments in Slate.
- **Actions:** Quick-copy button positioned top-right that animates from a copy glyph to a green checkmark on click.

### 5. Input Fields & Contact Triggers
- **Base:** Dark inset field (`rgba(11, 15, 25, 0.8)`) with `1px` border (`rgba(255, 255, 255, 0.1)`).
- **Focus:** Border transitions smoothly to `#06B6D4` with an inner shadow and an ambient cyan field blur. Placeholder text rests in muted slate (`#64748B`).

### 6. Lists & Milestone Timelines
- **Workflow Pipeline:** Vertical dashed timeline connector (`rgba(255, 255, 255, 0.1)`) joining engineering milestones, equipped with pulsating status nodes (Emerald for production release, Cyan for active architecture).