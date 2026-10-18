---
name: Cupcakes & Cucumbers
description: A pink pedicure soak with cucumber slices floating in it, built as a phone-first booking page for at-home spa parties.
colors:
  rose: "#C23A66"
  rose-deep: "#9E2A50"
  pink: "#D85A82"
  foam-pink: "#E8789A"
  cuke: "#5A8A42"
  cuke-deep: "#3E6A2C"
  ground: "#FFF0F2"
  blush: "#FBE4E8"
  mint: "#EAF3E1"
  berry: "#4B1F35"
  berry-2: "#764460"
  plum: "#3B1A2C"
  line: "rgba(75,31,53,.14)"
  error: "#A5203F"
  error-edge: "#C2304F"
  white: "#FFFFFF"
  control-edge: "#C07590"
  placeholder: "#865A70"
  selection: "#F6BFD0"
  card-edge: "#F3C6D3"
  amp: "#C98597"
  soak-top: "#F2B3C3"
  soak-mid: "#F7C8D4"
  soak-low: "#F1B0C1"
  slice-flesh: "#EEF4D2"
  slice-band: "#B9D57F"
  close-amp: "#F9B9CB"
  close-cuke: "#DDF0C7"
  footer-text: "#F6DCE5"
  footer-muted: "#E2BFCC"
  footer-pink: "#F6A9C0"
  footer-cuke: "#B6D99A"
typography:
  wordmark:
    fontFamily: "\"CC Script\", cursive"
    fontSize: "21px"
    fontWeight: 400
    lineHeight: 1
  wordmark-wide:
    fontFamily: "\"CC Script\", cursive"
    fontSize: "22px"
    fontWeight: 400
    lineHeight: 1
  wordmark-desk:
    fontFamily: "\"CC Script\", cursive"
    fontSize: "30px"
    fontWeight: 400
    lineHeight: 1
  wordmark-close:
    fontFamily: "\"CC Script\", cursive"
    fontSize: "clamp(2.4rem, 11vw, 4.6rem)"
    fontWeight: 400
    lineHeight: 1.15
  step-desk:
    fontFamily: "ui-rounded, system-ui, sans-serif"
    fontSize: "1.85rem"
    fontWeight: 800
    lineHeight: 1.05
  list-desk:
    fontFamily: "ui-rounded, system-ui, sans-serif"
    fontSize: "1.9rem"
    fontWeight: 800
    lineHeight: 1.3
  close-text:
    fontFamily: "system-ui, sans-serif"
    fontSize: "1.125rem"
    fontWeight: 400
    lineHeight: 1.55
  display:
    fontFamily: "ui-rounded, \"SF Pro Rounded\", \"Hiragino Maru Gothic ProN\", system-ui, -apple-system, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(2.55rem, 11.6vw, 5.6rem)"
    fontWeight: 800
    lineHeight: 1.02
    letterSpacing: "-0.015em"
  headline:
    fontFamily: "ui-rounded, \"SF Pro Rounded\", \"Hiragino Maru Gothic ProN\", system-ui, -apple-system, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(2rem, 8.4vw, 3.4rem)"
    fontWeight: 800
    lineHeight: 1.02
    letterSpacing: "-0.01em"
  title:
    fontFamily: "ui-rounded, \"SF Pro Rounded\", \"Hiragino Maru Gothic ProN\", system-ui, -apple-system, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(1.25rem, 5.4vw, 1.5rem)"
    fontWeight: 800
    lineHeight: 1.15
  title-step:
    fontFamily: "ui-rounded, \"SF Pro Rounded\", \"Hiragino Maru Gothic ProN\", system-ui, -apple-system, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(1.6rem, 7vw, 2.2rem)"
    fontWeight: 800
    lineHeight: 1.05
  body:
    fontFamily: "system-ui, -apple-system, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.55
  lede:
    fontFamily: "system-ui, -apple-system, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(1.0625rem, 4.6vw, 1.25rem)"
    fontWeight: 400
    lineHeight: 1.45
  label:
    fontFamily: "ui-rounded, \"SF Pro Rounded\", \"Hiragino Maru Gothic ProN\", system-ui, -apple-system, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 800
    lineHeight: 1.2
  small:
    fontFamily: "system-ui, -apple-system, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "0.9375rem"
    fontWeight: 500
    lineHeight: 1.3
