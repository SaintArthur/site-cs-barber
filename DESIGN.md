---
name: CS Barber
description: Graphite ground, bone text, one brass accent — a barber pole is the only colour the page spends on itself.
colors:
  grafite: "#0c0c0e"
  couro: "#151518"
  elev: "#1c1c21"
  campo: "#141418"
  osso: "#f4f1ea"
  muted: "#9b9ba4"
  muted-2: "#c6c6ce"
  gold: "#c9a56a"
  gold-light: "#e2ca97"
  gold-deep: "#a27947"
  line: "rgba(226,202,151,.16)"
  line-2: "rgba(226,202,151,.30)"
  wash: "rgba(40,40,48,.26)"
  wash-soft: "rgba(40,40,48,.2)"
  poste-r: "#c8323a"
  poste-a: "#2b4ea8"
  error: "#e0616b"
  whatsapp: "#25D366"
  bella-rose: "#dd9db3"
  white: "#ffffff"
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
  fact:
    fontFamily: "Poppins, system-ui, sans-serif"
    fontSize: "21px"
    fontWeight: 500
    letterSpacing: "-.02em"
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
  pole: "5px"
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
    textColor: "{colors.grafite}"
    typography: "{typography.action}"
    rounded: "{rounded.control}"
    padding: "12px 22px"
    height: "46px"
  button-primary-hover:
    backgroundColor: "{colors.gold-light}"
    textColor: "{colors.grafite}"
  button-outline:
    backgroundColor: "transparent"
    textColor: "{colors.osso}"
    typography: "{typography.action}"
    rounded: "{rounded.control}"
    padding: "12px 22px"
    height: "46px"
  button-outline-hover:
    backgroundColor: "rgba(201,165,106,.07)"
    textColor: "{colors.osso}"
  button-header:
    backgroundColor: "{colors.gold}"
    textColor: "{colors.grafite}"
    rounded: "{rounded.control}"
    padding: "10px 18px"
    height: "40px"
  card:
    backgroundColor: "{colors.wash}"
    textColor: "{colors.muted-2}"
    rounded: "{rounded.card}"
    padding: "clamp(22px, 3.4vw, 30px)"
  card-form:
    backgroundColor: "rgba(12,12,14,.55)"
    textColor: "{colors.osso}"
    rounded: "{rounded.card}"
    padding: "clamp(20px, 3vw, 28px)"
  input:
    backgroundColor: "{colors.campo}"
    textColor: "{colors.osso}"
    rounded: "{rounded.control}"
    padding: "12px 13px"
    size: "16px"
  chip-static:
    backgroundColor: "transparent"
    textColor: "{colors.muted-2}"
    rounded: "{rounded.pill}"
    padding: "0 13px"
    height: "32px"
  chip-toggle:
    backgroundColor: "{colors.wash}"
    textColor: "{colors.muted-2}"
    rounded: "{rounded.control}"
    padding: "9px 12px"
    height: "46px"
  chip-toggle-checked:
    backgroundColor: "{colors.wash}"
    textColor: "{colors.osso}"
  nav-link:
    backgroundColor: "transparent"
    textColor: "{colors.muted-2}"
    size: "14px"
  nav-link-hover:
    textColor: "{colors.osso}"
  header:
    backgroundColor: "rgba(12,12,14,.82)"
    textColor: "{colors.osso}"
    height: "64px"
---

# Design System: CS Barber

## Overview

**Creative North Star: "The Pole and the Brass"**

A barbershop reads as a barbershop from across the street because of two things: the brass on the fittings and the striped pole turning by the door. This system is built from exactly those two and nothing else. The ground is graphite — a neutral near-black with no colour cast at all — and the text is bone. Against that grey quiet, brass is the only colour that can be acted on, and the pole appears once, beside the headline, as the page's single authored moment.

The palette was rebuilt from the one fixed brand fact: the logo asset's brass gradient. Brass is the company's; the previous navy ramp was not, and navy is what made the page read as generic category SaaS. Removing it left a ground with no hue to compete with brass, which is the whole reason the three-colour risk of a barber pole is survivable here. Red and blue are identifiers, not palette: they stripe the pole and they mark two profile cards, and they are forbidden from touching an action.

