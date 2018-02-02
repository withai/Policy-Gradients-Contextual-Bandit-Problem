# Policy Gradients Contextual Bandit Problem

Overview
=========
Policy Gradients is one of the Reinforcement Learning Algorithm. In this method, a simple neural-network learns a policy for picking actions by adjusting it's weights through gradient descent using feedback from our environment.

In this experiment we are going to solve Contextual Bandit Problem. This problem falls in the intermediary of a simple Bandit problem and full Reinforcement Learning problem.

Lets put some of the pointers of Contextual Bandit Problem:
*  The environment consists of several states(bandits) and are independent of each other. 
*  Given a state(bandit) the agent understands the environment and tries to make best possible action(pull arm) which results in better rewards.

Dependencies
============
* Jupyter Notebook
* NumPy
* Tensorflow (https://www.tensorflow.org/install/)

Credits
========
Most of the conceptual and programmatic understanding is borrowed from the Reinforcement Learning Series by Arthur Juliani [here](https://medium.com/emergent-future/simple-reinforcement-learning-with-tensorflow-part-0-q-learning-with-tables-and-neural-networks-d195264329d0).
