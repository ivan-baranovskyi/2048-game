2048 Game Project Description

This project is a browser-based implementation of the popular game 2048 using JavaScript. The game is played on a 4x4 grid where the player slides numbered tiles in four directions. When two tiles with the same number touch, they merge into one tile with the sum of the two numbers. The goal of the game is to create a tile with the number 2048.

Technologies Used:

JavaScript: The core programming language used to implement the game logic and interactions.
HTML/CSS: Used for structuring the webpage and styling the game interface.
DOM Manipulation: JavaScript is used to dynamically update the game board and handle user interactions.
Event Handling: Keyboard events are used to control tile movement within the game.
Random Number Generation: Random tiles with values 2 or 4 are added to empty cells on the game board.
Merge Logic: Tiles are merged when they collide and have the same value, with the sum of their values replacing them.
Win/Lose Conditions: The game checks for win or loss conditions after each move.
Restart Functionality: Players can restart the game at any time to start over.
Game Mechanics:

The game starts with two randomly placed tiles of value 2 or 4 on the board.
Players use arrow keys to move tiles in up, down, left, or right directions.
When two tiles with the same value collide, they merge into a single tile with the sum of their values.
After each move, a new tile of value 2 or 4 is added to an empty random cell.
The game continues until the player achieves the 2048 tile or there are no possible moves left.
Players can restart the game at any time by clicking the "Restart" button.
Project Structure:

index.html: Contains the structure of the game interface.
styles.css: Stylesheet for styling the game elements.
script.js: JavaScript file containing the game logic and functionality.
README.md: Documentation file providing information about the project, including how to play the game and details about the implementation.

    - [DEMO LINK][(https://ivan-baranovskyi.github.io/2048-game/)
