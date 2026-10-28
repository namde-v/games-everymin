# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 650
- **Latest game:** 0650 — Ice Sculptor Chisel
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
| 007 | 0601–0700 (50, in progress) | [catalogs/readme-007.md](./catalogs/readme-007.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 065

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0641 | Glacier Kayak Rapids | Arcade / River Kayak Rapids | [Play](./games/game-0641.html) |
| 0642 | Constellation Weaver | Puzzle / Star Connection Logic | [Play](./games/game-0642.html) |
| 0643 | Beehive Honey Manager | Strategy / Beehive Management Simulation | [Play](./games/game-0643.html) |
| 0644 | Taiko Drum Festival | Rhythm / Drum Beat Timing | [Play](./games/game-0644.html) |
| 0645 | Archery Wind Trial | Precision / Archery Wind Aiming | [Play](./games/game-0645.html) |
| 0646 | Volcano Ash Glider | Arcade / Volcanic Gliding Action | [Play](./games/game-0646.html) |
| 0647 | Tumbler Code Breaker | Puzzle / Safe Dial Deduction | [Play](./games/game-0647.html) |
| 0648 | Desert Oasis Caravan | Strategy / Caravan Route Management | [Play](./games/game-0648.html) |
| 0649 | Flamenco Clap Circle | Rhythm / Handclap Pattern Timing | [Play](./games/game-0649.html) |
| 0650 | Ice Sculptor Chisel | Precision / Ice Sculpting Timing | [Play](./games/game-0650.html) |
## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
