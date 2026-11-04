---
name: Para Dayana
description: A love letter as a one-night concert slot machine; every pull lights a stadium of wristband stars and prints one ticket of the setlist.
colors:
  night-0: "#0A0726"
  night-1: "#170F4A"
  night-2: "#2D1666"
  night-3: "#5A2380"
  well: "#0B0726"
  cabinet-top: "#4636BE"
  cabinet-mid: "#2C2196"
  cabinet-deep: "#1D1572"
  drawer-top: "#20166A"
  drawer-deep: "#140D4A"
  ink: "#F5F2FF"
  ink-2: "#CFC6F5"
  paper-ink: "#1C1245"
  paper-ink-2: "#2E2366"
  sun: "#FFC93C"
  sun-deep: "#E8890B"
  sun-ink: "#2A1500"
  seed: "#5A3214"
  pink: "#FF4FA3"
  cyan: "#3FE0F0"
  orange: "#FF8A3D"
  green: "#6BE38A"
  violet: "#9B7BFF"
  band-lilac: "#B9A6FF"
  band-lavender: "#C2A8FF"
  quiet-crowd: "#C9C2FF"
  gold: "#FFD24A"
  gold-hi: "#FFF1B8"
  gold-deep: "#B9800A"
  gold-low: "#E2A419"
  paper-yellow: "#FFD45C"
  paper-pink: "#FFA3CF"
  paper-cyan: "#93E7F3"
  paper-orange: "#FFC29A"
  paper-green: "#B2F1C5"
  paper-lavender: "#D6C8FF"
  paper-quiet: "#F4F1FF"
  paper-quiet-violet: "#E9E3FF"
  paper-entry: "#F6F3FF"
  reel-face: "#F7F3FF"
  pass-face: "#FBF9FF"
typography:
  display:
    fontFamily: "Doto, ui-monospace, SFMono-Regular, Menlo, monospace"
    fontSize: "clamp(46px, 15vw, 84px)"
    fontWeight: 900
    lineHeight: 0.9
    letterSpacing: "0.02em"
  headline:
    fontFamily: "Grandstander, Arial Rounded MT Bold, ui-rounded, system-ui, sans-serif"
    fontSize: "clamp(31px, 8.8vw, 42px)"
    fontWeight: 900
    lineHeight: 1
    letterSpacing: "-0.01em"
  title:
    fontFamily: "Grandstander, Arial Rounded MT Bold, ui-rounded, system-ui, sans-serif"
    fontSize: "22px"
    fontWeight: 900
    lineHeight: 1.08
  action:
    fontFamily: "Grandstander, Arial Rounded MT Bold, ui-rounded, system-ui, sans-serif"
    fontSize: "22px"
    fontWeight: 900
    lineHeight: 1
    letterSpacing: "0.005em"
  body:
    fontFamily: "M PLUS Rounded 1c, ui-rounded, system-ui, -apple-system, Segoe UI, sans-serif"
    fontSize: "18.5px"
    fontWeight: 500
    lineHeight: 1.6
  body-sm:
    fontFamily: "M PLUS Rounded 1c, ui-rounded, system-ui, -apple-system, Segoe UI, sans-serif"
    fontSize: "15px"
    fontWeight: 500
    lineHeight: 1.45
  marquee:
    fontFamily: "Doto, ui-monospace, SFMono-Regular, Menlo, monospace"
    fontSize: "20px"
    fontWeight: 900
    letterSpacing: "0.06em"
  label:
    fontFamily: "Doto, ui-monospace, SFMono-Regular, Menlo, monospace"
    fontSize: "12.5px"
    fontWeight: 900
    lineHeight: 1.4
    letterSpacing: "0.07em"
rounded:
  reel: "11px"
  tile: "16px"
  window: "18px"
  ticket: "22px"
  sheet: "26px"
  cabinet: "32px"
  pill: "999px"
spacing:
  gutter: "16px"
  ticket-x: "24px"
  ticket-top: "28px"
  cabinet-x: "20px"
  stub: "66px"
