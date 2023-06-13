# Maze Solver Program

This is a C++ program that solves a maze using the backtracking algorithm. The program reads the maze configuration from a text file and finds a path from the start position to the end position, avoiding any hurdles in between.

## Program Structure

The program consists of the following files:

1. `Maze.cpp`: This file contains the implementation of the Maze class, which represents the maze and provides methods for solving it.
2. `Maze.h`: This header file defines the Maze class and its member functions.
3. `Maze.txt`: This text file stores the maze configuration and hurdle positions.
4. `MazeSolver.cpp`: This file contains the `main()` function and provides a user interface to interact with the maze solver.

## Compilation

To compile the program, follow these steps:

1. Ensure that you have a C++ compiler installed on your system (e.g., g++ for Linux or MinGW for Windows).
2. Open a terminal or command prompt and navigate to the directory containing the program files.
3. Run the following command to compile the program:

```shell
g++ MazeSolver.cpp Maze.cpp -o maze_solver
```

This command compiles both `MazeSolver.cpp` and `Maze.cpp` files and generates an executable named `maze_solver`.

## Usage

To run the program, execute the following command in the terminal or command prompt:

```shell
./maze_solver
```

The program will read the maze configuration from the `Maze.txt` file and attempt to solve it. The solved path will be displayed on the console, and the maze with the path will be printed as well.

## Maze Configuration File Format

The `Maze.txt` file stores the maze configuration and hurdle positions. It has the following format:

```
rowsize: <number_of_rows> ,columnsize: <number_of_columns>
no of hurdles: <number_of_hurdles>
<x1> <y1>
<x2> <y2>
...
<xN> <yN>
```

- `<number_of_rows>`: The number of rows in the maze.
- `<number_of_columns>`: The number of columns in the maze.
- `<number_of_hurdles>`: The number of hurdles in the maze.
- `<x1> <y1>` to `<xN> <yN>`: The coordinates (x, y) of the hurdles in the maze.

You can modify the `Maze.txt` file to create different maze configurations and hurdle positions.

## Contributing

If you would like to contribute to this program, please follow these steps:

1. Fork the repository.
2. Create a new branch for your changes.
3. Make the necessary modifications and improvements.
4. Test your changes thoroughly.
5. Commit and push your changes to your forked repository.
6. Open a pull request, describing the changes you have made.

Your contributions are greatly appreciated!

## License

This program is licensed under the [MIT License](LICENSE). Feel free to modify and distribute it according to the terms of the license.

## Contact

If you have any questions or suggestions regarding this program, please contact basitnazir585@gmail.com.

Thank you for using our Maze Solver program!
