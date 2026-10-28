# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 720
- **Latest game:** 0720 — Moonlit Kite Runner
- **Current volume:** 008 (Games 0701 to 0800) — in progress (20 of 100)
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
| 007 | 0601–0700 (100, complete) | [catalogs/readme-007.md](./catalogs/readme-007.md) |
| 008 | 0701–0800 (20, in progress) | [catalogs/readme-008.md](./catalogs/readme-008.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 072

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0711 | Aurora Ice Slide Dash | Arcade / Ice Slide Collection | [Play](./games/game-0711.html) |
| 0712 | Clockwork Gear Lock | Puzzle / Gear Rotation Logic | [Play](./games/game-0712.html) |
| 0713 | Desert Oasis Caravan | Strategy / Caravan Trade Routes | [Play](./games/game-0713.html) |
| 0714 | Tide Drum Circle | Rhythm / Drum Beat Timing | [Play](./games/game-0714.html) |
| 0715 | Harbor Lighthouse Beam Aim | Precision / Rotating Beam Targeting | [Play](./games/game-0715.html) |
| 0716 | Volcano Ember Dodger | Arcade / Falling Hazard Dodge | [Play](./games/game-0716.html) |
| 0717 | Mosaic Tile Weaver | Puzzle / Pattern Weaving | [Play](./games/game-0717.html) |
| 0718 | Mountain Observatory Scheduler | Strategy / Telescope Night Planning | [Play](./games/game-0718.html) |
| 0719 | Starlight Archery Range | Precision / Archery Wind Aim | [Play](./games/game-0719.html) |
| 0720 | Moonlit Kite Runner | Arcade / Wind Gust Runner | [Play](./games/game-0720.html) |
## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
