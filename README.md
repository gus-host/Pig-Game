# Pig Game
This repository contains the code for a simple Pig Game implemented using HTML, CSS, and JavaScript.

## Introduction
Pig Game is a two-player dice game where the players take turns to roll a dice. The objective of the game is to reach a predefined score (typically 100) before your opponent does.

## Installation
To run the game locally, follow these steps:

1. Clone this repository to your local machine using the following command:
- git clone https://github.com/your-username/pig-game.git

2. Navigate to the directory where you cloned the repository:
- cd pig-game

3. Open the index.html file in your preferred web browser.

## How to Play
1. The game starts with Player 1.
2. Each turn, a player rolls a dice as many times as they wish. Each result gets added to their current score.
3. However, if a player rolls a 1, all their current score is lost, and it becomes the next player's turn.
4. A player can choose to "Hold," which means that their current score gets added to their total score. After that, it's the next player's turn.
5. The first player to reach the predefined score wins the game.

## Features
- Dynamic UI: The interface displays each player's score and current score dynamically.
- Dice Rolling: Players can roll a dice to add to their current score.
- Hold Option: Players can choose to hold, which adds their current score to their total score and switches to the next player.
- Winner Declaration: The game automatically declares a winner when one player reaches the predefined score.

## Repository Structure
- index.html: Contains the HTML structure of the game.
- style.css: Stylesheet for the game layout and design.
- script.js: JavaScript file containing the game logic.
  
## Contributing
Contributions are welcome! If you have any suggestions or improvements, feel free to open an issue or create a pull request.
