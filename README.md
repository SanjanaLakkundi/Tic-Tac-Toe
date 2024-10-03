Key Points of the Program:

Win Patterns:
The winPatterns array defines all possible winning combinations in the Tic-Tac-Toe grid (rows, columns, diagonals). This array is crucial for checking whether a player has won after each move.

Turn Tracking:
A boolean variable turnO is used to keep track of which player’s turn it is (O or X).
The display (currentTurnDisplay) is updated after every move to show the next player’s turn.

Check for a Winner:
The function checkWinner checks if any of the win patterns are matched by the current game state. If a match is found, the game ends, and the winner is displayed.

Handling Draw:
A count variable is used to track the number of moves made. If 9 moves are made without a winner, the game ends in a draw, and this is displayed to the user.

Reset Functionality:
The resetGame function resets the game board and player status, allowing a new game to start without reloading the page. This is triggered by clicking the "New Game" or "Reset" buttons.
