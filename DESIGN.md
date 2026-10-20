---
name: Cupcakes & Cucumbers
description: Luxury at-home spa parties for little divas in NY & NJ, in calm cucumber-green bands with one cupcake-pink accent.
colors:
  paper: "#fbf5f6"
  card: "#ffffff"
  field: "#f3e4ea"
  ink: "#1d3a20"
  body: "#2e3a2c"
  soft: "#4f5a4b"
  cucumber: "#3b6a34"
  cucumber-deep: "#1f3a22"
  on-dark: "#f7fbf3"
  on-dark-soft: "#dbe8d2"
  cupcake-pink: "#f6a6c0"
  cupcake-pink-light: "#f9bfd2"
  pink-ink: "#a52c59"
  error: "#b3261e"
typography:
  display:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(42px, 12vw, 80px)"
    fontWeight: 400
    lineHeight: 1.02
    letterSpacing: "-0.005em"
  headline:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(30px, 7.6vw, 48px)"
    fontWeight: 400
    lineHeight: 1.08
    letterSpacing: "-0.005em"
  title:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(19px, 5.2vw, 26px)"
    fontWeight: 400
    lineHeight: 1.2
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.7
  lede:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(17px, 4.6vw, 20px)"
    fontWeight: 400
    lineHeight: 1.5
  label:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.2
  small:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "15px"
    fontWeight: 400
    lineHeight: 1.35
  wordmark:
    fontFamily: "CC Script (Pacifico subset), cursive"
    fontWeight: 400
    lineHeight: 1
rounded:
  field: "10px"
  card: "24px"
  pill: "999px"
  circle: "50%"
spacing:
  gutter: "20px"
  gutter-desktop: "40px"
  section: "64px"
  section-desktop: "96px"
  stack: "16px"
  form-gap: "26px"
components:
  button-primary:
    backgroundColor: "{colors.cupcake-pink}"
    textColor: "{colors.ink}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  button-primary-hover:
    backgroundColor: "{colors.cupcake-pink-light}"
    textColor: "{colors.ink}"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.on-dark}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  button-line:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  input:
    backgroundColor: "{colors.field}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.field}"
    padding: "13px 14px"
    height: "52px"
  chip:
    backgroundColor: "{colors.field}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    padding: "0 18px"
    height: "48px"
  chip-selected:
    backgroundColor: "{colors.ink}"
    textColor: "#ffffff"
  form-card:
    backgroundColor: "{colors.card}"
    rounded: "{rounded.card}"
    padding: "clamp(20px, 5vw, 32px)"
  service-row:
    textColor: "{colors.on-dark}"
    typography: "{typography.title}"
    height: "64px"
  arrow-disc:
    rounded: "{rounded.circle}"
    size: "44px"
  step-number:
    backgroundColor: "{colors.cupcake-pink}"
    textColor: "{colors.ink}"
    rounded: "{rounded.circle}"
    size: "48px"
  floating-text-circle:
    backgroundColor: "{colors.cupcake-pink}"
    textColor: "{colors.ink}"
    rounded: "{rounded.circle}"
    size: "60px"
---

# Design System: Cupcakes & Cucumbers

## Overview

**Creative North Star: "The Cucumber Slice on a Calm Afternoon"**

A pretend-luxury kids' spa, dressed grown-up enough that a parent trusts it with her daughter's party. The page is a stack of full-bleed colour bands (blush paper, cucumber-skin green, deep cucumber with faint diagonal lines) and every band speaks in one heading face, Cal Sans, with system text underneath. Warmth comes from a single cupcake pink, used as a fill for the things you press and as the colour of the last phrase in a heading. The flyer's script wordmark stands in for a logo and is the only decorative type.

