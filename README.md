[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/abcdefgwy/tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/abcdefgwy/tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

# Tiny Chess Engine

Ultra-compact 4 KB Python chess engine for the make.fun tiny-chess-01 competition.

## Architecture
- **Board**: Rank-only flip 10x12 representation
- **Evaluation**: Full 12-table PeSTO Piece-Square Tables with tapered phase interpolation
- **Search**: PVS + Quiescence Search + Null Move Pruning + Late Move Reductions
- **Budget**: Deterministic fixed-node search (zero wall-clock dependence)
