# Maze-Problem
A program to solve mazes by finding a path from a start point to an end point using BFS and DFS algorithm

# Maze Problem Solver

This is a Python program that solves maze problems by finding a path from a start point (A) to an end point (B).

## Requirements

- Python 3.x
- PIL or Pillow library (for generating maze images)

## Usage

To run the program, execute the following command:

python maze.py maze.txt

Replace `maze.txt` with the path to your maze file. The maze file should be a text file representing the maze, where `#` represents walls, `A` represents the start point, and `B` represents the end point.

## Implementation Details

The program uses a stack-based frontier for the depth-first search algorithm to explore the maze and find a solution. The solution, if found, is printed and an image of the maze with the solution is generated.

## Example

Solving...
States Explored: 11
Solution:

#####B#
#####*#
####**#
####*##
*****##
A######
