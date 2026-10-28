# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 610
- **Latest game:** 0610 — Avalanche Architect
- **Current volume:** 007 (Games 0601 to 0700) — in progress (10 of 100)
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
| 007 | 0601–0700 (10, in progress) | [catalogs/readme-007.md](./catalogs/readme-007.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 061

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0601 | Ember Forge | Arcade / Blacksmith Ember Forging | [Play](./games/game-0601.html) |
| 0602 | Coral Cipher | Puzzle / Underwater Code-Breaking | [Play](./games/game-0602.html) |
| 0603 | Vineyard Ventures | Strategy / Vineyard Management Simulation | [Play](./games/game-0603.html) |
| 0604 | Flamenco Footwork | Rhythm / Flamenco Dance Timing | [Play](./games/game-0604.html) |
| 0605 | Zephyr Balloon Race | Arcade / Hot-Air Balloon Racing | [Play](./games/game-0605.html) |
| 0606 | Clockwork Contraption | Puzzle / Gear Machine Logic | [Play](./games/game-0606.html) |
| 0607 | Desert Caravan Co. | Strategy / Desert Caravan Trading | [Play](./games/game-0607.html) |
| 0608 | Taiko Thunder Drums | Rhythm / Taiko Drum Timing | [Play](./games/game-0608.html) |
| 0609 | Lantern Lake Fishing | Arcade / Night Fishing Tension | [Play](./games/game-0609.html) |
| 0610 | Avalanche Architect | Precision / Avalanche Barrier Placement | [Play](./games/game-0610.html) |
## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
