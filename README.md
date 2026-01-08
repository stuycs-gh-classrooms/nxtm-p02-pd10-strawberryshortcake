[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/jiVqpuMN)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=22153571)
# NeXtCS Final Project
### Name 0: Unmesh Ghosh
### Name 1: Andrew Zhao
### Name 2: Sufia Nanenco
---

### Project Description
Our project is a Minesweeper game, we will implement a tile class that will fill up the board, and various subclasses to determine the state of the tile. This will be an addon to Minesweeper with animations and powerups! (edit this to make it more professional sounding)

### Skill Usage
Explain what skills from this semester you will be using in this project, and how they will be used.

### Controls

Keyboard Commands:
- "r": reset the game
- "1": easy mode
- "2": hard mode
Mouse Control:
- Left Click: Uncover tile
- Right Click: Place a flag on an uncovered tile


### Classes
What classes will you be creating for this project? Include the instance variables and methods that you believe you will need. You will be required to create at least 2 different classes. If you are going to use classes similar to those we've made for previous assignments, you will have to add new features to them.

class Tile

Variables:
  - array pos: the position of the tile at the top left corner
  - int state: the state of the tile as a variable, 0 for uncovered, 1 for covered
  - boolean bomb: determines whether this tile is a bomb tile or not
  - int mineNum: the number of mines around the tile. Displayed when the tile is uncovered.
    
Methods:
  - void display: displays the tile,
  - void covered: the display of a covered tile
  - void uncovered: the display of an uncovered tile
  - void bomb: the display of an uncovered bomb tile
  - void uncover: uncovers the tile, if its a bomb then it blows up and the game is over. Or changes the tile to an uncovered tile, and displays a number.

class Board

Variables:
  - array cell[][] grid: grid of cells
  - int width: width of the board
  - int height: height of the board
  - int mines: amount of mines on the board
  - int revealedCount: amount of revealed tiles
  - int flagCount: amount of flags
  - boolean gameOver:
  - boolean gameStarted:
    
Methods:
  - void setup: calls gameStart
  - void gameStart: initializes all variables and starts the game.
  - void mouseClicked: if left mouse is clicked, reveal the tile on that spot. if right mouse is clicked place a flag.
  - void draw: continuously runs all the functions below this one.
  - void gameOver: checks whether game is over and if true, ends the game and displays the end screen.
  - void display: displays the board


  
