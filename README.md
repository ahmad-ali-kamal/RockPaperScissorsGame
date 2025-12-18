# Rock Paper Scissors Console Game (C++)

## 📌 Project Overview

This project is a **console-based Rock Paper Scissors game** implemented in **C++**. The player competes against the computer over a user-defined number of rounds. Each round, both the player and the computer make a choice, and the winner is determined based on the classic game rules.

The game provides visual feedback using console colors and sound alerts, and displays a detailed summary at the end of the match.

---

## 🎮 Game Features

* Play Rock, Paper, Scissors against the computer
* Choose the number of rounds (1–10)
* Randomized computer choices
* Round-by-round result display
* Console color changes based on win/lose/draw
* Final game statistics and winner announcement
* Option to replay the game

---

## 🛠️ Technologies Used

* **Language:** C++
* **Libraries:**

  * `<iostream>` for input/output
  * `<string>` for text handling
  * `<cstdlib>` for random number generation and system commands

---

## 📂 Project Structure

```
RockPaperScissorsGame/
│── RockPaperScissors.cpp
```

---

## ▶️ How to Run the Game

1. Make sure you have a C++ compiler installed (e.g. **g++**).
2. Compile the program:

   ```bash
   g++ RockPaperScissors.cpp -o RockPaperScissors
   ```
3. Run the executable:

   ```bash
   ./RockPaperScissors
   ```

   *(On Windows, run `RockPaperScissors.exe`)*

---

## 🧠 Game Rules

* **Stone beats Scissor**
* **Paper beats Stone**
* **Scissor beats Paper**
* Same choices result in a draw

---

## 📊 Game Output

At the end of the game, the program displays:

* Total number of rounds
* Player wins
* Computer wins
* Draws
* Final winner

---

## 🚀 Future Improvements

* Input validation for player choices
* Cross-platform console color handling
* Score saving system
* Multiplayer (Player vs Player)
* GUI version

---

## 👤 Author

Ahmed Ali Kamal
Computer Science Student | Backend & AI Enthusiast

## 📄 License

This project is licensed for educational use.

All rights reserved © 2025 Ahmed Ali Kamal.
