# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 220
- **Latest game:** 0220 — Lasso Legend
- **Current volume:** 003 (Games 0201 to 0300)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (100, complete) | [catalogs/readme-002.md](./catalogs/readme-002.md) |
| 003 | 0201–0220 (20 so far, up to 0300) | [catalogs/readme-003.md](./catalogs/readme-003.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 022

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0211 | Glacier Glider | Arcade / Ice Gliding | [Play](./games/game-0211.html) |
| 0212 | Glyph Garden | Puzzle / Symbol Matching Logic | [Play](./games/game-0212.html) |
| 0213 | Observatory Overseer | Strategy / Telescope Scheduling | [Play](./games/game-0213.html) |
| 0214 | Cello Cadence | Rhythm / Bow Timing | [Play](./games/game-0214.html) |
| 0215 | Dart Dynamo | Precision / Dart Throwing | [Play](./games/game-0215.html) |
| 0216 | Kite Kraze | Arcade / Kite Flying | [Play](./games/game-0216.html) |
| 0217 | Prism Pathfinder | Puzzle / Light Prism Routing | [Play](./games/game-0217.html) |
| 0218 | Apiary Architect | Strategy / Beehive Management | [Play](./games/game-0218.html) |
| 0219 | Harmonica Highway | Rhythm / Harmonica Note Run | [Play](./games/game-0219.html) |
| 0220 | Lasso Legend | Precision / Lasso Roping | [Play](./games/game-0220.html) |


## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
