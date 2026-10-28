# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 680
- **Latest game:** 0680 — Mirror Labyrinth Reflector
- **Current volume:** 007 (Games 0601 to 0700) — in progress (80 of 100)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (100, complete) | [catalogs/readme-002.md](./catalogs/readme-002.md) |
| 003 | 0201–0300 (100, complete) | [catalogs/readme-003.md](./catalogs/readme-003.md) |
| 004 | 0301–0400 (100, complete) | [catalogs/readme-004.md](./catalogs/readme-004.md) |
| 005 | 0401–0500 (100, complete) | [catalogs/readme-005.md](./catalogs/readme-005.md) |
| 006 | 0501–0600 (100, complete) | [catalogs/readme-006.md](./catalogs/readme-006.md) |
| 007 | 0601–0700 (80, in progress) | [catalogs/readme-007.md](./catalogs/readme-007.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 068

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0671 | Desert Dune Buggy Jump | Arcade / Dune Buggy Jumping | [Play](./games/game-0671.html) |
| 0672 | Mosaic Tile Weaver | Puzzle / Pattern Weaving Logic | [Play](./games/game-0672.html) |
| 0673 | Observatory Night Scheduler | Strategy / Telescope Scheduling | [Play](./games/game-0673.html) |
| 0674 | Synthwave Beat Runner | Rhythm / Synth Tap Timing | [Play](./games/game-0674.html) |
| 0675 | Sky Kite Collector | Arcade / Kite Wind Collection | [Play](./games/game-0675.html) |
| 0676 | Herb Garden Potion Sort | Puzzle / Potion Sorting Logic | [Play](./games/game-0676.html) |
| 0677 | Lighthouse Keeper Roster | Strategy / Lighthouse Shift Management | [Play](./games/game-0677.html) |
| 0678 | Archery Wind Shot | Precision / Archery Wind Aim | [Play](./games/game-0678.html) |
| 0679 | Deep Sea Pearl Diver | Arcade / Underwater Treasure Diving | [Play](./games/game-0679.html) |
| 0680 | Mirror Labyrinth Reflector | Puzzle / Laser Mirror Logic | [Play](./games/game-0680.html) |
## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
