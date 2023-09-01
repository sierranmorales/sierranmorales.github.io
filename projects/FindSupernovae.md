---
layout: project
type: project
image: ../img/FindSupernovae.png
title: "Find Supernovae"
date: 2022-2023
published: true
labels:
  - Neural Network
  - Python
summary: "The goal of this project is to create a convolutional neural network that is trained to anylize images from the Hubble Space Telescope and identify supernovae."
---

<div class="text-center p-4">
  <img width="200px" src="../img/FindSupernovae.png" class="img-thumbnail" >
</div>

<p>
The goal of this project is to create a convolutional neural network that is trained to anylize images from the Hubble Space Telescope and identify supernovae.

In order to locate supernovae, we must compare multiple images of the same spot in space, taken at different times. We must align and subtract these images, using TweakReg and AstroDrizzle, in order to locate any differences in light, which may indicate a supernova. 

The training data consists of real aligned and drizzled images with false supernovae planted into them.

Once trained, the neural network will be ran over all images in the Hubble Space Telescope archive.

</p>
