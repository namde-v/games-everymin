# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 710
- **Latest game:** 0710 — Firefly Meadow Catcher
- **Current volume:** 008 (Games 0701 to 0800) — in progress (10 of 100)
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
| 008 | 0701–0800 (10, in progress) | [catalogs/readme-008.md](./catalogs/readme-008.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 071

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0701 | Bamboo Panda Bounce | Arcade / Vertical Bounce Collection | [Play](./games/game-0701.html) |
| 0702 | Circuit Board Solder Puzzle | Puzzle / Circuit Tracing Logic | [Play](./games/game-0702.html) |
| 0703 | Highland Vineyard Scheduler | Strategy / Harvest Scheduling | [Play](./games/game-0703.html) |
| 0704 | Metronome March Parade | Rhythm / March Beat Timing | [Play](./games/game-0704.html) |
| 0705 | Comet Tail Sketcher | Precision / Orbital Slingshot Aim | [Play](./games/game-0705.html) |
| 0706 | River Rapids Raft Rescue | Arcade / Rapids Steering Rescue | [Play](./games/game-0706.html) |
| 0707 | Ancient Rune Decoder | Puzzle / Symbol Sequence Decoding | [Play](./games/game-0707.html) |
| 0708 | Wildflower Hive Keeper | Strategy / Hive Resource Management | [Play](./games/game-0708.html) |
| 0709 | Paper Plane Wind Tunnel | Precision / Glider Ring Flight | [Play](./games/game-0709.html) |
| 0710 | Firefly Meadow Catcher | Arcade / Firefly Catch Timing | [Play](./games/game-0710.html) |
## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
