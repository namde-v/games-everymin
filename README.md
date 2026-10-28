# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 690
- **Latest game:** 0690 — Coral Reef Turtle Race
- **Current volume:** 007 (Games 0601 to 0700) — in progress (90 of 100)
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
| 007 | 0601–0700 (90, in progress) | [catalogs/readme-007.md](./catalogs/readme-007.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 069

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0681 | Aurora Ice Skater Glide | Arcade / Ice Skating Momentum | [Play](./games/game-0681.html) |
| 0682 | Clockwork Gear Lock | Puzzle / Gear Rotation Logic | [Play](./games/game-0682.html) |
| 0683 | Harbor Crane Stacker | Strategy / Cargo Crane Logistics | [Play](./games/game-0683.html) |
| 0684 | Jungle Drum Circle | Rhythm / Drum Pattern Memory | [Play](./games/game-0684.html) |
| 0685 | Falcon Dive Hunter | Precision / Dive Timing Hunt | [Play](./games/game-0685.html) |
| 0686 | Ant Trail Architect | Puzzle / Trail Drawing Logic | [Play](./games/game-0686.html) |
| 0687 | Gemstone Mine Match | Puzzle / Match-3 Swap Logic | [Play](./games/game-0687.html) |
| 0688 | Airport Runway Controller | Strategy / Air Traffic Routing | [Play](./games/game-0688.html) |
| 0689 | Neon Beat Boxer | Rhythm / Beat Punch Timing | [Play](./games/game-0689.html) |
| 0690 | Coral Reef Turtle Race | Arcade / Underwater Racing | [Play](./games/game-0690.html) |
## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
