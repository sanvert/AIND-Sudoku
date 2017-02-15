# Artificial Intelligence Nanodegree
## Project: Diagonal Sudoku Solver

# 1 (Naked Twins)
Naked twins constraint is implemented as an independent check to apply over boxes of each unit during reduction operation. The "naked_twins" function get the values dictionary and removes same two digits included into exactly two boxes, from other boxes in same unit with these two namely naked twins.

# 2 (Diagonal Sudoku)
Having each digit once in diagonals is another constraint such as having each digit
once in rows, columns and 3*3 blocks. I have created unit list for left and right diagonals
and added that two into "unitlist" to be checked at each constraint propagation operation
triggered in "reduce_puzzle" method.

### Install

This project requires **Python 3**.

We recommend install [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project.

##### Pygame

You can also install pygame if you want to see your visualization. If you've followed our instructions for setting up our conda environment, you should be all set.

If not, please see how to download pygame [here](http://www.pygame.org/download.shtml).

### Code

* `solutions.py` - Implementation of AI to solve sudoku.
* `solution_test.py` - You can test solution by running `python solution_test.py`.
* `PySudoku.py` - This is code for visualizing solution.
* `visualize.py` - This is code for visualizing solution.

### Visualizing

To visualize solution, please only assign values to the values_dict using the ```assign_values``` function provided in solution.py

### Data

The data consists of a text file of diagonal sudokus for you to solve.