components:
  button-pull:
    backgroundColor: "{colors.sun}"
    textColor: "{colors.sun-ink}"
    typography: "{typography.action}"
    rounded: "{rounded.pill}"
    height: "62px"
    width: "100%"
  button-pull-jackpot:
    backgroundColor: "{colors.gold}"
    textColor: "{colors.sun-ink}"
    rounded: "{rounded.pill}"
  button-ticket:
    backgroundColor: "{colors.paper-ink}"
    textColor: "{colors.paper-yellow}"
    rounded: "{rounded.pill}"
    height: "56px"
    width: "100%"
  button-gift-confirm:
    backgroundColor: "{colors.gold}"
    textColor: "{colors.sun-ink}"
    rounded: "{rounded.pill}"
    height: "60px"
    padding: "0 24px"
  icon-button:
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    size: "44px"
  ticket:
    backgroundColor: "{colors.paper-yellow}"
    textColor: "{colors.paper-ink}"
    rounded: "{rounded.ticket}"
    padding: "28px 24px 20px"
  ticket-quiet:
    backgroundColor: "{colors.paper-quiet}"
    textColor: "{colors.paper-ink}"
    rounded: "{rounded.ticket}"
  ticket-stub:
    textColor: "{colors.paper-ink-2}"
    typography: "{typography.label}"
    height: "66px"
    padding: "0 22px"
  marquee:
    backgroundColor: "{colors.well}"
    textColor: "{colors.sun}"
    typography: "{typography.marquee}"
    rounded: "{rounded.reel}"
    height: "36px"
  reel:
    backgroundColor: "{colors.reel-face}"
    rounded: "{rounded.reel}"
  setlist-drawer:
    backgroundColor: "{colors.drawer-top}"
    textColor: "{colors.ink}"
    rounded: "{rounded.sheet}"
    padding: "20px 18px"
  pass-card:
    backgroundColor: "{colors.pass-face}"
    textColor: "{colors.paper-ink}"
    rounded: "{rounded.window}"
---

# Design System: Para Dayana

## Overview

**Creative North Star: "Cielo lleno de estrellas"**

The page is the "A Sky Full of Stars" moment of a one-night concert, held in a phone. A deep indigo-to-violet night is the ground; a stadium bowl of LED wristband dots fills the lower sky and waves in color; a rounded indigo slot cabinet with a chasing LED-bulb rim sits center stage with a panda resting its paws on top, holding a sunflower, wristband glowing. Each pull prints one paper concert ticket of the setlist. The world is playful and warm but never a greeting card: light comes from the crowd, not from hearts.

Density is one-handed and vertical: a narrow column (460px max), a single full-width primary action in the thumb zone, and everything readable arrives on paper sheets that rise from the bottom. Color is carried by light (wristbands, bulbs, marquee) on the night, and by tinted paper on the tickets. Metallic gold is held back for the jackpot so that its arrival reads as an event.

Motion is part of the world, not decoration: the lever has weight, reels land with overshoot, the crowd answers each ticket with a wave in that ticket's band color, tickets print out of the slot and fly into the setlist. Hard fragments drop the whole stage into quiet mode.

**Key Characteristics:**
- Night ground, light-as-color: wristband LED palette on a vertical indigo-to-violet gradient.
- Sunflower yellow is the single warm primary and the flat action color.
- Metallic gold exists only in the jackpot state.
- Paper tickets per song: tinted stock, perforated stub, Doto print, grain overlay.
- Panda and sunflower are the illustration language, drawn as inline SVG.
- Quiet mode for hard fragments: dimmer crowd, pale paper, slower bulbs, lowered panda.
- Reduced motion collapses every animation to its end state without losing content.

## Colors

A night-sky ground lit by six wristband LEDs, one warm sunflower primary, tinted ticket papers, and a gold that is held in reserve.

### Primary
- **Sunflower Yellow** (`sun`): the pull button fill, payline and its arrows, marquee text at rest, the live digit in the ticket counter, active carousel dot, the sender signature on the finale, text selection, and the constellation petals. It is the flat action color: the pull button is a solid fill, never a gradient.
- **Sunflower Deep** (`sun-deep`) and **Seed Brown** (`seed`): petal shading and the sunflower disk in illustrations and the favicon; never UI fills.
- **Sunflower Ink** (`sun-ink`): text on sunflower and gold fills.

### Secondary
- **Wristband LEDs** (`pink`, `cyan`, `sun`, `orange`, `green`, `violet`): the crowd palette. They color stadium dots, cabinet bulbs (cycled in this order), the entry ticket's dot strip, confetti, and each song's band. Pink also carries the unread badge and the armed reset link. Cyan is the global focus ring.
- **Quiet bands** (`band-lilac`, `band-lavender`): paler violet bands for the quiet and closing songs.

