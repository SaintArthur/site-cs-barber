---
name: CS Barber
description: Near-black navy ground, one gold accent, flat hairline-ruled surfaces — the barbershop-software category convention executed at full fidelity.
colors:
  black: "#0a0d14"
  navy: "#1c263f"
  navy-deep: "#141b2e"
  field: "#121826"
  gold: "#c9a56a"
  gold-light: "#e2ca97"
  gold-deep: "#a27947"
  cream: "#f1e6cf"
  white: "#ffffff"
  muted: "#9aa3b8"
  muted-bright: "#c3cadb"
  line: "rgba(226,202,151,.16)"
  line-strong: "rgba(226,202,151,.30)"
  error: "#e0616b"
  whatsapp: "#25D366"
  bella-rose: "#dd9db3"
typography:
  display:
    fontFamily: "Poppins, system-ui, sans-serif"
    fontSize: "clamp(33px, 7.2vw, 58px)"
    fontWeight: 500
    lineHeight: 1.04
    letterSpacing: "-.03em"
  headline:
    fontFamily: "Poppins, system-ui, sans-serif"
    fontSize: "clamp(27px, 4.4vw, 40px)"
    fontWeight: 500
    lineHeight: 1.1
    letterSpacing: "-.022em"
  title:
    fontFamily: "Poppins, system-ui, sans-serif"
    fontSize: "18.5px"
    fontWeight: 500
    lineHeight: 1.1
    letterSpacing: "-.022em"
  lede:
    fontFamily: "Poppins, system-ui, sans-serif"
    fontSize: "17px"
    fontWeight: 300
    lineHeight: 1.62
  body:
    fontFamily: "Poppins, system-ui, sans-serif"
    fontSize: "16px"
    fontWeight: 300
    lineHeight: 1.6
  body-small:
    fontFamily: "Poppins, system-ui, sans-serif"
    fontSize: "15.5px"
    fontWeight: 300
    lineHeight: 1.6
  label:
    fontFamily: "Poppins, system-ui, sans-serif"
    fontSize: "11.5px"
    fontWeight: 500
    letterSpacing: ".13em"
  tier-label:
    fontFamily: "Poppins, system-ui, sans-serif"
    fontSize: "12px"
    fontWeight: 500
    letterSpacing: ".17em"
  wordmark:
    fontFamily: "Poppins, system-ui, sans-serif"
    fontSize: "17px"
    fontWeight: 600
    letterSpacing: ".14em"
  action:
    fontFamily: "Poppins, system-ui, sans-serif"
    fontSize: "15px"
    fontWeight: 600
    letterSpacing: "-.005em"
rounded:
  control: "6px"
  card: "10px"
  focus: "3px"
  pill: "99px"
spacing:
  section: "clamp(64px, 8.5vw, 104px)"
  section-half: "clamp(36px, 5vw, 56px)"
  gutter: "clamp(20px, 5vw, 28px)"
  header: "64px"
  container: "1160px"
