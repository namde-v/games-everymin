# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 20
- **Latest game:** 0020 — Clockwork City
- **Current volume:** 001 (Games 0001 to 0100)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0020 (20 so far, up to 0100) | [catalogs/readme-001.md](./catalogs/readme-001.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 002

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0011 | Comet Courier | Arcade / Parcel Dash | [Play](./games/game-0011.html) |
| 0012 | Hex Vault | Puzzle / Circuit Logic | [Play](./games/game-0012.html) |
| 0013 | Harbor Master | Strategy / Port Logistics | [Play](./games/game-0013.html) |
| 0014 | Echo Drums | Rhythm / Pattern Memory | [Play](./games/game-0014.html) |
| 0015 | Abyss Angler | Arcade / Deep-Sea Catch | [Play](./games/game-0015.html) |
| 0016 | Glyph Grid | Puzzle / Symbol Deduction | [Play](./games/game-0016.html) |
| 0017 | Meadow Market | Simulation / Farm Trading | [Play](./games/game-0017.html) |
| 0018 | Pendulum Perch | Precision / Balance Swing | [Play](./games/game-0018.html) |
| 0019 | Storm Chaser | Arcade / Weather Dodge | [Play](./games/game-0019.html) |
| 0020 | Clockwork City | Strategy / Gear Builder | [Play](./games/game-0020.html) |

## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