### Tertiary
- **Jackpot Gold** (`gold`, `gold-hi`, `gold-deep`, `gold-low`): the jackpot state only. Gold recolors the bulbs, marquee, payline (thicker, flashing), reel window ring, crowd waves, constellation stars, confetti share, the pull button (a `gold-hi` to `gold` to `gold-low` gradient), the gift-confirm button, and the chosen gift pass ring. `gold-deep` strokes constellation petals.
- **Ticket papers** (`paper-yellow`, `paper-pink`, `paper-cyan`, `paper-orange`, `paper-green`, `paper-lavender`, `paper-quiet`, `paper-quiet-violet`, `paper-entry`): one tinted stock per song, a light tint of that song's band. Quiet songs use the near-white lilac stocks; the entry ticket uses `paper-entry`.

### Neutral
- **Night** (`night-0` to `night-3`): the body gradient, top to bottom at 0 / 44 / 78 / 100%, fixed to the viewport. `night-0` is also the theme color and html background.
- **Well** (`well`): recessed surfaces inside the cabinet (marquee, reel window).
- **Cabinet indigo** (`cabinet-top` / `cabinet-mid` / `cabinet-deep`): the cabinet's vertical gradient. **Drawer indigo** (`drawer-top` / `drawer-deep`): the setlist drawer gradient.
- **Starlight Ink** (`ink`) and **Lilac Ink** (`ink-2`): primary and secondary text on night.
- **Paper Ink** (`paper-ink`) and **Paper Ink 2** (`paper-ink-2`): titles and body text on paper; `paper-ink` is also the ticket button fill.
- **Reel face** (`reel-face`) and **pass face** (`pass-face`): the near-white faces of reels and gift passes.
- **Quiet crowd** (`quiet-crowd`): the single pale tint the stadium dots take in quiet mode.

### Named Rules
**The Gold Is The Jackpot Rule.** Metallic gold and gold gradients appear only in the jackpot and its finale. Everywhere else the warm color is flat sunflower. If a non-jackpot surface needs warmth, it uses `sun`.

**The Light Not Hearts Rule.** Color on the night comes from wristband light (dots, bulbs, marquee, glows), not from pink fills or floating hearts. Hearts exist only as one of the reel symbols.

**The Band Follows The Ticket Rule.** The current song's band color drives the panda's wristband and glow (`--band`), the crowd wave, and the ticket stock is that band's paper tint.

## Typography

**Display Font:** Grandstander (with Arial Rounded MT Bold, ui-rounded, system-ui)
**Body Font:** M PLUS Rounded 1c (with ui-rounded, system-ui, -apple-system, Segoe UI)
**Label/Mono Font:** Doto (with ui-monospace, SFMono-Regular, Menlo)

**Character:** Grandstander is fan-sign lettering, the voice of song titles, buttons and signatures. M PLUS Rounded 1c is the letter itself: soft, highly legible on a phone. Doto is the machine: LED dot-matrix for the marquee, counter, ticket print, and the JACKPOT mark.

### Hierarchy
- **Display** (Doto 900, clamp(46px, 15vw, 84px), 0.9): the jackpot mark on the finale, in gold.
- **Headline** (Grandstander 900, clamp(31px, 8.8vw, 42px), 1.0, -0.01em): ticket song titles; the finale birthday line uses the same face at clamp(29px, 8.4vw, 58px).
- **Title** (Grandstander 800 to 900, 19 to 27px): drawer heading (27px), setlist song names (19px), gift pass titles (22px), signatures (21 to 22px).
- **Action** (Grandstander 900, 22px): the pull button; ticket and gift buttons use 800 to 900 at 19 to 20px.
- **Body** (M PLUS Rounded 1c 500, 18.5px, 1.6, max 62ch): letter fragments on tickets. Finale and closing text use 18px. Supporting text (body-sm) runs 13.5 to 15.5px.
- **Label / Print** (Doto 900, 12.5px, 0.07em, uppercase): ticket stub print. The counter (17px, 0.04em), marquee (20px, 0.06em), slot label and lanyards (10 to 12px, 0.2em+) are the same voice at other sizes.

### Named Rules
**The Machine Speaks Doto Rule.** Doto is used only for things the machine prints or lights: marquee, counter, stub, slot label, lanyard, pass header, jackpot mark. Never for the letter or for buttons.

**The Letter Stays Readable Rule.** Letter text is never below 18px on paper, never Doto, never uppercase.

## Layout

