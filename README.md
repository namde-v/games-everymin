# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 190
- **Latest game:** 0190 — Dartboard Duel
- **Current volume:** 002 (Games 0101 to 0200)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (90 so far) | [catalogs/readme-002.md](./catalogs/readme-002.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 019

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0181 | Canyon Crasher | Arcade / River Raft Dodger | [Play](./games/game-0181.html) |
| 0182 | Prism Pathfinder | Puzzle / Prism Refraction Routing | [Play](./games/game-0182.html) |
| 0183 | Tea House Tycoon | Strategy / Tea House Management | [Play](./games/game-0183.html) |
| 0184 | Steel Drum Serenade | Rhythm / Steelpan Beat Timing | [Play](./games/game-0184.html) |
| 0185 | Boomerang Bounty | Precision / Boomerang Throw Aim | [Play](./games/game-0185.html) |
| 0186 | Penguin Plunge | Arcade / Ice Slide Collector | [Play](./games/game-0186.html) |
| 0187 | Word Well | Puzzle / Falling Letter Word Builder | [Play](./games/game-0187.html) |
| 0188 | Terminal Tycoon | Strategy / Airport Terminal Management | [Play](./games/game-0188.html) |
| 0189 | Folk Fiddle Fest | Rhythm / Fiddle Tune Timing | [Play](./games/game-0189.html) |
| 0190 | Dartboard Duel | Precision / Moving Dartboard Aim | [Play](./games/game-0190.html) |


## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
