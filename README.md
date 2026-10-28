# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 480
- **Latest game:** 0480 — Mycelium Mayor
- **Current volume:** 005 (Games 0401 to 0500)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (100, complete) | [catalogs/readme-002.md](./catalogs/readme-002.md) |
| 003 | 0201–0300 (100, complete) | [catalogs/readme-003.md](./catalogs/readme-003.md) |
| 004 | 0301–0400 (100, complete) | [catalogs/readme-004.md](./catalogs/readme-004.md) |
| 005 | 0401–0500 (80 so far) | [catalogs/readme-005.md](./catalogs/readme-005.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 048

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0471 | Quarry Quake | Action / Falling-Rock Dodger | [Play](./games/game-0471.html) |
| 0472 | Riddle Reef | Puzzle / Clue-Chain Deduction | [Play](./games/game-0472.html) |
| 0473 | Solar Shepherd | Strategy / Orbital Power Management | [Play](./games/game-0473.html) |
| 0474 | Tempo Tailor | Rhythm / Beat Stitching | [Play](./games/game-0474.html) |
| 0475 | Wisp Warden | Arcade / Ghost-Light Herding | [Play](./games/game-0475.html) |
| 0476 | Cipher Canyon | Puzzle / Code-Breaking Trail | [Play](./games/game-0476.html) |
| 0477 | Tidal Trader | Strategy / Harbor Cargo Trading | [Play](./games/game-0477.html) |
| 0478 | Pulse Pilot | Rhythm / Heartbeat Lane Runner | [Play](./games/game-0478.html) |
| 0479 | Boulder Bouncer | Action / Ricochet Physics | [Play](./games/game-0479.html) |
| 0480 | Mycelium Mayor | Strategy / Fungal City Builder | [Play](./games/game-0480.html) |

## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
