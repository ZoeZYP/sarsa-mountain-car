# MountainCar using SARSA Learning 

The mountain car is location on the one dimensional track, and the its goal is to climb up the mountain on the right. However, car engine is not strong enough, and the car must drive left and right in order to gain enough momentum.  

MountainCar problem is a part of the OpenAI project:  
(https://gym.openai.com/envs/MountainCar-v0/)

Each timestep results in **-1 reward**, until the goal is reached. 

Agent state is represented with **2 continuos features: position and velocity.**

At each time step, agent can perform one of **3 actions: move left, move right, stay in place.**

## Prerequisites

* gym  
```bash
pip install gym
```
* numpy  
``` bash
pip install numpy
```

## Implementation

**SARSA** reinforcement learning algorithm was used for estimating Q function. 

Continuous state features were discretized into 10 bins per feature.
## Visualizations