Everything else is the category convention executed straight — fixed header, left-aligned hero, two-tier module block, numbered implantation sequence, accordion, form — and the discipline is in refusing the signals the category reaches for: no surface gradients, no glow, no card lift, no stock iconography, no second action colour. One typeface at one light weight carries the body; headings step up one notch and never further. Sections breathe on a clamped rhythm that never falls below 64px.

**Key Characteristics:**
- Neutral graphite ground with bone text; no hue in the neutrals at all
- Brass is the only colour that fills an action, by rule
- The barber pole: one animated striped bar beside the H1, and two 3px card edges — nothing else
- Flat surfaces, one-pixel brass hairlines, no gradient fills
- Poppins alone: body at 300, headings at 500, actions at 600
- Hairline-opened sections on a clamped vertical rhythm
- Motion is two gestures: the pole's slow travel, and a staggered rise-and-fade on scroll

## Colors

A neutral dark palette — four greys from graphite to field, bone and two cool greys for text — carrying one brass accent, plus a red and a blue that exist only to draw a barber pole.

### Primary
- **Brass** (`{colors.gold}`): The only colour that fills an action. It is the primary button, the "Em breve" stamp, the step ordinals, the accordion chevron, the select caret, the footer marks and the field caret. If a surface can be clicked and it is coloured, it is this.
- **Lit Brass** (`{colors.gold-light}`): The hover state of the brass button, the emphasised span inside the H1, the micro-link under a profile card, the skip link, and the focus ring. Brass with the lights up.
- **Deep Brass** (`{colors.gold-deep}`): Scrollbar thumb on hover and the Firefox thumb colour, and the midpoint of the logo asset's own brass gradient. Browser chrome and brand asset only; never a surface or text colour.

### Secondary
- **Pole Red** (`{colors.poste-r}`): One of the two pole stripes, and the 3px top edge of the first profile card in `#dores`, where it marks "already runs a system". It appears nowhere else.
- **Pole Blue** (`{colors.poste-a}`): The other pole stripe, and the 3px top edge of the second profile card, marking "has no system yet". It appears nowhere else.

### Neutral
- **Graphite** (`{colors.grafite}`): The page ground, the scrollbar track, and the ink printed on brass. A neutral near-black — no navy, no warmth, no cast.
- **Leather** (`{colors.couro}`): The one tonal lift. It backs the trial section and the inside of the desktop panel frame, separating a block from the page by tone rather than by shadow.
- **Elevated** (`{colors.elev}`): Declared in the token block as the next step up the grey ramp. No element paints with it in the shipped build.
- **Field** (`{colors.campo}`): Input and select interiors only. One step off the ground, so the field reads as a recess.
- **Bone** (`{colors.osso}`): All headings and all primary text. Warm-white rather than white; this is the page's reading colour.
- **Soft Grey** (`{colors.muted-2}`): Secondary prose — supporting paragraphs, card bodies, FAQ answers, nav links at rest. The tier just below bone.
- **Dim Grey** (`{colors.muted}`): Functional and ancillary text — uppercase labels, fact captions, the legal line, the toggle knob at rest. The floor for this colour is 11.5px.
- **Wash** (`{colors.wash}`): The surface tint that lifts a card off the ground — a neutral grey at 26% alpha, not a tinted panel. Footer rows use the softer 20% step (`{colors.wash-soft}`).
- **Hairline** (`{colors.line}`): Every rule and every default border. Brass at 16% alpha, not grey, so the structure carries the accent's warmth against a neutral ground.
- **Hairline Bright** (`{colors.line-2}`): The raised hairline (30%) for hover borders, the secondary button's resting edge, the toggle track and the desktop panel frame.
- **Paper White** (`{colors.white}`): Declared in the token block and held in reserve; no element paints with it.

### Tertiary
- **Alert Coral** (`{colors.error}`): Invalid field borders and their error text. Validation only.
- **WhatsApp Green** (`{colors.whatsapp}`): The WhatsApp glyph only, at its brand value. Never text, never a surface.
- **Bella Rose** (`{colors.bella-rose}`): The sibling-product mark in the footer, identifying CS Bella. Never used for CS Barber's own content.

