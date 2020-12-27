
<img src="https://github.com/lotanaharoni/Image-Blending-Project/blob/main/images/Blended%20picture.png?raw=true" align="left" width = 300px hight = 300px  hspace="1" vspace="1"/>

# Image-Blending Project

This program performs blending on two images using pyramid blending. <br>
The program deals with image pyramids, low-pass and band-pass filtering.<br>

<br><br><br><br><br><br><br>

## Table of Contents

1. [Key Features](#Key-Features)
4. [Api](#Api)
5. [Supported OS](#supported-os)
6. [Internal tools](#Internal-tools)

---
<br>
# Key Features
<br>

## Gets the High frequencies
### In order to blend the images smoothly
<p align="center">
<img src="https://github.com/lotanaharoni/Image-Blending-Project/blob/main/images/High_frequencies.png?raw=true" width = 400px hight = 400px/>
</p>

## Gets the image pyramid
### In order to blend the images
<p align="center">
<img src="https://github.com/lotanaharoni/Image-Blending-Project/blob/main/images/Elsa_High_frequrncies.png?raw=true" width = 400px hight = 400px/>
</p>

## Images blending
### The final results
<p align="center">
<img src="https://github.com/lotanaharoni/Image-Blending-Project/blob/main/images/All%20pictures.png?raw=true" width = 400px hight = 400px/>
</p>


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

This program is written in Python.
- The program used the libraries: 'numpy', 'scipy', 'imageio', 'skimage' and 'mayplotlib'.    

    
