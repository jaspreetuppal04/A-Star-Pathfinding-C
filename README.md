# A-Star Pathfinding in C

A simple implementation of the **A\* (A-Star) Search Algorithm** in C for finding the shortest path on a 5×5 grid while avoiding obstacles.

## Features

- A* Search Algorithm implementation
- Manhattan Distance heuristic
- User-defined start and destination positions
- Supports obstacles in the grid
- Displays the shortest path if one exists

## Technologies Used

- C Programming
- Standard C Libraries (`stdio.h`, `stdlib.h`, `math.h`)

## Grid Representation

- `0` → Free cell
- `1` → Obstacle

## How to Compile

```bash
gcc a_star_pathfinding.c -o astar
```

## How to Run

```bash
./astar
```

## Sample Input

```
Enter grid (0 = free, 1 = obstacle):

0 0 0 0 0
1 1 0 1 0
0 0 0 1 0
0 1 0 0 0
0 0 0 1 0

Enter start position (x y):
0 0

Enter destination position (x y):
4 4
```

## Concepts Covered

- A* Search Algorithm
- Pathfinding
- Heuristic Search
- Manhattan Distance
- Structures
- Arrays
- Grid Traversal

## Author

**Jaspreet Uppal**