### Named Rules

**The Brass Acts Alone Rule.** Brass is the only colour that ever fills an action. Red and blue never fill a button, never carry a link, never underline text and never appear in a hover state. They exist in exactly two places — the pole beside the H1 and the 3px identifier edge on each of the two profile cards — and that is the complete inventory. The moment a third strong colour starts competing for the eye, brass stops reading as the thing to press, and the palette stops working.

**The Neutral Ground Rule.** The greys carry no hue. Ground, surface, field and wash are all neutral, deliberately, so that brass and the pole are the only chroma on the page. A new surface tints with `{colors.wash}` over graphite; it does not get a colour of its own.

**The Warm Hairline Rule.** Dividers are brass at 16% alpha, never neutral grey and never solid. A new divider inherits `{colors.line}`; raising a border to `{colors.line-2}` is a state change (hover, inset), not a decoration.

**The No Surface Gradient Rule.** No surface in this system is filled with a gradient. Three gradients exist and each one draws a shape, not a fill: the pole's repeating stripe, the select caret's two 5x5px triangles, and the scrim over the barbershop photograph. Flat paint everywhere else.

## Typography

**Display Font:** Poppins (with system-ui, sans-serif)
**Body Font:** Poppins (with system-ui, sans-serif)

**Character:** One geometric sans carries the whole page, and the hierarchy is built from weight and tracking rather than from a second face. Body copy runs at Light (300), which keeps long Portuguese paragraphs airy on a phone; headings step to Medium (500) with negative tracking that tightens as the size grows. Nothing is set heavier than 600, and only the action label and the wordmark go that far. Self-hosted WOFF2 in Latin and Latin-Extended subsets; zero third-party font requests.

### Hierarchy
- **Display** (500, `clamp(33px, 7.2vw, 58px)`, 1.04, `-.03em`): The H1 only. Two lines, left-aligned, indented 30px to clear the pole, with one emphasised span in Lit Brass — an `<em>` with its italic removed.
- **Headline** (500, `clamp(27px, 4.4vw, 40px)`, 1.1, `-.022em`): Section H2s. One per section, standing alone.
- **Title** (500, 18.5px, 1.1): Item headings inside lists — module rows, steps, differentiators. Two siblings exist: `clamp(21px, 3vw, 26px)` for the two profile cards and 17px for the three audience cards.
- **Lede** (300, 17px, 1.62, max 52ch): The hero's supporting paragraph. Its `<b>` spans go to 500 and Bone rather than to bold.
- **Fact** (500, 21px, `-.02em`, Bone): The four hero facts, each over a 13px Dim Grey caption. A short noun, not a metric.
- **Body** (300, 16px, 1.6): The document default. Section descriptions run 16.5px at a 62ch cap; list and FAQ prose run 15.5px, capped between 48ch and 68ch per component.
- **Label** (500, 11.5px, `.13em`, uppercase, Dim Grey): Form field labels and fieldset legends.
- **Tier Label** (500, 12px, `.17em`, uppercase, Dim Grey): The two tier markers inside the module block. It labels a list that follows it, below and separate from the section heading.
- **Action** (600, 15px, `-.005em`): Button labels. The header's compact variant drops to 14px; the form's full-width submit rises to 16px.
- **Wordmark** (600, 17px, `.14em`): "CS **BARBER**" in the header, the second word in Lit Brass. The widest tracking in the system.

### Named Rules

**The One Face Rule.** Poppins is the only family. No display face, no mono, no serif, and no system font stack reached for as a shortcut. A new surface that needs a different voice gets it from weight (300 / 500 / 600) and tracking.

**The Naked Heading Rule.** A section heading stands alone. No eyebrow, no kicker, no ordinal and no coloured rule sits above an H2 — the heading carries its own weight. Ordinals appear only in the four implantation steps, where the sequence is the information. An uppercase tier label is legal *inside* a block, placed below the heading to divide a list; it is never promoted to sit above one. The pole is attached to the H1 itself, beside it and spanning its height — it is not an ornament sitting above a heading, and it does not repeat on H2s.

