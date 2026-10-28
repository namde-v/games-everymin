# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 560
- **Latest game:** 0560 — Stardust Stepper
- **Current volume:** 006 (Games 0501 to 0600) — in progress (60 of 100)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (100, complete) | [catalogs/readme-002.md](./catalogs/readme-002.md) |
| 003 | 0201–0300 (100, complete) | [catalogs/readme-003.md](./catalogs/readme-003.md) |
| 004 | 0301–0400 (100, complete) | [catalogs/readme-004.md](./catalogs/readme-004.md) |
| 005 | 0401–0500 (100, complete) | [catalogs/readme-005.md](./catalogs/readme-005.md) |
| 006 | 0501–0600 (60 so far) | [catalogs/readme-006.md](./catalogs/readme-006.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 056

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0551 | Skyline Skater | Arcade / Rooftop Grind Runner | [Play](./games/game-0551.html) |
| 0552 | Prism Pantry | Puzzle / Color Mixing Logic | [Play](./games/game-0552.html) |
| 0553 | Harbor Hauler | Strategy / Port Cargo Logistics | [Play](./games/game-0553.html) |
| 0554 | Neon Tide Drummer | Rhythm / Wave Beat Sync | [Play](./games/game-0554.html) |
| 0555 | Canyon Echo | Precision / Echo Bounce Aim | [Play](./games/game-0555.html) |
| 0556 | Solar Orchard | Strategy / Solar Farm Planning | [Play](./games/game-0556.html) |
| 0557 | Sundial Sorting | Puzzle / Sundial Shadow Logic | [Play](./games/game-0557.html) |
| 0558 | Sonar Salvage | Precision / Sonar Targeting | [Play](./games/game-0558.html) |
| 0559 | Emberline Express | Arcade / Fire Train Track Switcher | [Play](./games/game-0559.html) |
| 0560 | Stardust Stepper | Rhythm / Dance Step Timing | [Play](./games/game-0560.html) |

## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
