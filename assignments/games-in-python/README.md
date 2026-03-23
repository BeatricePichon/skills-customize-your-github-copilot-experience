
# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

In this assignment, you will build a text-based Hangman game in Python. You will practice working with loops, conditionals, strings, and user input to manage game state from start to finish.

## 📝 Tasks

### 🛠️ Build the Core Game Loop

#### Description
Create the main Hangman gameplay so a player can guess letters and reveal a secret word one step at a time.

#### Requirements
Completed program should:

- Randomly select one secret word from a predefined list.
- Display the current word progress using underscores for unknown letters (for example: `_ _ _ _ _`).
- Ask the player for one letter guess during each turn.
- Continue the loop until the word is fully guessed or the player runs out of allowed incorrect guesses.


### 🛠️ Track Guesses and End Conditions

#### Description
Add logic to handle correct and incorrect guesses, update attempts, and clearly communicate the game result.

#### Requirements
Completed program should:

- Store guessed letters and reveal all matching positions when a correct letter is entered.
- Reduce remaining attempts only when the guess is incorrect.
- Prevent duplicate guesses from changing game state and inform the player when a letter was already tried.
- Print a clear win message when the player guesses the full word and a clear lose message (including the secret word) when attempts reach zero.