**The Light Body Rule.** Body copy is weight 300. Emphasis inside it goes to 500 and Bone, never to 700. Functional text never drops below 11.5px.

## Layout

A single centred column, `{spacing.container}` wide, with a fluid gutter of `{spacing.gutter}`. Everything lives inside one wrapper; nothing is full-bleed except the ground itself, the fixed header and the Leather-toned trial section.

Vertical rhythm is governed by two clamps: `{spacing.section}` for the padding above and below every section, and `{spacing.section-half}` as its companion step. Each section opens with a one-pixel hairline across the full column width — suppressed on the first — so the page reads as a stack of ruled panels. The hero adds the 64px header height plus `clamp(40px, 7vw, 78px)` to its top padding. Scroll padding is header height plus 16px, so an anchored jump never lands under the bar.

The hero ships as a single column: headline, lede, actions, then a four-up fact strip under a hairline. The direction brief described a product screenshot beside the headline; the build does not have one there — the screenshots live in the differentiators composition instead, and the hero's right side is empty space the pole is read against.

Internal rhythm is small and specific rather than a global scale: 16px between a heading and its description, `clamp(30px, 4vw, 46px)` from a section head to whatever follows it, 20–22px of padding inside list rows, `clamp(30px, 4vw, 44px)` between stacked blocks. Measure is capped per component, from 34rem on a section head to 48–68ch on prose.

**Breakpoints.** Three ascending, plus one inverse.
- **720px and up:** two-column profile pair, three-column audience cards, the four-up fact strip.
- **960px and up:** the differentiators pair and the footer links go to even columns; the trial section splits `.9fr / 1.1fr`; the module base list goes two-up with a 40px column gap.
- **959px and down:** the header switches — desktop nav and header CTA hide, the hamburger appears, and navigation moves to a full-width panel sliding down from under the bar.
- **519px and down:** hero actions stack full-width; the form grid and the toggle chips collapse to one column; the pole narrows from 9px to 7px and the headline indent from 30px to 22px; the overlapping composition pulls back inside a 22rem frame.

Mobile-first in construction: every grid is a single column by default and gains columns upward.

**Motion.** Two gestures and no more. The pole's stripe travels upward continuously — `@keyframes poste` moving its background position over 3.4s linear infinite — and scroll-revealed elements rest at `opacity: 0, translateY(14px)` until an IntersectionObserver (12% bottom root margin, 6% threshold) marks their section visible and unobserves it, releasing children over 0.6s / 0.7s on `cubic-bezier(.16, 1, .3, 1)` with a per-element `--i` delay at 70ms a step. The accordion animates its own height over 0.34s on the same curve. `prefers-reduced-motion` stops the pole, collapses every transition to 0.001ms, disables smooth scrolling and skips the observer, so content is visible and still at rest.

### Named Rules

**The Hairline Opens Rule.** Every section but the first opens with a one-pixel `{colors.line}` rule across the column. It is the page's only section separator; do not add a background change, a spacer graphic or a decorative divider to do the same job. The pole's stripe does not belong on a section rule — it was tried there as a 56px segment, read as a dashed grey line, and was removed.

**The One Gesture Rule.** Apart from the pole, scroll motion is a 14px rise with a fade, staggered by `--i`. No parallax, no scale, no lateral slide, and nothing animates more than once.

## Elevation & Depth

This system is flat. Surfaces do not lift, and nothing uses shadow to signal interactivity or importance. Depth comes from three devices, in order of use: the warm hairline border; a tonal wash (neutral grey at 20–26% alpha over the graphite ground, or Leather as a whole-section tone); and overlap, where the differentiators composition stacks a photograph, a desktop panel and a phone panel so they occlude each other.

Shadows are contact shadows: large negative-spread blurs that darken the ground directly beneath an element so an overlapping object does not float. They are never ambient glows, never coloured, never hard-offset, and never attached to a hover state.

