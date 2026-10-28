# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 360
- **Latest game:** 0360 — Labyrinth Ledger
- **Current volume:** 004 (Games 0301 to 0400)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (100, complete) | [catalogs/readme-002.md](./catalogs/readme-002.md) |
| 003 | 0201–0300 (100, complete) | [catalogs/readme-003.md](./catalogs/readme-003.md) |
| 004 | 0301–0400 (60 so far) | [catalogs/readme-004.md](./catalogs/readme-004.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 036

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0351 | Glacier Glider | Arcade / Ice Sliding | [Play](./games/game-0351.html) |
| 0352 | Hex Haven | Puzzle / Hex Matching | [Play](./games/game-0352.html) |
| 0353 | Bazaar Baron | Strategy / Market Trading | [Play](./games/game-0353.html) |
| 0354 | Drumline Dash | Rhythm / Drum Timing | [Play](./games/game-0354.html) |
| 0355 | Volcano Voyager | Arcade / Lava Platforming | [Play](./games/game-0355.html) |
| 0356 | Cipher Citadel | Puzzle / Word Cipher | [Play](./games/game-0356.html) |
| 0357 | Railway Regent | Strategy / Train Scheduling | [Play](./games/game-0357.html) |
| 0358 | Waltz Waves | Rhythm / Waltz Timing | [Play](./games/game-0358.html) |
| 0359 | Orchard Outlaw | Arcade / Fruit Catching | [Play](./games/game-0359.html) |
| 0360 | Labyrinth Ledger | Puzzle / Maze Path Planning | [Play](./games/game-0360.html) |


## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
