# Simon Game - README

## Overview

This project is a simple implementation of the classic Simon game. The game generates a sequence of colors and the player must repeat the sequence in the same order. Each time the player successfully repeats the sequence, the game adds a new color to the sequence, increasing the difficulty.

## Features

- A colorful interface with four buttons (red, blue, green, yellow).
- A sequence generation algorithm to create random sequences.
- Player interaction through mouse clicks and keyboard presses.
- Sound effects for button presses and game over.
- Game over and restart functionality.

## Technologies Used

- HTML
- CSS
- JavaScript (jQuery)
- Google Fonts
- jQuery Library

## Files

- `index.html`: The main HTML file containing the structure of the game.
- `styles.css`: The CSS file for styling the game.
- `game.js`: The JavaScript file containing the game logic.

## Setup and Usage

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/simon-game.git
   cd simon-game
   ```

2. **Open `index.html` in a web browser**

   Simply double-click on the `index.html` file or right-click and select "Open with" to choose your preferred web browser.

3. **Play the Game Online**

   **The game is deployed and can be played online at: [Simon Game](https://tasmii.github.io/Simon-Game/)**

## Game Instructions

1. **Start the Game**

   - Press any key to start the game.
   - The game will display "Level 0" and generate the first color in the sequence.

2. **Play the Game**

   - Click the buttons in the order shown by the game.
   - The game will add a new color to the sequence each time you successfully repeat the previous sequence.
   - The current level is displayed at the top of the screen.

3. **Game Over**

   - If you click the wrong button, the game will play a "wrong" sound and the screen will flash red.
   - The game will display "Game Over, Press Any Key to Restart".
   - Press any key to restart the game from level 0.

## Code Overview

### HTML (`index.html`)

- Contains the structure of the game including the title and the color buttons.
- Links to the external CSS and JavaScript files.
- Loads the jQuery library and Google Fonts.

### CSS (`styles.css`)

- Styles the game elements including the title, buttons, and game container.
- Defines the appearance of the buttons and different states (e.g., pressed, game over).

### JavaScript (`game.js`)

- Initializes game variables (`gamePattern`, `buttonColours`, `userClickedPattern`, `started`, `level`).
- Listens for keyboard presses to start the game.
- Handles button clicks, updating the user pattern and checking against the game pattern.
- Contains the game logic for sequence generation, checking answers, playing sounds, and animations.

## Dependencies

- jQuery: A fast, small, and feature-rich JavaScript library.

## Additional Notes

- Ensure the sound files (`red.mp3`, `blue.mp3`, `green.mp3`, `yellow.mp3`, `wrong.mp3`) are placed in a folder named `sounds` in the same directory as the `index.html` file.

## Author

- Tasmiya Ilahi
- [GitHub](https://github.com/Tasmii)
