# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 150
- **Latest game:** 0150 — Zip Line Zephyr
- **Current volume:** 002 (Games 0101 to 0200)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (50 so far) | [catalogs/readme-002.md](./catalogs/readme-002.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 015

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0141 | Meteor Miner | Arcade / Asteroid Mining | [Play](./games/game-0141.html) |
| 0142 | Hex Harvest | Puzzle / Hex Tile Matching | [Play](./games/game-0142.html) |
| 0143 | Desert Depot | Strategy / Caravan Trading | [Play](./games/game-0143.html) |
| 0144 | Jazz Jamboree | Rhythm / Swing Beat | [Play](./games/game-0144.html) |
| 0145 | Lantern Lift | Precision / Balloon Altitude | [Play](./games/game-0145.html) |
| 0146 | Coral Courier | Arcade / Reef Delivery | [Play](./games/game-0146.html) |
| 0147 | Pattern Painter | Puzzle / Nonogram Logic | [Play](./games/game-0147.html) |
| 0148 | Apiary Architect | Strategy / Bee Colony | [Play](./games/game-0148.html) |
| 0149 | Metronome March | Rhythm / Marching Steps | [Play](./games/game-0149.html) |
| 0150 | Zip Line Zephyr | Precision / Zipline Timing | [Play](./games/game-0150.html) |

## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
