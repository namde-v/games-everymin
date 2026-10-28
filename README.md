# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 310
- **Latest game:** 0310 — Storm Shepherd
- **Current volume:** 004 (Games 0301 to 0400)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (100, complete) | [catalogs/readme-002.md](./catalogs/readme-002.md) |
| 003 | 0201–0300 (100, complete) | [catalogs/readme-003.md](./catalogs/readme-003.md) |
| 004 | 0301–0400 (10 so far) | [catalogs/readme-004.md](./catalogs/readme-004.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 031

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0301 | Coral Courier | Arcade / Underwater Delivery | [Play](./games/game-0301.html) |
| 0302 | Hex Harvest | Puzzle / Hex Tile Matching | [Play](./games/game-0302.html) |
| 0303 | Glacier Governor | Strategy / Ice Colony Management | [Play](./games/game-0303.html) |
| 0304 | Tempo Tinkerer | Rhythm / Beat Crafting | [Play](./games/game-0304.html) |
| 0305 | Comet Catcher | Precision / Orbital Catch | [Play](./games/game-0305.html) |
| 0306 | Vine Vault | Puzzle / Vine Untangling | [Play](./games/game-0306.html) |
| 0307 | Bazaar Baron | Strategy / Market Trading | [Play](./games/game-0307.html) |
| 0308 | Echo Explorer | Arcade / Sonar Exploration | [Play](./games/game-0308.html) |
| 0309 | Orbit Organizer | Puzzle / Satellite Sorting | [Play](./games/game-0309.html) |
| 0310 | Storm Shepherd | Precision / Wind Herding | [Play](./games/game-0310.html) |


## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
