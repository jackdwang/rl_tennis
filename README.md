# rl_tennis
Reinforcement Learning DDPG for solving the tennis environment

# Project Description
The environment is composed of two agents, each controlling a racket to hit a ball over the net. For every instance where the agent hits the ball over the net, a reward of +0.1 is given; otherwise the agent receives a -0.01. The ultimate objective of each agent is to keep the ball in play.

The observation space has 8 variables that include the position and velocity of the ball as well as the racket. Each agent receives its own observation of the environment. There are two continuous actions: horizontal movement (forward or backward) and jump.

The environment is episodic, and it is considered solved when an average score of +0.5 over 100 consecutive episodes has been achieved.

# Getting Started
To install all the necessary dependencies for this project, run: !pip -q install ./python

# Run the Code
To run the code for training the agent, open the jupyter notebook named learning.ipynb and run all cells. The training automatically terminates when the reward requirement is reached for the agent. It will save the model output as checkpoint_actor.pth and checkpoint_critic.pth.
