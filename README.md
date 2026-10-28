# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 350
- **Latest game:** 0350 — Botanical Blueprint
- **Current volume:** 004 (Games 0301 to 0400)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (100, complete) | [catalogs/readme-002.md](./catalogs/readme-002.md) |
| 003 | 0201–0300 (100, complete) | [catalogs/readme-003.md](./catalogs/readme-003.md) |
| 004 | 0301–0400 (50 so far) | [catalogs/readme-004.md](./catalogs/readme-004.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 035

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0341 | Avalanche Aviator | Arcade / Mountain Flight | [Play](./games/game-0341.html) |
| 0342 | Kaleido Keys | Puzzle / Color Sequence | [Play](./games/game-0342.html) |
| 0343 | Timber Tycoon | Strategy / Forestry Management | [Play](./games/game-0343.html) |
| 0344 | Pulse Pogo | Rhythm / Beat Hopping | [Play](./games/game-0344.html) |
| 0345 | Tidepool Trawler | Arcade / Deep-Sea Fishing | [Play](./games/game-0345.html) |
| 0346 | Enigma Engine | Puzzle / Code Machine | [Play](./games/game-0346.html) |
| 0347 | Dockside Dynamo | Strategy / Port Logistics | [Play](./games/game-0347.html) |
| 0348 | Samba Steps | Rhythm / Dance Timing | [Play](./games/game-0348.html) |
| 0349 | Canyon Courier | Arcade / Delivery Dash | [Play](./games/game-0349.html) |
| 0350 | Botanical Blueprint | Puzzle / Garden Layout | [Play](./games/game-0350.html) |


## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
