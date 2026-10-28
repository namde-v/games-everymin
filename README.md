# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 440
- **Latest game:** 0440 — Drift Diver
- **Current volume:** 005 (Games 0401 to 0500)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (100, complete) | [catalogs/readme-002.md](./catalogs/readme-002.md) |
| 003 | 0201–0300 (100, complete) | [catalogs/readme-003.md](./catalogs/readme-003.md) |
| 004 | 0301–0400 (100, complete) | [catalogs/readme-004.md](./catalogs/readme-004.md) |
| 005 | 0401–0500 (40 so far) | [catalogs/readme-005.md](./catalogs/readme-005.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 044

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0431 | Umbra Umbrella | Arcade / Rain Shield Defense | [Play](./games/game-0431.html) |
| 0432 | Velvet Voyager | Puzzle / Gravity Slingshot Orbit | [Play](./games/game-0432.html) |
| 0433 | Willow Warden | Strategy / Forest Tower Defense | [Play](./games/game-0433.html) |
| 0434 | Xenon Xylophone | Rhythm / Falling Note Precision | [Play](./games/game-0434.html) |
| 0435 | Yeti Yodeler | Action / Avalanche Echo Climber | [Play](./games/game-0435.html) |
| 0436 | Zephyr Zealot | Puzzle / Wind Maze Airflow | [Play](./games/game-0436.html) |
| 0437 | Atlas Acrobat | Action / Grappling Swing Platformer | [Play](./games/game-0437.html) |
| 0438 | Beacon Builder | Strategy / Lighthouse Signal Network | [Play](./games/game-0438.html) |
| 0439 | Cipher Courier | Puzzle / Code-Breaking Delivery | [Play](./games/game-0439.html) |
| 0440 | Drift Diver | Arcade / Deep-Sea Current Dodging | [Play](./games/game-0440.html) |

## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
