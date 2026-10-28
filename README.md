# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 520
- **Latest game:** 0520 — Amber Archivist
- **Current volume:** 006 (Games 0501 to 0600) — in progress (20 of 100)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (100, complete) | [catalogs/readme-002.md](./catalogs/readme-002.md) |
| 003 | 0201–0300 (100, complete) | [catalogs/readme-003.md](./catalogs/readme-003.md) |
| 004 | 0301–0400 (100, complete) | [catalogs/readme-004.md](./catalogs/readme-004.md) |
| 005 | 0401–0500 (100, complete) | [catalogs/readme-005.md](./catalogs/readme-005.md) |
| 006 | 0501–0600 (20 so far) | [catalogs/readme-006.md](./catalogs/readme-006.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 052

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0511 | Quartz Quarry Dash | Arcade / Mine Cart Runner | [Play](./games/game-0511.html) |
| 0512 | Lunar Librarian | Puzzle / Moon Phase Sequence Logic | [Play](./games/game-0512.html) |
| 0513 | Tidal Turbine Tycoon | Strategy / Coastal Energy Management | [Play](./games/game-0513.html) |
| 0514 | Bongo Bazaar | Rhythm / Market Beat Timing | [Play](./games/game-0514.html) |
| 0515 | Falcon Ferry | Arcade / Wind Glider Delivery | [Play](./games/game-0515.html) |
| 0516 | Glyph Geyser | Puzzle / Water Glyph Flow Logic | [Play](./games/game-0516.html) |
| 0517 | Cactus Cantina | Strategy / Desert Tavern Management | [Play](./games/game-0517.html) |
| 0518 | Steelpan Serenade | Rhythm / Steel Drum Melody | [Play](./games/game-0518.html) |
| 0519 | Asteroid Angler | Precision / Star Fishing Aim | [Play](./games/game-0519.html) |
| 0520 | Amber Archivist | Puzzle / Fossil Sequence Deduction | [Play](./games/game-0520.html) |


## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
