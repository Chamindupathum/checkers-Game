# 🎯 Advanced Checkers Game with AI

This is a single-file, browser-based implementation of a traditional Checkers game featuring a highly optimized Artificial Intelligence (AI) opponent. The game is played between a Human Player (Red) and the AI (Black).

## ✨ Features

* **Human vs. AI Gameplay:** Play against an advanced computer opponent.
* **Adjustable AI Difficulty:** Select from Easy (Depth 2) to Expert (Depth 8).
* **Sophisticated AI:** Implements a full **Negamax** search with **Iterative Deepening** and **Alpha-Beta Pruning**.
* **AI Optimizations:**
    * **Transposition Table:** Caches evaluations to speed up repeated board analysis.
    * **Advanced Move Ordering:** Uses **Killer Moves** and a **History Heuristic** to prioritize the most promising moves.
    * **Quiescence Search:** Prevents the "horizon effect" by fully analyzing sequences of immediate captures.
    * **Enhanced Evaluation:** Scores positions based on material, piece advancement, center control, and mobility.
* **Game-State Logic:** Simple logic for handling **Opening Book** moves and **Endgame** strategy.
* **Performance Monitoring:** Detailed AI metrics (nodes searched, cache hit rate, search time) are logged to the console after each AI turn.
* **Utility Tools:** Includes a **Hint** system and **Move History** display.

## 🛠️ Technology

* **HTML:** Structure
* **CSS:** Styling (Responsive design and vibrant checkerboard)
* **JavaScript (Class-based):** Game logic and AI implementation

## 🎮 How to Play

1.  **Open the File:** Download and open the `checkers.html` file in any modern web browser.
2.  **Start Game:** The game starts automatically with Red (You) making the first move.
3.  **Select Piece:** Click on one of your Red pieces to select it.
4.  **View Moves:** Valid squares will be highlighted in yellow.
5.  **Move Piece:** Click on a yellow-highlighted square to make your move. If a capture is available, you *must* take it.
6.  **AI Turn:** After your move, the AI (Black) will calculate its optimal response based on the selected difficulty.
7.  **New Game:** Click the **"New Game"** button at any time to reset the board.

## ⚙️ AI Difficulty Settings

| Level | Search Depth | Notes |
| :--- | :--- | :--- |
| Easy | 2 | Very fast, simple moves |
| Medium | 4 | Balanced challenge (Default) |
| Hard | 6 | Significant computation, strong play |
| Expert | 8 | Maximum challenge, longest calculation time |
