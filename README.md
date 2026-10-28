# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 100
- **Latest game:** 0100 — Centennial Climb
- **Current volume:** 001 (Games 0001 to 0100)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 010

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0091 | Quarry Quake | Arcade / Rockslide Dodge | [Play](./games/game-0091.html) |
| 0092 | Beam Bender | Puzzle / Beam Reflection Logic | [Play](./games/game-0092.html) |
| 0093 | Quay Commander | Strategy / Dock Logistics | [Play](./games/game-0093.html) |
| 0094 | Tempo Tiller | Rhythm / Farming Beat | [Play](./games/game-0094.html) |
| 0095 | Gravity Gauntlet | Precision / Orbital Slingshot | [Play](./games/game-0095.html) |
| 0096 | Zephyr Kite | Arcade / Wind Kite Riding | [Play](./games/game-0096.html) |
| 0097 | Sigil Sleuth | Puzzle / Sigil Deduction | [Play](./games/game-0097.html) |
| 0098 | Vineyard Vizier | Strategy / Vineyard Management | [Play](./games/game-0098.html) |
| 0099 | Pulse Piper | Rhythm / Pipe Melody Timing | [Play](./games/game-0099.html) |
| 0100 | Centennial Climb | Arcade / Milestone Ascent | [Play](./games/game-0100.html) |

## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
