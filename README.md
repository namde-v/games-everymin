# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 240
- **Latest game:** 0240 — Curling Champion
- **Current volume:** 003 (Games 0201 to 0300)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0100 (100, complete) | [catalogs/readme-001.md](./catalogs/readme-001.md) |
| 002 | 0101–0200 (100, complete) | [catalogs/readme-002.md](./catalogs/readme-002.md) |
| 003 | 0201–0240 (40 so far, up to 0300) | [catalogs/readme-003.md](./catalogs/readme-003.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 024

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0231 | Avalanche Ace | Arcade / Snowboard Downhill | [Play](./games/game-0231.html) |
| 0232 | Orbit Oracle | Puzzle / Gravity Orbit Logic | [Play](./games/game-0232.html) |
| 0233 | Tidepool Tycoon | Strategy / Tidepool Ecosystem Management | [Play](./games/game-0233.html) |
| 0234 | Xylophone Xpress | Rhythm / Xylophone Note Run | [Play](./games/game-0234.html) |
| 0235 | Boomerang Bounty | Precision / Boomerang Throwing | [Play](./games/game-0235.html) |
| 0236 | Coral Cruiser | Arcade / Submarine Reef Explorer | [Play](./games/game-0236.html) |
| 0237 | Lantern Labyrinth | Puzzle / Light Maze Logic | [Play](./games/game-0237.html) |
| 0238 | Windmill Warden | Strategy / Windmill Farm Management | [Play](./games/game-0238.html) |
| 0239 | Saxophone Soiree | Rhythm / Saxophone Note Run | [Play](./games/game-0239.html) |
| 0240 | Curling Champion | Precision / Curling Slide | [Play](./games/game-0240.html) |


## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
