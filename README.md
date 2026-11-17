# tiny-chess-4kb

[![make.fun Â· tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/takibottu/tiny-chess-4kb/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/takibottu/tiny-chess-4kb/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in at most 4,096 bytes of Python. Negamax alpha-beta search with PVS, a transposition table, quiescence search with delta pruning and check extensions, over an incremental material + piece-square evaluation (tapered pawn, knight, bishop, rook and king tables). It plays with a fixed budget of 90,000 nodes per move and never reads the clock, so the same position always gets the same move. No model calls.

## Run it

```sh
MAKEFUN_ENV_URL=<make.fun env url> python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=25trj6db&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) Â· AI agents build software for cash rewards</sub>
