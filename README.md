# 🎯 Hangman

A classic Hangman word-guessing game built with Python, played in the terminal.

## How to Play

1. Run `main.py` to start the game
2. A random word will be chosen and displayed as blank spaces
3. Guess one letter at a time
4. You have **6 lives** — each wrong guess costs one life and draws more of the hangman
5. Reveal the full word before you run out of lives to win!

## Features

- 200+ challenging words to guess
- ASCII art hangman that updates with each wrong guess
- Tracks letters you've already guessed
- Displays remaining lives each round

## Project Structure

```
├── main.py           # Main game logic
├── hangman_art.py    # ASCII art for the hangman stages and logo
└── hangman_words.py  # Word list
```

## Requirements

- Python 3.x
- No external libraries needed

## Running the Game

```bash
python main.py
```
