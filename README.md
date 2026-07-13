# Perihelion

A gravity-golf game. Slingshot a probe through gravity wells — stars that pull, anomalies that push, moons on timed orbits — and land it on the beacon in as few launches as you can.

**[Play it here](https://maait26.github.io/Perihelion/)**

## How to play

- **Drag anywhere** on screen, then release. Pull further for more power — the probe launches opposite the direction you drag, like a slingshot.
- Gold bodies pull the probe in. Violet bodies push it away.
- Reach the teal beacon in as few launches as possible. Par is the target to beat.

Three modes:
- **Campaign** — 26 hand-built sectors across three acts and four flight ratings (difficulty levels), earning stars as you go. Act I teaches static gravity, Act II adds orbiting bodies and timing, Act III brings in everything else — debris, pulsars, wormholes, and relays.
- **Puzzles** — 20 sectors built around a single mechanic each: wormholes, pulsars, debris, relays.
- **Deep Space** — endless, procedurally generated sectors. Each one is verified winnable before it's shown to you.

Campaign and Puzzle progress saves automatically in your browser as you play — close the tab anytime, and "Continue" will be waiting for you on the menu when you're back.

## Running it locally

It's a single self-contained HTML file with no dependencies — just open `perihelion_3.html` in a browser, or serve the folder with anything static (`python3 -m http.server`, etc).

## Tech

Vanilla HTML/CSS/JS, rendered on a `<canvas>`. No build step, no external libraries. Deep Space sectors are generated and brute-force verified as winnable client-side before being shown.
