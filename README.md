# Sudoku Solver Using Backtracking
A basic python code to solve a given Sudoku board.

This solver was written as a response to an interest in sudoku, with the intent on making it easier to solve basic rules sudoku games
without the need of annotating the board.

The sudoku solver uses a backtracking algorithm, whereby it sees the board as a 2x2 array and finds the next position needing a number
(designated by a zero in the inital array). It cycles through each number, checking all positions in its row, column, and box for a
repeat of that same number. If it doesn't find a repeat, it places that number then moves to the next empty position. If it cycles through all of the numbers 1-9 and cannot place a number, it backtracks to the position that was previously placed, and continues cycling through
until it is able to place another valid number.

For debugging purposes and step by step validation, line 15 of the code shows the progression of the solver as it recursively solves.
This can be commented out if desired.

Potential next steps include a gui to show the code recursively solving and a way to input any sudoku board to solve.
