# deep-reinforcement-learning-p3_collab-compet
This is the third project of the deep reinforcement learning course built by Dan Dumitru Damian - collaboration and competiton

## Project Details

For this project I built and trained two actor-critic agents for the [Tenis](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#tennis) environment

IIn this environment, two agents control rackets to bounce a ball over a net. If an agent hits the ball over the net, it receives a reward of +0.1. If an agent lets a ball hit the ground or hits the ball out of bounds, it receives a reward of -0.01. Thus, the goal of each agent is to keep the ball in play.

The observation space consists of 8 variables corresponding to the position and velocity of the ball and racket. Each agent receives its own, local observation. Two continuous actions are available, corresponding to movement toward (or away from) the net, and jumping.

The task is episodic, and in order to solve the environment, your agents must get an average score of +0.5 (over 100 consecutive episodes, after taking the maximum over both agents).

The environment is considered solved, when the average (over 100 episodes) of those scores is at least +0.5.

## Getting started

1. Download the project files from this GitHub repository into a local directory

2. Download the environment for playing from one of the links below.  You need only select the environment that matches your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86.zip),
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86_64.zip)

3. Create `env/` sub-folder, place the env files in it and unzip (or decompress) them.

## Instructions

1. Read the `Reporrt.ipynb` containing full desccription of all the steps built for training the agent(s) for controlling the environment.

2. Read and run the `Tennis.ipynb` to visualize a trained agent, based on the saved actor and critic NNs.
