# IDDFS Maze Solver

## Description
This project implements the Iterative Deepening Depth First Search (IDDFS) algorithm to solve a 2D maze pathfinding problem.

## Input Format
- First line: rows and columns
- Next lines: maze grid (0 = path, 1 = wall)
- Start: x y
- Target: x y

## Example Input
4 4
0 0 1 0
1 0 1 0
0 0 0 0
1 1 1 0
Start: 0 0
Target: 2 3

## Example Output
Path found at depth 5 using IDDFS
Traversal Order: [(0,0), (0,1), (1,1), (2,1), (2,2), (2,3)]

## How to Run
```bash
python lab_report.py



