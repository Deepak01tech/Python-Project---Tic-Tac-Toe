🟢 Tic-Tac-Toe GUI Game
A simple 2-player Tic-Tac-Toe (X/O) game built using Python's tkinter module. This project provides a fun and interactive way for two players to compete in a classic game with a user-friendly graphical interface.

🧩 Features
3x3 grid interface built with Tkinter

Turn-based gameplay for Player 'X' and Player 'O'

Random starting player

Automatic win detection

Draw detection with alert

Automatic board reset after each game

🖥️ GUI Preview
The interface consists of:

A 3x3 button grid

A label showing the current player's turn

Pop-up messages for win and draw outcomes

🚀 How to Run
Make sure you have Python installed (version 3.x).

Save the code to a file, e.g., tic_tac_toe.py.

Run the script using:

bash
Copy
Edit
python tic_tac_toe.py
📦 Requirements
Python 3.x

tkinter (usually comes pre-installed with Python)

To verify tkinter is installed, run:

bash
Copy
Edit
python -m tkinter
If the window opens successfully, tkinter is available. If not, you may need to install it manually depending on your OS:

On Ubuntu/Debian:
bash
Copy
Edit
sudo apt-get install python3-tk
On Fedora:
bash
Copy
Edit
sudo dnf install python3-tkinter
On Windows:
tkinter is included with standard Python installers.

🛠️ Code Overview
button(frame): Creates a styled button.

change_a(): Switches current player.

reset(): Resets the board after a game ends.

check(): Checks win/draw conditions.

click(row, col): Handles player's move.

The game grid is managed using a nested list b.

📄 License
This project is open-source and free to use.

