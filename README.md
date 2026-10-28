# games-everymin

A continuously growing collection of fully offline, single-file HTML5 games. Every game is one `.html` file with inline CSS and JavaScript, procedural Web Audio sound, and Canvas 2D / DOM graphics — no CDNs, no external assets, no build step. Open any game file directly in a browser and play.

## Dashboard

- **Total games:** 70
- **Latest game:** 0070 — Lantern Labyrinth
- **Current volume:** 001 (Games 0001 to 0100)
- **Production cycle:** 10 new games every 5 minutes, in distinct genres

## Volume index

| Volume | Games | Catalog |
|--------|-------|---------|
| 001 | 0001–0070 (70 so far, up to 0100) | [catalogs/readme-001.md](./catalogs/readme-001.md) |

Next volumes are created every 100 games: Volume 002 covers 0101–0200, Volume 003 covers 0201–0300, and so on.

## Structure

```
games-everymin/
├── games/                  # All game-XXXX.html files
├── catalogs/               # Partitioned indexes, 100 games per file
├── assets/                 # Optional purely offline assets (inline data/SVGs preferred)
└── README.md               # This dashboard
```

## Latest batch — Batch 007

| # | Game Title | Genre | Play |
|---|------------|-------|------|
| 0061 | Frostbite Frontier | Arcade / Ice Rescue | [Play](./games/game-0061.html) |
| 0062 | Glyph Grove | Puzzle / Rune Path Logic | [Play](./games/game-0062.html) |
| 0063 | Railway Rendezvous | Strategy / Train Yard Scheduler | [Play](./games/game-0063.html) |
| 0064 | Beat Botanist | Rhythm / Garden Groove | [Play](./games/game-0064.html) |
| 0065 | Magnet Minefield | Arcade / Polarity Action | [Play](./games/game-0065.html) |
| 0066 | Clockwork Courier | Puzzle / Gear Route Logic | [Play](./games/game-0066.html) |
| 0067 | Desert Drone Dash | Arcade / Canyon Racer | [Play](./games/game-0067.html) |
| 0068 | Orbit Orchard | Strategy / Asteroid Farming | [Play](./games/game-0068.html) |
| 0069 | Echo Chamber | Rhythm / Memory Echo | [Play](./games/game-0069.html) |
| 0070 | Lantern Labyrinth | Puzzle / Mirror Light Maze | [Play](./games/game-0070.html) |

## Quality standard

Every game must have: a title screen, Start button, How-to-Play instructions, a score/lives/status HUD, a definitive Win / Game Over state with instant Restart, and keyboard + mouse + touch controls.
