# Dice Game

This project is a simple dice game implemented using JavaScript. It features two players who take turns rolling a dice and accumulating points. The first player to reach 100 points wins the game. The game includes functionalities to roll the dice, hold points, and start a new game.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)
- [Code Overview](#code-overview)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Introduction

Dice Game is an interactive web-based game where two players take turns rolling a dice. Players accumulate points based on dice rolls, and the game continues until one player reaches 100 points. The game provides a visual interface for rolling dice, holding points, and resetting the game.

## Getting Started

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

   Open the `index.html` file in your web browser to view and interact with the game.

## Usage

1. **Rolling the Dice**:

   Click the "Roll Dice" button to roll the dice. The dice result will be displayed, and the score will be updated accordingly.

2. **Holding Points**:

   Click the "Hold" button to add the current score to the active player's total score. The game will switch to the next player.

3. **Starting a New Game**:

   Click the "New Game" button to reset the game. All scores will be set to zero, and the game will start fresh.

## Code Overview

### 1. Initial Setup

The `init()` function sets up the initial game state, including resetting scores, setting the current player, and hiding the dice.

### 2. Switching Players

The `switchPlayer()` function updates the game state when a player rolls a 1. It switches the active player and resets the current score.

### 3. Rolling Dice

The dice rolling functionality is handled in the `btnRoll` event listener. It generates a random dice result, updates the display, and manages the game logic based on the dice roll.

### 4. Holding Points

The `btnHold` event listener handles adding the current score to the active player's total score. It checks if the player has won and updates the game state accordingly.

### 5. Starting a New Game

The `btnNew` event listener calls the `init()` function to reset the game and start a new session.

## Technologies Used

- **HTML**: Structure of the game interface.
- **CSS**: Styling and layout of the game.
- **JavaScript**: Game logic and interactivity.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please fork the repository and create a pull request. For significant changes, please open an issue to discuss your ideas.

## License

This project is licensed under the MIT License.

## Acknowledgments

- Thanks to the developers who provided inspiration and examples for game logic and implementation.
- Special thanks to the creators of various JavaScript libraries and resources used in building this game.
