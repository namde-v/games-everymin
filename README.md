# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 90
- **Latest game:** 0090 — Castle Cartographer
- **Current volume:** 001 (Games 0001 to 0100)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0090 (90 so far, up to 0100) | [catalogs/readme-001.md](./catalogs/readme-001.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 009

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0081 | Ashen Aviator | Arcade / Smoke-Ring Flight | [Play](./games/game-0081.html) |
| 0082 | Sundial Sleuth | Puzzle / Shadow Deduction | [Play](./games/game-0082.html) |
| 0083 | Hive Herald | Strategy / Bee Colony Routing | [Play](./games/game-0083.html) |
| 0084 | Cymbal Storm | Rhythm / Percussion Timing | [Play](./games/game-0084.html) |
| 0085 | Anchor Aim | Precision / Anchor Toss | [Play](./games/game-0085.html) |
| 0086 | Tidepool Tumble | Arcade / Crab Pearl Catch | [Play](./games/game-0086.html) |
| 0087 | Span Solver | Puzzle / Bridge Logic | [Play](./games/game-0087.html) |
| 0088 | Windmill Warden | Simulation / Wind Farm Management | [Play](./games/game-0088.html) |
| 0089 | Frost Flute | Rhythm / Melody Memory | [Play](./games/game-0089.html) |
| 0090 | Castle Cartographer | Strategy / Map Expansion | [Play](./games/game-0090.html) |

## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
