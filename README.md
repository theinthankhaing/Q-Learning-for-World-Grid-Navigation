# Q-Learning for World Grid Navigation

## Project Overview

* Implement Q - learning algorithm
* Make the robot reach the goal by maximizing the total reward of the trip
* Make Q-function converge to the optimal values
* Programming Language - MATLAB
_______________________________________________________________
## Environment Set Up
* MATLAB
_________________________________________________________________
## Finding optimal route

* Before the program is started, Q – function is initialized as zero and k value is updated after each trial and Q value is updated after each run.
* In each trial, to balance the exploration – exploitation, greedy exploration policy is applied to find the action for next step.
* To get the optimal value of Q, the probability must be higher than exploration probability which can also reduce exploration

### Trajectory Plot

![image](https://user-images.githubusercontent.com/50255936/110663943-eeecb300-8201-11eb-842d-1de07de58d5c.png)
