# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 40
- **Latest game:** 0040 — War Council
- **Current volume:** 001 (Games 0001 to 0100)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0040 (40 so far, up to 0100) | [catalogs/readme-001.md](./catalogs/readme-001.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 004

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0031 | Avalanche Ascent | Arcade / Vertical Climber | [Play](./games/game-0031.html) |
| 0032 | Cipher Lock | Puzzle / Code Breaking | [Play](./games/game-0032.html) |
| 0033 | Rail Baron | Strategy / Train Routing | [Play](./games/game-0033.html) |
| 0034 | Tempo Tower | Rhythm / Beat Stacking | [Play](./games/game-0034.html) |
| 0035 | Meteor Miner | Arcade / Asteroid Mining | [Play](./games/game-0035.html) |
| 0036 | Tile Turner | Puzzle / Flip Tiles | [Play](./games/game-0036.html) |
| 0037 | Bakery Rush | Simulation / Bakery Management | [Play](./games/game-0037.html) |
| 0038 | Shadow Shot | Precision / Ricochet Archery | [Play](./games/game-0038.html) |
| 0039 | Vine Vault | Arcade / Grapple Swing | [Play](./games/game-0039.html) |
| 0040 | War Council | Strategy / Turn-Based Tactics | [Play](./games/game-0040.html) |

## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
