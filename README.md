
🎮 Hangman Game – Python

A simple and interactive Hangman Game built using Python.
This project is a console-based word guessing game where the player tries to guess a randomly selected word by entering one letter at a time.

The project was developed as a practical Python programming project to strengthen fundamental programming concepts such as loops, conditional statements, functions, lists, strings, user input, and the "random" module.

---

📌 About the Project

Hangman is a classic word-guessing game.

In this version, the computer randomly selects a word from a predefined list. The selected word is hidden from the player, and the player has to guess it one letter at a time.

For every correct guess, the letter is revealed in its correct position. For every incorrect guess, the player loses one attempt.

The game ends when:

- The player successfully guesses the complete word 🎉
- The player uses all available attempts ❌

---

✨ Features

- 🎲 Random word selection
- 🔤 Letter-by-letter word guessing
- ✅ Displays correctly guessed letters
- ❌ Tracks incorrect guesses
- ❤️ Limited number of attempts
- 📊 Displays the current progress of the word
- 🏆 Win and lose conditions
- 🖥️ Simple console-based interface
- 🐍 Built using Python without external libraries

---

🛠️ Technologies Used

Technology| Purpose
Python| Main programming language
Random Module| Randomly selects a word

The project uses only Python's built-in functionality, so no external packages are required.

---

🧠 Concepts Used

This project helped in practicing the following Python concepts:

- Variables
- Strings
- Lists
- Conditional statements ("if", "elif", "else")
- "for" loops
- "while" loops
- Functions
- User input using "input()"
- The "random" module
- String manipulation
- Boolean conditions
- Basic problem-solving and game logic

---

⚙️ How the Game Works

Step 1 – Select a Word

The program contains a list of possible words.

The "random" module is used to select one word randomly.

Step 2 – Hide the Word

The selected word is hidden from the player and represented using underscores.

For example:

_ _ _ _ _ _

Step 3 – Enter a Guess

The player enters a letter.

For example:

Enter a letter: p

Step 4 – Check the Guess

The program checks whether the entered letter exists in the selected word.

If the letter is correct, its position is revealed.

Example:

p _ _ _ _ _

If the letter is incorrect, the player loses an attempt.

Step 5 – Continue the Game

The player continues guessing letters until:

- Every letter in the word has been guessed, or
- All available attempts have been used.

---

🎮 Example Gameplay

Welcome to Hangman!

Word: _ _ _ _ _ _

Guess a letter: p

Correct guess!

Word: p _ _ _ _ _

Guess a letter: x

Wrong guess!

Remaining attempts: 5

The actual output depends on the randomly selected word and the player's guesses.

---

▶️ How to Run

Prerequisites

Make sure Python 3 is installed on your computer.

Check the installed version:

python --version

1. Clone the Repository

git clone <YOUR-GITHUB-REPOSITORY-LINK>

2. Open the Project Folder

cd Hangman-Game-Python

3. Run the Program

python hangman.py

The game will start in the terminal.

---

📂 Project Structure

Hangman-Game-Python/
│
├── hangman.py
│
└── README.md

"hangman.py"

Contains the complete source code and game logic.

"README.md"

Contains the documentation, setup instructions, features, and information about the project.

---

🎯 Project Objectives

The main objectives of this project are:

- To practice Python programming fundamentals
- To understand loops and conditional logic
- To work with lists and strings
- To handle user input
- To implement random word selection
- To develop basic problem-solving skills
- To build a functional Python project from scratch

---

🚀 Future Improvements

The project can be improved further by adding:

- 🎨 Graphical User Interface (GUI)
- 📚 Larger word database
- 🎚️ Easy, Medium, and Hard difficulty levels
- 🏆 Score system
- 🔄 Replay option
- 💡 Hint system
- 📊 Win/loss statistics
- 👥 Two-player mode
- 🔊 Sound effects
- 🖼️ Visual Hangman stages

---

📈 Learning Outcome

Building this project helped me understand how basic Python concepts can be combined to create an interactive application.

It improved my understanding of:

- Program flow
- Loops and conditions
- Functions
- User input
- Randomization
- String and list operations
- Debugging
- Basic application development

---

👩‍💻 Author

Akshita

BCA Student | Python Learner | Aspiring Software Developer

---

📌 Project Type

Python Programming Project

Category: Console-Based Game

Language: Python 3

---

⭐ Acknowledgement

This project was created as part of my Python programming learning journey and internship project work.

---

📜 License

This project is created for educational and learning purposes.