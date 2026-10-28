# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 570
- **Latest game:** 0570 — Magnet Marbles
- **Current volume:** 006 (Games 0501 to 0600) — in progress (70 of 100)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (100, complete) | [catalogs/readme-002.md](./catalogs/readme-002.md) |
| 003 | 0201–0300 (100, complete) | [catalogs/readme-003.md](./catalogs/readme-003.md) |
| 004 | 0301–0400 (100, complete) | [catalogs/readme-004.md](./catalogs/readme-004.md) |
| 005 | 0401–0500 (100, complete) | [catalogs/readme-005.md](./catalogs/readme-005.md) |
| 006 | 0501–0600 (70 so far) | [catalogs/readme-006.md](./catalogs/readme-006.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 057

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0561 | Lantern Leap | Arcade / Lantern Tower Climber | [Play](./games/game-0561.html) |
| 0562 | Quarry Quilt | Puzzle / Gem Pattern Logic | [Play](./games/game-0562.html) |
| 0563 | Reef Restoration | Strategy / Coral Reef Management | [Play](./games/game-0563.html) |
| 0564 | Clockwork Clapper | Rhythm / Gear Beat Timing | [Play](./games/game-0564.html) |
| 0565 | Paper Plane Pilot | Precision / Wind Glide Aim | [Play](./games/game-0565.html) |
| 0566 | Bubble Bazaar | Arcade / Bubble Catcher | [Play](./games/game-0566.html) |
| 0567 | Locksmith's Ladder | Puzzle / Code Lock Logic | [Play](./games/game-0567.html) |
| 0568 | Windmill Village | Strategy / Village Energy Planning | [Play](./games/game-0568.html) |
| 0569 | Rainforest Rumble | Rhythm / Call-and-Response Drums | [Play](./games/game-0569.html) |
| 0570 | Magnet Marbles | Precision / Marble Flick Aim | [Play](./games/game-0570.html) |

## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
