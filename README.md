# 🎰 Slot Machine

A Python-based console application that simulates a classic casino slot machine. Players can deposit money, place bets on multiple lines, spin the reels, and win rewards based on matching symbols. This mini project demonstrates Python fundamentals such as functions, loops, conditional statements, dictionaries, random number generation, and input validation.

---

## 📖 Overview

The **Slot Machine** project is a command-line game developed using Python. It recreates the basic functionality of a casino slot machine where players deposit money, place bets, spin randomly generated reels, and earn rewards when matching symbols appear on the selected betting lines.

This project was created to strengthen programming fundamentals and understand how real-world game logic can be implemented using Python.

---

## ✨ Features

- 💰 Deposit money before playing
- 🎯 Bet on 1 to 3 lines
- 🎲 Randomly generated slot reels
- 🏆 Winning calculation based on matching symbols
- 💳 Automatic balance management
- ✅ User input validation
- 🔄 Continuous gameplay until the player quits
- ⚡ Lightweight console-based application

---

## 🛠️ Technologies Used

| Technology     | Purpose                       |
| -------------- | ----------------------------- |
| Python 3       | Core programming language     |
| Random Module  | Generates random slot symbols |
| CLI (Console)  | User interaction              |

---

## 📂 Project Structure

```text
Slot-Machine/
│── slot.py
│── README.md
```

---

## ⚙️ How It Works

1. Deposit an initial balance.
2. Choose the number of betting lines (1–3).
3. Enter the bet amount per line.
4. The program generates a random 3×3 slot machine.
5. Matching symbols on a betting line result in winnings.
6. The balance is updated after every spin.
7. Continue playing or quit anytime.

---

## 🎮 Winning Symbols
| Symbol | Multiplier | Frequency   |
| ------ | ---------- | ----------- |
| A      | 5× Bet     | Rare        |
| B      | 4× Bet     | Uncommon    |
| C      | 3× Bet     | Common      |
| D      | 2× Bet     | Very Common |

> Higher-value symbols appear less frequently, increasing the challenge.

---

## 🚀 Installation

### Clone the Repository

```bash
git clone https://github.com/Shreenivhas-18/Slot-Machine.git
```

### Navigate to the Project Folder

```bash
cd Slot-Machine
```

### Run the Program

```bash
python slot.py
```

---

## 📚 Concepts Covered

## 📚 Concepts Covered

- **Functions** – Organizes program logic into reusable blocks
- **Loops** – Controls repeated gameplay
- **Conditional Statements** – Determines winning conditions
- **Dictionaries** – Stores symbol frequencies and payouts
- **Lists** – Represents slot machine columns
- **Random Module** – Generates random slot symbols
- **Input Validation** – Prevents invalid user inputs
- **Game Logic** – Calculates winnings and updates the player's balance
---

## 📸 Sample Gameplay

```text
How much would you like to deposit: ₹1000

Current balance: ₹1000

Would you like to bet on each line (1-3)? 3

How much would you like to bet on each line? ₹50

You are betting ₹50 on 3 lines.

A | B | C
A | A | A
D | C | D

You won ₹250
Winning lines: 2

Current balance: ₹1100
```

---

## 🔮 Future Enhancements

- 🖥️ Graphical User Interface (GUI)
- 🔊 Sound effects
- 🎁 Bonus rounds
- 💎 Jackpot feature
- 📊 Save player statistics
- 🏅 Leaderboard system
- 🎨 Improved game themes
- 👥 Multiplayer mode

---

## 👨‍💻 Author

**Shreenivhas N**

Developed as a Python mini project to practice programming fundamentals, problem-solving, and console-based game development.

---

## 📄 License

This project is intended for **educational and learning purposes**.