Density is phone-first and generous: 64px band padding on phones (96px on desktop), single columns that open to two or three on desktop, every tap target 44px or more. There are no photographs (every real party photo shows children's faces); the hero is a textured green band, and on desktop only three illustrated cucumber slices float to its right, well clear of the copy. Motion is three quiet devices: the hero H1 letters bounce in once, below-the-fold blocks rise 12px as they arrive, and a pink text circle slides up after the hero.

This is the calm band house style (after lpmr.co.uk) applied to the flyer's own colours. The previous "pink pedicure soak" world was replaced on 2026-10-19 and nothing from it carries forward.

**Key Characteristics:**
- Full-bleed bands alternate paper, cucumber green and deep cucumber; content sits in a 1160px column.
- One warm accent: cupcake pink as fill, a darker pink-ink when pink must be text on light.
- Cal Sans at weight 400 for every heading, button, label and list row; system stack for running text.
- Pills and circles for everything you can press; 24px-radius white card for the form.
- Flat surfaces; depth only on the two things that float (Instagram card, text circle).
- Motion is once-only and fully disabled under reduced motion.

## Colors

Blush paper and two cucumber greens carry the page; one cupcake pink is the only warm voice.

### Primary
- **Cupcake Pink** (cupcake-pink): primary button fill, step-number discs, the floating text circle, list bullets, the eyebrow dot on dark bands, text selection, and the last phrase of a heading on green bands. Text on it is always Ink.
- **Pink Frosting** (cupcake-pink-light): hover fill for the primary button only.
- **Pink Ink** (pink-ink): pink as text on light grounds (6.4:1 on paper): heading accents on paper, the "sit back and relax" line, the header phone icon, the Instagram glyph.

### Secondary
- **Cucumber Skin** (cucumber): the hero band, the "Perfect for" band and the closing band. Also the form focus and hover outline and the input caret, so focus reads as green against the pink fills.
- **Deep Cucumber** (cucumber-deep): the services band and the footer, always with the diagonal line texture.

### Neutral
- **Blush Paper** (paper): page ground, header, "How it works" and the plan section; also the inner ground of the post-submit panel.
- **Card White** (card): the form card and the Instagram card.
- **Rose Field** (field): fill for inputs, selects, textareas and unselected chips. Fields have their own fill, never the paper.
- **Ink** (ink): headings and labels on light, text on pink, selected chips.
- **Body Green-Grey** (body): running text on light.
- **Soft Sage** (soft): secondary text: ledes, hints, "optional" tags, notes.
- **Leaf White** (on-dark) and **Pale Leaf** (on-dark-soft): headings and running text on green bands.
- **Error Red** (error): field error text and error border only.
- Hairlines are translucent, never solid colours: `rgba(29,58,32,.13)` between form groups on light, `rgba(255,255,255,.16)` between rows on green.

### Named Rules
**The Fill-Only Pink Rule.** Cupcake pink is a fill, or display-size text on a green band (32px and up). On paper, pink text is always Pink Ink. Never set body-size text in Cupcake Pink, and never put white text on pink: text on pink is Ink.

**The Two-Greens Rule.** Bands are paper, Cucumber Skin or Deep Cucumber, nothing else. Deep Cucumber always carries the line texture; Cucumber Skin carries it only in the hero.

**The Green Focus Rule.** Focus and hover outlines on light grounds are Cucumber Skin (3px, 3px offset), so they never blend into a pink fill. On green bands the outline switches to Cupcake Pink.

## Typography

**Display Font:** Cal Sans (Google Fonts), falling back to Avenir Next, Segoe UI, system-ui
**Body Font:** system stack (-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial)
**Wordmark:** "CC Script", a Pacifico subset embedded as base64 covering only the business name

**Character:** Cal Sans is round, friendly and confident at one weight; the system body keeps the page quick and familiar inside Facebook and Instagram in-app browsers. The script wordmark is the only flourish and is never used for anything except the name.

### Hierarchy
- **Display** (400, clamp(42px, 12vw, 80px), 1.02, max 11ch): the hero H1 only, white on the green hero, last phrase in Cupcake Pink.
- **Headline** (400, clamp(30px, 7.6vw, 48px), 1.08): one H2 per band. Balanced wrapping.
- **Title** (400, 19 to 26px fluid, 1.15 to 1.2): service group H3s, service rows, occasion list items, step titles, the Instagram card label. Cal Sans carries every list item that a parent might tap or scan.
- **Lede / Promise** (400, 17 to 20px fluid, 1.5): the line under the H1 or H2, max 30 to 38ch. A bold lead-in in Leaf White on green bands.
- **Body** (400, 16px, 1.7): running text. Inputs are 16px so iOS never zooms.
- **Label** (Cal Sans 400, 17px, 1.2): form labels and legends; fieldset legends step up to 23px. Buttons use Cal Sans at 18px.
- **Small** (system 400, 14 to 15px, 1.3 to 1.4): row subtitles, hints, "optional" tags, notes, errors.
- **Big phone** (Cal Sans 400, clamp(30px, 9vw, 52px), 1): the closing phone number, the largest text after the H1.

### Named Rules
**The One Weight Rule.** Cal Sans is always weight 400; hierarchy comes from size alone. Bold (600) exists only in system text as a lead-in phrase.

**The Accent-Phrase Rule.** A heading may colour its last phrase as an accent ("NY & NJ.", "bring."). One phrase, at the end, never the whole heading.

**The Name-Only Script Rule.** The script face sets "Cupcakes & Cucumbers" and nothing else. Its three parts take three tints: pink for "Cupcakes", a dusky rose for "&", green for "Cucumbers", re-tinted lighter on green bands.

## Layout

A single centred column (max 1160px) with a 20px gutter on phones and 40px from 760px. Each section is a full-bleed band with 64px vertical padding on phones and 96px from 760px; the hero is 56/64px on phones and 96/112px on desktop. Bands alternate paper and green so the colour change itself separates sections; there are no dividers between bands.

Breakpoints are 430px (wordmark sits on one line), 760px (two-column service groups, side-by-side hero buttons, desktop spacing) and 1024px (three service columns, four steps in a row, the split "Perfect for" layout, a sticky intro beside the form, the closing phone number right-aligned). A 380px max query tightens chip padding.

Section intros stack at 16px gaps and cap at 640px. Lists are full-width rows separated by hairlines, not cards. The form card caps at 640px; inside it, groups sit 26px apart and each fieldset group opens with a hairline and 24px top padding. On desktop the form's text fields pair up in two or three columns.

The footer reserves 96px plus the safe-area inset at the bottom so the floating text circle never covers it.

## Elevation & Depth

Flat by default. Depth comes from band colour and the faint 135-degree line texture (`repeating-linear-gradient(135deg, transparent 0 22px, rgba(255,255,255,.035) 22px 23px)`), which reads as fabric or a spa towel rather than a pattern. Only things that float above a band get a shadow, and they share one soft, green-tinted drop.

### Shadow Vocabulary
- **Float** (`box-shadow: 0 10px 28px rgba(15,35,17,.18)`): the white Instagram card sitting on the green band.
- **Float, strong** (`box-shadow: 0 10px 28px rgba(20,40,22,.3)`): the fixed text circle, which floats over every band.
- **Illustration lift** (`filter: drop-shadow(0 18px 30px rgba(10,30,12,.35))`): the desktop cucumber slices in the hero.

### Named Rules
**The Only-What-Floats Rule.** A shadow means the element sits above the band (a card on green, a fixed control). Buttons, fields, chips and rows are flat.

## Shapes

Round everywhere a finger lands: buttons, chips and the skip link are full pills (999px); arrows, step numbers, list bullets and the text circle are circles. Containers are softly rounded: the form card at 24px, the Instagram card at 20px, the post-submit panel at 18px. Fields are the one squarer shape (10px), so they read as places to type rather than things to press. No hard borders on surfaces; borders appear only as 2px states (focus, hover, error) or as the outline of a secondary button.

## Components

### Buttons
Soft, round and confident; Cal Sans 18px, min-height 56px.
- **Shape:** full pill (999px), 2px border.
- **Primary:** Cupcake Pink fill and border, Ink text, 0 26px padding. Full-width in the form and on phones in the hero; side by side, min 220px each, from 760px.
- **Hover / Focus:** primary lightens to Pink Frosting on real pointers only (`@media (hover:hover)`). Inside the form the hover is the 3px green outline instead. Focus is a 3px outline, 3px offset. Press scales to 0.98.
- **Ghost (on green):** transparent with a 70% Leaf White border and Leaf White text; hover goes to a solid white border and a 10% white wash.
- **Line (on light):** transparent with a 35% Ink border; used for the post-submit "Open in Messages" and "Copy message".
- Icons sit 10px before the label at 20px, stroked line icons only.

### Chips
- **Style:** Rose Field pill, 48px tall, 0 18px padding, system 16px Ink text, 2px transparent border. The real checkbox or radio is visually hidden behind it.
- **State:** hover draws the green border; selected flips to an Ink fill with white text; keyboard focus gets the 3px green outline. Used for multi-select (services) and single-select (occasion, "partied before").

### Cards / Containers
- **Form card:** white, 24px radius, 20 to 32px fluid padding, no shadow, on blush paper.
- **Instagram card:** white, 20px radius, the Float shadow, Cal Sans label with a small system subtitle, an arrow disc on the right.
- **Post-submit panel:** blush paper inside the white form, 18px radius, with the composed message in a white 12px-radius block.

### Inputs / Fields
- **Style:** Rose Field fill, 2px transparent border, 10px radius, 13px 14px padding, 52px min height, system 16px Ink text, a custom green chevron on selects. Labels are Cal Sans 17px above; "optional" sits beside the label in soft 14px system text, and required fields carry no marker.
- **Focus / Hover:** the border turns Cucumber Skin; no glow.
- **Error:** border turns Error Red and a plain-language message appears below in 15px Error Red.

### Navigation
- **Header:** paper, 64px (76px desktop). Script wordmark left (stacks on two lines below 430px), a tap-to-call number right in Cal Sans 17 to 20px with a Pink Ink phone icon. No menu.
- **Footer:** Deep Cucumber with the texture, the wordmark in light tints at 26px, one line of facts, and an Instagram link at 44px tap height; links hover to Cupcake Pink.

### Service Row (signature)
A full-width link row on a green band: Cal Sans 19 to 21px Leaf White label, optional small system subtitle, a 44px translucent arrow disc on the right, a 16% white hairline below, 64px min height. Hover and keyboard focus fill the arrow disc with Cupcake Pink (Ink arrow) instead of highlighting the row. Tapping a row ticks the matching chip in the form.

### Step List (signature)
Numbered steps with a 48px Cupcake Pink disc holding a Cal Sans numeral, a Cal Sans 21 to 22px title and a plain body line. One column on phones, four across from 1024px.

### Floating Text Circle (signature)
A 60px Cupcake Pink circle fixed bottom-right (16px plus safe-area inset), holding a 26px chat icon, opening a pre-filled `sms:`. It slides up from 120px below once the hero has scrolled away (0.35s `cubic-bezier(.2,.8,.2,1)`) and hides while the form is on screen, so two "text us" controls are never in view together. When hidden it is `aria-hidden` and out of the tab order. One circle, never a bottom bar. Controlled by `CONFIG.FLOAT`.

### Hero H1 Bounce-In (signature motion)
The hero H1 only. JS waits for Cal Sans (at most 700ms), splits the heading into per-letter spans inside no-wrap word wrappers, and each letter travels from 50px right and transparent to rest over 1s `cubic-bezier(.34,1.56,.64,1)`, 20ms apart; the overshoot is the bounce. After the last letter lands the original markup is restored. No JS or reduced motion shows the plain heading at once. No other heading animates this way.

### Fade-Up
Blocks marked to rise move up 12px and fade in over 0.4s ease-out as they enter. Only blocks that start below the first screen are hidden; everything is visible without JS and under reduced motion.

### Eyebrow Pill (house-style exception, not a system rule)
The build carries three small pills above key headings (the hero offer, "Any reason to celebrate", "Goes straight to Marissa"): 14px system text, a 7px pink dot, a 6% Ink wash (12% white on green), no hover, no arrow. Impeccable's craft floor bans eyebrows; they are here only because Ellie's calm band house style requires them. Their authority is that house style, not this file: do not add eyebrows to new surfaces on the strength of this document.

## Do's and Don'ts

### Do:
- **Do** build each section as a full-bleed band in paper, Cucumber Skin or Deep Cucumber, with 64px (phone) and 96px (desktop) padding.
- **Do** put text on pink in Ink, and use Pink Ink whenever pink must be text on a light ground.
- **Do** set every heading, button, label and list row in Cal Sans 400, and running text in the system stack at 16px / 1.7.
- **Do** make every pressable thing a pill or circle at 44px or more (buttons 56px, chips 48px, fields 52px).
- **Do** give fields the Rose Field fill and a green 2px border on hover and focus.
- **Do** gate hover styles behind `@media (hover:hover)` so taps don't stick.
- **Do** turn off every transition and animation under `prefers-reduced-motion`, leaving all content visible.

### Don't:
- **Don't** add a fourth band colour or a second warm accent.
- **Don't** set body-size text in Cupcake Pink, or white text on a pink fill.
- **Don't** use any Cal Sans weight other than 400, or the script face for anything but the business name.
- **Don't** put shadows on buttons, fields, chips or rows; only elements that float above a band get one.
- **Don't** animate any heading except the hero H1, or replace the floating circle with a bottom bar.
- **Don't** use party photographs without the owner's consent; every one on hand shows children's faces.
