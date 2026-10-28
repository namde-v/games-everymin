# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 140
- **Latest game:** 0140 — Crane Commander
- **Current volume:** 002 (Games 0101 to 0200)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (40 so far) | [catalogs/readme-002.md](./catalogs/readme-002.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 014

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0131 | Avalanche Ace | Arcade / Snowboard Slalom | [Play](./games/game-0131.html) |
| 0132 | Cipher Circuit | Puzzle / Logic-Gate Routing | [Play](./games/game-0132.html) |
| 0133 | Orchard Overseer | Strategy / Orchard Management | [Play](./games/game-0133.html) |
| 0134 | Beat Beacon | Rhythm / Beat Timing | [Play](./games/game-0134.html) |
| 0135 | Orbit Overture | Precision / Gravity Slingshot | [Play](./games/game-0135.html) |
| 0136 | Ink Infiltrator | Arcade / Stealth Spray | [Play](./games/game-0136.html) |
| 0137 | Sigil Solver | Puzzle / Rune Deduction | [Play](./games/game-0137.html) |
| 0138 | Dockside Director | Strategy / Port Logistics | [Play](./games/game-0138.html) |
| 0139 | Samba Step | Rhythm / Dance Steps | [Play](./games/game-0139.html) |
| 0140 | Crane Commander | Precision / Crane Stacking | [Play](./games/game-0140.html) |

## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
