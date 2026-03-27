# Rat in a Maze - Backtracking Algorithm

A C++ implementation of the classic **Rat in a Maze** problem using the Backtracking approach.

## 📌 Problem Description
A rat starts at the source location $(0, 0)$ and wants to reach the destination $(N-1, N-1)$ in an $N \times N$ grid. 
* The grid contains `1`s (path) and `0`s (dead ends).
* The rat can move in four directions: **Down (D)**, **Left (L)**, **Right (R)**, and **Up (U)**.
* The goal is to find all possible paths from the start to the end without visiting the same cell twice in a single path.

## 🚀 Features
* **Backtracking Logic:** Efficiently explores all possible paths and undoes moves that lead to dead ends.
* **Directional Mapping:** Systematic movement using coordinate offsets.
* **Visited Tracking:** Prevents infinite loops by marking cells currently in the recursion stack.

## 🛠️ How to Run
1.  **Ensure you have a C++ compiler** (like `g++`) installed on your system.
2.  **Save the code** to a file named `main.cpp`.
3.  **Compile the code** using the terminal:
    ```bash
    g++ main.cpp -o rat_in_maze
    ```
4.  **Execute the program**:

5.  ![image alt](https://github.com/ashutosh096/Rat_in_maze_problem/blob/365ebdc98cecee9619436065f74ada837eace96d/Screenshot%202026-03-27%20233637.png)
    ```bash
    ./rat_in_maze
    ```

## 📋 Example Output
For a $4 \times 4$ maze, the output will list the sequences of moves:
```text
Possible paths: 
DDRRDR DDRRRD
