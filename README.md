# tiny-chess-01 work files

Work files for the tiny-chess-01 chess engine (Mate Book + Trap-Beam Search), split into two parts because each is under 25 MB.

Download both parts, then rejoin and extract:

```sh
cat tiny-chess-01-workfiles.part00 tiny-chess-01-workfiles.part01 > tiny-chess-01-workfiles.tar.gz
tar xzf tiny-chess-01-workfiles.tar.gz
```

Contents: beam.py, beam2.py, merge_best.py, assemble.py, validate.py, replay.py, oracle, all trial-0 mate books, the competition kit, Stockfish, and STRATEGI.md. Best so far: 171 plies, spare 1029.
