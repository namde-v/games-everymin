# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 280
- **Latest game:** 0280 — Horseshoe Hero
- **Current volume:** 003 (Games 0201 to 0300)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (100, complete) | [catalogs/readme-002.md](./catalogs/readme-002.md) |
| 003 | 0201–0280 (80 so far, up to 0300) | [catalogs/readme-003.md](./catalogs/readme-003.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 028

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0271 | Penguin Plunge | Arcade / Ice Slide Dodging | [Play](./games/game-0271.html) |
| 0272 | Mosaic Maker | Puzzle / Tile Pattern Matching | [Play](./games/game-0272.html) |
| 0273 | Lighthouse Keeper | Strategy / Coastal Rescue Management | [Play](./games/game-0273.html) |
| 0274 | Flute Frenzy | Rhythm / Wind Melody Timing | [Play](./games/game-0274.html) |
| 0275 | Slingshot Safari | Precision / Slingshot Launch | [Play](./games/game-0275.html) |
| 0276 | Volcano Vault | Arcade / Lava Leap Platformer | [Play](./games/game-0276.html) |
| 0277 | Cipher Castle | Puzzle / Codebreaking Logic | [Play](./games/game-0277.html) |
| 0278 | Zoo Zookeeper | Strategy / Animal Habitat Management | [Play](./games/game-0278.html) |
| 0279 | Banjo Bonanza | Rhythm / String Strumming Timing | [Play](./games/game-0279.html) |
| 0280 | Horseshoe Hero | Precision / Horseshoe Toss | [Play](./games/game-0280.html) |


## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
