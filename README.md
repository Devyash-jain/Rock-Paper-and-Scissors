
Here's a `README.md` file suitable for uploading your **Rock, Paper, Scissors** Python game to GitHub. It includes a project description, features, instructions, and usage details:

---

## 🪨 Rock, Paper, Scissors Game 🎮

A simple **Rock, Paper, Scissors** game implemented in Python. This project demonstrates the use of conditionals, user input, and basic game logic to simulate a match between a user and the computer.

---

### 📜 Description

This command-line Rock, Paper, Scissors game allows the player to choose between rock, paper, or scissors by typing a number (0, 1, or 2). The computer randomly selects a choice, and the game compares both inputs to determine the winner.

---

### ✨ Features

* ASCII art representation of rock, paper, and scissors.
* Random computer move generation.
* Proper input handling.
* Simple and fun gameplay.

---

### 🛠️ Requirements

* Python 3.x

No external libraries are required except for Python's built-in `random` module.

---

### ▶️ How to Run

1. Clone the repository or download the `.py` file:

   ```bash
   git clone https://github.com/Devyash-jain/Rock-Paper-and-Scissors.git
   cd rock-paper-scissors-python
   ```

2. Run the game:

   ```bash
   python rock_paper_scissors.py
   ```

3. Follow the on-screen instructions to play:

   ```
   What do you choose? Type 0 for Rock, 1 for Paper or 2 for Scissors.
   ```

---

### 🧠 Game Logic

* Rock (0) beats Scissors (2)
* Scissors (2) beats Paper (1)
* Paper (1) beats Rock (0)
* Same choices result in a draw

Invalid inputs result in an automatic loss.

---

### 📁 File Structure

```
rock-paper-scissors-python/
│
├── rock_paper_scissors.py   # Main game script
└── README.md                # Project documentation
```

---

### 💡 Example Output

```
What do you choose? Type 0 for Rock, 1 for Paper or 2 for Scissors.
1

    _______
---'   ____)____
          ______)
          _______)
         _______)
---.__________)

Computer chose:

    _______
---'   ____)
      (_____)
      (_____)
      (____)
---.__(___)

You win!
```
