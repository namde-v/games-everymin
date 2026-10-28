# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 330
- **Latest game:** 0330 — Lantern Logic
- **Current volume:** 004 (Games 0301 to 0400)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (100, complete) | [catalogs/readme-002.md](./catalogs/readme-002.md) |
| 003 | 0201–0300 (100, complete) | [catalogs/readme-003.md](./catalogs/readme-003.md) |
| 004 | 0301–0400 (30 so far) | [catalogs/readme-004.md](./catalogs/readme-004.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 033

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0321 | Solar Swooper | Arcade / Sun-Diving Collector | [Play](./games/game-0321.html) |
| 0322 | Prism Pipes | Puzzle / Light-Routing | [Play](./games/game-0322.html) |
| 0323 | Vineyard Baron | Strategy / Vineyard Management | [Play](./games/game-0323.html) |
| 0324 | Beat Blacksmith | Rhythm / Hammer Beat | [Play](./games/game-0324.html) |
| 0325 | Geyser Glider | Arcade / Geyser Gliding | [Play](./games/game-0325.html) |
| 0326 | Cipher Canyon | Puzzle / Symbol Cipher | [Play](./games/game-0326.html) |
| 0327 | Aurora Outpost | Strategy / Arctic Station | [Play](./games/game-0327.html) |
| 0328 | Tempo Tailor | Rhythm / Sewing Beat | [Play](./games/game-0328.html) |
| 0329 | Cinder Climber | Arcade / Volcano Climbing | [Play](./games/game-0329.html) |
| 0330 | Lantern Logic | Puzzle / Lantern Grid | [Play](./games/game-0330.html) |


## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
