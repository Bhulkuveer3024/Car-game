# Car-game

This is a simple car racing game created using Pygame. The objective of the game is to avoid colliding with other vehicles while driving on the road. The game gets progressively faster as you avoid more vehicles.

Requirements

Python 3.x
Pygame 2.x
Installation :

Install Python and Pygame if you haven't already.
Clone this repository or download the source code as a zip file.
Navigate to the project directory in your terminal or command prompt.
Run the following command to start the game: python car_game.py


Gameplay:

Use the left and right arrow keys to change lanes. The car will automatically move forward. Avoid colliding with other vehicles by changing lanes to create space. The game gets progressively faster as you avoid more vehicles.

Scoring:

You score 1 point for every vehicle you avoid. Your score is displayed on the screen.

Game Over:

The game ends when you collide with another vehicle. A game over screen will be displayed with your final score. Press 'Y' to play again or 'N' to exit the game.

Code Structure:

The code is organized into the following files:

car_game.py: The main file that runs the game.
vehicle.py: Contains the Vehicle class that represents a vehicle in the game.
player.py: Contains the Player class that represents the player's car.
constants.py: Contains constants used throughout the code.
