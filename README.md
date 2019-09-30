
## P1 - Navigation

This is a repo a project in Udacity's Deep Reinforcement Learnign Nanodegree.
It trains an agent in a Unity Environment. Unity Machine Learning Agents (ML-Agents) is an open-source Unity plugin that enables games and simulations to serve as environments for training intelligent agents.

Original Referenc: https://github.com/udacity/deep-reinforcement-learning/tree/master/p1_navigation

### The environment

This project trains an agent to navigate (and collect bananas) in a large, square world.

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

+ 0 - move forward.

+ 1 - move backward.

+ 2 - turn left.

+ 3 - turn right.

The task is episodic, and in order to solve the environment, the agent must get an average score of +13 over 100 consecutive episodes.

<br>
<center>
<img src="https://user-images.githubusercontent.com/10624937/42135619-d90f2f28-7d12-11e8-8823-82b970a54d7e.gif">
</center>
<br>

### Project Instruction from Udacity

I ran this project in Udacity's workspace. These are the instructions given in the project's Github.

#### Getting Started

1. Download the environment from one of the links below. You need only select the environment that matches your operating system:
  * Linux: click <a href="https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip">here</a>
  * Mac OSX: click <a href="https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip">here</a>
  * Windows (32-bit): click <a href="https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip">here</a>
  * Windows (64-bit): click <a href="https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip">here</a>

2. Place the file in the DRLND GitHub repository, in the p1_navigation/ folder, and unzip (or decompress) the file. The correspondig file path must be refrenced in `env = UnityEnvironment(file_name="...")`.

### Instructions
All the code is contained in **Report.ipynb**. Running the code sequentially in the notebook will train the agent and generate a checkpoint.
