# Turtle Crossy Road

This is a simple Python game where the player navigates a character across a busy road filled with moving cars. The goal is to safely reach the other side without getting hit by a car.

## Requirements
- Python 3.x
- Turtle module

## How to Play
1. Run the `main.py` file.
2. Use the "Up" arrow key to move the player character upwards.
3. Avoid getting hit by the cars moving across the road.
4. Safely reach the other side of the road to score points.
5. The game gets progressively harder as you advance levels.

## Files
- `main.py`: Contains the main game loop and setup.
- `player.py`: Defines the Player class responsible for player movement.
- `car_manager.py`: Manages the cars moving on the road.
- `scoreboard.py`: Keeps track of the player's score and level.

## How It Works
- The game window is set up using the Turtle module.
- The player can move their character up using the "Up" arrow key.
- Cars are generated and move from the right side of the screen to the left.
- Collision detection is used to determine if the player character collides with any cars.
- If the player reaches the other side safely, the level increases, making the game more challenging.
