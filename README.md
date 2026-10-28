# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 300
- **Latest game:** 0300 — Lunar Leap
- **Current volume:** 003 (Games 0201 to 0300)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (100, complete) | [catalogs/readme-002.md](./catalogs/readme-002.md) |
| 003 | 0201–0300 (100, complete) | [catalogs/readme-003.md](./catalogs/readme-003.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 030

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0291 | Mirror Meadow | Puzzle / Light Reflection | [Play](./games/game-0291.html) |
| 0292 | Photon Pilgrim | Arcade / Solar Wind Riding | [Play](./games/game-0292.html) |
| 0293 | Cinderfield Cultivator | Strategy / Farm Simulation | [Play](./games/game-0293.html) |
| 0294 | Metronome Maze | Rhythm / Beat Maze | [Play](./games/game-0294.html) |
| 0295 | Paper Plane Patrol | Arcade / Gliding Flight | [Play](./games/game-0295.html) |
| 0296 | Rune Relay | Puzzle / Sequence Logic | [Play](./games/game-0296.html) |
| 0297 | Quarry Quest | Arcade / Digging Adventure | [Play](./games/game-0297.html) |
| 0298 | Starlight Stitch | Puzzle / Constellation Drawing | [Play](./games/game-0298.html) |
| 0299 | Lighthouse Ledger | Strategy / Lighthouse Management | [Play](./games/game-0299.html) |
| 0300 | Lunar Leap | Precision / Low-Gravity Jumping | [Play](./games/game-0300.html) |


## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