A single centered column, max 460px, 16px side gutters, padded by safe-area insets top and bottom. The stage is a vertical flex: top bar (48px min, counter left, round icon buttons right), constellation progress at top center (clamp(64px, 15dvh, 150px), hidden below 620px of height), the cabinet anchored low, and the full-width pull button (max 360px) in the thumb zone.

The cabinet width is fluid: `min(100vw - 84px, 330px, 44dvh)`; reel width, cell height and window height all derive from it, so the machine scales with the shorter of width and height. The cabinet is offset 40px left to make room for the lever on its right edge, and leaves half its width above it for the panda.

Readable content arrives in bottom sheets (ticket sheet up to 470px wide; setlist drawer up to 88dvh). The finale is a full-screen scroll layer (max 820px) with a horizontal snap carousel of gift passes on phones that becomes a centered row at 760px and up.

## Elevation & Depth

Depth is soft and physical: objects in the night cast long, diffuse, downward shadows; recessed parts of the machine use inset shadows; light sources glow. There are no hard offset shadows.

### Shadow Vocabulary
- **Cabinet body** (`inset 0 2px 0 rgba(255,255,255,.24), inset 0 -12px 24px rgba(5,2,30,.5), 0 30px 56px -14px rgba(3,1,18,.8)`): top highlight, bottom weight, long cast shadow.
- **Recessed well** (`inset 0 3px 9px rgba(0,0,0,.75)`): reel window, marquee, slot mouth.
- **Raised button** (`0 14px 26px -12px rgba(0,0,0,.65), inset 0 1px 0 rgba(255,255,255,.6)`): pull and gift-confirm buttons.
- **Floating paper** (`drop-shadow(0 24px 30px rgba(3,1,20,.62))`): the ticket sheet, as a filter so the perforation cutouts cast correctly.
- **Gift pass** (`0 18px 32px -14px rgba(0,0,0,.7)`); chosen pass adds a 3px gold ring and warm glow.
- **LED glow**: blur or drop-shadow in the light's own color (panda wristband, lit constellation stars).

### Named Rules
**The Glow Is Light Rule.** Glows are always in the emitting color and only on things that emit light (wristbands, bulbs, stars). Paper and buttons get shadows, never glows.

## Shapes

Everything is rounded and toy-like. Pills (999px) for every button and badge; circles for icon buttons, bulbs, dots and stars; a generous 32px top / 24px bottom radius on the cabinet; 26px top corners on the drawer; 22px on tickets; 18px on the reel window and passes; 11px on reels and marquee.

The ticket is the signature silhouette: a rounded rectangle with two semicircular perforation notches (11px radius) cut by mask at the stub line, a 2px dashed tear line, and a fine paper-grain overlay at 22% multiply. When the stub is torn the mask is removed. Gift passes hang from a colored lanyard and a metal clip, with a punched slot in the colored header.

## Components

### Buttons
- **Pull (primary):** solid sunflower pill, 62px tall, full width to 360px, Grandstander 900 22px in sunflower ink, lever icon left. Press: translateY(2px) scale(.985). Disabled while spinning: 50% opacity, desaturated. In jackpot it becomes the gold gradient.
- **Ticket button:** paper-ink pill on the paper, 56px, text in the paper's own color; fades up after the letter has typed in (delay scales with word count).
- **Gift confirm:** gold gradient pill, 60px min, sticky at the bottom of the finale; disabled state is a muted indigo (`#4A3E86`) with lilac text, not a faded gold.
- **Icon buttons:** 44px circles, 7% white fill, 18% white hairline, 21px SVG icon; hover 14% fill; press scale(.94). A pink pill badge counts unread tickets and pops on change.
- **Text links:** underlined Lilac Ink, 4px offset, brighten to Starlight Ink on hover.
- **Focus:** 3px cyan outline, 3px offset, everywhere; on sunflower it switches to white, on paper to paper ink.

### Slot Cabinet (signature)
Indigo gradient body with an LED-bulb rim cycling the six wristband colors in a chase; a recessed Doto marquee; three near-white reels behind a soft top/bottom indigo vignette; a sunflower payline with arrow tips; a slot mouth with the Doto label "BOLETAS". The lever sits on the right edge: chrome base and rod, sunflower knob, draggable (fires past 84% travel), with a nudging hint until first use.

