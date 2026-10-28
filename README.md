# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 670
- **Latest game:** 0670 — Blacksmith Hammer Strike
- **Current volume:** 007 (Games 0601 to 0700) — in progress (70 of 100)
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
| 007 | 0601–0700 (70, in progress) | [catalogs/readme-007.md](./catalogs/readme-007.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 067

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0661 | Tidal Harbor Ferry Dash | Arcade / Harbor Ferry Navigation | [Play](./games/game-0661.html) |
| 0662 | Lantern Riddle Grid | Puzzle / Light-Up Logic | [Play](./games/game-0662.html) |
| 0663 | Alpine Apiary Manager | Strategy / Beekeeping Management | [Play](./games/game-0663.html) |
| 0664 | Festival Drum Clash | Rhythm / Taiko Drum Timing | [Play](./games/game-0664.html) |
| 0665 | Harbor Crane Hook Drop | Precision / Crane Hook Timing | [Play](./games/game-0665.html) |
| 0666 | Mangrove Kayak Escape | Arcade / River Kayak Descent | [Play](./games/game-0666.html) |
| 0667 | Constellation Connect Logic | Puzzle / Star Connection Logic | [Play](./games/game-0667.html) |
| 0668 | Tea House Service Strategy | Strategy / Tea House Customer Management | [Play](./games/game-0668.html) |
| 0669 | River Reed Flute Melody | Rhythm / Melody Matching | [Play](./games/game-0669.html) |
| 0670 | Blacksmith Hammer Strike | Precision / Hammer Timing | [Play](./games/game-0670.html) |
## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
