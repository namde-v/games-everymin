# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 760
- **Latest game:** 0760 — Archery Wind Shot
- **Current volume:** 008 (Games 0701 to 0800) — in progress (60 of 100)
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
| 007 | 0601–0700 (100, complete) | [catalogs/readme-007.md](./catalogs/readme-007.md) |
| 008 | 0701–0800 (60, in progress) | [catalogs/readme-008.md](./catalogs/readme-008.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 076

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0751 | Glacier Penguin Slide | Arcade / Penguin Slide Collector | [Play](./games/game-0751.html) |
| 0752 | Constellation Connector | Puzzle / Star Connection Logic | [Play](./games/game-0752.html) |
| 0753 | Desert Oasis Trader | Strategy / Caravan Trading | [Play](./games/game-0753.html) |
| 0754 | Bell Tower Chime Master | Rhythm / Bell Chime Timing | [Play](./games/game-0754.html) |
| 0755 | Paper Plane Glider | Precision / Glider Ring Flight | [Play](./games/game-0755.html) |
| 0756 | Meadow Bee Pollinator | Arcade / Pollination Flight | [Play](./games/game-0756.html) |
| 0757 | Tile Bridge Builder | Puzzle / Bridge Construction Logic | [Play](./games/game-0757.html) |
| 0758 | Bakery Supply Chain | Strategy / Bakery Logistics | [Play](./games/game-0758.html) |
| 0759 | Ukulele Island Strum | Rhythm / Ukulele Strum Timing | [Play](./games/game-0759.html) |
| 0760 | Archery Wind Shot | Precision / Wind Archery | [Play](./games/game-0760.html) |
## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
