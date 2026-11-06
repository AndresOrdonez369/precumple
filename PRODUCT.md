# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Stack

Static single-file HTML (the user asked for "una página web .html"). Code, styles and fonts (base64 woff2) are inline in index.html; media sits beside it in fotos/ and musica/. The publicar/ folder is the upload copy (index.html + fotos/ + musica/) for a static host such as Netlify Drop.

## Users

One reader: Dayana Erazo, born on 13 November (the year is uncertain, 1997 or 1998, so never mention her age anywhere; only the date matters), nicknamed "Panda". Address her only as "Panda" or "Pandita", never "mi Panda" (user, 2026-11-04); the full greeting is "¡Feliz precumpleaños, Pandita Erazo!" (his "panditerazo"). She reads it on her phone, a few days before her birthday. She receives the page from her partner (sender signs as Andrés; inferred from the account, confirm before sending). She is the only audience; nobody else is meant to see it.

## Product Purpose

A pre-birthday gift ("regalo de precumpleaños"): a love letter delivered as a small slot-machine game. Each pull of the lever releases one of seven tickets of the letter, so the message arrives in pieces she chooses to open, at her pace, instead of as a wall of text. It ends in a jackpot where she picks a birthday gift.

Success: she plays it to the end, reads every fragment, feels loved and also understands what hurt him, and sends back her gift choice.

## Positioning

Not a generic birthday card. The letter carries two truths at once: unconditional love and an honest account of what has hurt. The game structure lets the hard part arrive in sequence, held between love at the start and love at the end.

## Operating Context

- Opened on a phone, portrait, probably from a WhatsApp link or file. One-hand use, thumb reach.
- Her birthday is 13 November, and the core framing is that her birthday is not one day but all of November ("tu cumpleaños es todo noviembre"). Countdown copy is computed from the date.
- Music is a playlist he prepared, part of the gift ("Escucha esta playlist que preparé para ti"; the entry ticket says "hay una playlist para los dos", and the cassette reads "Para los dos"). Do not call any song "nuestra canción" (user, 2026-11-04). 9 tracks in musica/: Coldplay's "A Sky Full of Stars" plus the 8 he supplied ("Siempre Seré" has no known artist yet), shuffled on every visit. It starts on her first tap (browsers block autoplay before a gesture), advances track by track, and the player offers previous/next/mute (iPhone: mute only). Never reproduce lyrics. Keep the link private: the page carries copyrighted songs and their photos.
- She loves sunflowers.

## Capabilities and Constraints

- Slot-machine mechanic is pinned by the user: press a button, reels spin, messages come out.
- Gift options at the end (confirmed 2026-11-04, in this order): "Collar secreto" (one necklace, for her, with a secret inside); romantic dinner (the one they have pending, at the place she likes, with sunflowers described by metaphor); weekend getaway together (he chooses the destination, a surprise); Amazon gift card.
- The finale shows the gift choice first; once chosen, it becomes a personalized invitation card (Para / De / Cuándo / Dónde / Incluye / Dress code: Tu sonrisa), followed by the "¡Feliz precumpleaños, Pandita Erazo!" celebration (wish candle, "Tu vida es un regalo", her qualities, the playlist, the 19-photo album, and his final message on lined paper with a sleeping panda).
- Her choice is sent to him through WhatsApp with a prefilled message ("Acepto tu invitación: …"). His number is set in the WHATSAPP_NUMBER constant (Colombia, +57).
- Language: Spanish (Colombian register, warm, informal "tú").

## Brand Commitments

