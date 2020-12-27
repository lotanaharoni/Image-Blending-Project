
<img src="https://github.com/lotanaharoni/Image-Blending-Project/blob/main/images/Blended%20picture.png?raw=true" align="left" width = 300px hight = 300px  hspace="1" vspace="1"/>

# Image-Blending Project

This program performs blending on two images using pyramid blending. <br>
The program deals with image pyramids, low-pass and band-pass filtering.<br>

<br><br><br><br><br>

## Table of Contents

1. [Language](#Language)
2. [Introduction](#introduction)
3. [Setup](#setup)
4. [Api](#Api)
5. [Supported OS](#supported-os)
6. [Internal tools](#Internal-tools)

---

## Language

This static library is written in Python.
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

## Api

```typescript
build_gaussian_pyramid(im, max_levels, filter_size)
/**
 * This function construct a Gaussian pyramid of a given image.
 */
 
build_laplacian_pyramid(im, max_levels, filter_size)
/**
 * This function construct a Laplacian pyramid of a given image.
 */

display_pyramid(pyr, levels)
/**
 * This function display the pyramid.
 */
 
pyramid_blending(im1, im2, mask, max_levels, filter_size_im, filter_size_mask)
/**
 * This function implementing a pyramid blending.
 */
 
blending_images(image1_name, image2_name, mask_name, max_levels, filter_size_im, filter_size_mask)
/**
 * This function implements blending between two images.
 */

```

## Supported OS

I'm developing on linux and macOS, and the library was tested on linux.

## Internal tools


- The program used the libraries: 'numpy', 'scipy', 'imageio', 'skimage' and 'mayplotlib'.    





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

    
