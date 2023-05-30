
# Tic Tac Toe

This code is for a Tic Tac Toe game played on a 9x9 board. The game allows two players, referred to as user 1 and user 2, to take turns making moves on the board and checks for win conditions after each move.


## Authors

- [https://github.com/RafidBinBakhtiar


## Documentation

This code is for a Tic Tac Toe game played on a 9x9 board. The game allows two players, referred to as user 1 and user 2, to take turns making moves on the board. Here's a breakdown of the code:

1. The initial state of the game board is represented by the variable `dash_list`, which is a list of lists containing dashes ("-") to indicate empty spaces on the board.

2. The `board` function is used to display the current state of the game board.

3. The `validinp` function checks the validity of the user's input. It ensures that the input is a number between 1 and 9.

4. The `check_win` function checks if the current player has won the game. It checks for three conditions: horizontal, vertical, and diagonal lines of the same symbol (X or O) on the board.

5. The `checkrow` function checks each row on the board for a win condition.

6. The `checkcol` function checks each column on the board for a win condition.

7. The `checkdiag` function checks the two diagonals on the board for a win condition.

8. The `istaken` function checks if a particular position on the board is already filled or not.

9. The `add` function adds the player's symbol (X or O) to the specified position on the board if it's not already taken.

10. The `coordinates` function converts the user's input (a number between 1 and 9) into the corresponding row and column coordinates on the board.

11. The `curr_user` function determines the current active user based on the turn.

12. The `turned` function toggles the turn between the two players.

13. The main part of the code is a while loop that continues until there have been 9 moves or one of the players wins.

14. Inside the loop, the active user is determined, and their input is obtained.

15. If the user enters "q" or "Q", the game ends.

16. The input is validated, and if it's invalid, an error message is displayed.

17. The coordinates are calculated from the input, and if the position is already taken, an error message is displayed.

18. If the position is valid and available, the player's symbol is added to that position on the board.

19. After each move, the `check_win` function is called to check if the active player has won the game.

20. The count is incremented to keep track of the number of moves.

21. If the count reaches 9 without any winner, it is declared a tie.

22. Finally, the turn is toggled, and the loop continues for the next player's turn.

That's a summary of how the code works.
## FAQ

#### Does this code allows manually toggle between users?

No, it automatically starts with user 1 as default turn as "X"
followed by turn "O".

#### What does the "turn = not turn" does?

This mainly toggles the user.

