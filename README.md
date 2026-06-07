# SECTOR — Infinite Escape Rooms

A first-person, procedurally-generated **dystopian escape-room** game that runs entirely in the browser. No dependencies, no build step — one HTML file.

**▶ Play:** open `index.html`, or via GitHub Pages once enabled.

## The Loop
You wake locked in a decaying sector cell. Hidden somewhere is a **4-digit access code**. Find it, enter it at the door keypad, and descend to the next room — **forever**. Every room is a fresh procedural layout with its own random color palette, furniture, and hiding spot.

## How codes are hidden
- **Crawl** to look *underneath* beds, tables, and dressers
- **Climb the ladder** or **jump** to spot codes stashed *on top of* tall shelves, lockers, and fridges
- **Search** while standing to find codes hidden *inside* closets, lockers, and terminals

Wrong posture? The game hints ("there's a gap underneath — try crawling").

## Rooms are full of stuff
closets · lockers · shelves · refrigerators · dressers · beds · tables · crates · barrels · TVs · terminals · toilets · sinks · ladders — each drawn with its own grimy, procedurally-generated texture so no two rooms look alike.

## Controls
**Desktop** — `WASD` move · mouse look (click to lock) · `Space` jump · `C` crawl · `E` search · climb: stand on the ladder + `Space`

**Mobile** — left joystick to move, drag the right side to look, on-screen **JUMP / CRAWL / CLIMB / SEARCH** buttons (CLIMB appears at the ladder).

## Tech
Pure vanilla JavaScript + HTML5 Canvas. Custom raycaster engine with billboard sprites, vertical camera (jump/crawl/ladder), distance fog, a CRT scanline overlay, and per-room procedural texture generation. ~900 lines, zero libraries.

🤖 Built with [Claude Code](https://claude.com/claude-code)
