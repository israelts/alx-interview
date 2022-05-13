## :memo: N Queens
\[ [Back](../../..#readme) \]
\[ [Example](#Example) \]
\[ [Files](#Files) \]

#### Reference

![assets/judit.jpg](assets/judit.jpg)

Chess grandmaster [Judit Polgár](https://intranet.hbtn.io/rltoken/0Ouy8puhIfB2Gs-hEdrTog),
the strongest female chess player of all time

The N queens puzzle is the challenge of placing N non-attacking queens on an NN
chessboard. Write a program that solves the N queens problem.

- Usage: nqueens N
  - If the user called the program with the wrong number of arguments, print
Usage: nqueens N, followed by a new line, and exit with the status 1
- where N must be an integer greater or equal to 4
  - If N is not an integer, print N must be a number, followed by a new line,
and exit with the status 1
  - If N is smaller than 4, print N must be at least 4, followed by a new line,
and exit with the status 1
- The program should print every possible solution to the problem
  - One solution per line
  - Format: see example
  - You dont have to print the solutions in a specific order
- You are only allowed to import the sys module

Readings: 
[Queen]
[Backtracking]
#### Files:
\[ [0-nqueens.py](0-nqueens.py) \]


\[ [Back](../../..#readme) \]
