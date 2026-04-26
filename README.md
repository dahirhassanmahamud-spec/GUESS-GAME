# GUESS-GAME
My second guessing game program build using python 
# Number Guessing Game

This repository contains a dynamic, console-based **Number Guessing Game** implemented in Python. The application challenges users to identify a randomly generated integer within a specific range, utilizing progressive difficulty scaling and robust input validation.

---

## Features

* **Progressive Difficulty:** Each consecutive round increases the range of possible numbers by 50, raising the challenge as the player advances.
* **Attempt Limitation:** Players must identify the secret number within 7 attempts, requiring strategic deduction.
* **Intelligent Feedback:** The program provides "Too high" or "Too low" hints after each incorrect guess to guide the user toward the correct value.
* **Input Validation:** Built-in exception handling ensures that non-numeric inputs do not crash the program or consume a turn.
* **Session Management:** Users can play multiple rounds seamlessly or exit at their discretion after a game concludes.

---

## Technical Specifications

### Core Logic
The program is built using a nested loop structure:
1.  **The Outer Loop:** Manages game rounds and difficulty scaling ($max\_number$).
2.  **The Inner Loop:** Handles the turn-based logic, tracking the number of attempts and validating user input.
3.  **Randomization:** Utilizes Python's `random.randint` to ensure a uniform distribution of secret numbers.

### Implementation Details
* **Language:** Python 3.x
* **Modules:** `random`
* **Error Handling:** Implements `try-except` blocks to catch `ValueError` during integer casting of user input.

---

## How to Run

1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/yourusername/number-guessing-game.git
    ```
2.  **Navigate to the Directory:**
    ```bash
    cd number-guessing-game
    ```
3.  **Execute the Script:**
    ```bash
    python guessing_game.py
    ```

---

## Game Rules

1.  At the start of each round, a **Secret Number** is generated between 1 and the current maximum.
2.  You have **7 attempts** to guess the number.
3.  After each guess, the system will tell you if your guess was too high or too low.
4.  If you guess correctly, you move to the next round with an increased range.
5.  If you run out of attempts, the game reveals the number and asks if you wish to restart.

---

## Project Structure

| File | Description |
| :--- | :--- |
| `guessing_game.py` | The main executable script containing all game logic. |
| `README.md` | Documentation and instructions for the project. |

---

## Future Improvements

* Implement a persistent high-score system using file I/O.
* Add customizable difficulty levels (Easy, Medium, Hard).
* Create a Graphical User Interface (GUI) using Tkinter.
  ## Developer Information
  Name: Mohamud Dahir Hassan
  Reg.No : 25/BCC/BU/R/0014
  
