# tiny-chess-01

A chess engine in under 4 KB of Python: negamax alpha-beta with PVS, a
transposition table, quiescence search, null-move pruning and late-move
reductions, tapered piece-square tables and pawn-structure scoring, playing
at a fixed 30,000-node budget for full determinism.

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/Gas2405/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/Gas2405/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

Bounty: https://make.fun/bounty/tiny-chess-01

Local practice results (kit practice instances, 6 games each, this exact
build): trial-0 Elo 1809, trial-1 Elo 1099, trial-2 Elo 1364 — mean 1424.
Two runs of trial-0 produced byte-identical game records.
