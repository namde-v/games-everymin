# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 700
- **Latest game:** 0700 — Sky Lantern Festival
- **Current volume:** 007 (Games 0601 to 0700) — complete (100 of 100)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (100, complete) | [catalogs/readme-002.md](./catalogs/readme-002.md) |
| 003 | 0201–0300 (100, complete) | [catalogs/readme-003.md](./catalogs/readme-003.md) |
| 004 | 0301–0400 (100, complete) | [catalogs/readme-004.md](./catalogs/readme-004.md) |
| 005 | 0401–0500 (100, complete) | [catalogs/readme-005.md](./catalogs/readme-005.md) |
| 006 | 0501–0600 (100, complete) | [catalogs/readme-006.md](./catalogs/readme-006.md) |
| 007 | 0601–0700 (100, complete) | [catalogs/readme-007.md](./catalogs/readme-007.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 070

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0691 | Volcano Lava Runner | Arcade / Lava Dodging Runner | [Play](./games/game-0691.html) |
| 0692 | Starlight Constellation Connect | Puzzle / Constellation Drawing Logic | [Play](./games/game-0692.html) |
| 0693 | Desert Oasis Trader | Strategy / Caravan Trading Simulation | [Play](./games/game-0693.html) |
| 0694 | Tide Pool Crab Catcher | Precision / Timing Net Catch | [Play](./games/game-0694.html) |
| 0695 | Windmill Power Grid | Strategy / Energy Routing Puzzle | [Play](./games/game-0695.html) |
| 0696 | Echo Cave Explorer | Puzzle / Sound Echo Maze | [Play](./games/game-0696.html) |
| 0697 | Snowy Yeti Snowball Toss | Precision / Snowball Aim Toss | [Play](./games/game-0697.html) |
| 0698 | Clock Tower Bell Ringer | Rhythm / Bell Timing Sequence | [Play](./games/game-0698.html) |
| 0699 | Mushroom Forest Forager | Arcade / Foraging Collection Avoidance | [Play](./games/game-0699.html) |
| 0700 | Sky Lantern Festival | Arcade / Lantern Release Flight | [Play](./games/game-0700.html) |
## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
