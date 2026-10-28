# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 640
- **Latest game:** 0640 — Glassblower's Breath
- **Current volume:** 007 (Games 0601 to 0700) — in progress (40 of 100)
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
| 007 | 0601–0700 (40, in progress) | [catalogs/readme-007.md](./catalogs/readme-007.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 064

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0631 | Harbor Crane Stacker | Arcade / Harbor Crane Stacking | [Play](./games/game-0631.html) |
| 0632 | Mosaic Mender | Puzzle / Mosaic Pattern Restoration | [Play](./games/game-0632.html) |
| 0633 | Tide Mill Operator | Strategy / Tide Mill Management | [Play](./games/game-0633.html) |
| 0634 | Samba Street Parade | Rhythm / Samba Parade Timing | [Play](./games/game-0634.html) |
| 0635 | Geyser Hopper | Arcade / Geyser Platform Hopping | [Play](./games/game-0635.html) |
| 0636 | Herbalist's Potion Lab | Puzzle / Herbal Remedy Deduction | [Play](./games/game-0636.html) |
| 0637 | Railway Junction Tycoon | Strategy / Railway Junction Routing | [Play](./games/game-0637.html) |
| 0638 | Metronome Mechanic | Rhythm / Metronome Repair Timing | [Play](./games/game-0638.html) |
| 0639 | Paper Plane Postman | Arcade / Paper Plane Delivery | [Play](./games/game-0639.html) |
| 0640 | Glassblower's Breath | Precision / Glassblowing Breath Control | [Play](./games/game-0640.html) |
## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
