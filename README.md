# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 290
- **Latest game:** 0290 — Discus Dynamo
- **Current volume:** 003 (Games 0201 to 0300)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (100, complete) | [catalogs/readme-002.md](./catalogs/readme-002.md) |
| 003 | 0201–0290 (90 so far, up to 0300) | [catalogs/readme-003.md](./catalogs/readme-003.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 029

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0281 | Deepsea Dispatch | Arcade / Underwater Parcel Dash | [Play](./games/game-0281.html) |
| 0282 | Loom Logic | Puzzle / Weaving Pattern Logic | [Play](./games/game-0282.html) |
| 0283 | Grove Guardian | Strategy / Orchard Management | [Play](./games/game-0283.html) |
| 0284 | Cajon Cadence | Rhythm / Hand Drum Timing | [Play](./games/game-0284.html) |
| 0285 | Boomerang Bounce | Precision / Boomerang Throw | [Play](./games/game-0285.html) |
| 0286 | Skyline Swing | Arcade / Rooftop Grapple Swing | [Play](./games/game-0286.html) |
| 0287 | Pollen Path | Puzzle / Bee Pathfinding Logic | [Play](./games/game-0287.html) |
| 0288 | Subway Scheduler | Strategy / Transit Scheduling | [Play](./games/game-0288.html) |
| 0289 | Synth Samba | Rhythm / Synth Beat Timing | [Play](./games/game-0289.html) |
| 0290 | Discus Dynamo | Precision / Discus Throw | [Play](./games/game-0290.html) |


## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
