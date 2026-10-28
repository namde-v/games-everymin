# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 120
- **Latest game:** 0120 — Ricochet Range
- **Current volume:** 002 (Games 0101 to 0200)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (20 so far) | [catalogs/readme-002.md](./catalogs/readme-002.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 012

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0111 | Kelp Keeper | Arcade / Underwater Collector | [Play](./games/game-0111.html) |
| 0112 | Mirror Maze | Puzzle / Laser Reflection | [Play](./games/game-0112.html) |
| 0113 | Vineyard Vintner | Strategy / Harvest Management | [Play](./games/game-0113.html) |
| 0114 | Beat Bazaar | Rhythm / Percussion Market | [Play](./games/game-0114.html) |
| 0115 | Comet Catcher | Precision / Orbital Timing | [Play](./games/game-0115.html) |
| 0116 | Storm Surfer | Arcade / Wave Rider | [Play](./games/game-0116.html) |
| 0117 | Rune Riddle | Puzzle / Rune Sequence | [Play](./games/game-0117.html) |
| 0118 | Harbor Master | Strategy / Port Logistics | [Play](./games/game-0118.html) |
| 0119 | Echo Ensemble | Rhythm / Melody Memory | [Play](./games/game-0119.html) |
| 0120 | Ricochet Range | Precision / Bouncing Target Shot | [Play](./games/game-0120.html) |

## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