components:
  button-primary:
    backgroundColor: "{colors.gold}"
    textColor: "{colors.black}"
    typography: "{typography.action}"
    rounded: "{rounded.control}"
    padding: "12px 22px"
    height: "46px"
  button-primary-hover:
    backgroundColor: "{colors.gold-light}"
    textColor: "{colors.black}"
  button-outline:
    backgroundColor: "transparent"
    textColor: "{colors.cream}"
    typography: "{typography.action}"
    rounded: "{rounded.control}"
    padding: "12px 22px"
    height: "46px"
  button-outline-hover:
    backgroundColor: "rgba(201,165,106,.07)"
    textColor: "{colors.cream}"
  button-header:
    backgroundColor: "{colors.gold}"
    textColor: "{colors.black}"
    rounded: "{rounded.control}"
    padding: "10px 18px"
    height: "40px"
  card:
    backgroundColor: "rgba(28,38,63,.26)"
    textColor: "{colors.muted-bright}"
    rounded: "{rounded.card}"
    padding: "clamp(22px, 3.4vw, 30px)"
  card-form:
    backgroundColor: "rgba(10,13,20,.55)"
    textColor: "{colors.cream}"
    rounded: "{rounded.card}"
    padding: "clamp(20px, 3vw, 28px)"
  input:
    backgroundColor: "{colors.field}"
    textColor: "{colors.cream}"
    rounded: "{rounded.control}"
    padding: "12px 13px"
    size: "16px"
  input-focus:
    backgroundColor: "#161d2e"
    textColor: "{colors.cream}"
  chip-static:
    backgroundColor: "transparent"
    textColor: "{colors.muted-bright}"
    rounded: "{rounded.pill}"
    padding: "0 13px"
    height: "32px"
  chip-toggle:
    backgroundColor: "rgba(28,38,63,.26)"
    textColor: "{colors.muted-bright}"
    rounded: "{rounded.control}"
    padding: "9px 12px"
    height: "46px"
  chip-toggle-checked:
    backgroundColor: "rgba(28,38,63,.26)"
    textColor: "{colors.cream}"
  nav-link:
    backgroundColor: "transparent"
    textColor: "{colors.muted-bright}"
    size: "14px"
  nav-link-hover:
    textColor: "{colors.cream}"
  header:
    backgroundColor: "rgba(10,13,20,.82)"
    textColor: "{colors.cream}"
    height: "64px"
---

# Design System: CS Barber

## Overview

**Creative North Star: "The Lit Back Bar"**

A barbershop after hours: the room goes nearly black, the mirrors are edged in a thin warm line, and exactly one brass fitting catches the light. Nothing glows, nothing floats, nothing is embossed. The surfaces are flat panels of near-black navy separated by hairlines the colour of brass at sixteen percent — you read the structure by where the light stops, not by shadow or fill.

This is the category convention taken seriously rather than decorated. The page sits alongside Booksy Biz, AppBarber and Trinks and reads as the same kind of object: a fixed header, a left-aligned hero with a product screenshot beside it, a two-tier module block, a numbered implantation sequence, an accordion, a form. The discipline is not in inventing a form the category does not have; it is in refusing every cheap signal the category reaches for — no gradient fills, no glow, no card lift, no stock iconography, no second accent. One typeface at one light weight carries the body copy; headings step up one notch to medium and never further. Density is generous rather than packed: sections breathe on a clamped rhythm that never falls below 64px, and the eye is given one thing at a time.

The ground is not pure black and the text is not pure white. Both are warmed — a navy-black and a cream — so the page reads as a lit interior rather than a terminal. That warmth is the entire atmospheric budget; everything else is restraint.

**Key Characteristics:**
- Near-black navy ground with cream text; no pure black, no pure white body copy
- A single gold accent, scarce by rule
- Flat surfaces, one-pixel hairlines, zero gradient fills
- Poppins alone: body at 300, headings at 500, actions at 600
- Hairline-opened sections on a clamped vertical rhythm
- Browser chrome themed to match: selection, caret, scrollbar, focus ring
- Motion is one gesture: a short rise-and-fade on scroll, staggered

## Colors

A warm-dark palette: two near-blacks and a navy for ground and surface, a cream and two cool greys for text, and one brass gold that is the only saturated colour on the page.

### Primary
- **Brass Gold** (`{colors.gold}`): The single accent. It fills the primary action button and the "Em breve" ribbon; it draws the step ordinals, the accordion chevron, the select caret, the footer markers and the field caret. Nothing else on the page is saturated.
- **Lit Brass** (`{colors.gold-light}`): The hover state of the gold button, the emphasised span inside the H1, the micro-link under a profile card, the skip link, and the focus ring. It is gold with the lights up.
- **Deep Brass** (`{colors.gold-deep}`): Scrollbar thumb on hover and the Firefox scrollbar thumb colour. Browser chrome only; never a surface or text colour.

