# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 60
- **Latest game:** 0060 — Boomerang Bay
- **Current volume:** 001 (Games 0001 to 0100)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0060 (60 so far, up to 0100) | [catalogs/readme-001.md](./catalogs/readme-001.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 006

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0051 | Ember Escape | Arcade / Lava Platform Hopper | [Play](./games/game-0051.html) |
| 0052 | Rune Rings | Puzzle / Ring Rotation Logic | [Play](./games/game-0052.html) |
| 0053 | Antlion Empire | Strategy / Ant Colony Builder | [Play](./games/game-0053.html) |
| 0054 | Neon Note Runner | Rhythm / Lane Runner | [Play](./games/game-0054.html) |
| 0055 | Paper Plane Pilot | Precision / Wind Glider | [Play](./games/game-0055.html) |
| 0056 | Deep Dive Dash | Arcade / Cave Diver | [Play](./games/game-0056.html) |
| 0057 | Shadow Shapes | Puzzle / Silhouette Matching | [Play](./games/game-0057.html) |
| 0058 | Skyline Tycoon | Strategy / City Builder | [Play](./games/game-0058.html) |
| 0059 | Synth Surfer | Rhythm / Wave Riding | [Play](./games/game-0059.html) |
| 0060 | Boomerang Bay | Precision / Boomerang Throw | [Play](./games/game-0060.html) |

## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
