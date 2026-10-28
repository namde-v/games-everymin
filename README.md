# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 750
- **Latest game:** 0750 — Meteor Shower Defender
- **Current volume:** 008 (Games 0701 to 0800) — in progress (50 of 100)
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
| 008 | 0701–0800 (50, in progress) | [catalogs/readme-008.md](./catalogs/readme-008.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 075

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0741 | Volcano Ash Runner | Arcade / Lava Dodge Runner | [Play](./games/game-0741.html) |
| 0742 | Mirror Maze Light Bender | Puzzle / Mirror Reflection Logic | [Play](./games/game-0742.html) |
| 0743 | Orchard Harvest Planner | Strategy / Farm Planning | [Play](./games/game-0743.html) |
| 0744 | Samba Street Drummer | Rhythm / Samba Beat | [Play](./games/game-0744.html) |
| 0745 | Deep Sea Pearl Diver | Arcade / Underwater Collection | [Play](./games/game-0745.html) |
| 0746 | Rune Stone Decoder | Puzzle / Rune Sequence Logic | [Play](./games/game-0746.html) |
| 0747 | Mountain Rescue Dispatcher | Strategy / Rescue Coordination | [Play](./games/game-0747.html) |
| 0748 | Flamenco Castanet Tempo | Rhythm / Castanet Timing | [Play](./games/game-0748.html) |
| 0749 | Windmill Blade Balancer | Precision / Windmill Balance Timing | [Play](./games/game-0749.html) |
| 0750 | Meteor Shower Defender | Arcade / Meteor Defense Shooter | [Play](./games/game-0750.html) |
## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
