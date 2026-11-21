# Homeric Epistles — Burning Letters

An interactive, single-file WebGL paper-burning letter experience inspired by classical Homeric poetry and tactile handmade cotton stationery.

Click or drag anywhere across the page with the wooden matchstick cursor to ignite the paper and watch a slow, irregular smoldering fire with curling wisps of smoke consume each epistle to reveal the next passage beneath.

## Highlights

- **Slow, Irregular GPU Smoldering Simulation**: A 16-bit packed WebGL ping-pong reaction-diffusion simulation paired with a procedural dry-vein & paper-knot permeability map, creating organic fractal burn fronts and trapped unburned paper islands.
- **Watercolor Flames & Realistic Curling Smoke**: Dedicated fine-step upward flame tongues (unique alchemical hue per passage) and tall S-curved translucent smoke ribbons layered with subtle volumetric smoke puffs, charred ash flakes, and ember rings.
- **Five Homeric Passages**:
  1. *The Odyssey, Book I* — Olive Emerald Flame
  2. *The Iliad, Book VI* — Rosy Dawn Flame
  3. *The Odyssey, Book V* — Wine-Dark Violet Flame
  4. *The Iliad, Book XVIII* — Hephaestus Gold Flame
  5. *The Odyssey, Book XIII* — Aegean Mist Flame
- **Free Open-Source Literary Typography (SIL OFL)**: Set in `La Belle Aurore`, `EB Garamond`, `Cormorant Garamond`, and `IBM Plex Mono`.
- **Custom Matchstick Cursor & Procedural Web Audio**: Minimal wooden matchstick cursor with strike flame and synthesized match-strike & paper-crackle soundscape (toggleable via `( SOUND ON )`).

## Usage

Open `index.html` directly in any modern WebGL-enabled browser, or serve it locally:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.
