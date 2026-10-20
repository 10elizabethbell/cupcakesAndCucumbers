# Cupcakes & Cucumbers — handoff at ~60%

**Live:** https://10elizabethbell.github.io/cupcakesAndCucumbers/ · **Repo:** https://github.com/10elizabethbell/cupcakesAndCucumbers · **Built:** 2026-10-17 from Muse brief (run 2026-10-18, NJ Small Business Network group post) · **Revamped:** 2026-10-19 to the calm band style

## Revamp (2026-10-19): what changed
The business hadn't been contacted, so the whole page was rebuilt under the new house default (calm band style, after lpmr.co.uk; copied from DPG's build). Facts, the form's fields and the text-message wiring carry over; the look, structure and motion are new.
- **Gone:** the pink pedicure soak (canvas water, cucumber slices you push around, bubbles), the moving water seams between sections, the tick-a-pick foam splash, the rounded uppercase system headings, the "Text us to book" button in the close. All of it is in git history (`e1e6119`).
- **New look:** blush paper (#fbf5f6) and two cucumber greens (#3b6a34 hero / services-close bands, #1f3a22 textured bands and footer), cupcake pink (#f6a6c0) as the one accent, used as a fill with dark-green text on it; #a52c59 when pink has to be text on light. Cal Sans headings, system body at 16/1.7, pill buttons, 24px form card. The Pacifico script wordmark stays as the logo stand-in.
- **New structure:** header (wordmark, tap-to-call top right) → green hero → What we bring (service rows on deep green) → You host nothing (four numbered steps on paper, plus her own "You sit back, relax..." line) → Perfect for (occasions as a quiet list, Instagram card) → Plan her party (form) → close (wordmark, offer, big phone number) → footer.
- **New motion:** hero H1 bounces in letter by letter (waits up to 700ms for Cal Sans so it doesn't bounce in the fallback font), one 12px fade-up on things below the first screen, a 60px floating pink text circle that shows after the hero and hides over the form. Reduced motion and no-JS show everything at once.
- **Form:** same fields (it still covers her Jotform "Birthday Club Sign-Up"), reordered so the essentials come first: what she'd love → occasion → date/kids/ages → where → you → the birthday girl → before/heard/notes. Tapping a service row ticks it at the top of the form. Required: party date, town, your first and last name. After submit a fallback shows the text with Open in Messages / Copy message / "or call".
- **Phone number:** top-right on the first screen; then only the close's big number and plain text in the footer (the footer's extra "Call" link was cut).
- **Copy changes:** hero promise "Luxury at-home spa parties for little divas. We bring everything, and we leave nothing behind."; the offer reads "10% off parties booked in 2026" everywhere; "Marissa gets back to you" instead of "texts you back" (texting is unconfirmed); "Your living room becomes her spa" (dropped the "before the first guest arrives" timing promise); "birthday girl / she" in the form.
- New `og.jpg` (the new hero). Favicon and home-screen icon unchanged ("C&C" in the script lettering).

## Assumptions I made
- **Palette roles:** the calm style wants navy bands and a warm accent; this brand has no navy, so cucumber green plays navy and cupcake pink plays the accent, both from the flyer wordmark.
- **No photo hero:** plain textured green band, because every photo available (the flyer, the Instagram profile picture) shows children's faces. Three static cucumber slices sit on the right of the hero on desktop only (≥1024px).
- **Voice "we"**, from the caption ("We travel. We set up..."). Marissa named as the person you text, from the brief.
- **Step lines** ("Right to your door in New York and New Jersey", "Your living room becomes her spa", "Every little guest gets pampered", "We leave your home the way we found it") are my wording of their four-word promise. Owner should confirm.
- **Karaoke and Glampagne** come from the flyer tiles. Glampagne listed as-is; I don't know what it is.
- **Occasions** read from the flyer image.
- **Audience** treated as parents under 40 (moms of young girls), so the calm style's motion is on.
- **"10% off parties booked in 2026"** shortens "booked between now & the end of 2026" so the hero eyebrow fits one line at 360px.

## Placeholders and gaps
- **No photos** (faces). Setup and product shots without kids' faces (stations, mini bars, teepees, cupcakes) would fill a photo section and could go behind the hero.
- **No Facebook page:** posts come from Marissa's personal profile, which I didn't link. Instagram sits where Facebook usually goes (under "Perfect for") and in the footer.
- **No email** found, so the footer has none.
- **Texts unknown:** "Text us", the floating circle and the form all text 347-620-8903. If she doesn't text, swap them for a call.
- The **10% offer expires end of 2026**: hero eyebrow, close, og description. Remove in January.
- No prices, hours, towns or reviews, so none on the page.

## Questions for the owner
- Do you take texts at 347-620-8903?
- Can we use party photos? Setup and product shots without kids' faces first, or ones parents have OK'd.
- Packages and starting prices (the niche norm is package pages; Glamour n Glitz shows from $589)?
- Which towns or how far do you travel? Minimum guests? Ages?
- What is Glampagne, and what's in a Mini Bar?
- Want a business email for the footer?

## Open questions for Ellie
- Green as the "navy": the alternative is deep berry/plum bands with the pink accent (more girly, less contrast between bands). I went green because the name pairs pink with cucumber.
- Cucumber slices in the hero are desktop-only; the finish reviewer suggested one slice cropped off the right edge of the phone hero (about 120px, ~175px down, clear of the copy). Not built.
- Was the old soak hero worth keeping as the opt-in signature motion? It's in `e1e6119` if you want it back.

## Ideas not built (yours to pick)
- **Signature motion (opt-in):** the old pink soak with cucumber slices (git `e1e6119`) is the ready runner-up. Other worlds from the trade: nail polish painting across the hero in the brand pinks; sprinkles scattering under a finger; frosting-swirl dividers; fall leaves drifting through November (the flyer is all fall leaves).
- Package cards once prices exist ("One-off parties always welcome" above them, per the calm kit).
- Photo cards with an Instagram row under them once face-free photos arrive.
- A small reward when "Text this to Marissa" is tapped.
- **Declined Impeccable findings (house style):** eyebrow pills (craft floor bans them), the H1 letter bounce-in, the floating circle (on phone it passes over the service rows' arrows while scrolling; the rows stay tappable full width), Cal Sans, the diagonal band texture (detector: `repeating-stripes-gradient`), the same fade-up on every section, and no seed key in the contract's FORM line.

## Not verified
- Real-device touch and the SMS hand-off from Facebook's and Instagram's in-app browsers (`sms:` links built and decoded correctly in tests).
- That @cupcakes_and_cucumbers is definitely her account (name matches and the handle is printed on her flyer).
- iOS date field rendering on a real iPhone (left-aligned via `::-webkit-date-and-time-value`, checked in WebKit only).

## Review passes run (revamp)
- Playwright audit in Chromium and WebKit at 360, 390, 414, 430 and 1440: no sideways overflow, no tap targets under 44px, no inputs under 16px, one phone number on the first screen, primary button inside the first screen. Bounce-in checked mid-animation (letters 50px out) and settled (plain H1 restored, same three lines). Reduced motion and JS-off: nothing hidden. Floating circle: hidden on the hero, shown below it, hidden over the form, shown at the close.
- Contrast by calculation: pink-on-green H1 accent 3.4:1 (large text only), white on green 6.4:1, dark green on pink 6.6:1, pink ink on paper 6.3:1, placeholder on field 4.6:1.
- Impeccable: detector (only `repeating-stripes-gradient`, kept; design-system drift findings were against the old DESIGN.md, now rewritten), then the finish reviewer covering critique, audit, polish, clarify, typeset, layout, colorize, harden, adapt, animate, delight, distill, quieter/bolder and optimize. Applied: footer call link cut, form reordered, bounce-in waits for the font, eyebrow shortened for 360px, copy truth fixes, no accent on the light-band heading, form section dividers and desktop rows, `aria-required` on required fields, iOS date alignment.
- Finishing-rules checklist re-checked after the fixes.

## Call Sheet
- `call-sheet-site.sh` returned `LOCK BUSY: held by muse 2026-10-19 21:56` twice (2026-10-19 evening). The sheet already lists this prospect with the same live URL (read-only check of `prospects.json`), so nothing needed to change; no hand edit made.
- Detector leftovers after the DESIGN.md rewrite are advisory design-system drift (wordmark colours on dark bands, a few one-off sizes/radii not in DESIGN.md) plus the kept band texture.
