# 🎲 Dice Game

Welcome to the **Dice Game**, an exciting and interactive web-based game where two players compete to be the first to reach 100 points! Players take turns rolling the dice, accumulating points, and strategizing their way to victory. With features to roll the dice, hold points, and start a new game, it's a classic test of luck and strategy.

## 📑 Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)
- [Code Overview](#code-overview)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)
- [Screenshots](#screenshots)

## 🌟 Introduction

**Dice Game** brings a fun twist to the classic dice-rolling game. Players alternate turns, rolling dice to accumulate points while avoiding the pitfalls of rolling a 1. The game features a sleek interface for rolling dice, holding points, and restarting the game, all designed to keep players engaged and entertained.

## 🚀 Getting Started

### Prerequisites

- A modern web browser (e.g., Chrome, Firefox, Safari)
- Basic understanding of HTML, CSS, and JavaScript

### Installation

1. **Clone the Repository**:

   ```bash
   git clone <repository-url>
   cd dice-game
   ```

2. **Open the Project**:

   Open the `index.html` file in your web browser to start playing the game.

## 🕹️ Usage

1. **Rolling the Dice**:

   - Click the "Roll Dice" button to roll the dice. The result will be displayed, and the score will be updated based on the roll.

2. **Holding Points**:

   - Click the "Hold" button to add the current score to the active player's total. The game will switch to the next player.

3. **Starting a New Game**:

   - Click the "New Game" button to reset all scores and start a fresh game.

## 🧩 Code Overview

### 1. Initial Setup

The `init()` function sets up the game state, resets scores, assigns the current player, and hides the dice at the start of the game.

### 2. Switching Players

The `switchPlayer()` function handles player switching when a roll results in 1, resetting the current score and changing the active player.

### 3. Rolling Dice

The dice roll functionality is managed in the `btnRoll` event listener. It generates a random dice result, updates the display, and incorporates game logic based on the roll outcome.

### 4. Holding Points

The `btnHold` event listener adds the current score to the active player's total and checks if the player has won, updating the game state accordingly.

### 5. Starting a New Game

The `btnNew` event listener resets the game state by calling the `init()` function, providing a fresh start for a new session.

## 💻 Technologies Used

- **HTML**: Provides the structure of the game interface.
- **CSS**: Manages the styling and layout.
- **JavaScript**: Implements game logic and interactivity.

## 🤝 Contributing

We welcome contributions! If you want to enhance this project, please fork the repository and submit a pull request. For significant changes, please open an issue to discuss your ideas.

## 📜 License

This project is licensed under the MIT License.

## 🙏 Acknowledgments

- Thanks to the developers who provided insights and examples for the game logic.
- Special appreciation to the creators of JavaScript libraries and resources that aided in building this game.

## 📸 Screenshots

- ![Screenshot 1](https://github.com/shamshubham/pig-game/blob/master/screenShots/Capture.JPG)
- ![Screenshot 2](https://github.com/shamshubham/pig-game/blob/master/screenShots/Capture1.JPG)
- ![Screenshot 3](https://github.com/shamshubham/pig-game/blob/master/screenShots/Capture2.JPG)
- ![Screenshot 4](https://github.com/shamshubham/pig-game/blob/master/screenShots/Capture4.JPG)
