
# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Build a playable text-based Hangman game in Python. Practice using strings, loops, conditionals, random selection, and user input while managing the state of a game.

## 📝 Tasks

### 🛠️ Build the Game Setup

#### Description
Create the initial game state by selecting a hidden word and displaying its letters as blanks. Update the display as the player correctly guesses letters.

#### Requirements
Completed program should:

- Store at least five possible words and randomly select one word at the start of each game
- Display one underscore for each letter in the hidden word, such as `_ _ _ _`
- Record each letter the player has guessed so it can be recognized on later turns
- Reveal every matching position when the player guesses a letter in the word
- Display the current revealed word and the number of remaining attempts after each guess

Example progress display:

```text
Word: _ y _ h _ n
Attempts remaining: 5
```

### 🛠️ Add Gameplay and End Conditions

#### Description
Build the main game loop so the player can enter one letter at a time until the word is solved or the attempts run out. Make the end of the game clear and encouraging for the player.

#### Requirements
Completed program should:

- Prompt the player for one letter guess at a time
- Reduce the remaining attempts by one when a guessed letter is not in the word
- Continue until every letter is revealed or no attempts remain
- Display a clear win message when the player solves the word
- Display a clear loss message and reveal the hidden word when the player runs out of attempts
- Handle repeated guesses without revealing incorrect progress or reducing attempts more than once
