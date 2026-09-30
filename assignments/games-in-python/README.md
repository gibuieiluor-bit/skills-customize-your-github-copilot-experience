
# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Build a playable text-based Hangman game in Python. Practice using strings, loops, conditionals, random selection, and user input to manage the game state.

## 📝 Tasks

### 🛠️ Build the Game Setup

#### Description
Set up the game by choosing a hidden word and showing the player which letters have been revealed as guesses are made.

#### Requirements
Completed program should:

- Store a list of possible words and randomly select one at the start of each game
- Display one underscore for each letter in the hidden word, such as `_ _ _ _`
- Record the letters the player has guessed
- Reveal every matching position when the player guesses a letter in the word
- Display the revealed letters and remaining attempts after each guess

### 🛠️ Add Gameplay and End Conditions

#### Description
Create the main game loop so the player can guess letters until they solve the word or run out of attempts.

#### Requirements
Completed program should:

- Prompt the player for one letter guess at a time
- Reduce the remaining attempts by one for each incorrect guess
- End the game when all letters are revealed or no attempts remain
- Display a clear win or loss message and reveal the word when the game ends
