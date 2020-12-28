
<img src="https://github.com/lotanaharoni/Image-Blending-Project/blob/main/images/Blended%20picture.png?raw=true" align="left" width = 300px hight = 300px  hspace="1" vspace="1"/>

# Image-Blending Project

This program performs blending on two images using pyramid blending. <br>
The program deals with image pyramids, low-pass and band-pass filtering.<br>

<br><br><br><br><br><br><br>


## Introduction

The program performs blending on two images using pyramid blending.<br>
The program gets three images: two images to blend and one filter image.<br>
From the filter image it builds a Gaussian pyramid and from the other it builds Laplacian pyramids.<br>
The Gaussian pyramids is used like a band-pass filter.

## Supported OS

I'm developing on linux and macOS, and the library was tested on linux.

## Internal tools

This program is written in Python.
The program used the libraries: 'numpy', 'scipy', 'imageio', 'skimage' and 'mayplotlib'.<br><br>


## Key Features
<br>

### Build a Gaussian pyramid from one picture
#### In order to blend the images smoothly
<p align="center">
<img src="https://github.com/lotanaharoni/Image-Blending-Project/blob/main/images/Gaussian%20pyramid-%20Elsa.png?raw=true" width = 400px hight = 400px/>
</p>

### Build a Gaussian pyramid from the secoond picture
#### In order to blend the images smoothly
<p align="center">
<img src="https://github.com/lotanaharoni/Image-Blending-Project/blob/main/images/Gaussian%20pyramid%20-%20mask.png?raw=true" width = 400px hight = 400px/>
</p>

### Build a Gaussian pyramid from the filter image
#### In order to blend the images smoothly
<p align="center">
<img src="https://github.com/lotanaharoni/Image-Blending-Project/blob/main/images/Gaussian%20pyramid.png?raw=true" width = 400px hight = 400px/>
</p>

### Build a Laplacian pyramid from the filter image
#### In order to blend the images smoothly, represents the high frequencies
<p align="center">
<img src="https://github.com/lotanaharoni/Image-Blending-Project/blob/main/images/Elsa_High_frequrncies.png?raw=true"/>
</p>


### Images blending
#### The final results
<p align="center">
<img src="https://github.com/lotanaharoni/Image-Blending-Project/blob/main/images/All%20pictures.png?raw=true"/>
</p>




    
