# 🎮 Number Guessing Game
A simple number-guessing game written in Python. The project includes two versions - a classic command-line interface and a GUI version with a standalone Windows executable. Functionally, both work the same, with the big difference being that one runs in a terminal and the other as a desktop app.

## 🛠️ Technology
- `Python`
- `Tkinter`
- `PyInstaller`
- `HTML`

## 🚀 Features
- **Command-line version**: number guessing game playable entirely in the terminal
- **GUI version**: a friendly interface using Tkinter, with input field, messages and buttons
- **Standalone Windows executable**: the GUI version can be run without requiring Python to be installed, packaged as `.exe` for easy distribution
- **Gameplay**: guess a random number between 1 and 10, limited attempts, and feedback (too low / too high) after each guess

## 🧠 The Process
I started this project to try to package a simple Python project into an executable file, and figured a number guesser is as simple a Python project. I first wrote the command-line version to focus on the core logic - random number generation, input handling, attempt limits and feedback. Later, I wanted to see how the game would feel with a user-friendly interface, so I added a GUI version using Tkinter.

To make the GUI version easier to share - and to remove the dependency on Python for end users - I packaged it into a standalone Windows executable using `PyInstaller`. That way, anyone on Windows can run the .exe and play, without needing to install Python or manually run the script.

## 📦 Running the Project
### 1. Command-Line Version
1. Clone or download the repository
2. Make sure Python is installed on your machine
3. Run in terminal/command prompt: python Number_Guess_Game.py

### 1. GUI Version (Executable)
Option 1 - Using the pre-built `.exe`:
1. Download the ZIP from Releases (or the `dist/` folder)
2. Extract contents
3. Double-click `Number_Guess_Game_with_gui.exe` to run

Option 2 - Run from source (requires Python):
1. Clone or download the repository
2. Run with Python: python Number_Guess_Game_with_gui.py

## 🖼️ Preview
https://github.com/user-attachments/assets/3846d13b-4979-4ef1-9c1e-ad61f4a59ac0
