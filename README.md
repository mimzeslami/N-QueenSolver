# N-Queens Solver

This repository contains a simple implementation of an N-Queens solver in Go. The N-Queens problem is a classic puzzle that involves placing N queens on an N×N chessboard such that no two queens can attack each other. The program uses a backtracking algorithm to find all possible solutions to the N-Queens problem.

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Usage](#usage)

## Introduction

The `main.go` file in this repository contains the implementation of the N-Queens solver. It utilizes a recursive backtracking algorithm to explore all possible configurations of queens on the chessboard and identifies the valid solutions where no two queens can attack each other.

The program prompts the user to enter the number of queens (`N`) they want to solve for. It then outputs all the valid solutions found along with the total count of solutions.

## Prerequisites

To run the code in this repository, you need to have Go installed on your system. You can download and install Go from the official Go website: https://golang.org/

## Usage

1. Clone this repository to your local machine using the following command:

`git clone https://github.com/mimzeslami/N-QueenSolver.git`

2. Navigate to the repository's directory:

`cd N-QueenSolver`

3. Build and run the code using the following command:

`go run main.go`


4. The program will prompt you to enter the number of queens (`N`). Enter a valid number and press Enter.

5. The program will calculate and display all the valid solutions to the N-Queens problem along with the total count of solutions found.







