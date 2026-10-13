# Happy Birthday, Vismaya 🎂✨ (v20)

## Version 9 changes
- Newspaper masthead uses a clear bold serif (Playfair Display)
- Pop-ups, balloons and crackers (firework bursts) appear after the 3-2-1 countdown, keep coming for 10 seconds, then the scene stays still
- Falling wrappers (coloured paper pieces) drop from the top of the screen during those 10 seconds
- No diyas; the newspaper photo has a minimal frame
- "credits:" line is bigger with a highlighted name
- "Don't open" shows its pleading text after the first press
- Newspaper photo replaced; price line reads "Price: friendship"; newspaper kept minimal
- Cake page credit is larger and highlighted
- "TODAY IS YOUR DAY VISSU" pill text is larger
- Hero sub line "by neeru" uses a clearer font with neeru underlined

## Run locally
Open `index.html` in a browser. Internet is needed for the Google Fonts.

## Customize
- Pop-up emojis: `POP_EMOJI` in `index.html`
- Firework colours: `BURST_COLORS` in `index.html`
- Photo: `assets/vismaya-stage.jpg`

## Version 15 changes
- Share preview uses assets/share-card.jpg (not the newspaper photo). Social apps read the full hosted address, so host the folder and check the link preview.
- Newspaper photo is hidden under a scratch layer. Scratch to reveal it.
- Masthead uses Cinzel Decorative.
- Music button is a small round button on phones.

## Version 16 changes
- Removed the "Tap for a birthday compliment" section.
- Masthead "The Vismaya Times" is now blackletter (UnifrakturMaguntia) and gets "printed" in once as the paper scrolls into view; the columns follow.
- Warmer, more colourful theme: rose, marigold, teal, sky and plum; paper bunting across the top.
- After the countdown the title rises in gently; the scene now pauses smoothly after 10s instead of snapping still.
- Slower, shorter scroll reveals with one easing curve everywhere. Visible keyboard focus added.

## Version 17 changes
- Masthead is now Playball, a clear and readable cursive.
- "Expert opinion" now reads: "Dear Vismaya, many happy returns of the day! Celebrate your birthday to the fullest."
- Mobile pass: smaller balloons, one-line top pill, fitted headline sizes, centred newspaper header, narrower photo so there is room to scroll past it, no stuck hover after a tap, 44px tap targets, and safe-area spacing for notched phones.
- Scratch-to-reveal needs 40% scratched (was 50%) so it is easier with a finger.

## Version 18 changes
- No fonts or existing text changed.
- Tap the hero balloons to pop them (they float back after a few seconds).
- Scratching the photo clear now ends with a red "Birthday girl" rubber stamp and a small thud.
- Cake: flames lean as you blow into the mic, a wisp of smoke rises after each candle goes out, each slice you eat shows a slip of paper (edit `SLICE_NOTES` in index.html), and confetti fires when the cake is finished.
- Small sounds (whoosh, bite, pop) and phone vibration. Sounds only play while the music is on.
- The browser tab title changes when she switches to another tab.

## Version 19 changes
- Pinch-zoom and double-tap zoom are locked, so the page never zooms in or out on phones and tablets.
- Works in portrait and landscape on phones, with safe-area spacing for notches. In landscape the intro, title page, newspaper and cake page re-arrange to fit short screens (cake on the left, controls on the right).
- Nothing scrolls sideways at any screen size; the "Don't open" button stays inside its box when the phone is rotated.
- Cake page: the "Blow with mic" option and all microphone code were removed. Only the "Blow candles manually" button remains; tap it to blow out the candles.
- Everything else (text, fonts, colours, effects, music) is unchanged.

## Version 20 changes
- Music removed completely: no song file, no audio player, no "Stop music" button, nothing plays after the cake page opens.
- Cake page: the "Blow candles manually" button is gone. A note says "Touch the candles to blow them".
- Touch (finger) or click (mouse) each candle: it wobbles, the flame leans and goes out, a wisp of smoke rises and a soft blow sound plays. Candles have a bigger invisible touch area so they are easy to hit on a phone.
- Once all four are out the 3-2-1 countdown starts, the cake is cut, and the candles disappear so only the slices are left to tap and eat.
- Small sounds (blow, bite, pop) now always play; they no longer depend on music.
