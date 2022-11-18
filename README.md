# Tic Tac Toe

## Objectives

* Build a tic tac toe game in HTML, CSS, and vanilla JavaScript
* Use best practices when writing code

## Getting Started

* Before you even start working with JavaScript, construct the gameboard. The gameboard page should include the 3x3 grid (of divs), and at minimum a reset button. Using `id` and/or `class` on clickable elements will help you wire this up in JavaScript afterwards.
* The JavaScript portion will be next
  * Select elements and attach functions via event listeners
  * You will also need a variable to keep track of moves. This will be used to indicate whether or not to draw an `X` or an `O`

## Requirements
* A user should be able to click on different squares to make a move.
* Every click will alternate between marking an `X` and `O`
* Upon marking of an individual cell, use JavaScript to add an `X` or `O` to the cell, according to whose turn it is.
* A cell should not be able to be replayed once marked.
* You should not be able to click remaining empty cells after the game is over.
* Add a reset button that will clear the contents of the board.
* Display a message to indicate which turn is about to be played.
* Detect draw conditions (ties/cat's game) 
* Detect winner: Stop game and declare the winner if one player ends up getting three in a row. 

## TO DO

* Add an AI that can beat you every time with the mini-max algorithm.

