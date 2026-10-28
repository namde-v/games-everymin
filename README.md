# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 320
- **Latest game:** 0320 — Fossil Finder
- **Current volume:** 004 (Games 0301 to 0400)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (100, complete) | [catalogs/readme-002.md](./catalogs/readme-002.md) |
| 003 | 0201–0300 (100, complete) | [catalogs/readme-003.md](./catalogs/readme-003.md) |
| 004 | 0301–0400 (20 so far) | [catalogs/readme-004.md](./catalogs/readme-004.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 032

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0311 | Ember Escape | Arcade / Flame Runner | [Play](./games/game-0311.html) |
| 0312 | Mirror Maze | Puzzle / Laser Reflection | [Play](./games/game-0312.html) |
| 0313 | Sandstone Sovereign | Strategy / Desert Kingdom | [Play](./games/game-0313.html) |
| 0314 | Drum Grove | Rhythm / Percussion Garden | [Play](./games/game-0314.html) |
| 0315 | Anchor Ace | Precision / Docking Timing | [Play](./games/game-0315.html) |
| 0316 | Rune Riddle | Puzzle / Rune Decoding | [Play](./games/game-0316.html) |
| 0317 | Lighthouse Keeper | Strategy / Coastal Management | [Play](./games/game-0317.html) |
| 0318 | Starlight Skater | Arcade / Cosmic Skating | [Play](./games/game-0318.html) |
| 0319 | Pendulum Pilot | Precision / Swing Physics | [Play](./games/game-0319.html) |
| 0320 | Fossil Finder | Puzzle / Archaeology Dig | [Play](./games/game-0320.html) |

## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
