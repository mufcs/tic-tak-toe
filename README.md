
#Heading Project0 (tic tak toe)

#Subheadings High level functional requirement

### Lists

* As a game
I want to be Tic-tac-toe
so that players can play me.

* As a game
I want to have 3×3 board
so that players have an ability to mark on cell/s.

* As a game
I want to have two players player 1 and player 2
so that players can play with each other.

* As a player 1
I want to have an ability to mark "X" on any of the empty cell
so that I can figure out which cell/s I have chosen.

* As a player 2
I want to have an ability to mark "O" on any of the empty cell
so that I can figure out which cell/s I have chosen.

* As a player 1
I want to win when I get three of "X" marks in a horizontal, vertical or diagonal row
so that I can feel happy.

* As a player 2
I want to win when I get three of "O" marks in a horizontal, vertical or diagonal row
so that I can feel happy.

* As a player
I want to draw when all nine cells contains a mark and none have three marks in a row
so that the game can be played again.

* As a player
I want to have an ability to re-set the game on winning, loosing or draw
so that I can play again.


# Subheadings High level technical overview of this project:

* Build a board which is composed of a 3 x 3 square cells.
* There must be two players, "X" and "O". Player "X" always makes the first move.
* On mouse hover, in any of the empty cell/s their must be an indication of who the next player is (i.e. "X" or "O").
* On mouse click, in any of the empty cell/s there must be "X" and "O" sign marked depending on player's turn.
* On mouse hover, in any of the marked cell/s (i.e. "X" and "O") not allowed sign must be shown.
* Define the winning combination as per the board.
* Define the draw combination as per the board.
* Show message to the players on win.
* Show message to the player when draw.
* Once the game result is decided (either X wins, O wins, or draw) no more moves allowed.
* There must be a restart button for players to restart the game depending on "Win" or "Draw".
* On restart, the game must function as per the above conditions.

Applied CSS tricks:
