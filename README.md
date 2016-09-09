# Reinforcement Learning Control Center
A d3.js web interface that allows a user to view their RL agent's performance during training.

![RL Control Center](/image.png)


Current version displays:
* Reward over time
* Episode length over time
* Animated gif of agent behavior during sample episodes
* Agent's DDDQN activation during sample episodes


To try a live verion on an already trained network, go [here](http://awjuliani.github.io/Center/).

The control center works by reading csv logs and animated gifs generated during the training process. For an example implementation, see [Double-Dueling-DQN-Central.ipynb](https://github.com/awjuliani/RL-CC/blob/master/Double-Dueling-DQN-Central.ipynb). The current interface is relatively dependent on the particular nature of the environment and agent used, but feel free to fork this project and adapt it to your own reinforcement learning needs. 

See [this Medium post](https://medium.com/p/4f27b134bb2a) for more information on how to use the control center, and the motivation behind it's creation.
