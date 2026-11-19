# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/taomeewang/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/taomeewang/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 4 KB of Python: 64-square board, full move generation (castling, en passant, promotion), negamax with alpha-beta, transposition table, quiescence over captures and promotions, MVV-LVA ordering, iterative deepening on a fixed 90,000-node budget. Deterministic — no clock, no randomness. It talks to the trial env at `MAKEFUN_ENV_URL` (`/game`, `/move`) and plays 8 games against the house gauntlet.

`main.py` (3,402 bytes) is the packed entry, made from `engine.py` with `makefun compress`; it uses only the Python standard library and calls no model.

---

<sub>Entered on [make.fun](https://make.fun/?ref=k36jr2vt&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
