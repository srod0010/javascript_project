# JavaScript Project - PACMAN
##  Background and Overview
    * PACMAN is a game in where the goal is to accumulate the maximum number of points by moving through a maze collecting coins and eating ghosts. The game goes until all the coins in the maze have been collected, or the user runs into a ghost while the pacman in not in a powered up state.
## Functionality and MVP Features
    * Render canvas
    * Have pacman and ghosts stay within confines of canvas
    * Have user controlled pacman
    * Have ghosts conrolled by AI

## Architecture and Technologies
    * Vanilla JavaScript
        * Game logic
    * HTML 5 Canvas
        * DOM manipulation and rendering
    * Webpack
        * bundle scripts

    * board.js
        * responsible for rendering board
    * pacman.js
        * responsible for logic on user controlled pacman
    * ghost.js
        * responsible for logic on AI controlled ghosts

* Wireframe
    * <img src="https://upload.wikimedia.org/wikipedia/en/5/59/Pac-man.png"
     alt="Pacman"
     style="display: inline-block; margin-right: 10px;" />
    
    
## Implementation Timeline
    * Day 1
        * Review javascript curriculum - asteroid game and canvas
        * Get canvas rendered
    * Day 2
        * Get pacman rendered and responding to user input
        * Get pacman constrained to walls
        * Render dots - keep track of score
        * Game over logic
    * Day 3
        * Create a ghost class and have it initially respond to user input
        * Ghost constrained to walls
    * Day 4
        * Work on collision detection between pacman and ghosts
        * Work on power ups
        * Start working on AI
    * Day 5/6
        * Render additional ghosts 
        * Build AI - find the relative direction of the player when the ghost reaches a junction and decide where to move from there
        * Add play button and end of game screen
