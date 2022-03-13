# Connect4

## The Objective

The board consists of a vertically mounted grid with 6 rows and 7 columns. 
Two players take turns dropping coins in each column. 
The objective of the game is for a player to drop his or her coins such that they create a row, column or diagonal of 4 coins. 

## Declaring a Winner

When a player gets four coins in a row (horizontally, vertically, or diagonally), the game logic registers the player as the winner of the game.

## The Board

The game board is represented by a two-dimensional matrix of 6 rows and 7 columns. Each empty space is represented by ‘0’, and the spaces taken by a player are represented by their respective characters.

## Dropping a Coin

In real life, the board is a vertically mounted grid. So, in order to simulate the effects of gravity, a coin when dropped into a particular column falls to the lowest unoccupied space. 
In case the column already has 6 coins, the function governing the ‘drop coin’ action asks for a different column number from the user. 

## To Run The Code
Install all the files and run server.py in a terminal to start the server. Make sure your system has [localhost enabled](https://enterprise.arcgis.com/en/web-adaptor/latest/install/iis/enable-iis-10-components-server.htm). To start playing the game, run client1.py and client2.py each in separate terminals, 
