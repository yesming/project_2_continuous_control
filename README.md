# project_2_continuous_control
This repo deal with a 2nd deep reinforcement learing project of udacity.
In the project, I will implement a multi agent learning.

## Environment
In the environemnt, a double-jointed robot arm can move to target location (in 3 dimensions). A reward of +0.1 is provided for each step that the agent's hand in the goal location.
Thus, the goal of the agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

Note that I select the environemnt of version 2  which deal with multi-robot.

## Goal
When the average of those average scoress is at least +30, I will consider that the learning is over. 