### Neutral
- **Shop Black** (`{colors.black}`): The page ground, the scrollbar track, and the ink on gold buttons and the gold ribbon. Not pure black — it carries a navy cast.
- **Back-Room Navy** (`{colors.navy-deep}`): The one tonal lift in the system. It backs the trial section and the inside of screenshot frames, distinguishing a panel from the page by tone rather than by shadow.
- **Smoke Navy** (`{colors.navy}`): Never used at full strength. It appears only at 20–26% alpha as the wash inside cards, module tiles, toggle chips and footer links.
- **Field Navy** (`{colors.field}`): Input and select interiors only. One step darker than the card it sits in, so the field reads as a recess.
- **Warm Cream** (`{colors.cream}`): All headings and all primary body text. Warmer and softer than white; this is the page's reading colour.
- **Cool Grey** (`{colors.muted-bright}`): Secondary prose — supporting paragraphs, card bodies, FAQ answers, nav links at rest. The tier just below cream.
- **Dim Grey** (`{colors.muted}`): Functional and ancillary text — uppercase labels, fact captions, the legal line. The floor for this colour is 11.5px.
- **Hairline** (`{colors.line}`): Every rule and every default border. It is brass at 16% alpha, not a grey, so the lines carry the same warmth as the accent.
- **Hairline Bright** (`{colors.line-strong}`): The raised hairline (30%) for hover borders, the secondary button's resting edge, and the inset frames inside the overlap composition.
- **Paper White** (`{colors.white}`): Declared in the token block and held in reserve; no element paints with it today.

### Tertiary
- **Alert Coral** (`{colors.error}`): Invalid field borders and their error text. The only non-gold colour allowed to signal.
- **WhatsApp Green** (`{colors.whatsapp}`): The WhatsApp glyph only, at its brand value. Never applied to text or a surface.
- **Bella Rose** (`{colors.bella-rose}`): The sibling-product marker in the footer, identifying CS Bella. Never used for CS Barber's own content.

### Named Rules

**The One Brass Rule.** Gold is the only saturated colour on the page and it is spent on the action and the sequence. As a *fill* it appears at most twice in a viewport: the primary button and the "Em breve" ribbon. Everywhere else it is a stroke, a numeral or a marker at icon scale. A third gold fill on a screen means one of them is wrong.

**The Warm Hairline Rule.** Dividers are brass at 16% alpha, never neutral grey and never solid. A new divider inherits `{colors.line}`; raising a border to `{colors.line-strong}` is a state change (hover, inset), not a decoration.

**The No-Gradient Rule.** No surface in this system carries a gradient fill. The single `linear-gradient` in the stylesheet draws the select caret's two triangles at 5x5px — a shape, not a fill. Colour arrives as flat paint or not at all.

## Typography

**Display Font:** Poppins (with system-ui, sans-serif)
**Body Font:** Poppins (with system-ui, sans-serif)

**Character:** One geometric sans carries the whole page, and the hierarchy is built from weight and tracking rather than from a second face. Body copy runs at Light (300), which keeps long Portuguese paragraphs airy on a phone; headings step to Medium (500) with negative tracking that tightens as the size grows. Nothing is set heavier than 600, and only the action label and the wordmark go that far. Self-hosted WOFF2 in Latin and Latin-Extended subsets; zero third-party font requests.

