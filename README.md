# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 340
- **Latest game:** 0340 — Star Cartographer
- **Current volume:** 004 (Games 0301 to 0400)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (100, complete) | [catalogs/readme-002.md](./catalogs/readme-002.md) |
| 003 | 0201–0300 (100, complete) | [catalogs/readme-003.md](./catalogs/readme-003.md) |
| 004 | 0301–0400 (40 so far) | [catalogs/readme-004.md](./catalogs/readme-004.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 034

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0331 | Quarry Rumble | Arcade / Boulder Dodge | [Play](./games/game-0331.html) |
| 0332 | Hexfield Harvest | Puzzle / Hex Match | [Play](./games/game-0332.html) |
| 0333 | Beacon Keeper | Strategy / Lighthouse Management | [Play](./games/game-0333.html) |
| 0334 | Dune Drummers | Rhythm / Desert Drums | [Play](./games/game-0334.html) |
| 0335 | Sky Shepherd | Arcade / Cloud Herding | [Play](./games/game-0335.html) |
| 0336 | Glyph Relay | Puzzle / Rune Sequence | [Play](./games/game-0336.html) |
| 0337 | Foundry Foreman | Strategy / Factory Line | [Play](./games/game-0337.html) |
| 0338 | Metronome Mines | Rhythm / Precision Mining | [Play](./games/game-0338.html) |
| 0339 | Shadow Scribe | Arcade / Stealth Maze | [Play](./games/game-0339.html) |
| 0340 | Star Cartographer | Puzzle / Constellation Drawing | [Play](./games/game-0340.html) |


## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
