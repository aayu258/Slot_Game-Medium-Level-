# 🎰 Python Slot Machine Game

A beginner-friendly **Slot Machine Game** built with Python. The player deposits money, chooses how many lines to bet on, places a bet for each line, and spins the slot machine to try to win.

## ✨ Features

- Deposit an initial balance.
- Bet on 1 to 3 lines.
- Choose a bet amount for each line.
- Validate bets using minimum and maximum limits.
- Generate random slot-machine symbols.
- Check winning lines and calculate winnings.
- Update the balance after each spin.
- Quit the game at any time by entering `q`.

## 🛠️ Built With

- **Python**
- `random` — Python's built-in module for selecting random symbols.

## 🎮 How to Play

1. Run the Python program.
2. Enter the amount you want to deposit.
3. Press **Enter** to play.
4. Choose the number of lines to bet on (1–3).
5. Enter your bet per line (between `$1` and `$100`).
6. The slot machine displays a 3 × 3 grid.
7. Matching symbols across a selected line earn winnings.
8. Your balance is updated after the spin.
9. Press **Enter** to play again, or type `q` to quit.

## 📋 Game Rules

- Starting balance: chosen by the player.
- Number of rows: 3.
- Number of columns: 3.
- Minimum bet per line: `$1`.
- Maximum bet per line: `$100`.
- Maximum number of betting lines: 3.
- A winning line occurs when all symbols in that line match.
- Winnings depend on the symbol's value and the bet per line.

### Symbol Values

| Symbol | Approximate frequency in the symbol pool | Value multiplier |
|---|---:|---:|
| A | 2 | 5× |
| B | 4 | 4× |
| C | 6 | 3× |
| D | 8 | 2× |

The payout is calculated as:

`symbol value × bet per line`

## ▶️ Run Locally

### 1. Install Python

Install Python 3 if it is not already installed: https://www.python.org/downloads/

### 2. Download or clone this repository

If the project is on GitHub, clone it with:

```bash
git clone <your-repository-url>
```

Or download the repository as a ZIP file and extract it.

### 3. Open the project folder

Open the folder in VS Code or your terminal.

### 4. Run the game

Save the code in a file such as `slot_machine.py`, then run:

```bash
python slot_machine.py
```

On some Windows setups, you may need:

```bash
py slot_machine.py
```

## 📁 Project Structure

```text
slot-machine-game/
├── slot_machine.py
└── README.md
```

## 📚 Concepts Practiced

This project is useful for practicing:

- Variables and constants
- Dictionaries and lists
- `while` and `for` loops
- Functions and return values
- Conditional statements
- User input and validation
- Random selection with `random.choice()`
- Nested loops
- Basic game logic and balance calculations

## 🚀 Possible Improvements

- Add colored symbols and a more visual interface.
- Add a transaction or spin history.
- Save the player's balance between sessions.
- Add automated tests for the winning logic.
- Improve input handling to support decimal bets, if desired.

## 👨‍💻 Author

Created as a Python practice project.

---

**Note:** This is a learning project for educational purposes. It does not use real money.
