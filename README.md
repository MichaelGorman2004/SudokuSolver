# Sudoku Solver with Backtracking Algorithm

This Python script utilizes a backtracking algorithm to solve Sudoku puzzles. Given an incomplete Sudoku board, the script attempts to fill in the missing numbers in a way that satisfies all the rules of Sudoku.

## Features

The script provides the following features:

1. **Sudoku Solver**: Solves Sudoku puzzles by filling in the missing numbers using a backtracking algorithm.
2. **Input**: Accepts an incomplete Sudoku board as input, with missing numbers represented by zeros.
3. **Output**: Displays the solved Sudoku board once a solution is found.

## Requirements

To run the script, you need the following:

- Python installed on your system.

## Usage

1. Ensure you have Python 3.x installed on your system.
2. Download the script and save it to your local machine.
3. Open a terminal or command prompt and navigate to the directory where the script is located.
4. Run the script using the following command:

   ```bash
   python SudokuSolver.py
   ```

5. Follow the on-screen instructions to input the Sudoku board.
6. The script will attempt to solve the puzzle and display the solved Sudoku board if a solution is found.

## Customization

If you want to customize the script or incorporate it into your own project, you can modify the following parts:

- **Input Method**: Customize the way the Sudoku board is inputted. You can modify the script to read the board from a file, accept command-line arguments, or integrate it with a graphical user interface (GUI).
- **Output Method**: Modify the way the solved Sudoku board is displayed. You can customize the script to output the board to a file, print it in a different format, or integrate it with a GUI.

## Algorithm Explanation

The script utilizes a backtracking algorithm to solve the Sudoku puzzle. It follows these steps:

1. Find an empty cell in the Sudoku board.
2. Attempt to fill the cell with a number from 1 to 9.
3. Check if the number violates any Sudoku rules (e.g., if the same number already exists in the same row, column, or 3x3 box).
4. If the number is valid, move to the next empty cell and repeat steps 2 to 4 recursively.
5. If no number is valid, backtrack to the previous cell and try a different number.
6. Repeat the process until the entire Sudoku board is filled.

The backtracking algorithm ensures that every possible combination of numbers is tried until a valid solution is found.

## License

This script is released under the [MIT License](LICENSE.md). Feel free to use, modify, and distribute it as per the terms of the license.

## Contributing

If you find any issues or have suggestions for improvements, please open an issue or submit a pull request on the GitHub repository.

## Credits

This script was created by Michael Gorman. Special thanks to the developers and contributors of the backtracking algorithm for Sudoku puzzles.
