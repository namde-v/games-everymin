# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 500
- **Latest game:** 0500 — Tempest Tactician
- **Current volume:** 005 (Games 0401 to 0500) — complete; next volume 006 opens at game 0501
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (100, complete) | [catalogs/readme-002.md](./catalogs/readme-002.md) |
| 003 | 0201–0300 (100, complete) | [catalogs/readme-003.md](./catalogs/readme-003.md) |
| 004 | 0301–0400 (100, complete) | [catalogs/readme-004.md](./catalogs/readme-004.md) |
| 005 | 0401–0500 (100, complete) | [catalogs/readme-005.md](./catalogs/readme-005.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 050

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0491 | Kelp Keeper | Strategy / Underwater Farm Management | [Play](./games/game-0491.html) |
| 0492 | Lantern Labyrinth | Puzzle / Light Maze | [Play](./games/game-0492.html) |
| 0493 | Meteor Mechanic | Arcade / Asteroid Repair Action | [Play](./games/game-0493.html) |
| 0494 | Nightingale Navigator | Strategy / Star Chart Navigation | [Play](./games/game-0494.html) |
| 0495 | Obsidian Oracle | Puzzle / Rune Prophecy Logic | [Play](./games/game-0495.html) |
| 0496 | Prism Pilot | Arcade / Color Refraction Shooter | [Play](./games/game-0496.html) |
| 0497 | Quarry Quest | Strategy / Mining Tycoon | [Play](./games/game-0497.html) |
| 0498 | Ripple Racer | Rhythm / Wave Surf Timing | [Play](./games/game-0498.html) |
| 0499 | Solar Shepherd | Strategy / Orbit Herding Simulation | [Play](./games/game-0499.html) |
| 0500 | Tempest Tactician | Strategy / Storm Battle Tactics | [Play](./games/game-0500.html) |

## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
