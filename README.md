# JavaScript Snake Game

The JavaScript code provided implements a simple Snake game using the HTML5 canvas element. Here's a breakdown of its functionality:

1. **Initialization**: The necessary DOM elements such as the canvas (`gameBoard`), score display (`scoreText`), and reset button (`resetBtn`) are selected.

2. **Game Variables**: Variables are declared to store game-related data such as the game dimensions, colors, velocities, and the initial snake position.

3. **Event Listeners**: Event listeners are set up to handle key presses for changing the snake's direction and clicking the reset button to restart the game.

4. **Game Start**: The `gameStart()` function initializes the game state, sets the initial score, creates the food, and starts the game loop.

5. **Game Loop**: The `nextTick()` function controls the game loop. It clears the board, updates the snake's position, draws the snake and food, checks for game over conditions, and schedules the next tick.

6. **Drawing Functions**: Functions like `clearBoard()`, `drawFood()`, and `drawSnake()` are responsible for rendering elements on the canvas.

7. **Movement**: The snake's movement is handled by the `moveSnake()` function. It updates the snake's position based on its velocity and checks for collisions with the food.

8. **Direction Change**: The `changeDirection()` function listens for arrow key presses and changes the snake's direction accordingly, ensuring the snake cannot reverse its direction instantly.

9. **Collision Detection**: The `checkGameOver()` function checks for collisions between the snake and the game boundaries or itself. If a collision is detected, the game ends.

10. **Game Over Display**: The `displayGameOver()` function renders a "GAME OVER" message on the canvas when the game ends.

11. **Resetting the Game**: The `resetGame()` function resets the game state, including the score, snake position, and velocity, allowing the player to restart the game.

This code provides a foundation for a basic Snake game with functionality for movement, collision detection, scoring, and game over conditions.


<img width="512" alt="image" src="https://github.com/nileshrathi99/snake/assets/32071800/4b2cb5d2-2995-4f9c-900b-e49817f09f45">
<img width="512" alt="image" src="https://github.com/nileshrathi99/snake/assets/32071800/e9401df9-a286-45d5-8699-f78e73971713">
<img width="512" alt="image" src="https://github.com/nileshrathi99/snake/assets/32071800/2302d28e-f77c-45c0-9c11-5a9218818bc6">
