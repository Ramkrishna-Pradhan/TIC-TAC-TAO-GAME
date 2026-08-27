# 🎮 Tic-Tac-Toe Game

A simple and interactive **Tic-Tac-Toe game** built using **HTML, CSS, and JavaScript**. The project demonstrates fundamental front-end development concepts such as DOM manipulation, event handling, game-state management, conditional logic, and winning-pattern detection.

---

## 📌 Project Overview

Tic-Tac-Toe is a classic two-player strategy game played on a **3×3 grid**.

Players take turns placing their symbols — **O** and **X** — into empty cells. The first player to successfully place three identical symbols in a horizontal, vertical, or diagonal line wins the game.

This project provides a simple browser-based implementation of the game with:

- Interactive 3×3 game board
- Automatic player turn switching
- Win-condition detection
- Winner notification
- Board disabling after a win
- Reset functionality
- New Game functionality

---

## ✨ Features

### 🎯 Interactive Game Board

The game contains a 3×3 grid consisting of nine clickable cells.

### 🔄 Automatic Turn Switching

Players automatically alternate between **O** and **X** after every valid move.

### 🏆 Winner Detection

The JavaScript logic checks all possible winning combinations after every move.

There are **8 possible winning patterns**:

- 3 Horizontal
- 3 Vertical
- 2 Diagonal

### 🚫 Board Lock After Winning

Once a player wins, all game cells are disabled to prevent additional moves.

### 🔁 Reset Game

The **Reset** button clears the board and allows the game to continue from its current game state.

### 🆕 New Game

The **New Game** button completely resets the board and starts a fresh game.

### 🎨 Simple User Interface

The game uses CSS to create the board layout, buttons, colors, spacing, and visual appearance.

---

## 🕹️ How to Play

1. Open the game in a web browser.
2. The first player starts with **O**.
3. Click on any empty cell.
4. The second player plays with **X**.
5. Continue alternating turns.
6. The first player to create a line of three identical symbols wins.
7. If there is no winning combination, the board can be reset for another game.

### Winning Examples

A player wins by creating any of these patterns:

```text
O O O        O X X        O X X
X X O        O O X        X O X
X X O        X X O        X X O
```

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| **HTML5** | Creates the structure of the game |
| **CSS3** | Handles layout and visual styling |
| **JavaScript** | Implements game logic and interaction |
| **Git** | Version control |

---

## 📂 Project Structure

```text
Tic-Tac-Toe/
│
├── game.html
├── game.css
├── game.js
└── README.md
```

## 🎯 Learning Objectives
The main purpose of this project is to understand how JavaScript can be used to create an interactive web application.

Through this project, I practiced:

1. Connecting JavaScript with HTML elements.</br>
2. Handling user interactions using event listeners.</br>
3. Updating webpage content dynamically.</br>
4. Managing application state.</br>
5. Implementing game rules using JavaScript.</br>
6. Designing a basic user interface using CSS.</br>
7. Organizing a small front-end project into separate HTML, CSS, and JavaScript files.

## ⭐ Support
If you found this project useful or interesting, consider giving the repository a ⭐ on GitHub.
Your support is appreciated!