### Hierarchy
- **Display** (500, `clamp(33px, 7.2vw, 58px)`, 1.04, `-.03em`): The H1 only. Three lines, left-aligned, with one emphasised span in Lit Brass — an `<em>` with its italic removed.
- **Headline** (500, `clamp(27px, 4.4vw, 40px)`, 1.1, `-.022em`): Section H2s. One per section, standing alone.
- **Title** (500, 18.5px, 1.1): Item headings inside lists — module rows, steps, differentiators. Two siblings exist: `clamp(21px, 3vw, 26px)` for the two profile cards and 17px for the three audience cards.
- **Lede** (300, 17px, 1.62, max 40ch): The hero's supporting paragraph. Its `<b>` spans go to 500 and Warm Cream rather than to bold.
- **Body** (300, 16px, 1.6): The document default. Section descriptions run 16.5px at a 62ch cap; list and FAQ prose run 15.5px, capped between 48ch and 68ch per component.
- **Label** (500, 11.5px, `.13em`, uppercase, Dim Grey): Form field labels and fieldset legends.
- **Tier Label** (500, 12px, `.17em`, uppercase, Dim Grey): The two tier markers inside the module block. It labels a list that follows it, below and separate from the section heading.
- **Action** (600, 15px, `-.005em`): Button labels. The header's compact variant drops to 14px; the form's full-width submit rises to 16px.
- **Wordmark** (600, 17px, `.14em`): "CS **BARBER**" in the header, the second word in Lit Brass. The widest tracking in the system.

### Named Rules

**The One Face Rule.** Poppins is the only family. There is no display face, no mono, no serif, and no system font stack reached for as a shortcut. A new surface that needs a different voice gets it from weight (300 / 500 / 600) and tracking.

**The Naked Heading Rule.** A section heading stands alone. No eyebrow, no kicker, no ordinal and no coloured rule sits above an H2 — the heading carries its own weight. Ordinals appear only in the four implantation steps, where the sequence is the information. An uppercase tier label is legal *inside* a block, placed below the heading to divide a list; it is never promoted to sit above one.

**The Light Body Rule.** Body copy is weight 300. Emphasis inside it goes to 500 and Warm Cream, never to 700. Functional text never drops below 11.5px.

## Layout

A single centred column, `{spacing.container}` wide, with a fluid gutter of `{spacing.gutter}`. Everything lives inside one wrapper; nothing is full-bleed except the ground itself and the fixed header.

Vertical rhythm is governed by two clamps: `{spacing.section}` for the padding above and below every section, and `{spacing.section-half}` as its companion step. Each section opens with a one-pixel hairline across the full column width — suppressed on the first — so the page reads as a stack of ruled panels. The hero adds the 64px header height to its top padding; the differentiators section adds 54px to its bottom to clear the overhanging composition. Scroll padding is header height plus 16px, so an anchored jump never lands under the bar.

Internal rhythm is small and specific rather than a global scale: 16px between a heading and its description, `clamp(30px, 4vw, 46px)` from a section head to whatever follows it, 18–22px of padding inside list rows, `clamp(30px, 4vw, 44px)` between stacked blocks. Measure is capped per component, from 34rem on a section head to 40–68ch on prose.

**Breakpoints.** Three ascending, plus one inverse.
- **720px and up:** two-column profile pair, three-column audience cards, the four-up fact strip.
- **960px and up:** hero splits `1fr / 1.08fr` (text, screenshot); the differentiators pair and the footer links go to even columns; the trial section splits `.9fr / 1.1fr`; the module base list goes two-up with a 40px column gap.
- **959px and down:** the header switches — desktop nav and header CTA hide, the hamburger appears, and navigation moves to a full-width panel sliding down from under the bar.
- **519px and down:** hero actions stack full-width; the form grid and the toggle chips collapse to one column; the overlapping composition pulls back inside its frame.

Mobile-first in construction: every grid is a single column by default and gains columns upward.

**Motion.** One gesture. Elements marked for reveal rest at `opacity: 0, translateY(14px)`; an IntersectionObserver (12% bottom root margin, 6% threshold) marks each section visible as it enters and then unobserves it, releasing its children over 0.6s / 0.7s on `cubic-bezier(.16, 1, .3, 1)`. Order is controlled per element by a `--i` custom property at 70ms a step, typically 0 to 3 within a section. The accordion animates its own height over 0.34s on the same curve. `prefers-reduced-motion` collapses every transition to 0.001ms, disables smooth scrolling, and skips the observer so content is visible at rest.

