# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 630
- **Latest game:** 0630 — Marble Magnet Maze
- **Current volume:** 007 (Games 0601 to 0700) — in progress (30 of 100)
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
| 007 | 0601–0700 (30, in progress) | [catalogs/readme-007.md](./catalogs/readme-007.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 063

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0621 | Tidepool Treasure Dive | Arcade / Underwater Treasure Diving | [Play](./games/game-0621.html) |
| 0622 | Rune Vault Cipher | Puzzle / Rune Sequence Logic | [Play](./games/game-0622.html) |
| 0623 | Skyport Air Traffic | Strategy / Air Traffic Control | [Play](./games/game-0623.html) |
| 0624 | Metro Step Sync | Rhythm / Dance Step Timing | [Play](./games/game-0624.html) |
| 0625 | Ember Canyon Runner | Arcade / Lava Canyon Runner | [Play](./games/game-0625.html) |
| 0626 | Wordfall Anagram | Puzzle / Falling Word Puzzle | [Play](./games/game-0626.html) |
| 0627 | Ant Colony Architect | Strategy / Ant Colony Simulation | [Play](./games/game-0627.html) |
| 0628 | Clockwork Catapult | Precision / Catapult Trajectory | [Play](./games/game-0628.html) |
| 0629 | Storm Chaser Drone | Arcade / Storm Drone Flying | [Play](./games/game-0629.html) |
| 0630 | Marble Magnet Maze | Precision / Magnetic Maze Navigation | [Play](./games/game-0630.html) |
## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
