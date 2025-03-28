# Strands AI Project – Minimax-based Game

This project is a strategic game based on the "Strands" framework, built in Python as part of an Artificial Intelligence course project.  
It features an implementation of the **Minimax algorithm with Alpha-Beta pruning**, allowing an AI to play the game with strategic depth.

## 🧠 Features

- **Minimax AI with Alpha-Beta pruning**
- Evaluation function based on game state and potential win/loss scenarios
- Handling of hexagon-based game boards with dynamic updates
- A strong foundation for future enhancements such as Monte Carlo Tree Search (MCTS)

## 🎮 How to Play

To run the game:

1. Clone this repository
2. Open a terminal in the root folder
3. Run the main game script 

## 🕹️ Controls

Controls depend on the specific game interface.  
If using a graphical or console-based version, follow the on-screen instructions to select hexagons or take turns.

## ⚠️ Current Status & Known Issues

This project is still in an **early and experimental stage**.  
It contains **several bugs**, such as:

- Inconsistent game behavior under certain board states
- Unstable decision-making at deeper Minimax levels
- Occasional crashes due to state mismanagement

### 🛠️ What needs improvement

- General **code stability** and **bug fixes**
- **Refactoring** for better readability and modularity
- Enhanced **heuristics** and scoring logic
- Full integration of the **MCTS algorithm**

> 👨‍🔧 Contributions and suggestions are welcome!

## 📚 About the AI

This project includes a complete implementation of the **Minimax algorithm** with alpha-beta pruning, using:

- Recursion and score evaluation
- Selection and deselection of game hexagons to preserve game state
- Future-proof structure for heuristic improvements

Although a Monte Carlo Tree Search (MCTS) was planned, it was not fully implemented due to time constraints. However, design notes and partial structure were outlined for future integration.

## 🔍 Comparison: Minimax vs MCTS

| Algorithm | Pros | Cons |
|----------|------|------|
| Minimax | Precise, strategic, deterministic | Heavy computation on deep trees |
| MCTS | Adaptive, faster on complex games | Less predictable, incomplete (in this project) |

For "Strands", **MCTS would likely be more efficient**, but Minimax provides **more control** and **predictable strategy**, which was more suitable for this version.



Feel free to explore the code, experiment with the AI, report bugs, or contribute improvements! 🤖
