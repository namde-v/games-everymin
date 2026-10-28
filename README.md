# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 550
- **Latest game:** 0550 — Ashfall Ascent
- **Current volume:** 006 (Games 0501 to 0600) — in progress (50 of 100)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (100, complete) | [catalogs/readme-002.md](./catalogs/readme-002.md) |
| 003 | 0201–0300 (100, complete) | [catalogs/readme-003.md](./catalogs/readme-003.md) |
| 004 | 0301–0400 (100, complete) | [catalogs/readme-004.md](./catalogs/readme-004.md) |
| 005 | 0401–0500 (100, complete) | [catalogs/readme-005.md](./catalogs/readme-005.md) |
| 006 | 0501–0600 (50 so far) | [catalogs/readme-006.md](./catalogs/readme-006.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 055

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0541 | Polarity Pursuit | Arcade / Polarity Runner | [Play](./games/game-0541.html) |
| 0542 | Tide Lock | Puzzle / Tide Gate Logic | [Play](./games/game-0542.html) |
| 0543 | Hive Horizon | Strategy / Beehive Management | [Play](./games/game-0543.html) |
| 0544 | Parade Percussion | Rhythm / Marching Beat Timing | [Play](./games/game-0544.html) |
| 0545 | Comet Slingshot | Precision / Orbital Slingshot | [Play](./games/game-0545.html) |
| 0546 | Signal Switchboard | Puzzle / Wire Routing | [Play](./games/game-0546.html) |
| 0547 | Glacier Expedition | Strategy / Turn-Based Expedition Planning | [Play](./games/game-0547.html) |
| 0548 | Glass Harmonica | Rhythm / Melody Memory and Timing | [Play](./games/game-0548.html) |
| 0549 | Trident Toss | Precision / Trident Throw Aim | [Play](./games/game-0549.html) |
| 0550 | Ashfall Ascent | Arcade / Volcano Climb Dodger | [Play](./games/game-0550.html) |



## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
