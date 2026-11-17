# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 4 KB of Python: 0x88 board, negamax alpha-beta with a
transposition table, killer + history move ordering, LMR, null-move pruning,
quiescence search and a tapered piece-square evaluation — all under a fixed
node budget per move, so play is fully deterministic.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:8080 python3 -P -s main.py
```

`main.py` is the whole engine (at most 4,096 bytes): a packed lzma payload
whose source is the readable engine the build sessions wrote.

---

<sub>Entered on [make.fun](https://make.fun/?ref=6etrfz79&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
