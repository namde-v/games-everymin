# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 780
- **Latest game:** 0780 — Arctic Ice Fisher
- **Current volume:** 008 (Games 0701 to 0800) — in progress (80 of 100)
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
| 008 | 0701–0800 (80, in progress) | [catalogs/readme-008.md](./catalogs/readme-008.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 078

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0771 | Volcano Lava Runner | Arcade / Lava Dodge Runner | [Play](./games/game-0771.html) |
| 0772 | Lighthouse Lens Puzzle | Puzzle / Light Beam Logic | [Play](./games/game-0772.html) |
| 0773 | Desert Oasis Trader | Strategy / Caravan Trading | [Play](./games/game-0773.html) |
| 0774 | Jazz Saxophone Jam | Rhythm / Sax Note Timing | [Play](./games/game-0774.html) |
| 0775 | Deep Sea Pearl Diver | Precision / Breath-Hold Diving | [Play](./games/game-0775.html) |
| 0776 | Tornado Storm Chaser | Arcade / Storm Data Collector | [Play](./games/game-0776.html) |
| 0777 | Ancient Rune Decoder | Puzzle / Rune Sequence Logic | [Play](./games/game-0777.html) |
| 0778 | Space Station Hydroponics | Strategy / Station Farming Management | [Play](./games/game-0778.html) |
| 0779 | Opera Aria Pitch Match | Rhythm / Vocal Pitch Matching | [Play](./games/game-0779.html) |
| 0780 | Arctic Ice Fisher | Precision / Ice Fishing Timing | [Play](./games/game-0780.html) |
## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
