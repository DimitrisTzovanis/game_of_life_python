# Game of life in Python

## Members: Dimitris Tzovanis, Elpida Stasinou


### Rules

- Birth: A dead cell with exactly three live neighbors becomes a live cell (as if by reproduction).
- Survival: A live cell with two or three live neighbors stays alive for the next generation.
- Death by Isolation: A live cell with fewer than two live neighbors dies in the next generation.
- Death by Overpopulation: A live cell with more than three live neighbors dies in the next generation.

### Features

- Initialize the game board with a specified size.
- Set cells to be alive or dead.
- Generate the next generation of the board based on the game's rules.
- Print the board to the console for visualization.
- Predefined patterns such as "blinker" and "glider" for quick setup.