### Named Rules

**The Hairline Opens Rule.** Every section but the first opens with a one-pixel `{colors.line}` rule across the column. It is the page's only section separator; do not add a background change, a spacer graphic or a decorative divider to do the same job.

**The One Gesture Rule.** Scroll motion is a 14px rise with a fade, staggered by `--i`. No parallax, no scale, no lateral slide, and nothing animates more than once.

## Elevation & Depth

This system is flat. Surfaces do not lift, and nothing uses shadow to signal interactivity or importance. Depth comes from three devices, in order of use: the warm hairline border; a tonal wash (Smoke Navy at 20–26% alpha over the black ground, or Back-Room Navy as a whole-section tone); and overlap, where the differentiators composition stacks a photograph, a desktop panel and a phone panel so they occlude each other.

Shadows exist in exactly four places and all four are contact shadows: large negative-spread blurs that darken the ground directly beneath an element so an overlapping image does not float. They are never ambient glows, never coloured, never hard-offset, and never attached to a hover state.

### Shadow Vocabulary
- **Button seat** (`box-shadow: 0 6px 18px -10px rgba(0,0,0,.7)`): On the gold button only, where bright paint meets the dark ground. Removed when disabled.
- **Photo contact** (`box-shadow: 0 8px 14px -10px rgba(0,0,0,.8)`): Under the barbershop photograph in the overlap composition.
- **Panel contact** (`box-shadow: 0 8px 14px -9px rgba(0,0,0,.85)`): Under the desktop panel that overhangs the photograph.
- **Phone contact** (`box-shadow: 0 7px 12px -8px rgba(0,0,0,.85)`): Under the phone panel, the topmost layer.

The header is the one surface that uses translucency for depth: `rgba(10,13,20,.82)` with a 14px backdrop blur, deepening to `.94` and gaining a bottom hairline once the page scrolls past 10px.

### Named Rules

**The Flat Surface Rule.** Cards, tiles, inputs and list rows have no shadow at any state. If a new surface needs to separate from the ground, it gets a hairline and a tonal wash — not elevation.

**The Contact-Only Rule.** A shadow is permitted only where something physically overlaps something else, and only as a negative-spread contact darkening. A shadow that reads as a glow, a drop or a hard offset does not belong in this world.

## Shapes

Two radii, applied by function rather than by size. Controls — buttons, inputs, selects, toggle chips, radio pills, module tiles, the skip link — take `{rounded.control}`. Containers that hold content — cards, screenshot frames, footer links, the form box, the photograph — take `{rounded.card}`. Inside the overlap composition the two inset frames step down to 8px and 12px so they read as nested objects rather than siblings. The focus ring rounds to `{rounded.focus}`. Fully round (`{rounded.pill}`) is reserved for genuinely pill-shaped objects: the static fact chips, the toggle track and the scrollbar thumb. The one true circle is the 13px toggle knob. The one sharp corner is the 2px "Em breve" ribbon, which is a stamp, not a control.

Borders are one pixel, always, and always a brass alpha. There are no 2px borders, no dashed or dotted strokes, and no outlines except the focus ring (2px Lit Brass at 3px offset). The accordion chevron and the select caret are both drawn from primitives — a rotated 1.5px L-shape and two 5px gradient triangles — rather than imported as glyphs. Icons are inline SVG pulled from a single hidden sprite, stroked or filled at `currentColor`, at 13–26px.

### Named Rules

**The Two Radius Rule.** 6px if the user acts on it, 10px if it holds content. Do not introduce a third radius for a new component; decide which side it is on.

**The Drawn Mark Rule.** Chevrons, carets and arrows are drawn in CSS or as inline SVG in the sprite. No icon font, no glyph character, no emoji, no bitmap, no third-party icon package — the page makes zero external requests and the marks are part of that commitment.

## Components