rounded:
  focus: "6px"
  code: "12px"
  panel: "18px"
  pill: "999px"
  field: "16px"
  card: "24px"
  disc: "50%"
spacing:
  chip-gap: "8px"
  cta-gap: "12px"
  form-gap: "22px"
  gutter: "20px"
  gutter-wide: "40px"
  seam-clear: "36px"
  seam-clear-wide: "56px"
  section-end: "76px"
  section-end-wide: "104px"
components:
  button-fill:
    backgroundColor: "{colors.rose}"
    textColor: "#FFFFFF"
    rounded: "{rounded.pill}"
    padding: "0 28px"
    height: "56px"
  button-fill-hover:
    backgroundColor: "{colors.rose-deep}"
  button-line:
    backgroundColor: "transparent"
    textColor: "{colors.rose-deep}"
    rounded: "{rounded.pill}"
    padding: "0 28px"
    height: "56px"
  button-line-hover:
    backgroundColor: "#FFFFFF"
  service-row:
    textColor: "{colors.berry}"
    typography: "{typography.title}"
    padding: "10px 0"
    height: "60px"
  service-row-arrow:
    backgroundColor: "rgba(75,31,53,.07)"
    textColor: "{colors.berry}"
    rounded: "{rounded.disc}"
    size: "40px"
  service-row-arrow-hover:
    backgroundColor: "{colors.rose}"
    textColor: "#FFFFFF"
  chip:
    backgroundColor: "#FFFFFF"
    textColor: "{colors.berry}"
    rounded: "{rounded.pill}"
    padding: "0 16px"
    height: "44px"
  chip-selected:
    backgroundColor: "{colors.rose}"
    textColor: "#FFFFFF"
  field:
    backgroundColor: "#FFFFFF"
    textColor: "{colors.berry}"
    rounded: "{rounded.field}"
    padding: "12px 16px"
    height: "54px"
  instagram-card:
    backgroundColor: "#FFFFFF"
    textColor: "{colors.berry}"
    rounded: "{rounded.card}"
    padding: "20px 22px"
  close-button:
    backgroundColor: "#FFFFFF"
    textColor: "{colors.rose-deep}"
    rounded: "{rounded.pill}"
    padding: "0 28px"
    height: "56px"
---

# Design System: Cupcakes & Cucumbers

## Overview

**Creative North Star: "The Pink Pedicure Soak"**

The whole page is a spa-party treat you can play with before the party starts. The first screen ends in a basin of milky pink water. Cucumber slices and foam bubbles float in it, it ripples on its own, and it moves under a finger or a cursor. Everything below comes from that soak. Each section boundary is a moving water line, the grounds are soft spa colours (cream, blush, cucumber mint), and the cucumber slice comes back as the step marker, the promo mark and the occasion bullet. The world comes from the business's own name and flyer: cucumber slices, pink spa water, foam, and the pink-and-cucumber-green script wordmark.

The voice is loud and friendly. Headlines are heavy, rounded and uppercase. Body copy is plain system sans so it stays quick to read. The page has one script face, and it only spells the business name. Density is low and built for a phone: one column, big type, 44 to 60px touch targets, and every action is a pill. Wider screens add columns but never change the material.