### Shadow Vocabulary
- **Button seat** (`box-shadow: 0 6px 18px -10px rgba(0,0,0,.7)`): On the brass button only, where bright paint meets the dark ground. Removed when disabled.
- **Pole seat** (`box-shadow: inset 0 0 0 1px rgba(12,12,14,.55), 0 4px 12px -6px rgba(0,0,0,.9)`): The pole's own inset graphite hairline plus a contact darkening, so the bar reads as an object standing in front of the page rather than a painted stripe.
- **Photo contact** (`box-shadow: 0 10px 18px -12px rgba(0,0,0,.88)`): Under the barbershop photograph in the overlap composition.
- **Panel contact** (`box-shadow: 0 10px 18px -12px rgba(0,0,0,.9)`): Under the desktop panel that overhangs the photograph.
- **Phone contact** (`box-shadow: 0 12px 22px -14px rgba(0,0,0,.92)`): Under the phone panel, the topmost layer.

The header is the one surface that uses translucency for depth: `rgba(12,12,14,.82)` with a 14px backdrop blur, deepening to `.94` and gaining a bottom hairline once the page scrolls past 10px.

### Named Rules

**The Flat Surface Rule.** Cards, tiles, inputs and list rows have no shadow at any state. If a new surface needs to separate from the ground, it gets a hairline and a wash — not elevation.

**The Contact-Only Rule.** A shadow is permitted only where something physically overlaps something else, and only as a negative-spread contact darkening. A shadow that reads as a glow, a drop or a hard offset does not belong in this world.

## Shapes

Two radii, applied by function rather than by size. Controls — buttons, inputs, selects, toggle chips, radio pills, module tiles, the skip link — take `{rounded.control}`. Containers that hold content — cards, footer links, the form box, the photograph, the desktop panel — take `{rounded.card}`. The focus ring rounds to `{rounded.focus}` and the pole's bar to `{rounded.pole}`. Fully round (`{rounded.pill}`) is reserved for genuinely pill-shaped objects: the static fact chips, the toggle track and the scrollbar thumb. The one true circle is the 13px toggle knob. The one sharp corner is the 2px "Em breve" stamp. Inside the overlap composition the photograph steps to 12px and the phone frame to 16px with a 12px inner image, so the layers read as nested objects rather than siblings.

Borders are one pixel, always, and always a brass alpha — with one exception by design: the 3px top edge on each profile card, which is a colour identifier rather than a border. There are no dashed or dotted strokes, and no outlines except the focus ring (2px Lit Brass at 3px offset). The accordion chevron and the select caret are both drawn from primitives — a rotated 1.5px L-shape and two 5px gradient triangles — rather than imported as glyphs. Icons are inline SVG pulled from a single hidden sprite, stroked or filled at `currentColor`, at 13–26px.

### Named Rules

**The Two Radius Rule.** 6px if the user acts on it, 10px if it holds content. Do not introduce a third radius for a new component; decide which side it is on. The pole, the focus ring and the composition's nested frames are the named exceptions and they do not extend.

**The Drawn Mark Rule.** Chevrons, carets and arrows are drawn in CSS or as inline SVG in the sprite. No icon font, no glyph character, no emoji, no bitmap, no third-party icon package — the page makes zero external requests and the marks are part of that commitment.

## Components

### Buttons
- **Shape:** Lightly rounded (`{rounded.control}`), minimum 46px tall, inline-flex with a 9px gap to an optional 15px arrow.
- **Primary:** Brass fill, Graphite label at weight 600, 12px/22px padding, carrying the button seat shadow. Hover lifts the fill to Lit Brass and nudges the arrow 3px right.
- **Secondary:** Transparent with a Hairline Bright edge and a Bone label. Hover brings the border to full brass and washes the interior with brass at 7%.
- **States:** Both press to `scale(.985)` over 0.18s. Disabled drops to 50% opacity, suppresses the shadow and the press, and shows `not-allowed` — the form submit ships disabled in the HTML and is enabled by script.
- **Header variant:** 10px/18px padding, 40px tall, 14px label. Hidden below 960px, where it reappears at full size as the last item in the slide-down menu.
- **Form variant:** Full width, 52px tall, 16px label.

