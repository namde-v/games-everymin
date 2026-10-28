# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 80
- **Latest game:** 0080 — Glacier Gardener
- **Current volume:** 001 (Games 0001 to 0100)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0080 (80 so far, up to 0100) | [catalogs/readme-001.md](./catalogs/readme-001.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 008

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0071 | Tempest Trawler | Arcade / Storm Fishing | [Play](./games/game-0071.html) |
| 0072 | Mosaic Mason | Puzzle / Mosaic Tile Logic | [Play](./games/game-0072.html) |
| 0073 | Portside Planner | Strategy / Dock Scheduler | [Play](./games/game-0073.html) |
| 0074 | Drumline Dunes | Rhythm / Desert Beat Timing | [Play](./games/game-0074.html) |
| 0075 | Cinder Sprint | Arcade / Lava Lane Runner | [Play](./games/game-0075.html) |
| 0076 | Knot Garden | Puzzle / Rope Untangle Logic | [Play](./games/game-0076.html) |
| 0077 | Junkyard Tycoon | Strategy / Scrap Recycling Sim | [Play](./games/game-0077.html) |
| 0078 | Pulse Paddler | Precision / Timed River Paddle | [Play](./games/game-0078.html) |
| 0079 | Starlight Sniper | Precision / Constellation Aim | [Play](./games/game-0079.html) |
| 0080 | Glacier Gardener | Strategy / Ice Farm Sim | [Play](./games/game-0080.html) |

## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
