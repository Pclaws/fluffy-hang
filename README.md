# fluffy-hang 🪢

A simple **Hangman** game built with Python — my first Python project for learning the language!

---

## 🎮 About the Game

Hangman is a classic word-guessing game. The computer picks a secret word, and you try to guess it one letter at a time. Every wrong guess brings the hangman one step closer to being complete. Guess the word before you run out of attempts!

---

## ✨ Features

- Random word selection from a built-in word list
- Visual hangman drawing that updates with each wrong guess
- Tracks letters you have already guessed
- Displays correctly guessed letters in their positions
- Win/lose detection with a replay option

---

## 🚀 How to Run

Make sure you have **Python 3** installed, then run:

```bash
python hangman.py
```

---

## 🕹️ How to Play

1. The game picks a random secret word and displays blank spaces for each letter.
2. Type a single letter and press **Enter** to guess.
3. If the letter is in the word, it is revealed in the correct position(s).
4. If the letter is **not** in the word, a part of the hangman is drawn.
5. You have **6 attempts** before the hangman is complete and the game ends.
6. Guess all the letters correctly to win! 🎉

---

## 📂 Project Structure

```
fluffy-hang/
├── hangman.py      # Main game logic
├── words.py        # Word list used by the game
└── README.md       # Project documentation
```

---

## 🧠 What I Learned

- Using `random` to pick items from a list
- Working with `while` loops and `for` loops
- String manipulation and list indexing
- Accepting and validating user input
- Basic game-state management in Python

---

## 📋 Requirements

- Python 3.x

No external libraries are needed — this project uses only the Python standard library.

---

## 📄 License

This project is open source and available for learning purposes.
