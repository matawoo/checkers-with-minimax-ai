# checkers-game-with-minimax
Checkers Game written in Python using an AI opponent based on the Minimax Algorithm. This project was originally created for a submission on a module that focused on AI as part of the University of Sussex degree of Computer Science and Artifical Intelegence. The task of the coursework was to create a checkers game from scratch using Python and PyGame. The AI component is realised through an opponent using the MiniMax algortithm as well as a tool that predicts the best move for the player using the same algorithm. The weighting of the rewards for the AI were left up to the students, so I came up with a few simple algorithms to experiment with agressive AI, smart AI and "fun" AI.

# Required Packages
The following packages are required to run the game.
- pygame >= 2.1.0
- pygame-menu >= 4.2.0

To install these, run:

```python
pip install pygame pygame-menu
```
# Running the Game
The game was written and tested using a conda virtual environment with python 3.8.

To start the game, run the "main.py" file in the root of this project's files.

# Game Setting Warning
The verbose AI setting adds 500ms to each possible AI move as it outputs the move to the player. For this reason, it is ill-advised to run any "Difficulty" of AI beyond Medium with Verbose AI turned on. Additionally, the more challenging levels of AI have complex decision trees, so they can take a long time to compute innately.

# Gameplay Instructions
After the user has set the game conditions they wish to play with from the main menu, they may start by pressing the "Play" button. The user may press the "p" key on the keyboard; this brings up the pause menu. The user can access the "Help" screen from the pause menu, which explains the game's rules and how to play. The user can also access this pause menu by pressing the "i" key on the keyboard. Finally, the user can request a "hint" on the best move to play that round by pressing the "h" key. The game will display a "hint" to the user with two blue dots, one being on the current location of the counter to move and the other being on the location of the square to move the counter.
