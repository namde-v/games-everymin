# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 450
- **Latest game:** 0450 — Onyx Oracle
- **Current volume:** 005 (Games 0401 to 0500)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (100, complete) | [catalogs/readme-002.md](./catalogs/readme-002.md) |
| 003 | 0201–0300 (100, complete) | [catalogs/readme-003.md](./catalogs/readme-003.md) |
| 004 | 0301–0400 (100, complete) | [catalogs/readme-004.md](./catalogs/readme-004.md) |
| 005 | 0401–0500 (50 so far) | [catalogs/readme-005.md](./catalogs/readme-005.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 045

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0441 | Ember Engineer | Strategy / Furnace Logistics Simulation | [Play](./games/game-0441.html) |
| 0442 | Frost Falcon | Arcade / Dive-Bomb Fishing | [Play](./games/game-0442.html) |
| 0443 | Glade Gardener | Puzzle / Pollination Tile Rotation | [Play](./games/game-0443.html) |
| 0444 | Harbor Herald | Rhythm / Signal Drum Timing | [Play](./games/game-0444.html) |
| 0445 | Iron Inkmaster | Puzzle / Glyph Tracing Precision | [Play](./games/game-0445.html) |
| 0446 | Juniper Jumper | Action / Vine Bounce Platformer | [Play](./games/game-0446.html) |
| 0447 | Lantern Lurker | Strategy / Stealth Light Maze | [Play](./games/game-0447.html) |
| 0448 | Marble Miner | Arcade / Rolling Marble Physics | [Play](./games/game-0448.html) |
| 0449 | Nova Nomad | Strategy / Space Trade Route Planning | [Play](./games/game-0449.html) |
| 0450 | Onyx Oracle | Puzzle / Rune Deduction Logic | [Play](./games/game-0450.html) |

## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
