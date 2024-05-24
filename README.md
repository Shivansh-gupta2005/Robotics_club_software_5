# Mars Rover Escape

## Problem Description
Shaurya's rover is lost on Mars, surrounded by craters and obstacles. The goal is to determine the number of possible locations the rover can reach after a certain number of steps on a map that repeats infinitely in all directions.

## Approach and Solution
We approached the problem in two main steps:

1. **Initial BFS for Reachable Positions**: We initially performed a Breadth-First Search (BFS) algorithm to identify all reachable positions within one period of the map. This involved simulating the rover's movements on the map and marking each reachable position.

2. **Dynamic Programming for Large Steps**: Once we had the reachable positions within one period, we used Dynamic Programming (DP) techniques to efficiently calculate the positions reachable after a large number of steps. This involved leveraging the periodicity of the map and using modulo arithmetic to handle the repetition.
