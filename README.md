# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 600
- **Latest game:** 0600 — Aurora Archery
- **Current volume:** 006 (Games 0501 to 0600) — complete (100 of 100)
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

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 060

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0591 | Canyon River Run | Arcade / River Rapids Delivery | [Play](./games/game-0591.html) |
| 0592 | Mirror Maze | Puzzle / Mirror Beam Logic | [Play](./games/game-0592.html) |
| 0593 | Lighthouse Logistics | Strategy / Harbor Signal Planning | [Play](./games/game-0593.html) |
| 0594 | Samba Step Studio | Rhythm / Dance Step Timing | [Play](./games/game-0594.html) |
| 0595 | Meteor Miner | Precision / Asteroid Cannon Aim | [Play](./games/game-0595.html) |
| 0596 | Sky Kite Surfer | Arcade / Wind Kite Flight | [Play](./games/game-0596.html) |
| 0597 | Tide Pipe Puzzle | Puzzle / Water Pipe Flow Logic | [Play](./games/game-0597.html) |
| 0598 | Glacier Expedition | Strategy / Expedition Route Planning | [Play](./games/game-0598.html) |
| 0599 | Beat Box Bakery | Rhythm / Baking Beat Timing | [Play](./games/game-0599.html) |
| 0600 | Aurora Archery | Precision / Wind Archery Aim | [Play](./games/game-0600.html) |
## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
