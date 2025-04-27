# 🎯 Tic-Tac-Toe AI — Minimax and Alpha-Beta Pruning

## 📋 Overview
This project implements a fully functional Tic-Tac-Toe game where an AI opponent plays optimally using the Minimax algorithm, further enhanced with Alpha-Beta Pruning to optimize performance.
The assignment's goal is to understand decision trees, AI strategies, and optimization techniques in turn-based games.

## 🚀 Features
✅ Tic-Tac-Toe Game Logic — Standard 3x3 grid with win/draw conditions.

✅ AI Player with Minimax — Always makes the best move.

✅ Alpha-Beta Pruning — Speeds up AI move calculations by pruning unnecessary branches.

✅ Performance Comparison — Demonstrates efficiency gains.

✅ Demo Video — Walkthrough of AI in action.

## 🌟 Performance Comparison: Minimax vs Alpha-Beta Pruning

**Feature**            | **Standard Minimax**                         |  **Alpha-Beta Pruning Minimax**
___________________________________________________________________________________________________________________________________________________
Efficiency             | Explores every possible move.                | Skips unnecessary branches (cuts off unneeded moves).
___________________________________________________________________________________________________________________________________________________
Speed                  | Slower because it checks all nodes.          | Faster due to fewer nodes evaluated.
___________________________________________________________________________________________________________________________________________________
Time Complexity        | O(b^d) (b = branching factor, d = depth)     | Best case: O(b^(d/2))  (almost half the nodes explored!)
___________________________________________________________________________________________________________________________________________________
Memory Usage           | Higher (stores many nodes).                  | Lower (prunes irrelevant parts of the tree).
___________________________________________________________________________________________________________________________________________________
Optimality             | Always finds the best move.                  | Always finds the best move. (No compromise.)
___________________________________________________________________________________________________________________________________________________
Real-World Performance | Noticeable delay for deep trees.             | More responsive and quicker decisions.
___________________________________________________________________________________________________________________________________________________
Use Case               | Small games, simple AI.                      | Complex games, deeper AI logic (like Chess, Tic-Tac-Toe with smarter AI).
___________________________________________________________________________________________________________________________________________________

## ⚙️ How to Run
Clone this repository.

Open main.cpp in any modern C++ compiler.

Play against the AI and observe its decision-making!
