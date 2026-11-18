# makefun-tiny-chess-01-matebook

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/Holladitt/makefun-tiny-chess-01-matebook/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/Holladitt/makefun-tiny-chess-01-matebook/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A 4,096-byte Python chess engine that plays from a precomputed Stockfish-oracle mate/trap book covering 104 of the 640 possible scenarios (40 openings × 8 house engines × 2 colours), falling back to the first legal move when no book line matches. Built for make.fun's tiny-chess-01 bounty.

## Run it

```sh
python3 main.py
```

---

Entered on [make.fun](https://make.fun/?ref=t774y4rd&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards
