[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/jiVqpuMN)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=22153571)
# NeXtCS Final Project
### Name 0: Unmesh Ghosh
### Name 1: Andrew Zhao
### Name 2: Sufia Nanenco
---

### Project Description
Our project is a Minesweeper game, we will implement a tile class that will fill up the board, and various subclasses to determine the state of the tile. (edit this to make it more professional sounding)

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
Methods:
  - void display: displays the tile,
  - void covered: the display of a covered tile
  - void uncovered: the display of an uncovered tile
  - void bomb: the display of an uncovered bomb tile

class Board
Variables:
  - cell[][] grid: grid of cells
  - 
  
