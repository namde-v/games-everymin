# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 620
- **Latest game:** 0620 — Orbit Docking
- **Current volume:** 007 (Games 0601 to 0700) — in progress (20 of 100)
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
| 007 | 0601–0700 (20, in progress) | [catalogs/readme-007.md](./catalogs/readme-007.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 062

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0611 | Starlight Parcel Run | Arcade / Space Delivery Action | [Play](./games/game-0611.html) |
| 0612 | Prism Relay | Puzzle / Light Beam Logic | [Play](./games/game-0612.html) |
| 0613 | Quayside Commander | Strategy / Port Docking Simulation | [Play](./games/game-0613.html) |
| 0614 | Neon Beat Bounce | Rhythm / Bouncing Beat Timing | [Play](./games/game-0614.html) |
| 0615 | Kite Storm Surfer | Arcade / Wind Kite Surfing | [Play](./games/game-0615.html) |
| 0616 | Circuit Gardener | Puzzle / Circuit Connection Logic | [Play](./games/game-0616.html) |
| 0617 | Ovenlight Bakery | Strategy / Bakery Order Management | [Play](./games/game-0617.html) |
| 0618 | Pendulum Painter | Precision / Pendulum Timing Painting | [Play](./games/game-0618.html) |
| 0619 | Subzero Skater | Arcade / Ice Skating Collect | [Play](./games/game-0619.html) |
| 0620 | Orbit Docking | Precision / Spacecraft Docking | [Play](./games/game-0620.html) |
## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
