# Tiny Chess Engine

Ultra-compact 4 KB Python chess engine for the make.fun tiny-chess-01 competition.

## Architecture
- **Board**: Rank-only flip 10x12 representation
- **Evaluation**: Full 12-table PeSTO Piece-Square Tables with tapered phase interpolation
- **Search**: PVS + Quiescence Search + Null Move Pruning + Late Move Reductions
- **Budget**: Deterministic fixed-node search (zero wall-clock dependence)
