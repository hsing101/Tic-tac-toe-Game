# Tic-Tac-Toe with Minimax AI

An unbeatable Tic-Tac-Toe game powered by the **Minimax algorithm**. Play against an AI that always makes the optimal move.

<p align="center">
  <img src="preview/minimax_img.png" alt="Tic Tac Toe Minimax Preview">
</p>

## Features
- Implements Minimax algorithm for perfect play
- Game tree exploration with over **549,946 possible states**
- Written in **Python** with a simple, modular structure
- Interactive gameplay with AI opponent

## Minimax Overview
- **Zero-sum game AI**: one player wins (+1), the other loses (–1), or it’s a draw (0)
- Recursively explores all possible moves to guarantee the best outcome
- Can be extended to more complex games with optimizations like Alpha-Beta Pruning

## How It Works
1. Build a game tree of all possible moves
2. Assign scores to terminal states (win = +1, loss = –1, draw = 0)
3. Backtrack scores through recursion to choose the optimal move

<p align="center">
  <img src="preview/tic-tac-toe-minimax-game-tree.png" alt="Tic Tac Toe Minimax Game Tree">
</p>

## Try It Out
👉 [Play here](https://cledersonbc.github.io/tic-tac-toe-minimax/)

## References
- *Algorithms in a Nutshell* — George Heineman, Gary Pollice, Stanley Selkow (O’Reilly, 2009)
- [Minimax on Wikipedia](https://en.wikipedia.org/wiki/Minimax)
- [Tic-Tac-Toe AI by NTU](https://www.ntu.edu.sg/home/ehchua/programming/java/JavaGame_TicTacToe_AI.html)

