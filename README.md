Snake Ladder Game
This is a Snake Ladder game implemented using HTML, CSS, and JavaScript. The game provides a classic board game experience where players navigate through a grid-like board filled with snakes and ladders.

How to Play
Open the index.html file in a web browser to start the game.

The game board will be displayed, consisting of a grid with numbered cells.

Players take turns rolling a dice and moving their game pieces forward based on the number rolled.

If a player lands on the bottom of a ladder, they automatically climb to the higher numbered cell.

If a player lands on the head of a snake, they slide down to the lower numbered cell.

The game continues until one of the players reaches or surpasses the last cell on the board, indicating victory.

Customization
You can customize the number of players by modifying the playerCount variable in the JavaScript file (script.js).

The number of cells on the game board can be adjusted by modifying the totalCells variable in the JavaScript file.

You can add or remove snakes and ladders by modifying the snakes and ladders arrays in the JavaScript file. Each array entry consists of an object with start and end properties indicating the cell numbers where the snake or ladder starts and ends.

File Structure
index.html: The main HTML file that displays the game board and handles user interactions.

game.css: The CSS file containing styles for the game board and elements.

game.js: The JavaScript file that implements the game logic and handles user input.

Compatibility
This game has been tested and confirmed to work on modern web browsers such as Google Chrome, Mozilla Firefox, and Microsoft Edge.

Credits
This game was created by Raja Bhavesh as a Web Development project.

The project is inspired by the classic Snake and Ladder board game.
