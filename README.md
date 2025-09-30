# Simple Genetic Algorithm for path-finding problem

I used the basic concept of GA to minimize the distance in pathfinding problems. Here are some results showing how the average 
distance and minimum distance changed with each generation. I used 90% crossover and 10% mutation throughout the evolution 
process. The distance values I used in this example are between 0 to 100, and 50% nodes are connected. 
The Genetic Algorithm path finding is a part of the path planner that also uses Dijkstra, A*, AGA, etc 

## Average distance change with each generation
<img src="average.png" width="400"/>

## Best individual's evolution with each generation
<img src="shortest.png" width="400"/>

# Simple Genetic Algorithm (SGA) for Path-Finding

Find a near-optimal path from **Start (S)** to **Goal (G)** on a grid/maze with obstacles using a classic Genetic Algorithm.

> Compact, easy to read, and ready to run for coursework, demos, or as a baseline.

---

## ✨ What it does
- Searches a 2D grid for a collision-free path.
- Optimizes path **length** + **collision penalties**.
- Supports **cardinal** (UDLR) or **8-directional** moves.
- Works with fixed-length genomes or variable-length with pruning.

---

## 🔧 Problem Format
- Grid file (text or CSV): `0` = free, `1` = obstacle.
- Config JSON (optional): start, goal, GA params.

**Example grid.txt**
0 0 0 0 0
0 1 1 0 0
0 0 0 0 0
0 0 1 1 0
S 0 0 0 G
