---
layout: project
type: project
image: ../img/findSupernovaeThumbnail.png
title: "Find Supernovae"
date: 2022-2023
published: true
labels:
  - Neural Network
  - Python
summary: "The goal of this project is to create a convolutional neural network that is trained to anylize images from the Hubble Space Telescope and identify supernovae."
---

<div class="text-center p-4">
  <img width="350px" src="../img/FindSupernovae.png" class="img-thumbnail" >
</div>

<p>
The goal of this project is to create a convolutional neural network that is trained to anylize images from the Hubble Space Telescope (HST) and identify supernovae. <br><br>

In order to locate supernovae, we must compare multiple images of the same spot in space, taken at different times. We must align and subtract these images, using TweakReg and AstroDrizzle, in order to locate any differences in light, which may indicate a supernova. In order to do this, I first downloaded a csv file containing data about all images from the HST archive that fit my search conditions. Then I wrote a script to compare each image's data with each other image's data in order to see if they were compatible (same filter, same area, different time). All compatible image pairs were written to a txt file called MatchLog.txt. Then I wrote another script to read through the MatchLog.txt and download all of the images. I then wrote two more scripts to compile a list of images that should be alligned and drizzled together. Finally, AstroDrizzle was run on all of the compatible images in order to create subtracted images.

<br><br>

The training data consists of real aligned and drizzled images from the HST archive with false supernovae planted into them This approach ensures a balanced dataset, allowing the neural network to learn the nuanced differences between actual celestial objects and noise.. Once trained, the neural network will be run over all images in the Hubble Space Telescope archive.<br><br>

I have learned a lot over the course of this project, especially as it is my first project programmed in Python, as well as my first introduction to Artificial Intelligence. Not only have I learned the syntax and nuances of Python, but I have also gained invaluable insights into neural networks, data processing, and astronomical imaging. All programming and data analysis for this project have been done by me, under the expert guidance of my mentor, Dr. David Rubin<br><br>

<br>
<a href="https://github.com/sierranmorales/Finding-Supernovae" target="_top">Here is a link to the project Github</a>
</p>
