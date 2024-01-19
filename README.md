# Snake-Game
This  script is an implementation of the classic Snake game using the Tkinter library for the graphical user interface
Here's a summary of the key components:

### Game Settings:
Constants like GAME_WIDTH, GAME_HEIGHT, SPEED, SPACE_SIZE, BODY_PARTS, SNAKE_COLOR, FOOD_COLOR, and BACKGROUND_COLOR define the game parameters.

### Snake Class:
The Snake class initializes the snake with a specified number of body parts.
Snake coordinates and squares are managed within the class.

### Food Class:
The Food class generates food at random coordinates on the canvas.

### Game Logic:
The next_turn function handles the main game logic, including updating snake position, checking for collisions, and managing the score.
The change_direction function allows the user to control the snake's direction using arrow keys.

### Collision Detection:
The check_collisions function checks for collisions with the walls and the snake's own body.

### Game Over:
The game_over function is called when a collision is detected, displaying a "GAME OVER" message.

### Tkinter GUI:
The script uses Tkinter for the graphical user interface.
A canvas is used to display the game elements, and a label shows the current score.

### Input Handling:
Arrow key bindings ('<Left>', '<Right>', '<Up>', '<Down>') are used to change the snake's direction.

### Window Setup:
The Tkinter window is set up with a fixed size and centered on the screen.

### Main Loop:
The script enters the Tkinter main loop (window.mainloop()) to run the game.
This script allows users to play the classic Snake game with a simple graphical interface. 
