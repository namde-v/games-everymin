# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 250
- **Latest game:** 0250 — Bowling Blitz
- **Current volume:** 003 (Games 0201 to 0300)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (100, complete) | [catalogs/readme-002.md](./catalogs/readme-002.md) |
| 003 | 0201–0250 (50 so far, up to 0300) | [catalogs/readme-003.md](./catalogs/readme-003.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 025

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0241 | Kite Kraze | Arcade / Kite Flying | [Play](./games/game-0241.html) |
| 0242 | Rune Relay | Puzzle / Rune Sequence Memory | [Play](./games/game-0242.html) |
| 0243 | Bakery Baron | Strategy / Bakery Management | [Play](./games/game-0243.html) |
| 0244 | Marimba Marathon | Rhythm / Marimba Note Run | [Play](./games/game-0244.html) |
| 0245 | Darts Dynamo | Precision / Darts | [Play](./games/game-0245.html) |
| 0246 | Rocket Rodeo | Arcade / Asteroid Rider | [Play](./games/game-0246.html) |
| 0247 | Circuit Splicer | Puzzle / Circuit Routing | [Play](./games/game-0247.html) |
| 0248 | Harbor Haven | Strategy / Port Management | [Play](./games/game-0248.html) |
| 0249 | Accordion Alley | Rhythm / Accordion Beat | [Play](./games/game-0249.html) |
| 0250 | Bowling Blitz | Precision / Bowling | [Play](./games/game-0250.html) |


## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
