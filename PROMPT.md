# KidMash – Prototype Prompt

## Project Overview
Build a single-file browser-based app (`index.html`) called **KidMash** for toddlers and young kids who want to "work" next to their parents. The experience is simple: smash keys, see joy.

---

## Core Behavior

- **Black background**, full-screen, no UI chrome or distractions.
- When the user presses **any letter (A–Z) or number (0–9) key**, a **fun emoji** appears on screen at a random position.
- Each emoji should **animate in a delightful way** — choose from a mix of animations such as:
  - Bouncing in from a random direction
  - Spinning and growing
  - Floating upward and fading out
  - Wobbling/jiggling in place before fading
  - Popping (scale punch effect)
- Emojis should **disappear after a short time** (2–4 seconds) so the screen doesn't get cluttered.
- Use a **large, silly font** — load a playful Google Font like `Boogaloo`, `Fredoka One`, or `Baloo 2`.
- Display the **pressed key character** as large text (in addition to or beneath the emoji) for a moment, or skip it — your call, lean toward what looks most fun.

---

## Emoji Set
Use a diverse, cheerful set of emojis covering:
- Animals: 🐶 🐱 🦊 🐸 🐧 🦋 🐙 🦄 🐢 🦖
- Food: 🍕 🍦 🍩 🍉 🍓 🌮 🧁 🍔
- Fun objects: 🎈 🎉 ⭐ 🌈 🎸 🚀 🎊 🔥 💥 🌟
- Silly faces: 😂 🤪 😜 🥳 😎 🤩 🥸

Randomly pick one (or two!) emoji per keypress.

---

## Sound Mode

- Include a **sound toggle button** — a small, friendly speaker icon (🔊 / 🔇) pinned to a corner of the screen.
- When sound is **on**, each keypress plays a **short, fun sound**:
  - Use the **Web Audio API** to generate synthesized sounds (no external audio files needed).
  - Each keypress should play a random cheerful tone — vary pitch, use a short envelope (attack + decay), maybe add a slight vibrato or wobble.
  - Optionally, map different key groups (vowels, consonants, numbers) to slightly different timbres or pitches for variety.
- Sound is **off by default** to avoid surprising parents.

---

## Technical Requirements

- **Single `index.html` file** — all CSS and JS inline, no build tools, no dependencies except a Google Fonts import.
- Works in modern browsers (Chrome, Safari, Firefox).
- Mobile-friendly touch support is a bonus but not required.
- No frameworks — vanilla HTML/CSS/JS only.
- Keep it simple and fast. This will be opened directly in a browser.

---

## Vibe / Design Direction

- Fun, chaotic, colorful — like a digital toy box exploded.
- Emojis should feel **alive**: bouncy, wiggly, expressive.
- The experience should reward every single keypress with immediate visual delight.
- No scores, no goals, no failure states — just pure sensory fun.

---

## Deliverable

A single `index.html` file ready to open in a browser. No other files needed.
