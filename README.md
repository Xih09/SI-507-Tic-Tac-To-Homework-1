Download link : https://programming.engineering/product/si-507-tic-tac-to-homework-1/

SI 507 Tic Tac To Homework # 1
In this assignment you will implement a tic-tac-toe game for two players. If you are unfamiliar with the game, you should look it up so that you understand each piece that you will need to program.

The program will prompt each player for their move and then check to see if anyone has won after each move. If the board fills up and nobody has won, the program will declare the game a tie. You will start with a partially implemented game that has some functions implemented and documented as well as some functions that need to be implemented, documented, or both.

This assignment will give you experience working with functions and documentation, especially Python docstrings using the NumPy docstring format. You will also walk through the process of creating the program from scratch in your Discussion Section, so you will gain some experience with using functions to break a complex problem down into smaller problems that you can solve one at a time.

1. Copy the file hw1.py to your computer and rename it to “hw1_<your unique name>.py”. Open it in your code editor.

2. Find all of the # TODO comments and implement the missing pieces (documentation and/or function implementations).

3. Play-test your game as you develop to make sure that it works properly, and that it handles invalid inputs gracefully (i.e., the program does not crash). Use this in place of an autograder!

4. Your program should behave as shown in the file: ‘hw1_sample_output.pdf’

4a. Note that the sample code we provided does not display the winner (Nobody, X, or O) when the game ends as shown in the sample output. You should add this where appropriate.

Grading: Point Breakdown (total 90 points)

What to turn in: the hw1.py file appropriately renamed (“hw1_<your unique name>.py”)

PROGRAM BEHAVIORS (30 pts)

————————–

0 – Program displays 3×3 game board with numbers in cells and prompts user for X’s move (necessary for the rest of the program)

5 – Program rejects invalid inputs (non-numerics, numbers < 1 or > 9, and other ambiguous input) gracefully and prompts user for valid input as shown in sample output

5 – Program rejects moves into occupied spaces and prompts user for a different move.

5 – When player makes a valid move, board is displayed with their player name in the correct cell. Their name is displayed in that cell for the remainder of the game.

5 – Program correctly determines vertical wins

5 – Program correctly determines diagonal wins

5 – Program displays the correct winner (Nobody, X, or O) when the game is over

PROGRAM CODE (60 pts)

———————

10 – make_move() is implemented to match functionality specified in docstring

5 – docstring is correctly added for check_win_horizontal() to match function implementation

5 – docstring is correctly added to check_win_vertical()

10 – check_win_vertical() is correctly implemented and matches docstring

5 – docstring is correctly added to check_win_diagonal()

10 – check_win_diagonal() is correctly implemented and matches docstring

5 – next_player() is implemented to match functionality specified in docstring

10 – Code is readable and interpretable

IMPORTANT NOTE ON DOCSTRINGS

—————————-

You should use the Numpy format for ALL docstrings in this assignment and may lose points if you do not. The general format is below and there are examples you may follow in the hw1.py file. You can also read more about Numpy string formatting at: https://sphinxcontrib-napoleon.readthedocs.io/en/latest/example_numpy.html

def function_with_types_in_docstring(param1, param2):

“””Example function with types documented in the docstring.

This is where you would describe in plain English what your function is supposed to do.

Parameters

———-

param1 : int

The first parameter. You should give some helpful information about this, if necessary

param2 : str

The second parameter. ou should give some helpful information about this, if necessary

Returns

——-

bool

True if successful, False otherwise.

“””
