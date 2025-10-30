# Hangman Game

## Overview
This is a simple **Hangman Game** written in **Python**.  
It randomly selects a word from a text file (`words.txt`) and allows the user to guess letters one by one.  
The player has **7 chances** to guess the correct word before the game ends.

---

## Features
- Random word selection from file  
- Case-insensitive guessing  
- Underscore display for hidden letters  
- Updates correct guesses in real-time  
- Shows remaining chances and Hangman progress  
- Displays win or lose message at the end  

---

## How It Works
1. The program reads all words from `words.txt`.
2. It chooses one word at random and converts it to uppercase.
3. The user guesses letters:
   - If correct → the letter is revealed in the word.
   - If incorrect → one chance is lost, and the Hangman figure updates.
4. The game ends when:
   - The word is guessed → “Congrats! You win.”
   - Chances reach zero → “You lose. Try again.”

---

## Requirements
- Python 3.x  
- `words.txt` file in the same directory
