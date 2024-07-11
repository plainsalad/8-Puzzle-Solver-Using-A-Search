# 8-Puzzle Solver Using A* Search

This project implements an A* search algorithm to solve the 8-puzzle problem. The goal is to move the tiles in the puzzle to reach the goal state. The project includes defining a `PuzzleNode` class, implementing heuristic functions, and coding the A* search algorithm using these heuristics.

## Files

- `Code.ipynb`

## Requirements

- Python 3.x
- NumPy
- Math
- Queue

## Installation

1. Clone the repository or download the files.
2. Install the required libraries using pip:

    ```sh
    pip install numpy
    ```

## Usage

### Running the Solver

1. Open the `Assignment2.ipynb` notebook using Jupyter Notebook or JupyterLab.
2. Run all the cells to execute the solver. The notebook will:
    - Define the `PuzzleNode` class.
    - Implement heuristic functions.
    - Implement the A* search algorithm.
    - Solve the given 8-puzzle problem using the implemented heuristics.

## Project Structure

### PuzzleNode Class

The `PuzzleNode` class provides a structure for performing A* search for the 8-puzzle problem. It includes attributes and methods to:
- Initialize the puzzle state.
- Calculate heuristic values.
- Generate successor states.
- Check puzzle solvability and validity.

### Heuristic Functions

The project includes two heuristic functions:
- **Misplaced Tiles Heuristic**: Counts the number of misplaced tiles compared to the goal state.
- **Manhattan Distance Heuristic**: Calculates the Manhattan distance from the current state to the goal state.

### A* Search Algorithm

The `solvePuzzle` function implements the A* search algorithm. It takes an initial state and a heuristic function as input and returns:
- The number of steps to solve the puzzle.
- The number of nodes expanded.
- The maximum size of the frontier.
- The optimal path to the solution.
- An error code if the puzzle state is invalid or unsolvable.

## Conclusion

This project demonstrates the implementation of the A* search algorithm to solve the 8-puzzle problem using different heuristics. It provides insights into the performance and effectiveness of these heuristics in solving the puzzle.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
