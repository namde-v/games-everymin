# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 580
- **Latest game:** 0580 — Bamboo Bounce
- **Current volume:** 006 (Games 0501 to 0600) — in progress (80 of 100)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (100, complete) | [catalogs/readme-002.md](./catalogs/readme-002.md) |
| 003 | 0201–0300 (100, complete) | [catalogs/readme-003.md](./catalogs/readme-003.md) |
| 004 | 0301–0400 (100, complete) | [catalogs/readme-004.md](./catalogs/readme-004.md) |
| 005 | 0401–0500 (100, complete) | [catalogs/readme-005.md](./catalogs/readme-005.md) |
| 006 | 0501–0600 (80 so far) | [catalogs/readme-006.md](./catalogs/readme-006.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 058

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0571 | Avalanche Courier | Arcade / Snow Sled Delivery | [Play](./games/game-0571.html) |
| 0572 | Tidepool Tiles | Puzzle / Rotating Tile Logic | [Play](./games/game-0572.html) |
| 0573 | Desert Oasis Manager | Strategy / Oasis Resource Planning | [Play](./games/game-0573.html) |
| 0574 | Volcano Beat Forge | Rhythm / Hammer Beat Timing | [Play](./games/game-0574.html) |
| 0575 | Nebula Navigator | Precision / Orbital Slingshot Aim | [Play](./games/game-0575.html) |
| 0576 | Midnight Market Maze | Arcade / Ghost Market Chase | [Play](./games/game-0576.html) |
| 0577 | Star Chart Cipher | Puzzle / Constellation Logic | [Play](./games/game-0577.html) |
| 0578 | Fog Lantern Relay | Strategy / Beacon Relay Planning | [Play](./games/game-0578.html) |
| 0579 | Glacier Chime Choir | Rhythm / Chime Sequence Memory | [Play](./games/game-0579.html) |
| 0580 | Bamboo Bounce | Precision / Ricochet Aim | [Play](./games/game-0580.html) |

## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
