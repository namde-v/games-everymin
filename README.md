# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 390
- **Latest game:** 0390 — Marble Machinist
- **Current volume:** 004 (Games 0301 to 0400)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (100, complete) | [catalogs/readme-002.md](./catalogs/readme-002.md) |
| 003 | 0201–0300 (100, complete) | [catalogs/readme-003.md](./catalogs/readme-003.md) |
| 004 | 0301–0400 (90 so far) | [catalogs/readme-004.md](./catalogs/readme-004.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 039

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0381 | Juniper Juggler | Arcade / Ball Juggling Catch | [Play](./games/game-0381.html) |
| 0382 | Obsidian Oracle | Puzzle / Rune Prediction Logic | [Play](./games/game-0382.html) |
| 0383 | Willow Warden | Strategy / Forest Tower Defense | [Play](./games/game-0383.html) |
| 0384 | Tempo Trawler | Rhythm / Beat Fishing | [Play](./games/game-0384.html) |
| 0385 | Boulder Bard | Arcade / Downhill Boulder Roll | [Play](./games/game-0385.html) |
| 0386 | Moss Merchant | Strategy / Market Trading | [Play](./games/game-0386.html) |
| 0387 | Solar Sorter | Puzzle / Spectrum Sorting | [Play](./games/game-0387.html) |
| 0388 | Hollow Harvester | Arcade / Cave Harvesting | [Play](./games/game-0388.html) |
| 0389 | Zephyr Zookeeper | Strategy / Wind Aviary Management | [Play](./games/game-0389.html) |
| 0390 | Marble Machinist | Puzzle / Marble Machine Routing | [Play](./games/game-0390.html) |



## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
