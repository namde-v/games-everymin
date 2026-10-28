# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 270
- **Latest game:** 0270 — Curling Clash
- **Current volume:** 003 (Games 0201 to 0300)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (100, complete) | [catalogs/readme-002.md](./catalogs/readme-002.md) |
| 003 | 0201–0270 (70 so far, up to 0300) | [catalogs/readme-003.md](./catalogs/readme-003.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 027

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0261 | Tempest Rider | Arcade / Wave Surfing | [Play](./games/game-0261.html) |
| 0262 | Prism Path | Puzzle / Light Prism Logic | [Play](./games/game-0262.html) |
| 0263 | Pastry Palace | Strategy / Bakery Management | [Play](./games/game-0263.html) |
| 0264 | Drum Dash | Rhythm / Drum Timing | [Play](./games/game-0264.html) |
| 0265 | Tightrope Tango | Precision / Balance Timing | [Play](./games/game-0265.html) |
| 0266 | Glowbug Garden | Arcade / Firefly Catching | [Play](./games/game-0266.html) |
| 0267 | Glyph Quest | Puzzle / Rune Decoding | [Play](./games/game-0267.html) |
| 0268 | Port Captain | Strategy / Port Logistics | [Play](./games/game-0268.html) |
| 0269 | Songbird Serenade | Rhythm / Melody Timing | [Play](./games/game-0269.html) |
| 0270 | Curling Clash | Precision / Curling Slide | [Play](./games/game-0270.html) |


## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
