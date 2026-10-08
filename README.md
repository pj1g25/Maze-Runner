# Maze-Runner
A python program in which a "runner" goes through a given maze and calculates the optimal path to complete the maze.

The runner explores the maze and gathers information about it. Then it stops and computes the optimal path from the information it found. The mazes given are in a specific format such as:
###################
#.................#
#.#.#.#.#.#.#.#.#.#
#.................#
#.#.#.#.#.#.#.#.#.#
#.....#...........#
#.#.#.#.###.#.#.#.#
#.................#
#.#.#.#.#.#.#.#.#.#
#.................#
###################

The walls of the maze are represented by #
The spaces where the runner or a wall can go are represented by .
The spaces where the runner can go are not the same as the space where a wall could potentially be. The runner cannot go to a space adjacent to one of the hashtags in the rows where the symbols are alternating. In the previous example, there are 5 rows and 9 columns of available spaces.
