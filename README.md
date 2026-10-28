# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 530
- **Latest game:** 0530 — Kaleidoscope Keeper
- **Current volume:** 006 (Games 0501 to 0600) — in progress (30 of 100)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (100, complete) | [catalogs/readme-002.md](./catalogs/readme-002.md) |
| 003 | 0201–0300 (100, complete) | [catalogs/readme-003.md](./catalogs/readme-003.md) |
| 004 | 0301–0400 (100, complete) | [catalogs/readme-004.md](./catalogs/readme-004.md) |
| 005 | 0401–0500 (100, complete) | [catalogs/readme-005.md](./catalogs/readme-005.md) |
| 006 | 0501–0600 (30 so far) | [catalogs/readme-006.md](./catalogs/readme-006.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 053

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0521 | Avalanche Ace | Arcade / Snowboard Dodger | [Play](./games/game-0521.html) |
| 0522 | Circuit Sage | Puzzle / Wiring Logic | [Play](./games/game-0522.html) |
| 0523 | Lighthouse Luminary | Strategy / Lighthouse Keeper Simulation | [Play](./games/game-0523.html) |
| 0524 | Choir Conductor | Rhythm / Vocal Beat Conducting | [Play](./games/game-0524.html) |
| 0525 | Magnet Marauder | Arcade / Magnetic Maze Runner | [Play](./games/game-0525.html) |
| 0526 | Rune Reorder | Puzzle / Rune Sequence Logic | [Play](./games/game-0526.html) |
| 0527 | Hive Herald | Strategy / Beehive Management | [Play](./games/game-0527.html) |
| 0528 | Taproot Tango | Rhythm / Dance Step Timing | [Play](./games/game-0528.html) |
| 0529 | Comet Catcher | Precision / Orbital Slingshot Aim | [Play](./games/game-0529.html) |
| 0530 | Kaleidoscope Keeper | Puzzle / Mirror Reflection Logic | [Play](./games/game-0530.html) |


## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
