[//]: # (Image References)

[image1]: https://user-images.githubusercontent.com/10624937/42135623-e770e354-7d12-11e8-998d-29fc74429ca2.gif "Trained Agent"

# Project 3: Collaboration and Competition - Tennis

### Introduction
 
Given two agents that control rockets to bounce a ball over a net. The goal is that the agents must bounce ball between one another while not dropping or sending ball out of bounds.
The agent receives a reward of +0.1 if it hits the ball over the net. It receives a reward of -0.1 if the ball hits the ground or sends out of bounds. 

![Trained Agent][image1]

The observation space consists of 8 variables: the position of the ball and racket and the velocity of the ball and rocket. There are two continuous actions are available for each agent: (1) movement toward or away from the net, (2) jumping.

The environment is considered solved, when the agents get in average at least +0.5 reward over 100 episodes.


### Set up

1. Download the environment that matches your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86_64.zip)


2. Place the file in the DRLND (https://github.com/udacity/deep-reinforcement-learning), in the `p3_collab-compet/` folder, and unzip (or decompress) the file. 

### Getting started

1. Open `Tennis.ipynb`

#### Train the agent

Run the cells from 1. to 5.
After the training a checkpoint.pth file will be created containing all trained weights.
