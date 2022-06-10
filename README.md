# Tic-Tac-Toe
(with turtle)
----------------------------

User:  X
CPU :  O

This is a basic tic-tac-toe game in which the player has to compete with the cpu.
So each box of the grid has been assigned a number,and the user needs to enter the 
number of the box where he wants to place X.
[1 ][2 ][3 ]
[4 ][5 ][6 ]
[7 ][8 ][9 ]

For example, if the user enters 5, X will be placed at the center:
[ ][ ][ ]
[ ][X][ ]
[ ][ ][ ]
 
So for each step, user needs to fill the boxes by assigning the number.

The cpu will be using O,so these are the cases that might happen:

case 1:
(user wins the game): if Xs are placed in all the boxes in any row or column.
                      if any diagonal is filled with X.

case 2:
(cpu wins the game): if Os are placed in all the boxes in any row or column.
                      if any diagonal is filled with O.

case 3:
(Draw): If none of the above occurs and if number of Xs are greater than 3,it will be a tie.
