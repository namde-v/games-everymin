# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 10
- **Latest game:** 0010 — Skyline Leap
- **Current volume:** 001 (Games 0001 to 0100)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0010 (10 so far, up to 0100) | [catalogs/readme-001.md](./catalogs/readme-001.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 001

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0001 | Starfall Vanguard | Arcade / Space Shmup | [Play](./games/game-0001.html) |
| 0002 | Crate Keeper | Puzzle / Sokoban Logic | [Play](./games/game-0002.html) |
| 0003 | Ember Bastion | Strategy / Micro Tower Defense | [Play](./games/game-0003.html) |
| 0004 | Pulse Tap | Rhythm / Beat Timing | [Play](./games/game-0004.html) |
| 0005 | Mirror Maze | Puzzle / Laser Reflection | [Play](./games/game-0005.html) |
| 0006 | Slingshot Summit | Precision / Trajectory Launcher | [Play](./games/game-0006.html) |
| 0007 | Dune Dash | Arcade / Line Runner | [Play](./games/game-0007.html) |
| 0008 | Gem Cascade | Puzzle / Sliding Match | [Play](./games/game-0008.html) |
| 0009 | Haven Colony | Simulation / Resource Allocator | [Play](./games/game-0009.html) |
| 0010 | Skyline Leap | Platformer / Precision | [Play](./games/game-0010.html) |

## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
