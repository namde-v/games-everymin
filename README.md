# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 30
- **Latest game:** 0030 — Rune Duel
- **Current volume:** 001 (Games 0001 to 0100)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0030 (30 so far, up to 0100) | [catalogs/readme-001.md](./catalogs/readme-001.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 003

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0021 | Orbit Flip | Arcade / Gravity Flip Runner | [Play](./games/game-0021.html) |
| 0022 | Word Weaver | Puzzle / Word Logic | [Play](./games/game-0022.html) |
| 0023 | Skyport Control | Strategy / Air Traffic Routing | [Play](./games/game-0023.html) |
| 0024 | Beat Bounce | Rhythm / Bounce Timing | [Play](./games/game-0024.html) |
| 0025 | Prism Breaker | Arcade / Color Breakout | [Play](./games/game-0025.html) |
| 0026 | Boulder Balance | Puzzle / Physics Stacking | [Play](./games/game-0026.html) |
| 0027 | Lighthouse Keeper | Simulation / Beacon Management | [Play](./games/game-0027.html) |
| 0028 | Orbit Golf | Precision / Gravity Mini-Golf | [Play](./games/game-0028.html) |
| 0029 | Ghost Glider | Arcade / Stealth Glide | [Play](./games/game-0029.html) |
| 0030 | Rune Duel | Strategy / Card Duel | [Play](./games/game-0030.html) |

## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