- Sunflowers are required, and plenty of them (a meadow along the bottom, a garland, blooms from the gift).
- Pandas: she loves them (added by the user mid-brief). Kawaii baby pandas in the style of the reference he sent, in tender poses: walking, sitting (sentadito), lying on the belly with the chin on the paws and the feet kicking (acostadito), and sleeping (dormidito). They react when tapped (hearts, a happy wiggle, waking up).
- Coldplay, specifically "A Sky Full of Stars", is the musical thread; the A Head Full of Dreams flower of life lights one circle per ticket and blooms at the jackpot.
- The letter's content, from the user's own words:
  - He told her he wasn't feeling well and didn't want to do things at that moment, but he loves her.
  - The limits he has set are about what hurts him, so she understands; they are not to push her away.
  - She is important to him and will be for life; he doesn't want to lose her, even if he can't give exactly what she needs.
  - He understands her anxiety needs care.
  - What hurts most: feeling she doesn't fight for this love.
  - When he said things hurt, he didn't feel validated, and it made him feel bad. He doesn't like some of her behavior, and says so to be understood, not to set walls.
  - They live in a long, almost infinite cycle; he wants things to be different and for the same things not to happen again.
  - His love holds him up; he is still in love as always.
  - He understands if she no longer wants anything, but wanted her to know he loves her and wants to make her happy and give her something.
  - Her birthday is close; the goal is not to upset her but for her to be well and happy.
- Tone (confirmed 2026-11-04, final pass): not a request to get back together. It shows his love, wishes her happiness, says happy pre-birthday, and invites both to be well and at peace, loving each other despite everything. Hard truths stay honest in first person, without demands or reproach.
- Do not say she needs space literally. Say instead that he does all this without pressure and without expecting anything back, to celebrate her pre-birthday, because her birthday is the whole month, and "ya basta de tristezas".
- "Llevamos 8 años viviendo esta aventura": he wants no more sadness, only beautiful things, and to remember the beautiful better.
- Suki is her dog (photo in fotos/suki.webp, from the user on 2026-11-06). A surprise lucky-charm card, "¡Te envío una Suki de la suerte!", appears 3 times just to make her smile. It shows after ticket 2, after ticket 5 (right after the two hard tickets), and when she blows the wish candle; if she skips the wish, it shows when she reaches the final letter. It sits on a pink background of pandas and hearts. Each edition adds a sticker (four-leaf clover, sunflower at the ear, party hat) and counts "1 de 3" up to "3 de 3". Tapping Suki makes her "say" something and float hearts.
- The page ends with a postscript, "P. D.: Me guardé una sorpresa para tu día.", and a locked button: "Solo se abre el 13 de noviembre", with a countdown ("Faltan 7 días"). Tapping it only says "todavía no". What it opens is still to be defined by the user (added 2026-11-06), so for now it stays locked on every date and must be implemented before 13 November.
- It must be very clear that no matter what happens she is important to him, and that celebrating her life and seeing it as a gift always matters to him, whether he is angry or not. This is the finale's "Tu vida es un regalo" moment (a heart of sunflowers) and a line in ticket 2.
- Each ticket names one of her qualities he gave (inteligente, linda, trabajadora, leal, persistente, echada pa'lante, viajera; and "sigue a pesar de todo"), and photo captions say what he values ("Valoro…"). The finale gathers them under "Todo lo que eres" with her age.
- A birthday baby panda opens the page by walking in with a gift box that blooms into sunflowers, walks onto every ticket, and returns at the end with a heart balloon, a panda balloon and a cupcake for a wish-candle moment (no age numbers).

## Evidence on Hand

- 19 photos of the couple, provided by the user on 2026-11-04, in fotos/ (foto-01 to foto-19). Each ticket shows its own photos in panda-decorated polaroid frames; the finale shows all 19 as a pile she taps through. Photo 05 carries a green marker circle the user drew. Beyond "8 years together", no dates, places, or shared memories were provided: do not invent captions, anecdotes, or a trip destination.
- The letter text is the user's own dictated wording (7 tickets), organized and corrected for spelling. Keep his words; do not add sentiments he did not say.

## Product Principles

1. Her pace. She pulls the lever; nothing auto-advances past a fragment she hasn't read.
2. Love bookends honesty. Hard truths arrive in the middle, framed by love before and after.
3. His words, clarified, not rewritten. Organize and soften the grammar, keep the meaning.
4. It works on her phone the first time, offline-tolerant, no install.

## Accessibility & Inclusion

Readable text size on a phone, respects reduced-motion, works one-handed. Music starts on her first tap because he asked for it to play on its own; a visible control always mutes it.
