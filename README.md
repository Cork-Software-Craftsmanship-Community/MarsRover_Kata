Mars Rover Kata
===============

## Description

Develop an api that moves a rover around on a grid.

* You are given the initial starting point (x,y) of a rover and the 
direction (N,S,E,W) it is facing.
* The rover receives a character array of commands.
* Implement commands that move the rover forward/backward (f,b).
* Implement commands that turn the rover left/right (l,r).
* Implement wrapping from one edge of the grid to another. (planets are spheres after all)
* Implement obstacle detection before each move to a new square. 
If a given sequence of commands encounters an obstacle, the rover moves up 
to the last possible point and reports the obstacle.

## Rules
* Hardcore TDD. No Excuses!
* Change roles (driver, navigator) after each TDD cycle.
* No red phases while refactoring.
* Be careful about edge cases and exceptions. We can not afford to lose a mars rover, just 
because the developers overlooked a null pointer.

## Source
- http://kata-log.rocks/mars-rover-kata
