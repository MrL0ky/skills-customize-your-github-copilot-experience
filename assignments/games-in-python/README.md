

# 🎮 Games in Python: Hangman

## 🎯 Objective

Build a classic Hangman game in Python. Practice string manipulation, loops, conditionals, and random selection by creating a word-guessing game where players try to reveal a hidden word before running out of attempts.

## 📝 Tasks

### Task 1: Set Up the Word List
**Description:**
Create a list of at least 8 words that your game will randomly choose from.
**Requirements:**
- The list must contain at least 8 different words
- Words should be strings (e.g., "python", "computer")

### Task 2: Random Word Selection
**Description:**
Write code to randomly select a word from your list at the start of the game.
**Requirements:**
- Use Python's `random` module
- The selected word should be hidden from the player

### Task 3: Player Guess Loop
**Description:**
Allow the player to guess one letter at a time. Show their progress after each guess.
**Requirements:**
- Accept user input for letter guesses
- Display the word with underscores for unguessed letters (e.g., `_ _ t h o n`)
- Track and display incorrect guesses remaining

### Task 4: Game End Conditions
**Description:**
End the game when the player either guesses the word or runs out of attempts.
**Requirements:**
- Show a win message if the word is guessed
- Show a lose message and reveal the word if attempts are exhausted

#### Example
```
Word: _ _ t h o n
Guesses left: 3
Guess a letter: p
Word: p _ t h o n
Guesses left: 3
Guess a letter: y
Word: p y t h o n
Congratulations! You win!
```

---

**Starter code is provided in `starter-code.py`.**
