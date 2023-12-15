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
  - Hubble Space Telescope
  - Supernovae
summary: "This project aimed to create a convolutional neural network that is trained to anylize images from the Hubble Space Telescope and identify supernovae."
---

<div class="text-center p-4">
  <img width="350px" src="../img/supernova1.png" class="img-thumbnail" >
</div>

<p>
The goal of this project was to create a convolutional neural network that is trained to anylize images from the Hubble Space Telescope (HST) and identify supernovae. <br><br>

In order to locate supernovae, we must compare multiple images of the same spot in space, taken at different times. We must align and subtract these images, using TweakReg and AstroDrizzle, in order to locate any differences in light, which may indicate a supernova. In order to do this, I first downloaded a csv file containing data about all images from the HST archive that fit my search conditions. Then I wrote a script to compare each image's data with each other image's data in order to see if they were compatible (same filter, same area, different time). All compatible image pairs were written to a txt file called MatchLog.txt. Then I wrote another script to read through the MatchLog.txt and download all of the images. I then wrote two more scripts to compile a list of images that should be alligned and drizzled together. 
<br><br>

Once this list was compiled, I created a duplicate of this dataset and inserted false supernovae into the duplicate data set, noting their positions and flux levels into a text file.
<br><br>

Finally, AstroDrizzle was run on all of the compatible images in order to create subtracted images. This left me with 2 sets of subtracted images, a control set (the original data), and a supernova set (the data with implanted supernovae).
<br><br>

The core of the project involved developing a convolutional neural network. A pre-trained model was adapted for this purpose, with its top layer retrained on the project-specific dataset, comprising 70% training, 15% validation, and 15% testing categories. The model demonstrated a promising accuracy of approximately 93% in supernova detection.
<br><br>

I have learned a lot over the course of this project, especially as it is my first big project programmed in Python, as well as my first introduction to Artificial Intelligence. Not only have I learned the syntax and nuances of Python, but I have also gained invaluable insights into neural networks, data processing, and astronomical imaging. All programming and data analysis for this project have been done by me, under the expert guidance of my mentor, Dr. David Rubin<br><br>

<br>
<a href="https://github.com/sierranmorales/Finding-Supernovae" target="_top">Here is a link to the project Github</a>
</p>
