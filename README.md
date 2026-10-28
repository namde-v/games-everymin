# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 400
- **Latest game:** 0400 — Jubilee Jester
- **Current volume:** 005 (Games 0401 to 0500)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (100, complete) | [catalogs/readme-002.md](./catalogs/readme-002.md) |
| 003 | 0201–0300 (100, complete) | [catalogs/readme-003.md](./catalogs/readme-003.md) |
| 004 | 0301–0400 (100, complete) | [catalogs/readme-004.md](./catalogs/readme-004.md) |
| 005 | 0401–0500 (0 so far) | [catalogs/readme-005.md](./catalogs/readme-005.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 040

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0391 | Polaris Bowmaster | Arcade / Archery Timing | [Play](./games/game-0391.html) |
| 0392 | Brine Brigadier | Strategy / Naval Blockade Tactics | [Play](./games/game-0392.html) |
| 0393 | Cobalt Courier | Puzzle / Delivery Route Optimization | [Play](./games/game-0393.html) |
| 0394 | Dune Diplomat | Strategy / Negotiation Choices | [Play](./games/game-0394.html) |
| 0395 | Ember Acrobat | Rhythm / Beat Leap Timing | [Play](./games/game-0395.html) |
| 0396 | Fjord Forager | Arcade / Foraging Identification | [Play](./games/game-0396.html) |
| 0397 | Granite Gardener | Puzzle / Stone Pushing | [Play](./games/game-0397.html) |
| 0398 | Harbor Harpist | Rhythm / Melody Matching | [Play](./games/game-0398.html) |
| 0399 | Ivory Inventor | Puzzle / Contraption Wiring | [Play](./games/game-0399.html) |
| 0400 | Jubilee Jester | Arcade / Balloon Pop Precision | [Play](./games/game-0400.html) |



## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
