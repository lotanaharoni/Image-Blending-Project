<h1> Image-Blending-Project</h1>
<p>Include the library and use it according to the package's public interface</p>

## Table of Contents

1. [Language](#Language)
2. [Introduction](#introduction)
3. [Setup](#setup)
4. [Library functions](#Library-functions)
5. [Supported OS](#supported-os)
6. [Internal tools](#Internal-tools)

---

## Language

This static library is written in C++.
<br>

## Introduction

This is a static library, that creates and manages user-level threads.<br>
The library implements Round-Robin scheduling alghorithm.<br>
Each thread can be in one of the following states: RUNNING, BLOCKED and READY.
<br>

### Benefits

- The user can create, block, resume and terminate threads.
- The library supports different threads with different priorities, high priority threads will<br>
  get more time in the CPU when their turn arrive.

## Setup

Include the 'uthreads.h' header
<br>

## Library functions

```typescript
int uthread_init(int *quantum_usecs, int size)
/**
 * This function initializes the thread library.
 */

int uthread_spawn(void (*f)(void), int priority)
/**
 * This function creates a new thread, whose entry point is the function f with the signature void f(void).
 */

int uthread_change_priority(int tid, int priority)
/**
 * This function initializes the thread library.
 */

int uthread_terminate(int tid)
/**
 * This function changes the priority of the thread with ID tid.
 */

int uthread_block(int tid)
/**
 *  This function blocks the thread with ID tid.
 */

int uthread_resume(int tid)
/**
 * This function resumes a blocked thread with ID tid.
 */

```

## Supported OS

I'm developing on linux and macOS, and the library was tested on linux.

## Internal tools


- The library used system calls like 'sigsetjmp', 'siglongjmp' and 'sigprocmask'
- The following headers are included in the library: 'signal.h' and 'sys/time.h'
    




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

    
