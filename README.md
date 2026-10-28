# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 460
- **Latest game:** 0460 — Summit Skier
- **Current volume:** 005 (Games 0401 to 0500)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (100, complete) | [catalogs/readme-002.md](./catalogs/readme-002.md) |
| 003 | 0201–0300 (100, complete) | [catalogs/readme-003.md](./catalogs/readme-003.md) |
| 004 | 0301–0400 (100, complete) | [catalogs/readme-004.md](./catalogs/readme-004.md) |
| 005 | 0401–0500 (60 so far) | [catalogs/readme-005.md](./catalogs/readme-005.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 046

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0451 | Prism Pilot | Arcade / Light-Beam Mirror Dodging | [Play](./games/game-0451.html) |
| 0452 | Quartz Quest | Puzzle / Gem Vein Tracing | [Play](./games/game-0452.html) |
| 0453 | River Ranger | Strategy / Watershed Flow Management | [Play](./games/game-0453.html) |
| 0454 | Solar Scribe | Rhythm / Sunbeam Beat Tracing | [Play](./games/game-0454.html) |
| 0455 | Tempest Surfer | Action / Wave-Surfing Rescue | [Play](./games/game-0455.html) |
| 0456 | Umbra Unlocker | Puzzle / Shadow Lock Decoding | [Play](./games/game-0456.html) |
| 0457 | Vapor Voyager | Strategy / Airship Trade Expedition | [Play](./games/game-0457.html) |
| 0458 | Willow Whisperer | Rhythm / Wind-Chime Precision | [Play](./games/game-0458.html) |
| 0459 | Xenon Xplorer | Arcade / Gravity-Slingshot Orbit | [Play](./games/game-0459.html) |
| 0460 | Summit Skier | Action / Avalanche Slope Runner | [Play](./games/game-0460.html) |

## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
