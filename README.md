A. Project purpose
I want to display all the ways that we can set as much as queens on the chessboard such that no queens capture each other. In particular, the chessboard has 8 rows and 8 columns, so we can set atmost 8 queens on the board.

B. Project Idea
At the beginning, I will mark all the square with 0. I will set a queen on the first column. After that, I will mark all the square that this queen can capture and increase them by 1. After that, I will go to the second column and put a queen on a square marked with 0 and set all the square that the second queen can capture and add it by 1 too. There will be some squares marked with 2 because two first queens can capture this square. Gradually, I will go to the third column, fourth column....and eighth column to set 8 queens on the chessboard.

C. Recursion(Explaining in my code)

