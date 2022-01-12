[//]: # (Image References)

[image1]: https://thumbs.gfycat.com/ChubbyConventionalBrontosaurus-size_restricted.gif "Trained Agent"

# Project 1: Car mountain climbing

### Introduction

For this project, we will train a car climbing a mountain to reach a goal. 

![Trained Agent][image1]

The reward of the agent is based on actions and states.
A reward is positive if the car reaches the goal and negative if the car returns without reaching it.

The state space has 2 dimensions and contains the agent's velocity and speed.
Three discrete actions are available, corresponding to:
- **`0`** - Push left.
- **`1`** - Push right.
- **`2`** - No action.

The task is episodic. while training we fixed the goal reward  as a parameter.

### Dependencies

To work or try this project we used as:
- **`Programming language`** Python 3.8
- **`Frameworks`** Tensorflow 2.7.0 || Keras
- **`Libraries`** Numpy 1.19.5   ||  Matplotlib 3.2.2  ||  Pandas 1.1.5

For training we used Jupyter notebook.
#### 1. Clone the repository
```bash
git clone https://github.com/yossertlili/MountainCar-v0-using-Deep-Reinforcment-Learning
```
#### 2. Work with GPU
![alt text](https://vitalflux.com/wp-content/uploads/2021/06/Google-colab-change-runtime-to-GPU-640x527.jpg)

#### 3. Install tensorflow
```bash
pip install tensorflow
```
#### 4. run cells

```

### Train the agent
In order to train our agent we have to:

1. Initialize the agent.
2. Evaluate state and action space.
3. Train the agent using Double Deep Q-Networks (DDQN). 
4. Iterate until agent reaches a desired goal.
5. Train the agent using Dueling Deep Q-Networks. 
6. Iterate until agent reaches a desired goal.
7. Make a benchmarking.


"# projet" 
"# project" 