### Chips
- **Static chip:** A 32px pill with a Hairline edge, no fill, Soft Grey 13px text. Non-interactive; it states a fact.
- **Toggle chip:** A 46px control-radius row with the neutral wash, label left and a 30x17px track right. Checked brings the border to full brass and the text to Bone, and slides a 13px knob 13px right as it turns from Dim Grey to brass. The real checkbox is visually hidden; `:has(input:checked)` drives the styling.
- **Radio pill:** 76px minimum width, 44px tall, the same border-and-text promotion on check. No knob.

### Cards / Containers
- **Profile card:** The largest card — `clamp(22px, 3.4vw, 30px)` padding, card radius, Hairline edge, neutral wash, `overflow: hidden`, and a 3px pole-colour edge across its top. Hover raises the border to Hairline Bright over 0.3s and nothing else moves.
- **Audience card:** 22px padding, neutral wash, static.
- **Module tile:** Control radius, 14px/16px padding, laid out on an auto-fit grid from a 190px minimum. Name at 14.5px/500 in Bone over a 12.5px Dim Grey gloss.
- **Form box:** `clamp(20px, 3vw, 28px)` padding over graphite at 55% — darker than its Leather section, so the form recedes into the page rather than sitting on it.
- **Panel frame:** Card radius, Hairline Bright edge, Leather interior, overflow hidden. No device chrome, no browser bar, no bezel.

### Inputs / Fields
- **Style:** Field interior, Hairline edge, control radius, 12px/13px padding. Font size is pinned at 16px so iOS does not zoom on focus; weight stays 300. The caret is brass.
- **Focus:** The border goes to full brass over 0.2s. That border change is the focus signal; the native outline is suppressed on fields only, and the global focus ring still serves everything else.
- **Error:** `aria-invalid="true"` turns the border Alert Coral and reveals a 12px coral message through a sibling selector — CSS, not script, controls the visibility.
- **Select:** Appearance stripped, caret drawn as two 5px triangles from paired linear gradients, with 36px right padding to clear it.
- **Layout:** Two-column grid at a 14px gap, collapsing to one below 520px. Fieldsets are borderless except for a top hairline, with an uppercase legend.

### Navigation
- **Header:** Fixed, 64px, translucent `rgba(12,12,14,.82)` over a 14px backdrop blur. Scrolling past 10px deepens the ground to `.94` and fades in a bottom hairline over 0.3s. Logo and wordmark left in a 44px minimum touch area, four 14px Soft Grey links at a 30px gap, brass CTA right.
- **Mobile (≤959px):** Links and CTA hide; a 44x44px two-bar hamburger appears and crosses into an X on open, each bar translating 6.5px and rotating ±45°. The menu is a fixed panel below the header at `rgba(12,12,14,.98)`, sliding from `translateY(-10px)` with opacity and visibility over 0.32s. Rows are 52px tall, hairline-separated, with the brass CTA last. It closes on link click and on Escape, returning focus to the hamburger.
- **Footer links:** Card-radius rows with the soft wash, a 26px brass mark left, a name over an uppercase 12px caption, and a dimmed brass arrow right. Hover raises the border and translates 2px up — the only transform-based hover in the system. The sibling-product row swaps its mark to Bella Rose and carries a sharp 2px brass "Em breve" stamp.

### The Pole

The page's one authored moment, and the only place the three strong colours appear together. `.heroi h1::before` is a 9px-wide rounded bar (`{rounded.pole}`) absolutely positioned at the headline's left edge, spanning from `.14em` below its top to `.12em` above its bottom, so it is measured by the type rather than by a fixed height. It is filled with `--poste`, a `repeating-linear-gradient` at 150deg cycling Pole Red, Bone, Pole Blue, Bone in 9px bands, sized to `100% 180%` and translated upward by `@keyframes poste` over 3.4s linear infinite — the stripe climbs and the bar never moves. An inset graphite hairline and a short contact shadow seat it against the ground. Below 520px it narrows to 7px. Under `prefers-reduced-motion` the animation is switched off and the bar stands still, fully legible.

It exists once per page, attached to the H1. It is not a section marker, not a list bullet, not a divider, and not a hover decoration.

### The Step Ladder

