# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 180
- **Latest game:** 0180 — Lasso Roundup
- **Current volume:** 002 (Games 0101 to 0200)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (80 so far) | [catalogs/readme-002.md](./catalogs/readme-002.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 018

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0171 | Kite Kraze | Arcade / Storm Kite Dodger | [Play](./games/game-0171.html) |
| 0172 | Locksmith Labyrinth | Puzzle / Key-and-Lock Maze Logic | [Play](./games/game-0172.html) |
| 0173 | Oasis Operator | Strategy / Desert Oasis Management | [Play](./games/game-0173.html) |
| 0174 | Polka Party | Rhythm / Accordion Beat Timing | [Play](./games/game-0174.html) |
| 0175 | Boulder Bounce | Precision / Boulder Ricochet Aim | [Play](./games/game-0175.html) |
| 0176 | Skateboard Showdown | Arcade / Street Trick Runner | [Play](./games/game-0176.html) |
| 0177 | Constellation Connector | Puzzle / Star Pattern Logic | [Play](./games/game-0177.html) |
| 0178 | Submarine Salvage | Strategy / Deep-Sea Salvage Management | [Play](./games/game-0178.html) |
| 0179 | Choir Conductor | Rhythm / Choir Cue Conducting | [Play](./games/game-0179.html) |
| 0180 | Lasso Roundup | Precision / Lasso Targeting | [Play](./games/game-0180.html) |


## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
