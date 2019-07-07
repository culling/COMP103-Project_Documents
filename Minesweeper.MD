## Minesweeper
![Screenshot from image](docs/Minesweeper-screenshot-01.png)
### Purpose - Minesweeper Game

### Intro
Minesweeper is a very old video game in which the player tries to work out where the mines are hidden on a grid. Each cell in the grid starts off as hidden (dark green). The player can mark any hidden cell that they think contains a mine, and can expose any hidden cell that they think is safe.

### Details
Given a simple and incomplete implementation of a Minesweeper game I implemented the additional functions.
+ If the player exposes a cell with a mine, they lose and the game is over. All the cells are opened up so that the player can see where all the mines are.
+ If the player exposes a safe cell that is next to one or more mines, then the cell displays a number saying how many of the eight surrounding cells contain a mine.
+ If the player exposes a safe cell that is not next to a mine, then it "spreads" to all the connected cells that are also safe, and exposes them also. This was completed using recursion. 
