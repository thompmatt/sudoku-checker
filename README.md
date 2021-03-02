# SudokuBoardCheck
This program is the very simple C program that takes a file as input and outputs whether a Sudoku board is valid or not. With this project, I practiced the following topics:
- Fundamental C syntax
- C arrays
- How to dynamically allocate on the heap using malloc(), free()
- Address arithmetic

The file must be in the following format:
```
N // Where N is the number of rows and columns
1,2,3,4,5
0,3,4,5,1
3,4,0,1,2
4,5,1,0,3
5,1,2,3,4
```
Where the first row is the number of columns and rows of the N x N Sudoku board, and the rest of the lines are the numbers (between 1 and N inclusive). If 0's are present, they represent an empty board.

## Author - Matthew Thompson Soto, CS 354, Spring 2021
