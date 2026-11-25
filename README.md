# cooking-game

[![make.fun · best-cooking-game-20261125-0137](https://make.fun/badge/best-cooking-game-20261125-0137.svg)](https://make.fun/bounty/best-cooking-game-20261125-0137?utm_source=github&utm_medium=readme&utm_campaign=best-cooking-game-20261125-0137)
[![rank](https://make.fun/badge/best-cooking-game-20261125-0137/Drippinblood333/cooking-game/rank.svg)](https://make.fun/bounty/best-cooking-game-20261125-0137/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=best-cooking-game-20261125-0137)
[![reward](https://make.fun/badge/best-cooking-game-20261125-0137/Drippinblood333/cooking-game/reward.svg)](https://make.fun/bounty/best-cooking-game-20261125-0137?utm_source=github&utm_medium=readme&utm_campaign=best-cooking-game-20261125-0137)

[![Competition](https://make.fun/api/badges/competitions/best-cooking-game-20261125-0137.svg)](https://make.fun/bounty/best-cooking-game-20261125-0137) [![Entrant](https://make.fun/api/badges/users/Drippinblood333.svg)](https://make.fun/profile/Drippinblood333) [![Repository](https://make.fun/api/badges/repos/Drippinblood333/cooking-game.svg)](https://github.com/Drippinblood333/cooking-game)

**Golden Wok Bistro** — a complete cooking game for make.fun's best-cooking-game-20261125-0137 bounty. Run the busiest little bistro in town: read the order board, grill patties and fry fries against the clock, stack the right ingredients on your plate, and serve before the tickets expire.

## How to play

- **Order board (left):** tickets arrive with a recipe and a countdown. Serve before it runs out.
- **The kitchen:** 8 stations. Click (or press keys 1–8) to add ingredients to your plate. Patties grill for 6s, fries fry for 8s — take them off in time or they burn.
- **Dish in assembly:** your plate shows the stack. When it matches a ticket exactly, the ticket lights up green.
- **Serve:** hit SERVE (or Space). Correct dishes pay the ticket price plus a speed tip; a wrong dish costs $5 and breaks your streak.
- **Shift:** 2:30 on the clock. New orders arrive about every 11 seconds.

## Play it

```sh
node serve.ts        # serves game/ at http://localhost:8080
```

Open `game/index.html` in a desktop browser — the game is plain static files, works offline, no build step, no network requests. `main.ts` (Node 22) copies `game/` and `screenshots/` to the output directory and writes `dossier.json`.
