# Snake Game

## Created by Apeksha Mankar

This is a simple implementation of the classic Snake game using Python and Tkinter. The player controls a snake that moves around the screen, eating food and growing longer with each meal while avoiding collisions with the walls and itself.

## Features

- Basic Gameplay: The snake moves in a specified direction and can change direction using arrow keys.
- Food Collection: The snake collects food items that randomly appear on the screen, increasing the player's score.
- Collision Detection: The game detects collisions with the walls and with the snake's own body, leading to game over conditions.
- Score Tracking: The current score is displayed, updating each time the snake eats food.

## Technologies Used

- Python: Main programming language used for the game logic.
- Tkinter: Python library used for creating the GUI.

## Game Controls

- Use the arrow keys to change the direction of the snake:
  - Up Arrow: Move Up
  - Down Arrow: Move Down
  - Left Arrow: Move Left
  - Right Arrow: Move Right

## Code Overview

## Key Classes

- Snake: Manages the snake's body, movement, and growth.
- Food: Manages the food's appearance and random placement on the game board.

## Functions

- next_turn(snake, food): Updates the snake's position and checks for food collection or collisions.
- change_direction(new_direction): Changes the snake's movement direction based on user input.
- check_collision(snake): Checks if the snake has collided with the walls or itself.
- game_over(): Displays a game over message when the player loses.