### Buttons
- **Shape:** Lightly rounded (`{rounded.control}`), minimum 46px tall, inline-flex with a 9px gap to an optional 15px arrow.
- **Primary:** Brass Gold fill, Shop Black label at weight 600, 12px/22px padding, carrying the button seat shadow. Hover lifts the fill to Lit Brass and nudges the arrow 3px right.
- **Secondary:** Transparent with a Hairline Bright edge and a cream label. Hover brings the border to full gold and washes the interior with gold at 7%.
- **States:** Both press to `scale(.985)` over 0.18s. Disabled drops to 50% opacity, suppresses the shadow and the press, and shows `not-allowed` — the form submit ships disabled in the HTML and is enabled by script.
- **Header variant:** 10px/18px padding, 40px tall, 14px label. Hidden below 960px, where it reappears at full size as the last item in the slide-down menu.
- **Form variant:** Full width, 52px tall, 16px label.

### Chips
- **Static chip:** A 32px pill with a Hairline edge, no fill, Cool Grey 13px text. Non-interactive; it states a fact.
- **Toggle chip:** A 46px control-radius row with the Smoke Navy wash, label left and a 30x17px track right. Checked brings the border to full gold, the text to Warm Cream and the track border to gold, and slides a 13px knob 13px right as it turns from Dim Grey to gold. The real checkbox is visually hidden; `:has(input:checked)` drives the styling.
- **Radio pill:** 76px minimum width, 44px tall, the same border-and-text promotion on check. No knob.

### Cards / Containers
- **Profile card:** The largest card — `clamp(22px, 3.4vw, 30px)` padding, card radius, Hairline edge, Smoke Navy at 26%. Hover raises the border to Hairline Bright over 0.3s and nothing else moves.
- **Audience card:** 22px padding, Smoke Navy at 22%, static.
- **Module tile:** Control radius, 14px/16px padding, laid out on an auto-fit grid from a 190px minimum. Name at 14.5px/500 in cream over a 12.5px Dim Grey gloss.
- **Form box:** `clamp(20px, 3vw, 28px)` padding over Shop Black at 55% — darker than its Back-Room Navy section, so the form recedes into the page rather than sitting on it.
- **Screenshot frame:** Card radius, Hairline edge, Back-Room Navy interior, overflow hidden. No device chrome, no browser bar, no bezel — the image is framed by a hairline and nothing else.

### Inputs / Fields
- **Style:** Field Navy interior, Hairline edge, control radius, 12px/13px padding. Font size is pinned at 16px so iOS does not zoom on focus; weight stays 300. The caret is gold.
- **Focus:** Border goes to full gold and the interior lifts to `#161d2e` over 0.2s. The native outline is suppressed on fields only; the global focus ring still serves everything else.
- **Error:** `aria-invalid="true"` turns the border Alert Coral and reveals a 12px coral message through a sibling selector — CSS, not script, controls the visibility.
- **Select:** Appearance stripped, caret drawn as two 5px triangles from paired linear gradients, with 36px right padding to clear it.
- **Layout:** Two-column grid at a 14px gap, collapsing to one below 520px. Fieldsets are borderless except for a top hairline, with an uppercase legend.

### Navigation
- **Header:** Fixed, 64px, translucent `rgba(10,13,20,.82)` over a 14px backdrop blur. Scrolling past 10px deepens the ground to `.94` and fades in a bottom hairline over 0.3s. Logo and wordmark left in a 44px minimum touch area, four 14px Cool Grey links at a 30px gap, gold CTA right.
- **Mobile (≤959px):** Links and CTA hide; a 44x44px two-bar hamburger appears and crosses into an X on open, each bar translating 6.5px and rotating ±45°. The menu is a fixed panel below the header at `rgba(10,13,20,.98)`, sliding from `translateY(-10px)` with opacity and visibility over 0.32s. Rows are 52px tall, hairline-separated, with the gold CTA last. It closes on link click and on Escape, returning focus to the hamburger.
- **Footer links:** Card-radius rows with a Smoke Navy wash, a 26px gold mark left, a name over an uppercase 12px caption, and a dimmed gold arrow right. Hover raises the border and translates 2px up — the only transform-based hover in the system. The sibling-product row swaps its mark to Bella Rose and carries a sharp 2px gold "Em breve" stamp.

