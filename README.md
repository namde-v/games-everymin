# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 590
- **Latest game:** 0590 — Polar Plunge
- **Current volume:** 006 (Games 0501 to 0600) — in progress (90 of 100)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (100, complete) | [catalogs/readme-002.md](./catalogs/readme-002.md) |
| 003 | 0201–0300 (100, complete) | [catalogs/readme-003.md](./catalogs/readme-003.md) |
| 004 | 0301–0400 (100, complete) | [catalogs/readme-004.md](./catalogs/readme-004.md) |
| 005 | 0401–0500 (100, complete) | [catalogs/readme-005.md](./catalogs/readme-005.md) |
| 006 | 0501–0600 (90 so far) | [catalogs/readme-006.md](./catalogs/readme-006.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 059

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0581 | Harbor Hoist | Arcade / Crane Stacking Action | [Play](./games/game-0581.html) |
| 0582 | Glyph Grid | Puzzle / Symbol Match Logic | [Play](./games/game-0582.html) |
| 0583 | Alpine Apiary | Strategy / Beehive Management | [Play](./games/game-0583.html) |
| 0584 | Drumline Dunes | Rhythm / Marching Beat Timing | [Play](./games/game-0584.html) |
| 0585 | Comet Catcher | Precision / Gravity Steering Aim | [Play](./games/game-0585.html) |
| 0586 | Jungle Jetpack | Arcade / Jetpack Dodge Flight | [Play](./games/game-0586.html) |
| 0587 | Rune Vault | Puzzle / Rune Deduction Logic | [Play](./games/game-0587.html) |
| 0588 | Harvest Haven | Strategy / Farm Season Planning | [Play](./games/game-0588.html) |
| 0589 | Metronome Meadow | Rhythm / Tempo Matching | [Play](./games/game-0589.html) |
| 0590 | Polar Plunge | Precision / Ice Dive Aim | [Play](./games/game-0590.html) |
## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
