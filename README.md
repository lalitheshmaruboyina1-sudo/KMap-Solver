# K-Map Boolean Expression Solver

## About the Project

This project is a C++ program that takes a Boolean function in the form of a K-map and finds all possible minimum Boolean expressions.

The program supports:

- 1 variable
- 2 variables
- 3 variables
- 4 variables
- 5 variables

Therefore, the program supports:

n <= 5

## Input Format

The first value is the number of variables `n`.

After that, enter `2^n` K-map values.

Each value must be either `0` or `1`.

Example for 4 variables:

```text
4
0 1 0 1
1 0 0 0
0 0 0 1
0 0 0 1
