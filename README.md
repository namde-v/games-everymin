# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 430
- **Latest game:** 0430 — Timber Trapper
- **Current volume:** 005 (Games 0401 to 0500)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (100, complete) | [catalogs/readme-002.md](./catalogs/readme-002.md) |
| 003 | 0201–0300 (100, complete) | [catalogs/readme-003.md](./catalogs/readme-003.md) |
| 004 | 0301–0400 (100, complete) | [catalogs/readme-004.md](./catalogs/readme-004.md) |
| 005 | 0401–0500 (30 so far) | [catalogs/readme-005.md](./catalogs/readme-005.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 043

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0421 | Kelp Captain | Strategy / Kelp Farm Simulation | [Play](./games/game-0421.html) |
| 0422 | Lightning Locksmith | Puzzle / Circuit Lock Picking | [Play](./games/game-0422.html) |
| 0423 | Comet Cutter | Arcade / Asteroid Mining Dash | [Play](./games/game-0423.html) |
| 0424 | Night Navigator | Puzzle / Constellation Pathfinding | [Play](./games/game-0424.html) |
| 0425 | Opal Outpost | Strategy / Supply Route Trading | [Play](./games/game-0425.html) |
| 0426 | Prism Piper | Rhythm / Melody Memory Sequence | [Play](./games/game-0426.html) |
| 0427 | Quarry Quester | Action / Digging Platformer | [Play](./games/game-0427.html) |
| 0428 | Rune Runner | Arcade / Word Rune Collector | [Play](./games/game-0428.html) |
| 0429 | Solar Shepherd | Strategy / Herding Simulation | [Play](./games/game-0429.html) |
| 0430 | Timber Trapper | Action / Trap Setting Defense | [Play](./games/game-0430.html) |

## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
