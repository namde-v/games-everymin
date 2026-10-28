# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 770
- **Latest game:** 0770 — Comet Tail Navigator
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
| 008 | 0701–0800 (70, in progress) | [catalogs/readme-008.md](./catalogs/readme-008.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 077

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0761 | Moonlight Firefly Catcher | Arcade / Firefly Catching | [Play](./games/game-0761.html) |
| 0762 | Gearworks Cog Puzzle | Puzzle / Gear Rotation Logic | [Play](./games/game-0762.html) |
| 0763 | Harbor Ferry Scheduler | Strategy / Ferry Route Planning | [Play](./games/game-0763.html) |
| 0764 | Rainforest Rain Drummer | Rhythm / Rain Drum Timing | [Play](./games/game-0764.html) |
| 0765 | Glacier Crystal Skater | Precision / Crystal Gate Slalom | [Play](./games/game-0765.html) |
| 0766 | Canyon Condor Soarer | Arcade / Thermal Soaring Collector | [Play](./games/game-0766.html) |
| 0767 | Crystal Prism Sorter | Puzzle / Color Sorting Logic | [Play](./games/game-0767.html) |
| 0768 | Mountain Ski Resort Manager | Strategy / Resort Management | [Play](./games/game-0768.html) |
| 0769 | Alpine Yodel Echo | Rhythm / Melody Echo Timing | [Play](./games/game-0769.html) |
| 0770 | Comet Tail Navigator | Precision / Asteroid Gate Navigation | [Play](./games/game-0770.html) |
## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
