---
layout: project
type: project
image: ../img/rpsThumbnail.png
title: "Rock Paper Scissors"
date: 2022
published: true
labels:
  - C
summary: "Rock paper scissors game vs computer written in C."
---

<div class="text-center p-4">
  <img width="600px" src="../img/RockPaperScissors.PNG" class="img-thumbnail" >
</div>

For this project, I programmed a "Rock, Paper, Scissors" game to be played against the computer. The user inputs either "r" for rock, "p" for paper, "s" for scissors, or "q" to quit the game.  The user's choice is then immediately echoed back on the screen to confirm their selection. The user's textual inputs ("r," "p," "s," or "q") are internally converted to integer values for easier computation. Specifically, "r" is converted to 0, "p" to 1, and "s" to 2. These integer representations are crucial for the game logic. The computer's choice is generated using a random number generator that picks an integer between 0 and 2 inclusive. This randomness ensures that the game remains unpredictable and engaging. Both the player and the computer choices are then compared using a matrix and the game result is determined.<br>

Result Matrix:<br>
0, 2, 1<br>
1, 0, 2<br>
2, 1, 0<br>      

The rows represent the user's choice, and the columns represent the computer's choice. The matrix values indicate the winner (0 for a tie, 1 for the user win, and 2 for the computer win). This approach streamlines the decision-making process and makes the code more maintainable.
<br>

This project was programmed in C using a SSH server and emacs as the text editor. This was my first introduction to SSH and the linux command line, the knowledge of which have become invaluable assets, as I now frequently use command-line interfaces in my more advanced programming projects.
