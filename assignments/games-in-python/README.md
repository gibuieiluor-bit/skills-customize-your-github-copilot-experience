
# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Build a classic Hangman game in Python using strings, loops, and user input. This assignment helps students practice random word selection, conditionals, and tracking game state while creating a fun, playable text-based game.

## 📝 Tasks

### 🛠️ Build the Game Setup

#### Description
Set up the core game by choosing a hidden word and showing the player a blank version of it that updates as guesses are made.

#### Requirements
Completed program should:

- Randomly select a word from a predefined list
- Display the hidden word as underscores, such as `_ _ _ _`
- Track which letters have already been guessed
- Show the current progress after each guess

### 🛠️ Add Gameplay and End Conditions

#### Description
Create the main game loop so the player can guess letters until they either win by solving the word or lose after running out of chances.

#### Requirements
Completed program should:

- Accept one letter guess at a time from the player
- Reveal matching letters in the hidden word
- Reduce the remaining attempts for incorrect guesses
- Stop the game when the word is fully guessed or attempts reach zero
- Display a clear win or lose message at the end
