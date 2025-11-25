

# 📘 Assignment: Hangman Game

## 🎯 Objective

Build a classic Hangman game in Python. You'll practice string manipulation, loops, conditionals, and random selection by creating a word-guessing game where players try to reveal a hidden word before running out of attempts.

## 📝 Tasks

### 🛠️	Create the Hangman Game

#### Description
Write a Python program that lets a player guess letters to uncover a secret word. The game should track the number of incorrect guesses and end when the player either guesses the word or runs out of attempts.

#### Requirements
Completed program should:

- Randomly select a word from a predefined list
- Display the word as underscores (e.g., _ _ _ _)
- Accept single-letter guesses from the user
- Reveal correct letters in their positions
- Track and display the number of incorrect guesses remaining
- End the game with a win message if the word is guessed
- End the game with a lose message if attempts run out

Example:
```
Word: _ _ _ _
Guess a letter: a
Incorrect! Attempts left: 5
Word: _ a _ _
Guess a letter: t
Correct!
...etc.
```

### 🛠️	Enhance the Game (Optional Challenge)

#### Description
Add extra features to make your Hangman game more fun and user-friendly.

#### Requirements
Completed program could:

- Show all guessed letters so far
- Prevent repeated guesses from counting against the player
- Allow the player to play again after finishing a game
- Use a larger or themed word list
