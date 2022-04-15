# Minesweeper

[image]

This is a 2D minecraft implementation in python

You can start a game by running a script:

    python minesweeper.py

For now, this game script does not have a GUI, and you use the terminal to play. In order to "dig" at a certain location, you type in the index of the row, then the column, separated by a comma (whitespace optional). The game "digs" recursively around that location if there are no bombs nearby.

You can continue digging until either you hit a bomb (which is game over) or you've successfully dug up all n-b non-bomb locations (which is victory)!

The default game is 10x10 grid with 10 bombs, but you can change with the script bellow:

    python minesweeper.py --dim_size=(insert size of the board) --num_bombs=(number of bombs)
    

Warning some board sizes might make the visual board misalign and the number of bombs might make the game incompletable or extreme hard.