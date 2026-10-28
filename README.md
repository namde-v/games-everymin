# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 130
- **Latest game:** 0130 — Pendulum Plunge
- **Current volume:** 002 (Games 0101 to 0200)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (30 so far) | [catalogs/readme-002.md](./catalogs/readme-002.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 013

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0121 | Tide Turner | Puzzle / Tidal Flow Routing | [Play](./games/game-0121.html) |
| 0122 | Forge Frenzy | Arcade / Blacksmith Timing | [Play](./games/game-0122.html) |
| 0123 | Starship Steward | Strategy / Crew Allocation | [Play](./games/game-0123.html) |
| 0124 | Tempo Temple | Rhythm / Drum Pattern | [Play](./games/game-0124.html) |
| 0125 | Magnet Miner | Precision / Polarity Swing | [Play](./games/game-0125.html) |
| 0126 | Shadow Sprinter | Arcade / Stealth Runner | [Play](./games/game-0126.html) |
| 0127 | Glyph Grader | Puzzle / Symbol Sorting Logic | [Play](./games/game-0127.html) |
| 0128 | Bakery Baron | Strategy / Bakery Economy | [Play](./games/game-0128.html) |
| 0129 | Chime Chase | Rhythm / Melody Echo | [Play](./games/game-0129.html) |
| 0130 | Pendulum Plunge | Precision / Pendulum Drop | [Play](./games/game-0130.html) |

## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
