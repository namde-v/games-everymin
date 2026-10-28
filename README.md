# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 410
- **Latest game:** 0410 — Velvet Voyager
- **Current volume:** 005 (Games 0401 to 0500)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (100, complete) | [catalogs/readme-002.md](./catalogs/readme-002.md) |
| 003 | 0201–0300 (100, complete) | [catalogs/readme-003.md](./catalogs/readme-003.md) |
| 004 | 0301–0400 (100, complete) | [catalogs/readme-004.md](./catalogs/readme-004.md) |
| 005 | 0401–0500 (10 so far) | [catalogs/readme-005.md](./catalogs/readme-005.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 041

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0401 | Lunar Luthier | Rhythm / Moon-Note Plucking | [Play](./games/game-0401.html) |
| 0402 | Mossy Mechanic | Puzzle / Gear Connection | [Play](./games/game-0402.html) |
| 0403 | Obsidian Outrider | Arcade / Desert Lane Rider | [Play](./games/game-0403.html) |
| 0404 | Parchment Paladin | Strategy / Turn-Based Card Duel | [Play](./games/game-0404.html) |
| 0405 | Quiver Quartermaster | Puzzle / Arrow Sorting Stacks | [Play](./games/game-0405.html) |
| 0406 | Rustic Ranger | Arcade / Slingshot Target Precision | [Play](./games/game-0406.html) |
| 0407 | Sapphire Sommelier | Puzzle / Blend Deduction | [Play](./games/game-0407.html) |
| 0408 | Tidal Tinkerer | Strategy / Tide Defense Building | [Play](./games/game-0408.html) |
| 0409 | Umbral Undertaker | Arcade / Shadow Stealth Maze | [Play](./games/game-0409.html) |
| 0410 | Velvet Voyager | Arcade / Gravity Slingshot Navigation | [Play](./games/game-0410.html) |

## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
