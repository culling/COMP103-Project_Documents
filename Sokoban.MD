# Sokoban
![Screenshot from image](docs/Sokoban-screenshot-01.png)
### Purpose - Implement an undo, redo and pathfinding within Sokoban
## Intro
Sokoban is a computer game of the puzzle variety that was created in 1980, and is available on many computer platforms. The game involves controlling a worker in a warehouse who has to push boxes around the warehouse to get them onto their destination spots. The worker can only push one box at a time, and cannot pull boxes. It is easy for the player to get stuck in a deadlock where it is no longer possible to move some of the boxes. Some of the levels are extremely difficult to solve.

You can find out more about the Sokoban game from the web.
## Details
Given a simple implementation of the Sokoban game with four levels I implemented the additional functions.
+ Added an undo function
+ Added a redo function
+ Able to pathfind from the current position of the worker to a free cell clicked on by the user, if there was a possible path.
