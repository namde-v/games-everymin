# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 510
- **Latest game:** 0510 — Pyro Plant Planner
- **Current volume:** 006 (Games 0501 to 0600) — in progress (10 of 100)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (100, complete) | [catalogs/readme-002.md](./catalogs/readme-002.md) |
| 003 | 0201–0300 (100, complete) | [catalogs/readme-003.md](./catalogs/readme-003.md) |
| 004 | 0301–0400 (100, complete) | [catalogs/readme-004.md](./catalogs/readme-004.md) |
| 005 | 0401–0500 (100, complete) | [catalogs/readme-005.md](./catalogs/readme-005.md) |
| 006 | 0501–0600 (10 so far) | [catalogs/readme-006.md](./catalogs/readme-006.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 051

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0501 | Vault Voyager | Arcade / Gravity Vault Runner | [Play](./games/game-0501.html) |
| 0502 | Whispering Willow | Puzzle / Botanical Pattern Logic | [Play](./games/game-0502.html) |
| 0503 | Xenon Xenolith | Strategy / Alien Crystal Colony Simulation | [Play](./games/game-0503.html) |
| 0504 | Yodel Yard | Rhythm / Alpine Echo Timing | [Play](./games/game-0504.html) |
| 0505 | Zenith Zookeeper | Strategy / Sky Zoo Management | [Play](./games/game-0505.html) |
| 0506 | Saffron Sorcerer | Puzzle / Potion Mixing Logic | [Play](./games/game-0506.html) |
| 0507 | Brine Breaker | Arcade / Tide Wave Dodger | [Play](./games/game-0507.html) |
| 0508 | Cobalt Cartographer | Puzzle / Map Tile Rotation | [Play](./games/game-0508.html) |
| 0509 | Mirage Drummer | Rhythm / Desert Drum Timing | [Play](./games/game-0509.html) |
| 0510 | Pyro Plant Planner | Strategy / Volcano Power Plant Simulation | [Play](./games/game-0510.html) |


## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
