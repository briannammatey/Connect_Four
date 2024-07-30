# Connect Four Project
## Motivation 
My motivation behind this code was the game Connect Four, and it was incredibly fun to make

## Features
### Board Class
The purpose of this class is to set the board, and the rules  of the game
#### add_checker function:
adds the specified checker (either 'X' or 'O') to the
 column with the specified index col in the called Board.
inputs: checker is either 'X' or 'O' col is a valid column index

#### reset function:
Resets the board so that the board can be empty

#### add_checkers function
 takes a string of column numbers and places alternating
 checkers in those columns of the called Board object,
starting with 'X'.
input: colnums is a string of valid column numbers
#### can_add_to
iterates if we are able to add more in the column
#### is_full:
iterates if the colnums is full or not
#### remove_checker:
removes checkers from each slot that is proposed
#### is_win_for:
 iterates if there is a win by calling the other functions

#### is_horizontal_win:
checks for a horizontal win for the specified checker.
#### is_vertical_win:
checks if there is a vertical win
#### is_down_diagnol_win:
 checks if there is a down diagnol win
#### is_up_diagonol_win:
checks if there is an up diagnol win"
### Player Class
This class is the player class and processes the players move
#### opponent_checker:
returns the players checker
#### next_move:
return the player's next move"

### Main Connect Four game
#### connect_four
 Plays a game of Connect Four between the two specified players,
and returns the Board object as it looks at the end of the game.
 inputs: p1 and p2 are objects representing Connect Four
players (objects of the class Player or a subclass of Player).
One player should use 'X' checkers and the other player should
  use 'O' checkers.

#### process_move
takes two parameters: a Player object p for the player whose move is being processed, and a Board object b for the board on which the game is being played.
returns an output based on the input and returns a string based of it's a win or a tie'
### Random Player Class
class that has a player that randomly chooses to place a random checker, randomly


### AI Player Class

#### max_score_column
 input:scores  outputs: determines the max score to add to the list and breaks the Tie break

#### scores_for:
  input: takes in a board output: iterates the board to set the scores for each columns;  predicts the opponnents moves and iterate the columns scores based on it
###

#### next_move
Takes in the board object and use max_score_column to 
 put the max for amount from the scores for function
