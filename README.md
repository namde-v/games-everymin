# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 50
- **Latest game:** 0050 — Metronome Mayhem
- **Current volume:** 001 (Games 0001 to 0100)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0050 (50 so far, up to 0100) | [catalogs/readme-001.md](./catalogs/readme-001.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 005

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0041 | Solar Sailor | Arcade / Solar Wind Surfing | [Play](./games/game-0041.html) |
| 0042 | Ink Trail | Puzzle / Path Drawing Logic | [Play](./games/game-0042.html) |
| 0043 | Oasis Outpost | Simulation / Desert Management | [Play](./games/game-0043.html) |
| 0044 | Beat Smith | Rhythm / Forge Timing | [Play](./games/game-0044.html) |
| 0045 | Curling Clash | Precision / Ice Curling | [Play](./games/game-0045.html) |
| 0046 | Droid Depot | Strategy / Factory Automation | [Play](./games/game-0046.html) |
| 0047 | Bubble Bounty | Arcade / Bubble Shooter | [Play](./games/game-0047.html) |
| 0048 | Number Nexus | Puzzle / Number Merge Logic | [Play](./games/game-0048.html) |
| 0049 | Tide Trader | Simulation / Sea Trading | [Play](./games/game-0049.html) |
| 0050 | Metronome Mayhem | Rhythm / Tempo Shift | [Play](./games/game-0050.html) |

## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
