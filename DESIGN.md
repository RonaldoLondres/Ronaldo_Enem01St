---
name: ENEM Precision Prep
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#45464d'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#76777d'
  outline-variant: '#c6c6cd'
  surface-tint: '#565e74'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#131b2e'
  on-primary-container: '#7c839b'
  inverse-primary: '#bec6e0'
  secondary: '#4059aa'
  on-secondary: '#ffffff'
  secondary-container: '#8fa7fe'
  on-secondary-container: '#1d3989'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#251a00'
  on-tertiary-container: '#a67e00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#dce1ff'
  secondary-fixed-dim: '#b6c4ff'
  on-secondary-fixed: '#00164e'
  on-secondary-fixed-variant: '#264191'
  tertiary-fixed: '#ffdf9a'
  tertiary-fixed-dim: '#f7be1d'
  on-tertiary-fixed: '#251a00'
  on-tertiary-fixed-variant: '#5a4300'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Source Serif 4
    fontSize: 19px
    fontWeight: '400'
    lineHeight: 32px
    letterSpacing: 0.005em
  body-md:
    fontFamily: Source Serif 4
    fontSize: 17px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: 0.005em
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '600'
    lineHeight: 20px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-desktop: 1.5rem
  margin: 1rem
  margin-tablet: 1.5rem
  margin-desktop: 2.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

The design system establishes a high-performance, distraction-free environment tailored for students preparing for the Exame Nacional do Ensino Médio (ENEM). Combining academic rigor with modern digital ergonomics, the UI channels the institutional authority of official INEP examination booklets while removing visual friction, eye strain, and cognitive overload.

The aesthetic fuses **Modern Editorial** with **Tactile Utility**:
- **Clarity over ornament:** Generous margins, calculated typographic scales, and high-legibility text blocks recreate the seriousness of paper examinations without the clutter.
- **Cognitive pacing:** Deliberate balance between high-contrast reading surfaces and gentle, calming backgrounds to support extended 5-hour study blocks.
- **Emotional balance:** The system conveys confidence, seriousness, and academic structure, counteracted by warm, empowering affirmative signals upon problem resolution.

## Colors

The palette grounds the examination experience in institutional stability, with targeted high-contrast accents dedicated strictly to structural orientation, performance feedback, and thematic grouping.

### Semantic & Knowledge Area Tokens
- **Canvas Base:** `#F8FAFC` (Slate 50) delivers an off-white ground that avoids the harsh glare of `#FFFFFF` during prolonged reading sessions.
- **Card & Question Surface:** `#FFFFFF` (Pure White) provides crisp contrast against the base canvas for isolated cognitive focus.
- **Institutional Primary:** `#0F172A` (Slate 900) serves as primary text and structural framing, paired with `#1E3A8A` (Deep Navy) for primary actions, navigational anchors, and active states.
- **ENEM Gold Accent:** `#EAB308` (Amber Gold) used sparingly for progress highlights, key metrics, streak counters, and active question numbers.
- **Validation Signals:**
  - *Correct / Acerto:* `#16A34A` (Emerald 600) with soft surface fill `#DCFCE7` (Emerald 50).
  - *Incorrect / Erro:* `#DC2626` (Carmine 600) with soft surface fill `#FEE2E2` (Red 50).
- **Knowledge Domains (Badges & Section Anchors):**
  - *Linguagens, Códigos e suas Tecnologias:* Border & Text `#D97706` (Amber 600), Fill `#FEF3C7` (Amber 100).
  - *Ciências Humanas e suas Tecnologias:* Border & Text `#0284C7` (Sky 600), Fill `#E0F2FE` (Sky 100).
  - *Ciências da Natureza e suas Tecnologias:* Border & Text `#059669` (Emerald 600), Fill `#D1FAE5` (Emerald 100).
  - *Matemática e suas Tecnologias:* Border & Text `#7C3AED` (Violet 600), Fill `#EDE9FE` (Violet 100).

## Typography

The typographic strategy pairs **Plus Jakarta Sans** for crisp, structural UI chrome, navigation, timers, and quantitative metadata with **Source Serif 4** for long-form exam prompts, support texts, excerpts, and stimulus questions. 

- **Source Serif 4** honors the format of printed Brazilian exams while providing modern optical legibility on OLED and Retina displays. Its balanced serifs allow readers to digest multi-paragraph philosophical essays or science problem statements without eye fatigue.
- Paragraph spacing within question texts strictly adheres to a bottom margin of `1.25em` with a max measure (line length) of 68 characters (`68ch`) on desktop viewports.
- Alternative options (A–E) rely on `body-md` for clear visual scanning, while alternative keys (A, B, C, D, E) are rendered in bold `Plus Jakarta Sans` to create an unmistakable typographic pivot.

## Layout & Spacing

The layout is built mobile-first, ensuring students can resolve exams with single-handed thumb navigation on handheld devices while scaling cleanly to desktop dual-column layouts.

