# 🐍 Snake Game in Python  

This is a **classic Snake game** implemented in Python using the **Turtle module**. The game features a growing snake that moves around the screen, eats food to increase its length, and keeps track of the player's high score.  

## 🚀 Features  
- **Snake Movement**: The snake moves in four directions (Up, Down, Left, Right) using keyboard controls.  
- **Food System**: A randomly placed food object that increases the snake's length when eaten.  
- **Scoreboard**: Tracks the player's current score and highest score using a file-based system.  
- **Collision Detection**: Resets the game when the snake hits the wall or collides with its own body.  

## 📁 Project Structure  
```plaintext
├── main.py          # Game loop and main execution file
├── snake.py         # Handles snake movement and behavior
├── food.py          # Manages food generation
├── scoreboard.py    # Manages score tracking and display
├── score.txt        # Stores high score
└── README.md        # Project documentation
