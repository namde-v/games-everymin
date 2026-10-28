# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 200
- **Latest game:** 0200 — Catapult Castle
- **Current volume:** 002 (Games 0101 to 0200)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (100, complete) | [catalogs/readme-002.md](./catalogs/readme-002.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 020

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0191 | Magma Marathon | Arcade / Lava Runner | [Play](./games/game-0191.html) |
| 0192 | Rune Relay | Puzzle / Rune Sequence Logic | [Play](./games/game-0192.html) |
| 0193 | Seaport Supervisor | Strategy / Port Management | [Play](./games/game-0193.html) |
| 0194 | Timpani Thunder | Rhythm / Drum Beat Timing | [Play](./games/game-0194.html) |
| 0195 | Crossbow Clash | Precision / Crossbow Targeting | [Play](./games/game-0195.html) |
| 0196 | Bubble Bouncer | Arcade / Bubble Bounce Platformer | [Play](./games/game-0196.html) |
| 0197 | Mirror Mansion | Puzzle / Mirror Reflection Logic | [Play](./games/game-0197.html) |
| 0198 | Bakery Blitz | Strategy / Bakery Order Management | [Play](./games/game-0198.html) |
| 0199 | Marimba Melody | Rhythm / Marimba Note Matching | [Play](./games/game-0199.html) |
| 0200 | Catapult Castle | Precision / Catapult Siege Aim | [Play](./games/game-0200.html) |


## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