The build has no photography (the only images available show children's faces). Colour, the soak and the slice drawing carry the imagery instead.

**Key Characteristics:**
- An interactive water simulation is the hero image, and its water lines run down the page as section seams.
- Heavy rounded uppercase headlines over a plain system-sans body.
- A script wordmark (Pacifico subset) that only ever spells "Cupcakes & Cucumbers".
- Rose marks commitment (fills, selected states, the close section). Cucumber green marks the page responding to you (focus and hover on inputs).
- The darkest colours are berry and plum. The page never uses black.
- Pills everywhere. Soft drop shadows tinted rose, and only on a few tappable items.

## Colors

A warm pink family with one cucumber-green counter-voice, set on three pale spa grounds and grounded by berry and plum instead of black.

### Primary
- **Party Rose** (rose): the commit colour. Use it for filled buttons, selected chips, the service-row arrow disc on hover, the highlighted word in the hero headline, the phone icon, the caret, and the full ground of the closing call-to-action section. White text on it passes (5.1:1).
- **Deep Rose** (rose-deep): rose's pressed and hover state, and the text colour of outline buttons and of the white close button. It also tints every drop shadow.
- **Wordmark Pink** (pink): the "Cupcakes" half of the wordmark, plus the scrollbar thumb. At 3.3:1 on cream it is only for the large script wordmark and never for body text.
- **Foam Pink** (foam-pink): the colour of the water. Use it for the seam water lines (at 30% opacity), the outer tone of foam bubbles and the form's "pop" splash, and the warm end of the Instagram tile gradient.

### Secondary
- **Cucumber** (cuke): the "Cucumbers" half of the wordmark and the page's response colour. Use it for the 3px focus outline everywhere and for the border on hover and focus of chips and fields, with a 3px halo at 28% opacity. It passes 3:1 against every light ground the page uses.
- **Deep Cucumber** (cuke-deep): text-strength cucumber. Use it for step titles ("We travel"), the 10% promo line and the sticky promo beside the form. It passes on cream and mint (5.6 to 5.8:1).

### Neutral
- **Cream Ground** (ground): the hero, the "Perfect for" section, theme-color and the message preview panel.
- **Blush** (blush): the "What we bring" and "Plan her party" sections.
- **Cucumber Mint** (mint): the "How it works" section, the only green ground.
- **Berry** (berry): all primary text (12.3:1 on cream).
- **Berry Two** (berry-2): secondary text such as the lede, row sub-lines, group headings, "optional" tags and helper lines (6.3:1 on blush).
- **Plum** (plum): the footer ground. It is the darkest surface on the page.
- **Berry Hairline** (line): the 1px rule under each service row.
- **Error Red** (error): inline error text under required fields. The invalid field border uses a slightly brighter red (#C2304F).

Fields and chips at rest use a dusty rose 2px stroke (#C07590, about 3.2:1 on white), so the control boundary clears 3:1.

### Named Rules
**The Rose Acts, Cucumber Answers Rule.** Rose (and deep rose) belongs to things you commit to: fills, selected chips, the close ground. Cucumber green belongs to the page answering you: focus outlines and hover or focus borders on inputs. Don't swap them. A focus ring is never rose, and a primary fill is never green.

**The Plum-Not-Black Rule.** The darkest colours are berry (text) and plum (footer). No surface, text or shadow uses #000. Shadows are tinted rose-deep or plum.

**The Rotating Grounds Rule.** Section grounds rotate through cream, blush, mint, cream, blush, then rose for the close and plum for the footer. Two sections in a row never share a ground, so each seam always shows a change of water.

## Typography

**Display Font:** ui-rounded (SF Pro Rounded, then Hiragino Maru Gothic ProN, then the system sans stack)
**Body Font:** system-ui stack (-apple-system, Segoe UI, Roboto, Helvetica Neue, Arial)
**Wordmark Font:** "CC Script", an embedded WOFF2 subset of Pacifico (font-display: block)

**Character:** Rounded heavy uppercase shouts like a party invitation. The plain system body keeps the reading quiet and fast. The script exists only as the brand's signature. The page loads no web fonts apart from the wordmark subset (the house rule is a system font stack). The rounded character shows on Apple platforms. Elsewhere display falls back to the heavy system sans, which keeps the weight and case but not the rounding.

### Hierarchy
- **Wordmark** (400, 21px to 30px in the header, 26px in the footer, clamp(2.4rem, 11vw, 4.6rem) at the close, line-height 1): "Cupcakes" in pink, "&" in a muted pink (#C98597), "Cucumbers" in cucumber. On dark grounds the three parts switch to lighter tints: #FFE3EA / #F9B9CB / #DDF0C7 on rose, and #F6A9C0 / #C98597 / #B6D99A on plum. In the header it stacks on two lines on small phones and sits on one line from 430px.
- **Display** (800, clamp(2.55rem, 11.6vw, 5.6rem), 1.02, -0.015em, uppercase): the hero headline only. One word can switch to rose to say what the business is ("spa").
- **Headline** (800, clamp(2rem, 8.4vw, 3.4rem), 1.02, -0.01em, uppercase, 28px below): every section heading. Balanced wrapping.
- **Title** (800, clamp(1.25rem, 5.4vw, 1.5rem), 1.15): the service-row names, which are the main tappable list. Occasion lines use the same heavy rounded voice, larger (clamp(1.35rem, 6vw, 2.1rem), 1.3).
- **Step Title** (800, clamp(1.6rem, 7vw, 2.2rem), 1.05, uppercase, deep cucumber): the four "We ..." steps.
- **Group Heading** (800, 1.0625rem, 0.06em tracking, uppercase, berry-two): labels a service list (The spa / Add-ons / Extras). It names the list beneath it. It is not a teaser above a headline.
- **Lede** (400, clamp(1.0625rem, 4.6vw, 1.25rem), 1.45, berry-two, max 30ch): the line under the hero headline.
- **Body** (400, 17px, 1.55): running copy. Step descriptions cap at 34ch, and closing and lede lines at 30ch.
- **Label** (800, 1.0625rem, 1.2, rounded): form legends and field labels. A 15px system-sans "optional" tag follows inline in berry-two.
- **Button** (700, 1.0625rem, line-height 1, rounded). The close button is larger (800, 1.25rem).
- **Small** (500, 0.9375rem, 1.3): row sub-lines, helper text, errors, the footer line.

### Named Rules
**The One Script Rule.** Pacifico is subset to the glyphs of the business name and sets nothing else. It can't render other text, and it shouldn't. Headlines, buttons and labels use the rounded display stack.

**The Loud Rounded Rule.** Every heading voice is rounded and weight 800. Headings that name a section or step are uppercase. Never set a heading in a light or regular weight.

## Layout

Phone-first, one column, centred hero. The content wrapper is capped at 1120px and the header row at 1240px. Side gutters are 20px on phones and 40px from 760px.

- **Hero:** fills the viewport (min(100svh, 980px)) as a flex column. Header row, centred copy (max 860px), CTA stack (max 360px, 12px gap), promo line, then the soak takes all remaining height (at least 190px on phones, 300px from 760px). The soak sits flush to the edges with no frame.
- **Sections:** no top padding of their own. The seam overlaps the previous section by 55px, and the content starts 36px below it (56px from 760px). Sections end with 72 to 76px (104px from 760px).
- **Breakpoints:** 430px (header wordmark goes to one line, Instagram arrow appears), 760px (wider gutters, two-up hero CTAs, three service columns, two-column steps, two-column occasions), 1024px (four steps in a row with larger slices, occasions beside the Instagram card, the form beside a sticky heading and promo at a 0.8 / 1.2 split, two-up field pairs).
- **Rhythm:** 8px between chips, 12px between CTAs, 22px between form groups, 26 to 40px between steps, 36 to 48px between service groups.
- **Safe areas:** viewport-fit=cover, and the footer pads by env(safe-area-inset-bottom).

## Elevation & Depth

The page is flat. Depth comes from the soak (simulated water, sprites with soft cast shadows) and from the seams laying one colour of water over the next. A few tappable surfaces get a soft drop shadow tinted rose. The shadows have negative spread and sit low, so they read as a glow cast onto the water, not a card lifted off the page.

### Shadow Vocabulary
- **Rose Drop** (`box-shadow: 0 8px 20px -8px rgba(158,42,80,.55)`): under filled rose buttons only.
- **Card Drop** (`box-shadow: 0 14px 34px -18px rgba(158,42,80,.45)`, hover `0 18px 40px -18px rgba(158,42,80,.6)`): the Instagram card. Its shadow deepens on hover.
- **Plum Drop** (`box-shadow: 0 10px 26px -12px rgba(59,26,44,.6)`): the white button on the rose close section, where a rose shadow would vanish.
- **Focus Halo** (`box-shadow: 0 0 0 3px rgba(90,138,66,.28)`): chips and fields on focus. This is a state, not elevation.

### Named Rules
**The Rose-Tinted Drop Rule.** Shadows are soft, negative-spread and tinted rose-deep (plum on a rose ground). They appear only under a primary tappable item. No hard offsets, no neutral grey shadows, and no shadows on chips, rows, fields or section blocks.

## Shapes

Everything is soft. Every action is a pill (999px): buttons, chips, the skip link, the close button. Fields have gently rounded 16px corners, and so does the Instagram glyph tile. The Instagram card is a 24px rounded panel. The post-submit panel and its message preview use 18px and 12px. The arrow disc and the bubbles are circles. Borders are 2px when they define a control (outline button, chip, field, card) and 1px only for the hairline under service rows. Section edges are never straight: every boundary is the seam's wave. The cucumber slice (dark skin ring, pale band, pale flesh, three seed chambers) is the recurring circle motif, drawn as a 48-unit SVG symbol at 17px (promo), 46px or 64px (steps), and as a radial-gradient dot for occasion bullets.

## Components

### Buttons
Big, round and friendly. Every one is a full pill with a 56px minimum height.
- **Shape:** full pill (999px), 0 28px padding, 10px icon gap, 2px rose border on every variant.
- **Fill:** rose with white 700 rounded text and the Rose Drop shadow. Hover deepens to deep rose (fill and border). Use it for the main action on a screen (Plan the party, Text this to Marissa).
- **Line:** transparent with deep-rose text and a rose border. Hover fills white. It is the second action next to a fill (Text us, Copy message, Call).
- **Close:** a white pill with deep-rose 800 1.25rem text and the Plum Drop, on the rose close ground. Hover is a faint pink (#FFF0F4), and its focus outline switches to white.
- **Press:** every button drops 1px on :active. Transitions run 0.2s on background, colour, shadow and transform.
- **Icons:** 20px inline SVG with a 2px round-capped stroke in currentColor (phone, chat, arrow, Instagram).

### Service Rows
A tappable menu, not a set of cards.
- **Style:** full-width link, 60px minimum height, 10px vertical padding, berry 800 title-scale text, 1px berry hairline below. An optional 15px berry-two sub-line sits under the name.
- **Arrow:** a 40px circle in 7% berry with an 18px arrow, at the right edge.
- **Hover / Focus:** the row itself doesn't change: no background, outline or shadow. Only the arrow disc fills rose with a white arrow (0.2s).
- **Behaviour:** tapping a row ticks the matching chip in the form and scrolls to it, and the chip splashes foam.

### Chips
- **Style:** a hidden native radio or checkbox under a white 44px pill, 0 16px padding, 600 15px text, 2px pale-pink stroke, 8px gaps, wrapping.
- **Hover / Focus:** the border turns cucumber. Keyboard focus adds the 3px cucumber halo.
- **Selected:** rose fill, rose border, white text. When selected and hovered or focused, the border turns cucumber again.
- **Splash:** checking an option bursts seven 9px foam bubbles up from the chip (0.7s, cubic-bezier(.16,1,.3,1)). It is off under reduced motion.

### Inputs / Fields
- **Style:** white, 54px minimum height (textarea 96px, vertical resize), 12px 16px padding, 16px corners, 2px pale-pink stroke, 500 17px system text in berry. Native appearance is removed.
- **Hover:** cucumber border.
- **Focus:** cucumber border plus the 3px cucumber halo. The default outline is removed in favour of the halo.
- **Error:** the field border goes red (#C2304F) and a 15px 600 error-red line appears below with a specific, kind instruction. It clears as soon as the person types.
- **Labels:** sit above in the rounded label style, with an inline "optional" tag where it applies.

### Instagram Card
- **Corner Style:** 24px. **Background:** white, 2px soft pink border (#F3C6D3). **Padding:** 20px 22px.
- **Content:** a 52px rounded tile (16px corners) with a pink-to-rose 135° gradient and a white Instagram glyph, a bold 1.25rem line plus a 15px handle, then the arrow disc (shown from 430px).
- **Hover:** border turns rose, the Card Drop deepens and the arrow disc fills rose.

### Header & Footer
- **Header:** wordmark at left (links to top), tap-to-call number at right in 800 rounded berry with a rose phone icon. Hover turns it deep rose. Both have 44px minimum targets. There is no nav menu.
- **Footer:** plum ground, lighter wordmark tints, phone and Instagram links with 18px pink icons on 44px rows (hover underline offset 4px), and a 15px muted-pink line. Focus outlines switch to light cucumber (#B6D99A).

### Focus
The global keyboard focus is a 3px cucumber outline, offset 3px, with 6px rounding. On plum it switches to light cucumber, and on rose to white.

### The Soak (signature)
A canvas filling the bottom of the hero: a live pink pedicure basin.
- **Water:** a height-field ripple simulation on a 4px grid, stepped twice per frame, painted between a deep foam pink (rgb 232,140,168) and milky pink (rgb 252,216,226). Tileable value noise drifts across it as swirls of milk, and the ripple slopes add light and a soft specular sheen. Under the CSS it starts as a pink gradient (#F2B3C3 to #F7C8D4 to #F1B0C1) so the area is never empty.
- **Shore:** the top 18px stays cream. The water's edge undulates (amplitude 7px) and reflects ripples, with a rose shadow just under the lip.
- **Cucumber slices:** procedurally drawn sprites (wobbly dark-green skin with streaks, pale band, pale flesh, three seed chambers with seeds, wet highlight, soft rose shadow on the water). There are 5 on phones and 7 from 700px, at 30 or 42px radius with ±variation. They ride the ripples, swirl slowly around the centre, drift lazily, bump softly into each other, rotate, bob with the water height and leave wakes.
- **Foam:** 46 bubbles on phones and 120 on desktop, in four sprite sizes, mostly clustered at the shore and around slices. They slide around slices, never over them, fade in and out, and leave a tiny ripple when they pop.
- **Interaction:** pointer down or drag (touch or mouse) disturbs the water along the path and pushes slices and foam within a 74px radius. On desktop, hovering anywhere over the water band works too. Ambient drops fall every 650 to 1500ms, pausing for 2.6s after any touch.
- **Tunables** (top of the soak script): DAMP 0.982, DROP_EVERY [650, 1500] ms, TOUCH_QUIET 2600 ms, SLICES_PHONE 5 / SLICES_DESK 7, BUBBLES_PHONE 46 / BUBBLES_DESK 120, CURRENT 0.03, WANDER 22, PUSH_R 74px, SHORE 18px, SHORE_AMP 7px.
- **Cost and access:** device pixel ratio capped at 1.5. It pauses offscreen (IntersectionObserver) and ignores address-bar resizes. It is aria-hidden with touch-action none. Under reduced motion it renders a single settled frame with five set rings and no loop.

### Seams (signature)
Moving water lines where each section begins.
- **Construction:** a 56px full-width SVG (viewBox 1440×56, preserveAspectRatio none) pulled 55px up over the previous section. A filled wave in the new section's ground (data-fill) rises over the old one, and a 3px water line in foam pink sits about 7px above the fill's crest (cucumber-mid #8DB86F before the mint section) at 30% opacity, with a non-scaling stroke.
- **Motion:** each wave sums three sines (6, 3.2 and 1.4 units, scaled by AMP), and each seam has a phase offset of 1.7 times its index so no two move together. SPEED and AMP (both 1) are the tunables. The seams animate only while on screen and are static under reduced motion.

## Do's and Don'ts

### Do:
- **Do** start every new section with a seam whose fill is the new section's ground, and change the ground at every seam (The Rotating Grounds Rule).
- **Do** use rose for the one action that commits, and line buttons for its companion. Keep every button a 56px pill.
- **Do** give every control its cucumber response: a cucumber border on hover, and a 3px cucumber outline or halo on focus.
- **Do** reuse the cucumber slice symbol as the page's marker (steps, promo, bullets) instead of generic icons or dots.
- **Do** keep touch targets at 44px or more (60px for service rows), and keep phone layouts to one column.
- **Do** pause any new canvas or animated motif offscreen and give it a static reduced-motion state, as the soak and seams do.
- **Do** keep the soak's look tunable through its named constants, not by editing the simulation.

### Don't:
- **Don't** use Pacifico, or any script, for anything except the business name (The One Script Rule).
- **Don't** use black or neutral grey for text, surfaces or shadows. Use berry, berry-two or plum.
- **Don't** put background, outline or shadow hover states on service rows. Only the arrow disc reacts.
- **Don't** use rose for focus indication or cucumber for primary fills (The Rose Acts, Cucumber Answers Rule).
- **Don't** separate sections with straight rules, boxed panels or a flat colour change. The boundary is always the moving seam.
- **Don't** add hard-offset, grey or ambient card shadows. Shadows are soft, tinted rose and only under primary tappable items.
- **Don't** set body copy in wordmark pink, cucumber or the muted ampersand pink. They are display-only at their contrast.
- **Don't** lighten the field and chip stroke (#C07590) below 3:1 against white. Paler pinks read prettier but the controls disappear.
