# Cupcakes & Cucumbers — handoff at ~60%

**Live:** https://10elizabethbell.github.io/cupcakesAndCucumbers/ · **Repo:** https://github.com/10elizabethbell/cupcakesAndCucumbers · **Built:** 2026-10-17 from Muse brief (run 2026-10-18, NJ Small Business Network group post)

## What's built
- One phone-first page, `index.html` (~60KB, no images except the og/icon files).
- **World: a pink pedicure soak.** The hero's bottom is milky pink water with real-looking cucumber slices (skin, pale band, seed chambers) and foam bubbles. It drips and ripples by itself; a finger or mouse makes ripples in every direction and pushes the slices, which knock into each other and leave wakes. Bubbles slide around slices and pop. Moving water lines join every section.
- Sections: header (wordmark + tap-to-call number top-right), hero ("The spa comes to you", tagline, **Plan the party** / **Text us**, the 10% offer), What we bring (spa, add-ons, extras as tappable rows: tapping one ticks it in the form), You host nothing (We travel / set up / host / clean up), Perfect for (occasions), Instagram link, Plan her party (form → pre-written text to 347-620-8903), close (wordmark, 10% offer, **Text us to book**), footer (phone, Instagram, NY & NJ). The number shows once per screen: top-right on the first screen, then only in the footer (and the form's fallback after submit).
- Form: occasion, date, town, kids, ages, picks, name, notes. Date, town and name are required with inline errors. Submit opens Messages with the text written; a fallback shows the message with Copy and Call buttons.
- Tunables are constants at the top of each script: `DAMP`, `DROP_EVERY`, `CURRENT`, `WANDER`, `SLICES_PHONE/DESK`, `BUBBLES_PHONE/DESK`, `PUSH_R` (soak); `SPEED`, `AMP` (seams).

## Assumptions I made
- **Colors** sampled by eye from the flyer wordmark: "Cupcakes" pink, "Cucumbers" green, blush/cream grounds, deep rose buttons, dark plum footer (no black).
- **Wordmark** set in Pacifico (the closest match to the flyer's script), subset to the name's letters (2.7KB). There's no logo file; favicon/home-screen icon are "C&C" in that lettering.
- **Voice "we"**, from the caption ("We travel. We set up..."). Marissa named as the person you text, from the brief (owner/contact who posted).
- **Step lines** under We set up / We host / We clean up are my wording of their four-word promise ("Your living room turns into her spa before the first guest walks in", "nobody gets left out", "the way we found it"). Owner should confirm.
- **Karaoke and Glampagne** come from the flyer tiles (read on the image, not OCR). Glampagne listed as-is; I don't know what it is (likely a sparkling mocktail).
- **Occasions** read from the flyer image: birthday, sleepovers, girls nights, craft nights, Halloween, fall get-togethers, Friendsgiving.
- Audience treated as parents under 40 (moms of young girls), so the full signature motion is on.

## Placeholders and gaps
- **No photos.** The flyer and the Instagram profile picture both show children's faces; nothing used. Instagram (@cupcakes_and_cucumbers, 184 posts) needs a login to fetch posts. Setup shots without faces (stations, mini bars, teepees, cupcakes) would fill a proof section well.
- **No Facebook link:** the business has no page; posts come from Marissa's personal profile, which I didn't link. Instagram sits where Facebook usually goes (under "Perfect for" and in the footer).
- **No email** (none found), so the footer has none.
- **Texts unknown:** "Text us" and the form both text the number. If she doesn't text, swap them for a call.
- The **10% offer expires end of 2026**: it's in the hero, plan sidebar (desktop) and close. Remove in January.
- No prices, hours, towns or reviews, so none on the page.

## Questions for the owner
- Do you take texts at 347-620-8903?
- Can we use party photos? Setup and product shots without kids' faces first, or ones parents have OK'd.
- Packages and starting prices (the niche norm is package pages; Glamour n Glitz shows from $589)?
- Which towns or how far do you travel? Minimum guests? Ages?
- What is Glampagne, and what's in a Mini Bar?
- Want a business email for the footer?

## Ideas not built (yours to pick)
- **Runner-up world:** sprinkles and nail polish. Sprinkles scatter under a finger and polish paints across the hero in the brand pinks.
- Package cards once prices exist; a `book.html` page with the same soak.
- Photo bubbles floating in the soak (as on Blessed) once face-free photos arrive.
- A "Cupcakes" counterpart to the cucumbers: frosting swirl dividers, or a cupcake that "pops" sprinkles when you tick Homemade cupcakes.
- A burst of bubbles and slices when "Text this to Marissa" is tapped (finish reviewer's delight idea).
- Seasonal swap: fall leaves drifting on the water through November (the flyer is all fall leaves).

## Not verified
- Real-device touch on iPhone/Android, and the soak's frame rate on older phones (headless only: WebKit + Chromium at 360–1440 px, simulated mouse and touch sweeps moved slices ~100px).
- Real SMS hand-off from Facebook's and Instagram's in-app browsers (`sms:` link built and decoded correctly in tests).
- That @cupcakes_and_cucumbers is definitely her account (name matches and the handle is printed on her flyer; not confirmed with her).

## Review passes run
- Impeccable: detector (0 findings after fixes; one `overused-font=roboto` ignore, since Roboto is only the Android fallback in Ellie's system stack), the finish reviewer covering critique, audit, polish, clarify, typeset, layout, colorize, harden, adapt, animate, delight, distill, quieter/bolder and optimize. Fixes applied: thinner ripple rings, one soft seam line instead of two, one phone number per screen, "anywhere" removed from the travel line, the hero no longer repeats "sit back and relax", Instagram card beside the occasions on desktop, `aria-hidden` on the arrows, and the contrast and tap-target fixes.
- Kept despite review: "Click to see more of our parties" (Ellie's own wording in the finishing rules).
