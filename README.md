# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 470
- **Latest game:** 0470 — Nebula Navigator
- **Current volume:** 005 (Games 0401 to 0500)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (100, complete) | [catalogs/readme-002.md](./catalogs/readme-002.md) |
| 003 | 0201–0300 (100, complete) | [catalogs/readme-003.md](./catalogs/readme-003.md) |
| 004 | 0301–0400 (100, complete) | [catalogs/readme-004.md](./catalogs/readme-004.md) |
| 005 | 0401–0500 (70 so far) | [catalogs/readme-005.md](./catalogs/readme-005.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 047

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0461 | Ember Engineer | Strategy / Foundry Line Management | [Play](./games/game-0461.html) |
| 0462 | Fjord Fisher | Arcade / Ice-Hole Fishing Reflex | [Play](./games/game-0462.html) |
| 0463 | Glyph Gardener | Puzzle / Rune Garden Matching | [Play](./games/game-0463.html) |
| 0464 | Harbor Harmonizer | Rhythm / Dock Bell Timing | [Play](./games/game-0464.html) |
| 0465 | Iron Infiltrator | Action / Stealth Vault Runner | [Play](./games/game-0465.html) |
| 0466 | Jungle Juggler | Arcade / Vine Fruit Catching | [Play](./games/game-0466.html) |
| 0467 | Kepler Keeper | Puzzle / Orbital Ring Sorting | [Play](./games/game-0467.html) |
| 0468 | Lagoon Legislator | Strategy / Reef Council Simulation | [Play](./games/game-0468.html) |
| 0469 | Metronome Miner | Rhythm / Beat-Driven Digging | [Play](./games/game-0469.html) |
| 0470 | Nebula Navigator | Action / Starfield Asteroid Weaving | [Play](./games/game-0470.html) |

## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