- **Mobile Viewport (<768px):** Single-column vertical stream. The sticky header houses question metadata, timer, and quick-jump sheet trigger. The main content flows: Category Badge → Question Enunciation → Stimulus Graphic/Text → Alternatives A–E → Floating/Pinned Bottom Navigation bar.
- **Desktop Viewport (≥1024px):** Fixed-width centered canvas with a dual-column split:
  - Left column (65% width): Text base, references, supporting imagery, and problem enunciation.
  - Right column (35% width, sticky): A–E Answer selector cards, confirmation triggers, and resolution breakdown.
- **Rhythm:** An 8pt spatial grid anchors all padding and margins, guaranteeing consistent tapping areas (minimum target height of 48px for all mobile interactive targets).

## Elevation & Depth

This system intentionally departs from heavy drop shadows to preserve a clean, academic feel, relying instead on tonal separation, calibrated borders, and subtle structural elevation:

- **Level 0 (Canvas):** `#F8FAFC` flat surface.
- **Level 1 (Card Surface):** `#FFFFFF` bordered with `1px solid #E2E8F0` and an ambient tint: `box-shadow: 0 1px 3px 0 rgba(15, 23, 42, 0.04)`.
- **Level 2 (Hover / Active Options):** Subtle card lift for interactive alternatives: `box-shadow: 0 4px 6px -1px rgba(15, 23, 42, 0.08), 0 2px 4px -2px rgba(15, 23, 42, 0.04)`.
- **Level 3 (Sticky Headers / Modals / Question Drawer):** Pinned chrome uses translucent background backing with blur: `background-color: rgba(255, 255, 255, 0.92); backdrop-filter: blur(8px);` accompanied by a border-bottom of `1px solid #E2E8F0`.

## Shapes

The interface adopts a disciplined roundedness (`0.5rem` / `8px` baseline). This balances approachable software ergonomics with the structured geometric look of test sheets.

- **Question and Content Cards:** `0.5rem` (`rounded-md`) maintaining precise edges.
- **Buttons and Inputs:** `0.5rem` (`rounded-md`) ensuring clear tap ergonomics.
- **Alternative Key Badges (A, B, C, D, E):** `0.375rem` (`rounded-sm`) for compact, pill-neutral identification tags.
- **Domain & Area Tags:** Fully rounded pill (`9999px`) to distinguish categorical metadata from interactive cards.

## Components

### Question Cards & Alternatives (A through E)
- **Question Card Container:** Pure white background, `1px solid #E2E8F0`, padding `space-md` (mobile) to `space-xl` (desktop).
- **Alternative Item (`A–E`):**
  - *Default:* White background, border `1.5px solid #E2E8F0`, horizontal flex row aligning the badge letter and option text with `space-md` gap.
  - *Hover/Focus:* Border changes to `#94A3B8`, background shifts to `#F8FAFC`.
  - *Selected (Pending Submission):* Border `2px solid #1E3A8A`, background `#EFF6FF`. Letter badge becomes `#1E3A8A` background with white text.
  - *State - Correct (`Acerto`):* Border `2px solid #16A34A`, background `#F0FDF4`. Letter badge fills `#16A34A` with white text. Shows success check icon.
  - *State - Incorrect (`Erro`):* Border `2px solid #DC2626`, background `#FEF2F2`. Letter badge fills `#DC2626` with white text. Displays correct counterpart concurrently with a `#16A34A` outline.

### Buttons & Interactive Triggers
- **Primary Action (Confirmar Resposta / Próxima):** Height 48px, background `#1E3A8A`, text `#FFFFFF`, font `Plus Jakarta Sans` 600, border radius `0.5rem`. On hover: `#0F172A`.
- **Secondary Action (Pular Questão / Ver Gabarito):** Height 48px, background transparent, border `1px solid #CBD5E1`, text `#334155`.
- **Bookmark / Flag Trigger:** 44x44px square button, border radius `0.5rem`, displaying an SVG bookmark icon. Active state turns icon fill to `#EAB308`.

### Domain Badges (Áreas do Conhecimento)
- Height 24px, uppercase `label-sm`, tracking `0.05em`.
- Constructed as an inline-flex element with a 6px colored dot preceding the text:
  - *Linguagens:* Dot `#D97706`, Text `#92400E`, Background `#FEF3C7`.
  - *Humanas:* Dot `#0284C7`, Text `#075985`, Background `#E0F2FE`.
  - *Natureza:* Dot `#059669`, Text `#065F46`, Background `#D1FAE5`.
  - *Matemática:* Dot `#7C3AED`, Text `#5B21B6`, Background `#EDE9FE`.

### Exam Progress Header & Timer
- Persistent sticky banner containing question indicator (`Questão 142 de 180`), a countdown clock (HH:MM:SS format in tabular monospaced digits), and an ENEM Gold segmented linear progress indicator (`h-1.5`, background `#E2E8F0`, progress fill `#EAB308`).