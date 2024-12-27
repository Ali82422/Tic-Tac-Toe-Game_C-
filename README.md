Introduction to Tic-Tac-Toe Game in C++

Tic-Tac-Toe is a simple game that is very popular and is played on a 3x3 grid, where two players take turns marking their move on the grid with either 'X' or 'O'. The first player to get three of these marks in a row either horizontally, vertically, or diagonally wins.

This C++ implementation adds a twist to the classic game by giving the player an option to play in two different modes:

    Player vs. Player (1v1): Here, two human players play their turns on the same computer. Player 1 uses 'X', and Player 2 uses 'O'. The game continues until one of the players wins or when all the spots are filled, the result is a draw.

Player vs. Computer: In this option, one player plays against the computer. The player uses 'X' and the computer 'O'. The computer's choice can either be random or programmed using some kind of basic AI. This continues until either the player wins, or the computer wins, or else there is a draw where no more spaces are available on the board.

The game board is a 3x3 grid, and after each move, the updated board is displayed to both players. A player, or the human player in the case of Player vs. Computer, selects a spot by entering a number between 1 and 9, corresponding to an available position on the board.

This C++ version enables the user to:

Select their preferred game mode (Player vs. Player or Player vs. Computer).
    Take turns making moves.
    Have the computer make random moves (or implement basic AI for more challenge).
    Check the game for a winner after each move, or declare a draw when the board is full and no one wins.

This version of Tic-Tac-Toe is a fun and engaging way to practice programming logic while offering the flexibility of either playing with another person or challenging the computer.
