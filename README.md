# Readme

## Project Details

This project is a solution to the Udacity Deep Reinforcement Learning nanodegree project 2 (https://github.com/udacity/deep-reinforcement-learning/tree/master/p2_continuous-control). 

 A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of your agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

According to the project spec, the environment is considered solved if the agent is able to receive an average reward (over 100 episodes) of at least 30.

My implementation of an agent solving the environment is found in in `ddpg_agent.py` and `model.py` in the root directory.

It is heavily based on the DDPG bipedal walker example from the respective Udacity nanodegree Github repository  (https://github.com/udacity/deep-reinforcement-learning/tree/master/ddpg-bipedal).



## Getting Started

### Install the dependencies

    pip install -r requirements.txt

### Download the environment

Download the environment from one of the links below.  You need only select the environment that matches your operating system:

- **_Version 2: Twenty (20) Agents_**
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86_64.zip)

more detailed instructions can be found at https://github.com/udacity/deep-reinforcement-learning/tree/master/p2_continuous-control.

### Train an agent

`Continuous_Control.ipynb` contains the entry point to training an agent and loading a trained agent for evaluation.

`Report.ipynb` documents the parameters of the DDPG used to train the agent.
