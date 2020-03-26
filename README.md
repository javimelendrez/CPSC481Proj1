# CPSC 481-03 Project 1 

Team Name: AiBros

Team Members: Javier Melendrez, Omar Al Nabulsi, Brannon Ha, Daniel Pestolesi

Intro: we will build a bot that will start from the upper-left ring in of a 2D grid of cells 
containing red path tiles and black wall tiles and attempt to find a quality path to the 
lower-right ring. The bot will show it's path exploration as smaller dots. You will show the 
bot move from tile to tile, including backing up due to a dead end. And it will show the bot's
current best path tiles in a different color from those paths rejected. The project will be 
built in Jathp-Lisp running with P5, JS, HTML in a web browser page.

Set Up and installation: N/A

Features: bot starts at top left corner and makes its way down to the bottom right corner
using BestFS algorithm, the bot leaves yellow squares in which there are more than one
paths on the path given.

External requirements: none

Bugs: none
