# Bee-Bot Autonomous Systems

## Project Overview

This project implements an autonomous Bee-Bot navigation system in a grid environment using Python. It explores how search algorithms can help an agent navigate from an initial state to a goal state while avoiding obstacles.

## Objectives

- Represent the Bee-Bot environment as a grid.
- Define the agent's position, direction and possible actions.
- Implement valid movement and obstacle checking.
- Apply and compare Depth-First Search (DFS) and A* Search.
- Evaluate search performance and path quality.

## Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Matplotlib

## Search Algorithms

### 1. Depth-First Search (DFS)

DFS uses a stack to explore states and find a route to the goal. It records visited states and uses parent information to reconstruct the path.

### 2. A* Search

A* uses a cost function:

f(n) = g(n) + h(n)

It combines the cost already travelled with a heuristic estimate of the remaining distance. This project uses Manhattan distance as its heuristic.

## Results

The coursework compared DFS and A* using search performance and path length.

| Metric | DFS | A* |
|---|---:|---:|
| Average action path length | 58.60 | 14.60 |
| Average states recorded | 449* | 147.4 |

*449 is the reported visited-state count for the illustrated DFS run, not the average across trials.*

The results showed that A* found shorter paths, while DFS had a slightly faster execution time in the reported experiments.

## Repository Contents

- `bee_bot_autonomous_systems.ipynb` – Python implementation and experiments.
- `README.md` – Project documentation.

## Learning Outcomes

Through this project, I developed practical experience with:

- State-space representation.
- Search algorithms and heuristic functions.
- Python programming and problem-solving.
- Algorithm performance comparison.
- Autonomous agent navigation.

## Project Status

Completed academic coursework project.
