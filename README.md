# Outlaw Studio

A browser-based music studio in a single HTML file. Write a beat style and lyrics, get a take — arrangements are synthesized live in your browser with a procedural Web Audio engine. No server, no account, no samples: the sound is generated from your words, in the page.

## What it does

- **Beat Style first** — a plain-language style box (plus preset chips) drives tempo, key, and arrangement; the words lead
- **Lyrics with structure tags** — verses, hooks, and sections, with Take A / Take B generation
- **Stem lanes** — up to 8 tracks with mute / solo / pan / gain, per-stem regeneration, and section add/extend
- **Reference analysis** — drop in an audio file to read its tempo and key
- **Exports** — WAV, MIDI, and JSON

## Run it

Download `index.html` and open it in any modern browser. It is fully self-contained — no network calls, no build step.

## Honest limits

This is a clean-room studio built from scratch: the *workflow* (style + lyrics → takes → stems → export) is the product. The in-browser engine is procedural synthesis, not a large AI music model — it will not sound like one, and this README won't pretend it does. Large-model backends are a possible future plug-in, not part of this build.

## About

Built by [Myhomiesxyt](https://github.com/Myhomiesxyt) for the Outlaw / A.C. Bales music workflow — the working studio behind the songs, published as a real, usable tool.

## License

All rights reserved for now. Use it, learn from it, don't resell it.
