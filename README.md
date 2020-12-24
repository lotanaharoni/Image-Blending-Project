<h1> Image-Blending-Project</h1>

## Table of Contents

1. [Language](#Language)
2. [Introduction](#introduction)
3. [Api](#Api)
4. [Supported OS](#supported-os)

---

## Language

This program is written in C.
<br>

## Introduction

This program analyzes a Red-black tree.<br>
It guarantees searching, insertion and deletion in O(log(n)) time.<br>
When the tree is modified, the new tree is rearranged and repainted.
<br>


## Api

```typescript
int containsRBTree(RBTree *tree, void *data)
/**
 * This function searches data in the tree.
 */

int addToRBTree(RBTree *tree, void *data)
/**
 * This function addes data to the tree.
 */

RBTree *newRBTree(CompareFunc compFunc, FreeFunc freeFunc)
/**
 * This function creates a new tree.
 */

void freeRBTree(RBTree *tree)
/**
 * This function releases all the tree's data.
 */

```

## Supported OS

I'm developing on linux and macOS, and the program was tested on linux.




<img src="https://github.com/lotanaharoni/Connect-Four-game/blob/main/images/Connect_Four_Computer_VS_Man.gif?raw=true" align="left" width = 300px hight = 300px  hspace="1" vspace="1"/>

# Connect Four game Python

This is an interactive Connect Four program that applies a graphical user interface (GUI) with multiply choices to play.
All the project is written in Python.

The GUI is done with Tkinter library.
<br><br><br>

The rules of this game are the same as a regular <a href="https://en.wikipedia.org/wiki/Connect_Four" > Connect Four</a>.<br>
Follow the key features before you start to play.<br>
Enjoy!

<br> 

# Key Features
<br>

## Configure the game settings
#### 1. Choose the game's mode you wish to play.
##### a. Player VS Player
##### b. Player VS Computer - player starts
##### c. Player VS Computer - computer starts
##### d. Cimputer VS Computer
#### 2. Remember, the yellow player starts!
<p align="center">
<img src="https://github.com/lotanaharoni/Connect-Four-game/blob/main/images/Connect_Four_Menu.png?raw=true" width = 400px hight = 400px/>
</p>

## Play agains a friend
### The game offers the option to play against a friend.
#### 1. Pick the column to drop your disc. 
<p align="center">
<img src="https://github.com/lotanaharoni/Connect-Four-game/blob/main/images/Connect_Four_MAN_VS_MAN.gif?raw=true" width = 400px hight = 400px/>
</p>

## Play against the computer
### The game offers the option to play against the computer.<br>
### Can you beat the computer?
<p align="center">
<img src="https://github.com/lotanaharoni/Connect-Four-game/blob/main/images/Connect_Four_Computer_VS_Man.gif?raw=true" width = 400px hight = 400px/>
</p>


## Restart the game
### You have the option to restart the game and to start from the beginning.
#### 1. Click the 'Restart' button at the right panel.
<p align="center">
  <img src="https://github.com/lotanaharoni/Connect-Four-game/blob/main/images/Connect_Four_restart.gif?raw=true" width = 400px hight = 400px/>
</p>

    
