This project implements the popular 2048 game in Python. The game involves sliding numbered tiles on a grid to combine them and create a tile with the number 2048.

Features
Interactive Gameplay: Play the classic 2048 game with a user-friendly interface.
Keyboard Controls: Use arrow keys to move tiles in four directions.
Score Tracking: Keep track of your score as you combine tiles.
Game Over Detection: The game ends when there are no valid moves left.

Technologies Used
Python: The primary programming language for the implementation.
Pygame: A library for creating games in Python, used for rendering graphics and handling user input.

Installation
To run this project locally, follow these steps:

1.Clone the repository:
git clone https://github.com/yourusername/2048-game-python.git

2.Navigate to the project directory:
cd 2048-game-python

3.Install the required libraries:
pip install pygame

Usage
1.Start the game by running the following command:
python main.py
2.Use the arrow keys (up, down, left, right) to move the tiles.

Game Rules
1.The game is played on a 4x4 grid.
2.Each turn, you slide all tiles in one of the four directions (up, down, left, right).
3.When two tiles with the same number collide, they merge into one tile with their sum.
4.The objective is to create a tile with the number 2048.

How to Play
1.When the game starts, a tile with the number 2 or 4 appears randomly on the grid.
2.Use the arrow keys to slide tiles:
  Up Arrow: Move tiles up
  Down Arrow: Move tiles down
  Left Arrow: Move tiles left
  Right Arrow: Move tiles right
3.Combine tiles to create higher-numbered tiles.
4.The game ends when you create the tile 2048 or when there are no valid moves left.

Contributing
Contributions are welcome! If you have suggestions for improvements or new features, please create a pull request or open an issue.
