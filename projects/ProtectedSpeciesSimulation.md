---
layout: project
type: project
image: ../img/ProtectedSpeciesSimulation1.png
title: "Synthetic Data Generation for Protected Species Detection"
date: 2024
published: true
labels:
  - Data Augmentation
  - Synthetic Dataset Creation
  - OpenCV
summary: "This project aimed to simulate protected species in fishing environments, generating realistic training data for a CNN to improve species identification accuracy."
---

<div class="text-center p-4">
  <img width="650px" src="../img/ProtectedSpeciesSimulation.png" class="img-thumbnail" >
</div>
<h3>Summary</h3>
<p>
In this project, I developed a pipeline to generate synthetic training data for a Convolutional Neural Network (CNN) aimed at identifying 
protected marine species in fishing videos. The process involves combining Blender animations with real-world footage using Python scripting 
and computer vision techniques.
<br>
  
Note: This project is currently in process.
<br><br>
  
I completed this project in collaboration with 2 other people, and acted as the technical lead.
<br><br>

<h3>My Contributions Include:</h3>

- Frame Segmentation and Transparency: I created a Python script to automate the segmentation of each frame of a 3D Blender animation into individual still images with transparent backgrounds. 
- Video Interpolation with OpenCV: Using the OpenCV library, I created a script that integrates these segmented frames into real-footage videos. The script accurately interpolates the species into each frame, accounting for factors like rotation, size, and positioning.
- Dynamic and Realistic Animations: To achieve realistic behavior, I automated smooth rotations and looped animations, simulating natural movements and interactions with the environment.
- Automated and Scalable Data Generation: This project was designed with scalability in mind, allowing for large-scale automated generation of diverse training datasets by varying species, animations, and environmental conditions.
<br><br>

<br><br>
<br>
<a href="https://github.com/aidotfish/pixels" target="_top">Here is a link to the project Github</a>
</p>
