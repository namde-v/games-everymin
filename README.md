# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 160
- **Latest game:** 0160 — Tightrope Titan
- **Current volume:** 002 (Games 0101 to 0200)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (60 so far) | [catalogs/readme-002.md](./catalogs/readme-002.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 016

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0151 | Volcano Voyager | Arcade / Lava Flow Runner | [Play](./games/game-0151.html) |
| 0152 | Knot Keeper | Puzzle / Rope Untangling | [Play](./games/game-0152.html) |
| 0153 | Brewmaster Bay | Strategy / Tavern Management | [Play](./games/game-0153.html) |
| 0154 | Flamenco Fury | Rhythm / Clap Timing | [Play](./games/game-0154.html) |
| 0155 | Harpoon Harbor | Precision / Harpoon Fishing | [Play](./games/game-0155.html) |
| 0156 | Pogo Pioneer | Arcade / Pogo Platforming | [Play](./games/game-0156.html) |
| 0157 | Mosaic Maker | Puzzle / Tile Mosaic | [Play](./games/game-0157.html) |
| 0158 | Railroad Tycoonlet | Strategy / Train Network | [Play](./games/game-0158.html) |
| 0159 | Ukulele Uprising | Rhythm / Strum Timing | [Play](./games/game-0159.html) |
| 0160 | Tightrope Titan | Precision / Balance Walk | [Play](./games/game-0160.html) |

## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
