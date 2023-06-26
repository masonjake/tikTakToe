# Tik Tak Toe Game!

This is a simple tik-tak-toe game where each player switches off trying to match 3 squares in a row so they fit their symbol (X or O).

### Roadmap of Future Improvements

1. Add error handling to prevent a user from changing the square after it has been clicked
   I will add an alert that will prevent the user from changing the square as well as prevent the state from being updated if it has already been clicked. Furthermore, I will add the attribute `disabled` to the square to prevent the user from clicking it again.
2. Add a reset button to clear the board and start a new game.
   I will add a button that will reset the state of the board to all empty squares. I will doing this by checking if a winner has been declared and if so, I will reset the state of the board to all empty squares by using useEffect. I also create a button attached to a function that will reset the state of the board to all empty squares and then call that function when the button is clicked.
3. Add a score board to keep track of the number of wins for each player.
   The score board will be its own component that holds the state overtime of the number of wins for each player. I will also add a function that will update the state of the score board overtime a player wins. I will also add a function that will reset the state of the score board to 0 for each player.
4. Add a feature to allow the user to choose their symbol (X or O).
   This will also be attached to a custom name that the player can use. Above the scoreboard there will be the names and symbols of each player. I will implement this by creating a form for each player when the game begins. The form will have its own state that will be updated when the user submits the form. I will also add a function that will reset the state of the form to empty strings when the reset button is clicked.
