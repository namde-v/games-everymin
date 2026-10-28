# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 740
- **Latest game:** 0740 — Tightrope Acrobatic Balance
- **Current volume:** 008 (Games 0701 to 0800) — in progress (40 of 100)
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
| 008 | 0701–0800 (40, in progress) | [catalogs/readme-008.md](./catalogs/readme-008.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 074

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0731 | Canyon River Raft Rush | Arcade / Whitewater Raft Dodge | [Play](./games/game-0731.html) |
| 0732 | Clockwork Beetle Maze | Puzzle / Gear Path Logic | [Play](./games/game-0732.html) |
| 0733 | Harbor Lighthouse Keeper | Strategy / Ship Guidance | [Play](./games/game-0733.html) |
| 0734 | Drumline Parade March | Rhythm / Marching Beat | [Play](./games/game-0734.html) |
| 0735 | Ice Sculptor Chisel Master | Precision / Carving Timing | [Play](./games/game-0735.html) |
| 0736 | Storm Cloud Sailor | Arcade / Storm Sailing | [Play](./games/game-0736.html) |
| 0737 | Tidepool Shell Sorter | Puzzle / Shell Sorting | [Play](./games/game-0737.html) |
| 0738 | Arctic Research Station Manager | Strategy / Station Management | [Play](./games/game-0738.html) |
| 0739 | Firefly Lantern Beat | Rhythm / Firefly Catch Beat | [Play](./games/game-0739.html) |
| 0740 | Tightrope Acrobatic Balance | Precision / Balance | [Play](./games/game-0740.html) |
## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
