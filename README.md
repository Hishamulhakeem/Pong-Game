# Pong Game

A simple Pong game built using Java and Swing for the GUI. This project simulates the classic Pong game where two players control paddles to hit a ball back and forth.

## Features

- Two-player functionality with independent paddle controls.
- Ball speed increases after each paddle hit for added difficulty.
- Score tracking for both players.
- Smooth and responsive gameplay.

## Game Controls

- **Player 1**:
  - Move Up: `W`
  - Move Down: `S`

- **Player 2**:
  - Move Up: `Up Arrow`
  - Move Down: `Down Arrow`

## Project Structure

```
.
├── Ball.java          # Handles ball movement and drawing
├── GameFrame.java     # Main game window
├── GamePanel.java     # Game logic, collision detection, and rendering
├── Paddle.java        # Paddle movement and rendering
├── PongGame.java      # Entry point of the game
└── Score.java         # Score tracking and display
```

## Customization

- **Ball Speed**: Modify the `initialSpeed` in `Ball.java`.
- **Paddle Speed**: Change the `speed` variable in `Paddle.java`.
- **Window Size**: Adjust `GAME_WIDTH` and `GAME_HEIGHT` in `GamePanel.java`.

## Future Improvements

- Add sound effects.
- Implement AI for single-player mode.
- Improve collision detection for better accuracy.

## License

This project is licensed under the MIT License. Feel free to modify and distribute it.