### The Step Ladder
The implantation sequence. A CSS counter renders `decimal-leading-zero` ordinals in each row's `::before` — 01, 02, 03, 04 — at 13px/600 in Brass Gold with tabular numerals, spanning both rows of a two-column grid so the ordinal sits beside the heading and its paragraph. Rows are separated by top hairlines, the first suppressed. This is the only place in the system where a number precedes a heading, and the sequence is why.

### The Overlap Composition
Three stacked rasters inside a 34rem frame: the barbershop photograph as the base at card radius; a desktop panel absolutely positioned at 76% width breaking the left edge and the bottom; a phone panel at 23% width breaking the right edge lower still. Each inset carries a brighter hairline, a Back-Room Navy interior and its own contact shadow. Below 520px both insets pull back inside the frame. The section reserves 54px of extra bottom padding for the overhang.

### The Reveal
The system's scroll behaviour, applied as a class to individual elements rather than to containers. A marked element rests at `opacity: 0, translateY(14px)`; when its ancestor section becomes visible, it transitions in over 0.6s/0.7s with a delay of `--i x 70ms`. The stagger is authored inline per element. A `<noscript>` rule and the reduced-motion query both force the marked elements visible, so no content depends on script or on motion to be read.

## Do's and Don'ts

### Do:
- **Do** open every new section with a one-pixel `{colors.line}` rule and pad it with `{spacing.section}`.
- **Do** keep gold scarce: as a fill it belongs to the primary action; as a stroke or numeral it belongs to sequence markers, carets and footer marks.
- **Do** separate a surface from the ground with a hairline plus a Smoke Navy wash at 20–26% alpha.
- **Do** set body copy in Poppins 300 and let emphasis reach only to weight 500 and Warm Cream.
- **Do** pick a radius by function: `{rounded.control}` for anything the user acts on, `{rounded.card}` for anything that holds content.
- **Do** keep form inputs at 16px, interactive targets at 44px minimum, and functional text at or above 11.5px.
- **Do** theme the browser's own surfaces on any new page — gold `::selection` on black, gold `caret-color`, the thin brass scrollbar, the 2px Lit Brass `:focus-visible` ring at 3px offset, and a 4px underline offset on focused links.
- **Do** draw chevrons, carets and arrows as CSS shapes or inline sprite SVG, keeping the page at zero third-party requests.
- **Do** give new scroll-revealed content the reveal class and an explicit `--i`, and confirm it reads with motion disabled.

### Don't:
- **Don't** put an eyebrow, kicker, ordinal or coloured rule above a section heading. The heading stands alone; ordinals belong to the four implantation steps only.
- **Don't** fill any surface with a gradient. The only gradient in the system draws the 5px select caret.
- **Don't** add a shadow to a card, tile, input or list row, and don't use a shadow as a hover affordance. Shadows exist only as contact darkening under physically overlapping images.
- **Don't** introduce a second accent colour. Coral is for validation, WhatsApp green is for that one glyph, and Bella Rose identifies the sibling product — none of them are available as design colours.
- **Don't** add a second typeface, and don't set body copy above weight 300 or headings above 500.
- **Don't** use icon fonts, glyph characters, emoji or a third-party icon package; extend the inline sprite instead.
- **Don't** wrap a product screenshot in device chrome, a browser bar, a mockup bezel or a perspective transform. A hairline frame over Back-Room Navy is the treatment.
- **Don't** invent a third radius, a 2px border or a dashed stroke.
- **Don't** animate anything twice, and don't add parallax, scale or directional slides — the reveal is a 14px rise with a fade.
