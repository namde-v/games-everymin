# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 730
- **Latest game:** 0730 — Glassblower Breath Control
- **Current volume:** 008 (Games 0701 to 0800) — in progress (30 of 100)
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
| 008 | 0701–0800 (30, in progress) | [catalogs/readme-008.md](./catalogs/readme-008.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 073

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0721 | Coral Reef Diver Quest | Arcade / Underwater Treasure Dive | [Play](./games/game-0721.html) |
| 0722 | Shadow Puppet Theater | Puzzle / Shadow Shape Matching | [Play](./games/game-0722.html) |
| 0723 | Skyport Air Traffic Director | Strategy / Air Traffic Routing | [Play](./games/game-0723.html) |
| 0724 | Echo Cave Clapper | Rhythm / Echo Beat Memory | [Play](./games/game-0724.html) |
| 0725 | Blacksmith Forge Hammer | Precision / Hammer Strike Timing | [Play](./games/game-0725.html) |
| 0726 | Mushroom Grove Forager | Arcade / Forage Maze Collection | [Play](./games/game-0726.html) |
| 0727 | Wordfall Letter Cascade | Puzzle / Falling Word Builder | [Play](./games/game-0727.html) |
| 0728 | Railway Switch Yard | Strategy / Train Switching | [Play](./games/game-0728.html) |
| 0729 | Rain Tap Symphony | Rhythm / Rain Drop Catch Beat | [Play](./games/game-0729.html) |
| 0730 | Glassblower Breath Control | Precision / Breath Pressure Crafting | [Play](./games/game-0730.html) |
## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
