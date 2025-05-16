# Sudoku Solver (Python)

This is a terminal-based Sudoku solver built with Python using a backtracking algorithm.

## How It Works

- Uses recursion and backtracking to try all valid number placements.
- Prints the board before and after solving.
- Input board is a 9x9 list of lists with 0 representing empty cells.

## How to Run

```bash
python sudoku_solver.py
```

## Example Board
```
5 3 . | . 7 . | . . .
6 . . | 1 9 5 | . . .
. 9 8 | . . . | . 6 .
------+-------+------
8 . . | . 6 . | . . 3
4 . . | 8 . 3 | . . 1
7 . . | . 2 . | . . 6
------+-------+------
. 6 . | . . . | 2 8 .
. . . | 4 1 9 | . . 5
. . . | . 8 . | . 7 9
```

## References

- [GeeksforGeeks - Backtracking](https://www.geeksforgeeks.org/sudoku-backtracking-7/)
