

# 🎮 Hangman Game 🪢

Welcome to the classic **Hangman Game** implemented in Python!  
Test your guessing skills by revealing a hidden word, one letter at a time, before the hangman is complete. It's a fun terminal-based game for all ages!

---

## 🔗 Repository

GitHub Repo: [https://github.com/PiyushJaiswall/hangman](https://github.com/PiyushJaiswall/hangman)

---

## 📂 Project Structure

```
hangman/
├── hangman.py           # Main game logic
├── words.py             # List of words to guess from
└── hangman_visual.py    # ASCII visuals for remaining lives
```

- **`hangman.py`** – Handles the core game loop, user input, and game logic.
- **`words.py`** – Contains a list of words from which a random word is selected.
- **`hangman_visual.py`** – Provides ASCII art visuals based on remaining lives.

---

## 🚀 How to Run the Game

### ✅ Requirements:
- Python 3.x installed
- No external libraries required (only Python's built-in modules like `random` and `string`)

### ⚡ Installation and Execution:
1. **Clone the repository**:
   ```bash
   git clone https://github.com/PiyushJaiswall/hangman.git
   cd hangman
   ```

2. **Run the game**:
   ```bash
   python hangman.py
   ```

---

## 📝 How to Play

- The game randomly selects a word from `words.py`.
- You have **7 lives** to guess the hidden word by entering one letter at a time.
- Each wrong guess removes a life and progresses the hangman drawing.
- The game ends when:
  - ✅ You correctly guess all letters of the word.
  - ❌ You run out of lives and the hangman is complete.

---

## 🎨 Visual Representation

The hangman figure updates with each wrong guess. Example when **3 lives left**:

```
                ___________
               | /        | 
               |/        ( )
               |          
               |          
               |
```

---

## 🧩 Features

- ✅ Random word selection from a predefined list.
- ✅ ASCII art visuals that update as you play.
- ✅ Tracks already guessed letters.
- ✅ Handles invalid inputs and repeated guesses.
- ✅ Simple and clean terminal-based gameplay.

---

## 📌 Future Improvements

- [ ] Add difficulty levels (Easy, Medium, Hard).
- [ ] Expand the word list with more categories.
- [ ] Implement a GUI version using `tkinter` or `pygame`.
- [ ] Add a scoring system and high-score tracking.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Open a Pull Request

---
