# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 420
- **Latest game:** 0420 — Jade Juggler
- **Current volume:** 005 (Games 0401 to 0500)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (100, complete) | [catalogs/readme-002.md](./catalogs/readme-002.md) |
| 003 | 0201–0300 (100, complete) | [catalogs/readme-003.md](./catalogs/readme-003.md) |
| 004 | 0301–0400 (100, complete) | [catalogs/readme-004.md](./catalogs/readme-004.md) |
| 005 | 0401–0500 (20 so far) | [catalogs/readme-005.md](./catalogs/readme-005.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 042

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0411 | Amber Alchemist | Puzzle / Potion Mixing Sequence | [Play](./games/game-0411.html) |
| 0412 | Bramble Bandit | Arcade / Vine Swing Platformer | [Play](./games/game-0412.html) |
| 0413 | Coral Cartographer | Strategy / Reef Map Exploration | [Play](./games/game-0413.html) |
| 0414 | Dune Drifter | Arcade / Sandboard Descent | [Play](./games/game-0414.html) |
| 0415 | Ember Enchanter | Rhythm / Beat Spell Casting | [Play](./games/game-0415.html) |
| 0416 | Frost Falconer | Action / Aerial Dive Hunting | [Play](./games/game-0416.html) |
| 0417 | Granite Gardener | Strategy / Rock Garden Simulation | [Play](./games/game-0417.html) |
| 0418 | Harbor Harbinger | Puzzle / Signal Flag Decoding | [Play](./games/game-0418.html) |
| 0419 | Ivory Inventor | Puzzle / Clockwork Chain Reaction | [Play](./games/game-0419.html) |
| 0420 | Jade Juggler | Rhythm / Precision Juggling | [Play](./games/game-0420.html) |

## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
