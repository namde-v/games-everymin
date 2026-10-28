# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 170
- **Latest game:** 0170 — Archery Aurora
- **Current volume:** 002 (Games 0101 to 0200)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (70 so far) | [catalogs/readme-002.md](./catalogs/readme-002.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 017

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0161 | Glacier Glider | Arcade / Ice Momentum Slider | [Play](./games/game-0161.html) |
| 0162 | Rune Reactor | Puzzle / Rune Sequence Logic | [Play](./games/game-0162.html) |
| 0163 | Observatory Operator | Strategy / Telescope Scheduling | [Play](./games/game-0163.html) |
| 0164 | Bongo Blitz | Rhythm / Drum Beat Timing | [Play](./games/game-0164.html) |
| 0165 | Orbit Ordeal | Precision / Gravity Slingshot | [Play](./games/game-0165.html) |
| 0166 | Neon Nightrider | Arcade / Neon Lane Dodger | [Play](./games/game-0166.html) |
| 0167 | Hex Havoc | Puzzle / Hex Tile Rotation | [Play](./games/game-0167.html) |
| 0168 | Farmstead Frontier | Strategy / Crop Rotation Simulation | [Play](./games/game-0168.html) |
| 0169 | Meadow Maestro | Rhythm / Birdsong Conducting | [Play](./games/game-0169.html) |
| 0170 | Archery Aurora | Precision / Wind Archery | [Play](./games/game-0170.html) |


## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
