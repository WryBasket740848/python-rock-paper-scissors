# Rock Paper Scissors Game in Python

## Overview

This project is a simple command-line implementation of the classic Rock, Paper, Scissors game using Python.

The player competes against the computer by choosing Rock, Paper, or Scissors. The computer randomly selects its choice, and the program determines the winner based on the game rules.

---

## Features

* Interactive Command-Line Gameplay
* Random Computer Moves
* Input Validation
* Winner Determination Logic
* Play Again Option
* Beginner-Friendly Python Project

---

## Technologies Used

* Python
* Random Module

---

## Game Rules

* Rock beats Scissors
* Scissors beats Paper
* Paper beats Rock
* If both choose the same option, the game ends in a tie

---

## Project Structure

```text
Rock-Paper-Scissors/
│
├── rock_paper_scissors.py
├── README.md
```

---

## Requirements

Python 3.x

No external libraries are required.

---

## Running the Program

Open a terminal and run:

```bash
python rock_paper_scissors.py
```

---

## Example Gameplay

```text
Enter your choice (Rock, Paper, or Scissors): rock

You chose: rock
Computer chose: scissors

You win!

Do you want to play again? (yes/no): yes
```

---

## How It Works

### User Input

The program asks the player to choose:

* Rock
* Paper
* Scissors

Input is automatically converted to lowercase and validated.

### Computer Choice

The computer randomly selects one of:

* Rock
* Paper
* Scissors

### Winner Calculation

The program compares both choices and determines:

* Player Wins
* Computer Wins
* Tie

### Replay Feature

After each round, the player can choose to:

* Play Again
* Exit the Game

---

## Learning Outcomes

This project helps beginners understand:

* Functions in Python
* Conditional Statements
* Loops
* User Input Handling
* Random Number Generation
* Basic Game Logic

---

## Future Improvements

* Graphical User Interface (GUI)
* Score Tracking
* Multiplayer Mode
* Best of 3 / Best of 5 Matches
* Sound Effects
* Streamlit Web Version

---

## Sample Output

```text
Enter your choice (Rock, Paper, or Scissors): paper

You chose: paper
Computer chose: rock

You win!
```

---

## Author

Amal

Computer Science Student

Interested in:

* Python Development
* Artificial Intelligence
* Machine Learning
* Generative AI
* Software Development

---

## License

This project is open-source and available under the MIT License.
