---
layout: project
type: project
image: img/micromouse/micromouse-square.jpg
title: "Find-Supernovae"
date: 2015
published: true
labels:
  - Robotics
  - Arduino
  - C++
summary: "My team developed a robotic mouse that won first place in the 2015 UH Micromouse competition."
---

<div class="text-center p-4">
  <img width="200px" src="../img/micromouse/micromouse-robot.png" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-robot-2.jpg" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-circuit.png" class="img-thumbnail" >
</div>

The goal of this project is to create a convolutional neural network that is trained to anylize images from the Hubble Space Telescope and identify supernovae.

In order to locate supernovae, we must compare multiple images of the same spot in space, taken at different times. We must align and subtract these images, using TweakReg and AstroDrizzle, in order to locate any differences in light, which may indicate a supernova. 

The training data will consist of real aligned and drizzled images with false supernovae planted into them.

So far, this project is still in the phase of collecting and processing training data. 

