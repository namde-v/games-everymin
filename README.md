# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 540
- **Latest game:** 0540 — Dune Dasher
- **Current volume:** 006 (Games 0501 to 0600) — in progress (40 of 100)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (100, complete) | [catalogs/readme-002.md](./catalogs/readme-002.md) |
| 003 | 0201–0300 (100, complete) | [catalogs/readme-003.md](./catalogs/readme-003.md) |
| 004 | 0301–0400 (100, complete) | [catalogs/readme-004.md](./catalogs/readme-004.md) |
| 005 | 0401–0500 (100, complete) | [catalogs/readme-005.md](./catalogs/readme-005.md) |
| 006 | 0501–0600 (40 so far) | [catalogs/readme-006.md](./catalogs/readme-006.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 054

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0531 | Storm Sailor | Arcade / Storm Ship Dodger | [Play](./games/game-0531.html) |
| 0532 | Moss Maze | Puzzle / Living Maze Path Logic | [Play](./games/game-0532.html) |
| 0533 | Paper Mill Tycoon | Strategy / Paper Mill Management | [Play](./games/game-0533.html) |
| 0534 | Clap Cascade | Rhythm / Handclap Beat Timing | [Play](./games/game-0534.html) |
| 0535 | Glacier Grappler | Precision / Ice Hook Aim | [Play](./games/game-0535.html) |
| 0536 | Coral Current | Puzzle / Reef Tile Connection Logic | [Play](./games/game-0536.html) |
| 0537 | Observatory Operator | Strategy / Telescope Night Scheduling | [Play](./games/game-0537.html) |
| 0538 | Banjo Barnstorm | Rhythm / Banjo Strum Melody | [Play](./games/game-0538.html) |
| 0539 | Lantern Launcher | Precision / Lantern Trajectory Aim | [Play](./games/game-0539.html) |
| 0540 | Dune Dasher | Arcade / Sandboard Descent | [Play](./games/game-0540.html) |



## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
