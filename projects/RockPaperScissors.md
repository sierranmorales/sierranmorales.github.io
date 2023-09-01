![RockPaperScissors](https://github.com/sierranmorales/sierranmorales.github.io/assets/143547246/9a280b47-3f7a-4130-9ec1-f0c630c70e69)---
layout: project
type: project
image: img/micromouse/micromouse-square.jpg
title: "Micromouse"
date: 2015
published: true
labels:
  - C
summary: "Rock paper scissors game vs computer written in C."
---

<div class="text-center p-4">
  <img width="200px" src="..\Users\sierr\Pictures\School\ICS 314\RockPaperScissors.PNG" class="img-thumbnail" >
</div>

For this project I programmed a "Rock, Paper, Scissors" game to be played against the computer.

This project was programmed in C using a SSH server and emacs as the text editor.

```cpp
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```

