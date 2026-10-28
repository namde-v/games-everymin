# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 380
- **Latest game:** 0380 — Reef Ranger
- **Current volume:** 004 (Games 0301 to 0400)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (100, complete) | [catalogs/readme-002.md](./catalogs/readme-002.md) |
| 003 | 0201–0300 (100, complete) | [catalogs/readme-003.md](./catalogs/readme-003.md) |
| 004 | 0301–0400 (80 so far) | [catalogs/readme-004.md](./catalogs/readme-004.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 038

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0371 | Lantern Lifter | Arcade / Lantern Escort | [Play](./games/game-0371.html) |
| 0372 | Comet Cartographer | Puzzle / Constellation Tracing | [Play](./games/game-0372.html) |
| 0373 | Mycelium Mayor | Strategy / Fungal City | [Play](./games/game-0373.html) |
| 0374 | Cadence Climber | Rhythm / Beat Climbing | [Play](./games/game-0374.html) |
| 0375 | Frost Ferry | Arcade / Ice Ferry Delivery | [Play](./games/game-0375.html) |
| 0376 | Saffron Sleuth | Puzzle / Deduction | [Play](./games/game-0376.html) |
| 0377 | Foundry Flux | Strategy / Factory Routing | [Play](./games/game-0377.html) |
| 0378 | Echo Engineer | Rhythm / Pattern Repeat | [Play](./games/game-0378.html) |
| 0379 | Canopy Courier | Arcade / Zipline Delivery | [Play](./games/game-0379.html) |
| 0380 | Reef Ranger | Strategy / Reef Restoration | [Play](./games/game-0380.html) |


## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
