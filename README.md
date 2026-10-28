# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 370
- **Latest game:** 0370 — Starlight Surveyor
- **Current volume:** 004 (Games 0301 to 0400)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (100, complete) | [catalogs/readme-002.md](./catalogs/readme-002.md) |
| 003 | 0201–0300 (100, complete) | [catalogs/readme-003.md](./catalogs/readme-003.md) |
| 004 | 0301–0400 (70 so far) | [catalogs/readme-004.md](./catalogs/readme-004.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 037

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0361 | Aurora Archer | Arcade / Archery Aim | [Play](./games/game-0361.html) |
| 0362 | Quarry Quandary | Puzzle / Crate Pushing | [Play](./games/game-0362.html) |
| 0363 | Harbor Harbormaster | Strategy / Port Scheduling | [Play](./games/game-0363.html) |
| 0364 | Syncopation Station | Rhythm / Off-Beat Timing | [Play](./games/game-0364.html) |
| 0365 | Tempest Tamer | Arcade / Storm Dodging | [Play](./games/game-0365.html) |
| 0366 | Rune Reservoir | Puzzle / Rune Flow | [Play](./games/game-0366.html) |
| 0367 | Assembly Archon | Strategy / Workshop Assembly | [Play](./games/game-0367.html) |
| 0368 | Pulse Painter | Rhythm / Beat Painting | [Play](./games/game-0368.html) |
| 0369 | Dune Drifter | Arcade / Sandboarding | [Play](./games/game-0369.html) |
| 0370 | Starlight Surveyor | Puzzle / Constellation Connect | [Play](./games/game-0370.html) |


## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
