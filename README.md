# Snake Game in Python (No Pygame)

## Project Description

This project is a **classic Snake game** implemented in **Python**, built without the use of external libraries like Pygame. The game runs in the terminal/console, allowing users to control a snake, eat food, and grow longer while avoiding collisions with walls or itself.

## Features

- **Console-based Gameplay**: The game is rendered entirely in the console.
- **Snake Movement**: Control the snake using keyboard inputs (e.g., arrow keys or WASD).
- **Food Generation**: Random food is placed on the grid, which the snake eats to grow.
- **Score Tracking**: The score increases as the snake eats more food.
- **Game Over**: The game ends if the snake collides with itself or the screen borders.

## Technologies Used

- **Python 3.x**: The only programming language and tool used for the implementation.
- **Built-in Modules**: Python modules like `curses` (for handling keyboard input and rendering in the terminal) or `sys` and `time` (for controlling the game loop).

## How to Run the Project

1. **Install Python**: Ensure that you have Python installed on your machine. You can download it from [here](https://www.python.org/downloads/).

2. **Clone the repository**:
   
   git clone https://github.com/tomwooly/snake-game.git

3. **Navigate to the project directory**:
   
   cd snake-game
  
4. **Run the game**:
  
   python snake_game.py

## Code Overview

The code consists of the following key components:

1. **Game Grid**: The snake and food are displayed on a grid that is rendered in the console. The grid updates with each move.
2. **Snake Movement**: The snake's movement is controlled by keyboard input. The user can navigate the snake with the arrow keys (or WASD keys).
3. **Food Generation**: Food is randomly generated within the grid boundaries.
4. **Collision Detection**: The game checks for collisions between the snake and the walls or itself, triggering the game over state.
5. **Game Loop**: The game continuously runs in a loop, handling updates for the snake's movement, rendering the grid, and processing user input.

### Sample Code Snippets

- **Snake Movement**: The direction of the snake is controlled by detecting user input from the keyboard and updating the position accordingly.
- **Food Placement**: Food is randomly placed on the grid using Python’s `random` module.

## Project Demo

You can view a demo of the game running in the terminal [here].

## Future Enhancements

- **Improved Graphics**: Explore rendering options to improve the visual appearance of the game (e.g., colored blocks for the snake).
- **Level System**: Introduce levels with increasing difficulty or larger grid sizes.
- **Leaderboard**: Implement a feature to track and display high scores.
- **Pause/Resume**: Add functionality to pause and resume the game.

## Acknowledgments

- Thanks to [Python Documentation](https://docs.python.org/3/) for providing resources on handling keyboard input and console rendering.
- 100 Days of Code: The Complete Python Pro Bootcamp by Dr Angela Yu.
- Inspired by the classic Snake game, recreated in a simple, console-friendly format.

---
