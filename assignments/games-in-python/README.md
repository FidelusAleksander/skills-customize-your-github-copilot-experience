

# 📘 Assignment: Hangman Game

## 🎯 Objective

Build a classic Hangman game in Python. You'll practice string manipulation, loops, conditionals, and random selection by creating a word-guessing game where players try to reveal a hidden word before running out of attempts.

## 📝 Tasks

### 🛠️	Hangman Game Logic

#### Description
Create a Python program that runs a Hangman game. The program should randomly select a word, accept letter guesses from the player, and display the current progress. The game ends when the word is guessed or the player runs out of attempts.

#### Requirements
Completed program should:

- Randomly select a word from a predefined list
- Accept letter guesses from the user
- Display current progress using underscores for unguessed letters (e.g., _ a _ _ m a n)
- Track and display the number of incorrect guesses remaining
- End the game when the word is fully guessed or attempts are exhausted
- Show a win or lose message at the end

Example:
```
Word: _ a _ _ m a n
Guesses left: 4
Guessed letters: a, m, n, h
```

### 🛠️	Replay Feature (Optional)

#### Description
Add an option for the player to play another round after the game ends.

#### Requirements
Completed program should:

- Ask the player if they want to play again after each game
- Restart the game with a new word if the player chooses to replay
- Exit if the player chooses not to replay
