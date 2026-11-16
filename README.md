# Mobile Piano

A piano and harmonium for your phone, tuned on an iPhone 16e. It runs in the browser and can be added to the Home Screen as an app that works offline.

**Play it:** https://raghuramprabhu.github.io/MobilePiano/

## What it does

- **Two stacked keyboards upright, one wide keyboard sideways.** Sideways starts at 2.6 octaves (C to G). The ⟳ button turns the page sideways even when iPhone rotation lock is on.
- **Key size − / +**: fewer, wider keys or more, narrower ones. Upright and sideways remember their own size.
- **Jump anywhere**: the thin strip at the top is the whole 88-key piano (A0 to C8). Tap or drag it to jump. Swipe sideways on the dark area above the keys to slide, or use ◀ ▶ for one white key at a time. The keyboard can start on any white key.
- **Black-key guard**: at black-key height only black keys play, so fast passages don't catch stray white notes. A near-miss beside a black key counts as the black key. You can change or turn this off in ⚙︎.
- **Sounds**: grand piano, e-piano, organ, strings, music box, a 2-reed harmonium, and a **3-reed harmonium** with stops: Bass (octave below), Male, Male 2 (tuned slightly sharp), Female (octave above) and Tremolo.
- **Record video with sound** of exactly what's on the stage. Share → Save Video puts a take in Photos.
- Sa Re Ga or C D E labels, sustain, reverb, chord names, live frequency readout, and Bluetooth typing-keyboard support.
- On iPhone, sound plays even with the silent switch on, and the screen stays awake while you play.

## Add to Home Screen (iPhone)

In Safari, tap **Share**, then **Add to Home Screen**, then **Add**. It then opens full-screen and works with no internet. ⚙︎ → Home Screen app has the steps with pictures.

## Files

| File | What it is |
|---|---|
| `index.html` | the page |
| `mobile.css`, `mobile.js` | phone layout, sheets, whole-piano strip, install, rotation |
| `piano.js`, `piano.css` | keyboard, touch handling, recorder (shared with the full studio) |
| `engine.js` | the sound engine: every sound is synthesised live with Web Audio, with no sample files |
| `sw.js`, `manifest.webmanifest`, `icons/` | Home Screen app and offline support |

Plain HTML, CSS and JavaScript, with no build step. The full desktop studio and the music lessons live in [DigitalMarketingLearning/piano](https://raghuramprabhu.github.io/DigitalMarketingLearning/piano/).
