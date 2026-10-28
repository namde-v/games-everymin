# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 110
- **Latest game:** 0110 — Canyon Catapult
- **Current volume:** 002 (Games 0101 to 0200)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (10 so far) | [catalogs/readme-002.md](./catalogs/readme-002.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 011

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0101 | Ember Escort | Arcade / Flame Escort | [Play](./games/game-0101.html) |
| 0102 | Locksmith's Ledger | Puzzle / Tumbler Lock Logic | [Play](./games/game-0102.html) |
| 0103 | Beacon Builder | Strategy / Lighthouse Network | [Play](./games/game-0103.html) |
| 0104 | Drumline Dynamo | Rhythm / Marching Beat | [Play](./games/game-0104.html) |
| 0105 | Anchor Aim | Precision / Pendulum Drop | [Play](./games/game-0105.html) |
| 0106 | Spore Sprinter | Arcade / Forest Runner | [Play](./games/game-0106.html) |
| 0107 | Circuit Courier | Puzzle / Circuit Routing | [Play](./games/game-0107.html) |
| 0108 | Oasis Overseer | Strategy / Desert Water Management | [Play](./games/game-0108.html) |
| 0109 | Starlight Sonata | Rhythm / Falling-Note Piano | [Play](./games/game-0109.html) |
| 0110 | Canyon Catapult | Precision / Trajectory Launch | [Play](./games/game-0110.html) |

## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
