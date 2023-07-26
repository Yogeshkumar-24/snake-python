# snake-python
This is a simple snake game created usign python.

# Library  
-> Pygame  
-> Random
# Functions 
The Direction enum defines four directions: RIGHT, LEFT, UP, and DOWN, to represent the snake's movement direction.

The Point named tuple is used to represent a position on the game grid (x, y coordinates).

The SnakeGame class is the main class representing the Snake Game. It handles game initialization, updates, user input, and collision detection.

The game window size is set to 640x480 pixels, and the game runs at a constant speed of 10 frames per second.

The snake and food are represented as rectangles on the screen, and the snake moves in response to the player's arrow key input.

The _place_food() method is used to randomly place the food on the grid, ensuring it doesn't overlap with the snake's body.

The _update_ui() method redraws the game elements on the screen, including the snake, food, and score.

The _move() method updates the snake's head position based on the direction chosen by the player.

The play_step() method handles each step of the game, checking for collisions, updating the snake's position, and checking if the snake has eaten the food or collided with the wall or itself.

The _is_collision() method checks for collisions with the game boundaries or the snake's body.

In the main part of the code, an instance of the SnakeGame class is created, and the game loop starts. The loop continues until the game is over (e.g., when the snake collides). The final score is then displayed.
