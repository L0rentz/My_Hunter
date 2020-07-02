# My_Hunter

This is a point and click game like the DUCK HUNT on the NES but without the zapper, it was my first graphical project and it's poorly written but it is looking very good for what it is.

Made alone in 2 weeks

Here you can find the video of the end result of this project :

[![](https://i.ytimg.com/vi/Er367BJdZ4w/hqdefault.jpg?sqp=-oaymwEZCNACELwBSFXyq4qpAwsIARUAAIhCGAFwAQ==\u0026rs=AOn4CLDJ94INYymQtcKBmNFjg2E2372OWg)](https://www.youtube.com/watch?v=Er367BJdZ4w "My_Hunter")

## Usage

./my_hunter [-h]

## Description

My_Hunter is a shooter game in which the objective is to shoot moving targets on the screen in mid-flight. 
The ducks will move faster each rounds.  

## Rules

Shoot at least 5 out of 10 ducks each rounds or you'll game over, black duck = 500 pts, blue duck = 1000 pts and red duck = 1500 pts.  

## Controls
  
- Use arrow up or arrow down to select your game mode.  
- Press space to start.  
- Once in game press escape to pause.  
- If paused press space to resume  
- Aim by moving your mouse and shoot the ducks with your left mouse button.  
  
PS :  - Doggy will dodge your cursor  
  
## Infos

- **Binary name:** my_hunter
- **Language:** C
- **Group Size:** 1
- **Compilation:** via Makefile, including re, clean and fclean rules
  
## Table of content
<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [Subject](#subject)
	- [Requirements](#requirements)
		- [Must](#must)
		- [Should](#should)
		- [Could](#could)
	- [Authorized functions](#authorized-functions)

<!-- /TOC -->

## Subject
  
In this project, you are asked to make a small video game based on the rules of Duck Hunt.  
  
The basic rules for the my_hunter are as follows:  
- the player is a hunter who shoots ducks.  
- ducks must appear on the screen and move from one side to another.  
- the player can click on them to shoot them.  
  
Being able to manage inputs from the user and to display animated sprites are key skills when you want to develop basic games.  
  
## Requirements

### Must

- The window must be closed using events.  
- The program must manage the input from the mouse click.  
- The program must contain animated sprites rendered thanks to sprite sheets.  
- The program must contain moving (rotating, translating, or scaling) elements.  
- The program must accept the “-h” option, then display a short description of the program, and the available user inputs.  

### Should

- Animations and movements in your program should not depend on the speed of your computer.  
- Animations and movements in your program should be timed by sfClock elements.  
- Your window should stick between 800x600 pixels and 1920x1080 pixels.  
- Your window should have a limited frame rate such that it can be compute without lagging.  

### Could

- The program could have several different levels.  
- The program could display the score of the player.  
- The program could store the highest score made.  
- The program could display a small target under the mouse cursor.  

> :exclamation: The size of your repository (including the assets) must be as small as possible. Think about the format and the encoding of your resource files (sounds, musics, images, etc.).  
> An average maximal size might be 15MB, all included. Any repository exceeding this limit might not evaluated at all.  

## Gameplay

While the requirements don’t go deep into the gameplay, we are still asking you to make a video game.  
A basic example of what we are expecting is a simple game where we could score points by avoiding obstacles (either by jumping or crouching) while our character is running towards them.  
If you make an endless level the score should also based on how long the player can keep avoiding obstacles  

## Authorized functions

from the C library  
- malloc  
- free  
- memset  
- rand  
- srand  
- time (only with srand)  
- (f)open  
- (f)read  
- (f)write  
- (f)close  
- getline  
  
from the CSFML library  
All functions  
  
from the math library  
All functions  
  
> :exclamation: Any unspecified functions are de facto banned.  
