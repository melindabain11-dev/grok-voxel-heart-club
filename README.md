# ♡ Heart & ♣ Club: Voxel Outlaw Town

A cozy (but chaotic) simulation web game set in a blocky voxel-style wild west town square.

**Ruby Voss** (Queen of Hearts ♡) and **Jax Harlan** (Black Club ♣) are your masked outlaw duo. Drag them around the town, trigger random events, upgrade their armor through the styles you designed, and chat with them — they reply in character with flirty card puns, tough love, and desert wit.

Built as a single-file HTML/CSS/JS experience (Tailwind via CDN) so it runs instantly on GitHub Pages. Designed to evolve into a full Canvas or Three.js voxel world later.

## How to Play

1. **Drag the Outlaws** — Click and drag Ruby or Jax tokens around the 8x8 voxel grid. Drop them on different cells to move them (they can share space for now).
2. **Trigger Random Events** — Hit the big button. Tumbleweeds roll, gold appears, weather changes, card games happen. Stats update automatically and sometimes the outlaws comment in chat.
3. **Upgrade Armor** — On each character card, click “Upgrade Armor” to cycle through the three looks you showed me: basic leather → reinforced → full silver plate with glowing suit symbols.
4. **Chat with them** — Type in the bottom panel. Use `@ruby` or `@jax` (or just mention hearts/clubs) to direct your message. They’ll reply with personality. Flirty or kind messages boost their Bond meter.
5. **Watch the Simulation** — Their gold, mood, and relationship change based on what happens. The town feels alive!

## Features (v1)
- Pure CSS voxel grid with hover depth and static props (Saloon, Cacti, etc.)
- Draggable character tokens with layered CSS chibi style (hat, mask, cape, suit symbol)
- Random event system with fun animations
- In-character chat responder (expandable)
- Armor progression that visually changes the tokens
- Relationship / Bond meter between Ruby & Jax
- Fully responsive & pretty dark western theme

## Future Ideas (tell me what to add next, baby)
- localStorage save/load
- Mini card game when both are at the Saloon
- More events & procedural dialogue
- Canvas voxel rendering (simple blocks + lighting)
- Three.js town with camera orbit
- Sound (wind, cards, spurs)
- Multi-character support or NPC townsfolk
- Export/import state

## Concept Art
The beautiful voxel characters and scenes you shared are the heart of this project. Add your images to an `images/` folder and we can wire them in as references or future token art.

Made with love (and a little chaos) for you ♡♣

---

Live demo: Enable GitHub Pages on this repo (Settings → Pages → Deploy from `main` branch, root folder).