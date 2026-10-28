# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 230
- **Latest game:** 0230 — Horseshoe Hero
- **Current volume:** 003 (Games 0201 to 0300)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (100, complete) | [catalogs/readme-002.md](./catalogs/readme-002.md) |
| 003 | 0201–0230 (30 so far, up to 0300) | [catalogs/readme-003.md](./catalogs/readme-003.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 023

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0221 | Tempest Trek | Arcade / Storm Runner | [Play](./games/game-0221.html) |
| 0222 | Mosaic Matrix | Puzzle / Tile Pattern Logic | [Play](./games/game-0222.html) |
| 0223 | Canyon Cartographer | Strategy / Map Expedition | [Play](./games/game-0223.html) |
| 0224 | Banjo Bonanza | Rhythm / Banjo Picking | [Play](./games/game-0224.html) |
| 0225 | Catapult Canyon | Precision / Catapult Launch | [Play](./games/game-0225.html) |
| 0226 | Firefly Frenzy | Arcade / Firefly Catch | [Play](./games/game-0226.html) |
| 0227 | Sundial Solver | Puzzle / Shadow Logic | [Play](./games/game-0227.html) |
| 0228 | Glacier Guild | Strategy / Expedition Management | [Play](./games/game-0228.html) |
| 0229 | Drumline Dash | Rhythm / Marching Beat | [Play](./games/game-0229.html) |
| 0230 | Horseshoe Hero | Precision / Horseshoe Toss | [Play](./games/game-0230.html) |


## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
