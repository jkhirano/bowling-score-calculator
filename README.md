# bowling-score-calculator

Your task is to write a function for calculating the score of a 10 pin bowling game. The input for this function will be **an array of objects**, and each object represents one frame. The objects can have any properties and values you see fit. Figuring out your input's data structure is part of the challenge.
​

## Requirements

- Create a Git Repository for this challenge
  - commit often and have your commit messages be descriptive
- Write tests for your function using the Mocha and Chai.
  - Provide test for all cases. Handle unexpected inputs, invalid arguments, etc.
    ​

## General rules

​

### Rules of bowling in a nutshell:

​
A game consists of 10 frames. In each frame the player rolls 1 or 2 balls, except for the 10th frame, where the player rolls 2 or 3 balls.
The total score is the sum of your scores for the 10 frames

- If you knock down fewer than 10 pins with 2 balls, your frame score is the number of pins knocked down
- If you knock down all 10 pins with 2 balls (spare), you score the amount of pins knocked down plus a bonus - amount of pins knocked down with the next ball
- If you knock down all 10 pins with 1 ball (strike), you score the amount of pins knocked down plus a bonus - amount of pins knocked down with the next 2 balls
  ​

### Rules for 10th frame

​

- If the last frame is a spare, player rolls 1 bonus ball.
- If the last frame is a strike, player rolls 2 bonus balls.
  ​
  These bonus balls on 10th frame are only counted as a bonus to the respective spare or strike.
  ​

## Input

​
You may assume that the input is always valid. This means:
​
input list length is correct
number of pins knocked out per roll is valid

## More information

​
http://en.wikipedia.org/wiki/Ten-pin_bowling#Scoring
