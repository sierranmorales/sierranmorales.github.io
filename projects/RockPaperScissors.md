---
layout: project
type: project
image: ../img/RockPaperScissors.PNG
title: "Rock Paper Scissors"
date: 2022
published: true
labels:
  - C
summary: "Rock paper scissors game vs computer written in C."
---

<div class="text-center p-4">
  <img width="200px" src="../img/RockPaperScissors.PNG" class="img-thumbnail" >
</div>

For this project I programmed a "Rock, Paper, Scissors" game to be played against the computer. The user inputs either "r" for rock, "p" for paper, "s" for scissors, or "q" to quit the game. These inputs are converted to numbers, either 0, 1, or 2. The computer's choice is a random number between 0 and 3. Both the player and the computer choices are then compared using a matrix and the game result is determined.

<br>{{0, 2, 1},<br>
		 {1, 0, 2},<br>
		 {2, 1, 0}};<br>                   

This project was programmed in C using a SSH server and emacs as the text editor. This was my first introduction to SSH and the linux command line, which is something that I use often now that I am further in my programming journey.