### Ticket (signature)
Bottom sheet of tinted paper. Grandstander title, M PLUS letter text that resolves word by word from blur, a right-aligned signature, a sunflower mark bleeding off the top-right corner, and the perforated stub printed in Doto ("CANCIÓN 03 DE 08 / FILA 1 · ...") with the three-symbol reel combo. The entry ticket adds a six-color LED dot strip at the top and a Spotify play row.

### Setlist Drawer
Indigo gradient sheet with 26px top corners; songs as rows with a Doto number in the band color, Grandstander title and one-line M PLUS preview; dashed dividers; unplayed songs are dimmed and set in body type.

### Gift Pass
Concert lanyard pass: colored lanyard with Doto print, metal clip, white card with colored header and punched hole, illustration, Grandstander title, body description, and a radio-style pick indicator that fills with paper ink and a gold dot when chosen. After sending, a rotated pink rubber stamp lands on the card.

### Panda and Sunflower
Inline SVG illustration language: rounded panda (black and white with pink cheeks), sunflower with orange-shaded petals and a seed-brown disk, plus star, heart and planet reel symbols in the wristband palette. All icons are inline SVG symbols, never emoji or icon fonts. The panda idles (head sway, blinks), looks down while spinning, lowers its head in quiet mode, and cheers in jackpot.

### Motion grammar
- **Easing:** `cubic-bezier(.16,1,.3,1)` is the house ease-out; lever return and pops use a back-overshoot.
- **Pull:** lever snaps down in 170ms (ease-in), returns over 700ms with overshoot; the cabinet thuds 3px.
- **Weighted reel stops:** staggered stops (1000 / 1400 / 1850ms; jackpot 1150 / 1700 / 3400ms), each overshooting by up to 17% of a cell then settling, with motion blur during the fast phase.
- **Crowd wave:** a radial color wave through the stadium dots in the ticket's band color (74% band, rest crowd colors); bulbs chase faster while spinning.
- **Ticket print-and-fly:** the ticket grows out of the slot mouth (720ms), and on save the stub tears and falls while the ticket drops and flies to the setlist badge.
- **Quiet mode:** the crowd fades and turns a single pale lilac, the wave is soft (20% band), bulbs slow to 4s at low opacity, the marquee reads "ESTA LÉELA DESPACIO", the panda lowers its head, and the paper is the near-white lilac stock.
- **Jackpot:** everything goes gold (bulbs, marquee, payline flash, window ring, three gold crowd waves), the constellation blooms sunflower petals, and paper confetti with stars and butterflies falls.
- **Reduced motion:** all CSS animation and transition durations collapse to near zero; canvas loops do not run (sky renders single static frames, including the wave and quiet states); confetti is skipped; reels land instantly; tickets appear without print or fly; the letter text appears at once and the ticket button is visible immediately; waits shorten to 80ms max.

## Do's and Don'ts

### Do:
- **Do** keep the ground the fixed four-stop night gradient (`night-0` to `night-3`) and put color on it as light.
- **Do** use flat `sun` for the primary action and warm accents outside the jackpot.
- **Do** give every new song or ticket a band color from the wristband set and a paper stock that is a light tint of it.
- **Do** print machine text (counts, stubs, labels, marquee) in Doto 900 uppercase; set the letter in M PLUS Rounded 1c at 18px or more.
- **Do** draw panda, sunflower and symbols as inline SVG in the established rounded style.
- **Do** send hard fragments through quiet mode: pale stock, dim crowd, slow bulbs, lowered panda.
- **Do** keep every animation optional: under reduced motion, show the end state with all content.
- **Do** keep tap targets at 44px or larger and the primary action in the thumb zone.

### Don't:
- **Don't** use gold, gold gradients or a gold ring outside the jackpot and finale.
- **Don't** fill surfaces with pink or scatter hearts as decoration; hearts are a reel symbol only.
- **Don't** use emoji, icon fonts or stock icon sets for symbols.
- **Don't** set the letter text in Doto or in uppercase.
- **Don't** use hard offset shadows; shadows are long, soft and downward.
- **Don't** glow paper or buttons; glow is reserved for light sources.
- **Don't** reproduce song lyrics or band logos; songs appear as setlist titles only.

## Open Items

- **Font delivery: resolved 2026-11-04.** The user approved embedding. The latin subsets of Doto 900, Grandstander 800–900 (one variable file) and M PLUS Rounded 1c 500/700/800 are inlined as base64 woff2 `@font-face` rules (OFL fonts from Google Fonts). The page makes no font requests and keeps its type offline. Any new weight must be added to that inline block, not loaded from a host.
