# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 660
- **Latest game:** 0660 — Clockmaker Gear Calibration
- **Current volume:** 007 (Games 0601 to 0700) — in progress (50 of 100)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (100, complete) | [catalogs/readme-002.md](./catalogs/readme-002.md) |
| 003 | 0201–0300 (100, complete) | [catalogs/readme-003.md](./catalogs/readme-003.md) |
| 004 | 0301–0400 (100, complete) | [catalogs/readme-004.md](./catalogs/readme-004.md) |
| 005 | 0401–0500 (100, complete) | [catalogs/readme-005.md](./catalogs/readme-005.md) |
| 006 | 0501–0600 (100, complete) | [catalogs/readme-006.md](./catalogs/readme-006.md) |
| 007 | 0601–0700 (60, in progress) | [catalogs/readme-007.md](./catalogs/readme-007.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 066

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0651 | Monsoon Rooftop Runner | Arcade / Rooftop Sprint | [Play](./games/game-0651.html) |
| 0652 | Sundial Shadow Puzzle | Puzzle / Shadow Alignment Logic | [Play](./games/game-0652.html) |
| 0653 | Lighthouse Keeper Shifts | Strategy / Lighthouse Duty Management | [Play](./games/game-0653.html) |
| 0654 | Steelpan Island Beats | Rhythm / Steelpan Timing | [Play](./games/game-0654.html) |
| 0655 | Falconry Flight Trial | Precision / Falcon Dive Aiming | [Play](./games/game-0655.html) |
| 0656 | Avalanche Snowboarder | Arcade / Snowboard Descent | [Play](./games/game-0656.html) |
| 0657 | Cartographer's Map Match | Puzzle / Map Piece Logic | [Play](./games/game-0657.html) |
| 0658 | Vineyard Harvest Planner | Strategy / Vineyard Season Management | [Play](./games/game-0658.html) |
| 0659 | Carnival Samba Parade | Rhythm / Samba Parade Timing | [Play](./games/game-0659.html) |
| 0660 | Clockmaker Gear Calibration | Precision / Gear Timing Calibration | [Play](./games/game-0660.html) |
## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
