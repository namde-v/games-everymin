# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 490
- **Latest game:** 0490 — Jetstream Juggler
- **Current volume:** 005 (Games 0401 to 0500)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (100, complete) | [catalogs/readme-002.md](./catalogs/readme-002.md) |
| 003 | 0201–0300 (100, complete) | [catalogs/readme-003.md](./catalogs/readme-003.md) |
| 004 | 0301–0400 (100, complete) | [catalogs/readme-004.md](./catalogs/readme-004.md) |
| 005 | 0401–0500 (90 so far) | [catalogs/readme-005.md](./catalogs/readme-005.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 049

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0481 | Aurora Alchemist | Puzzle / Potion-Element Mixing | [Play](./games/game-0481.html) |
| 0482 | Basilisk Bounce | Arcade / Reflective Orb Pong | [Play](./games/game-0482.html) |
| 0483 | Cadence Courier | Rhythm / Delivery Beat Runner | [Play](./games/game-0483.html) |
| 0484 | Dune Diplomat | Strategy / Desert Alliance Negotiation | [Play](./games/game-0484.html) |
| 0485 | Eclipse Engineer | Puzzle / Shadow Alignment Puzzle | [Play](./games/game-0485.html) |
| 0486 | Falcon Flyer | Action / Aerial Dive Hunter | [Play](./games/game-0486.html) |
| 0487 | Glacier Gardener | Strategy / Ice Farm Simulation | [Play](./games/game-0487.html) |
| 0488 | Harmonic Harvester | Rhythm / Melody Crop Timing | [Play](./games/game-0488.html) |
| 0489 | Inkwell Investigator | Puzzle / Mystery Ink Deduction | [Play](./games/game-0489.html) |
| 0490 | Jetstream Juggler | Arcade / Wind Balloon Juggling | [Play](./games/game-0490.html) |

## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
