# Knapsack

## Usage
To compile, type "g++ -o knapsack knapsack.cpp". To run the program, type "./knapsack knapsack1.txt".

## Introduction
The command line program knapsack.cpp takes in one parameter,
an input file name. The input file specified by the input
file name should describe an instance of the knapsack problem
using the format

[knapsack capacity][number of items]

[value item 1][weight item 1]

...

The program solves the knapsack problem using dynamic 
programming to cache solutions to subproblems.