The implantation sequence. A CSS counter renders `decimal-leading-zero` ordinals in each row's `::before` — 01, 02, 03, 04 — at 13px/600 in Brass with tabular numerals, spanning both rows of a two-column grid so the ordinal sits beside the heading and its paragraph. Rows are separated by top hairlines, the first suppressed. This is the only place in the system where a number precedes a heading, and the sequence is why.

### The Overlap Composition

Three stacked rasters inside a 34rem frame at a 1/.86 aspect: the barbershop photograph top-right at 81% x 54%, rotated 1.2° and straightening to 0 over 0.6s on hover; a desktop panel absolutely positioned bottom-left at 83% width over Leather; a phone panel bottom-right at 21% width in a near-black 16px frame. Each layer carries its own contact shadow. Below 520px both panels drop below the photograph's frame and the whole composition caps at 22rem. The user pinned this composition to match the previous site.

### The Reveal

The system's scroll behaviour, applied as a class to individual elements rather than to containers. A marked element rests at `opacity: 0, translateY(14px)`; when its ancestor section becomes visible, it transitions in over 0.6s/0.7s with a delay of `--i x 70ms`. The stagger is authored inline per element. A `<noscript>` rule and the reduced-motion query both force the marked elements visible, so no content depends on script or on motion to be read.

## Do's and Don'ts

### Do:
- **Do** let brass be the only colour that fills an action, everywhere, without exception.
- **Do** keep red and blue to the pole and the two profile-card identifier edges; if a new surface needs a colour, it gets brass or it gets grey.
- **Do** open every new section with a one-pixel `{colors.line}` rule and pad it with `{spacing.section}`.
- **Do** separate a surface from the ground with a hairline plus the neutral wash at 20–26% alpha over graphite.
- **Do** keep the neutrals neutral: new greys are sampled off the graphite ramp, not tinted.
- **Do** set body copy in Poppins 300 and let emphasis reach only to weight 500 and Bone.
- **Do** pick a radius by function: `{rounded.control}` for anything the user acts on, `{rounded.card}` for anything that holds content.
- **Do** keep form inputs at 16px, interactive targets at 44px minimum, and functional text at or above 11.5px.
- **Do** theme the browser's own surfaces on any new page — brass `::selection` on graphite, brass `caret-color`, the thin brass scrollbar, the 2px Lit Brass `:focus-visible` ring at 3px offset, and a 4px underline offset on focused links.
- **Do** draw chevrons, carets and arrows as CSS shapes or inline sprite SVG, keeping the page at zero third-party requests.
- **Do** give new scroll-revealed content the reveal class and an explicit `--i`, and confirm it reads with motion disabled.

### Don't:
- **Don't** fill a button, a link, a stamp or a hover state with Pole Red or Pole Blue. They identify and they stripe the pole; they are not an accent pair for general use.
- **Don't** repeat the pole. One bar, on the H1, once per page — not on section rules, not as a bullet, not as a divider. It was tried on section rules, read as a dashed grey line, and was removed.
- **Don't** put a hue back into the neutrals, and don't reintroduce a navy ramp. The ground is neutral so that brass and the pole are the only chroma.
- **Don't** put an eyebrow, kicker, ordinal or coloured rule above a section heading. The heading stands alone; ordinals belong to the four implantation steps only.
- **Don't** fill a surface with a gradient. The three gradients in the system draw the pole, the 5px select caret and the photograph's scrim.
- **Don't** add a shadow to a card, tile, input or list row, and don't use a shadow as a hover affordance. Shadows exist only as contact darkening under physically overlapping objects.
- **Don't** add a second typeface, and don't set body copy above weight 300 or headings above 500.
- **Don't** use icon fonts, glyph characters, emoji or a third-party icon package; extend the inline sprite instead.
- **Don't** wrap a product screenshot in device chrome, a browser bar, a mockup bezel or a perspective transform. A hairline frame over Leather is the treatment.
- **Don't** invent a third radius or a dashed stroke, and don't use a thick border for anything but the two profile-card identifier edges.
- **Don't** animate anything twice, and don't add parallax, scale or directional slides — besides the pole, the reveal is a 14px rise with a fade.
