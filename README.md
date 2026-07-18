# Cat Grid Step-by-Step Solver

A dependency-free, single-page walkthrough of a 10x10 cat-placement puzzle.

## Rules

Place 10 cats so that:

1. Every row contains exactly one cat.
2. Every column contains exactly one cat.
3. Every colored region contains exactly one cat.
4. Cats do not touch horizontally, vertically, or diagonally.

The app starts from the blank colored grid and demonstrates an exact row-ordered forward-checking/backtracking proof. It independently enumerates the puzzle at runtime and verifies that the solution is unique.

## Unique solution

`R1C3, R2C10, R3C4, R4C8, R5C5, R6C7, R7C9, R8C1, R9C6, R10C2`

Column sequence by row: `3, 10, 4, 8, 5, 7, 9, 1, 6, 2`.

## Run

Open `index.html` directly in any modern browser. No server, build step, dependencies, or network access are required.
