# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 210
- **Latest game:** 0210 — Anchor Angler
- **Current volume:** 003 (Games 0201 to 0300)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (100, complete) | [catalogs/readme-002.md](./catalogs/readme-002.md) |
| 003 | 0201–0210 (10 so far, up to 0300) | [catalogs/readme-003.md](./catalogs/readme-003.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 021

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0201 | Zephyr Zipline | Arcade / Zipline Descent | [Play](./games/game-0201.html) |
| 0202 | Quill Quest | Puzzle / Word Letter Puzzle | [Play](./games/game-0202.html) |
| 0203 | Lighthouse Keeper | Strategy / Lighthouse Beam Management | [Play](./games/game-0203.html) |
| 0204 | Sitar Serenade | Rhythm / Sitar Note Timing | [Play](./games/game-0204.html) |
| 0205 | Boomerang Bandit | Precision / Boomerang Throwing | [Play](./games/game-0205.html) |
| 0206 | Coral Collector | Arcade / Underwater Collector | [Play](./games/game-0206.html) |
| 0207 | Circuit Crafter | Puzzle / Circuit Routing | [Play](./games/game-0207.html) |
| 0208 | Vineyard Venture | Strategy / Vineyard Management | [Play](./games/game-0208.html) |
| 0209 | Flute Flight | Rhythm / Melody Note Matching | [Play](./games/game-0209.html) |
| 0210 | Anchor Angler | Precision / Fishing | [Play](./games/game-0210.html) |


## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
