# Memory Card Game

A fun and engaging memory card game built using HTML, CSS, and JavaScript. The game challenges players to match pairs of cards featuring various emojis.

## Features

- Start and replay functionality
- Tracks the number of moves and the time taken
- Engaging animations and a responsive design
- Visual feedback for matched pairs and winning the game

## Installation

1. Clone the repository or download the ZIP file.
2. Extract the files to your desired location.

## Usage

1. Open `index.html` in your web browser.
2. Click the "Start" button to begin the game.
3. Flip the cards to find matching pairs.
4. The game ends when all pairs are matched. Click "Replay" to start a new game.

## Files

- `index.html`: The main HTML file containing the structure of the game.
- `style.css`: The CSS file containing styles and animations for the game.
- `script.js`: The JavaScript file containing the game logic.

## Game Logic

### JavaScript (script.js)

- **Selectors**: Various DOM elements are selected using `document.querySelector`.
- **State Management**: The game state is managed using an object that tracks if the game has started, the number of flipped cards, total flips, total time, and a loop for the timer.
- **Shuffling**: A function to shuffle the cards and distribute them randomly on the board.
- **Game Initialization**: The `generateGame` function sets up the board with a specific number of cards.
- **Game Start**: The `startGame` function initializes the game timer and updates the UI.
- **Card Flipping**: The `flipCard` function handles the logic for flipping cards, checking for matches, and updating the game state.
- **Event Listeners**: Event listeners are attached to handle user interactions with the cards and the start button.

### CSS (style.css)

- **General Styles**: Basic styles for the HTML and body to set dimensions and font.
- **Game Layout**: Styles for positioning the game elements in the center of the screen.
- **Controls**: Styles for the start button and game stats.
- **Board and Cards**: Styles for the game board and individual cards, including the flipping animation.
- **Win Screen**: Styles for the win message that appears when the game is completed.
- **Media Queries**: Responsive styles to ensure the game looks good on smaller screens.

## How to Customize

- **Changing Emojis**: Update the array of emojis in the `generateGame` function to include different icons.
- **Board Size**: Change the `data-dimension` attribute in the HTML to create a board with different dimensions.

## License

This project is open source and available under the MIT License.

