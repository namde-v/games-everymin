# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 260
- **Latest game:** 0260 — Archery Ace
- **Current volume:** 003 (Games 0201 to 0300)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (100, complete) | [catalogs/readme-002.md](./catalogs/readme-002.md) |
| 003 | 0201–0260 (60 so far, up to 0300) | [catalogs/readme-003.md](./catalogs/readme-003.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 026

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0251 | Corgi Canyon | Arcade / Corgi Canyon Runner | [Play](./games/game-0251.html) |
| 0252 | Hex Hive | Puzzle / Hex Tile Logic | [Play](./games/game-0252.html) |
| 0253 | Cactus Kingdom | Strategy / Desert Garden Management | [Play](./games/game-0253.html) |
| 0254 | Salsa Steps | Rhythm / Dance Step Timing | [Play](./games/game-0254.html) |
| 0255 | Javelin Journey | Precision / Javelin Throw | [Play](./games/game-0255.html) |
| 0256 | Mole Miner | Arcade / Underground Gem Digging | [Play](./games/game-0256.html) |
| 0257 | Lockpick Logic | Puzzle / Lock Mechanism Logic | [Play](./games/game-0257.html) |
| 0258 | Airship Admiral | Strategy / Airship Fleet Management | [Play](./games/game-0258.html) |
| 0259 | Beat Boxer | Rhythm / Beat Boxing | [Play](./games/game-0259.html) |
| 0260 | Archery Ace | Precision / Archery | [Play](./games/game-0260.html) |


## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
