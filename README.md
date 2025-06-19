# Simulation code of Assignment 1:

Code by Hoang Phi Yen Duong and Tinh Thanh Bui

# Prerequisites:

Python 3.9 or higher, Jupyter Notebook

In order to run the code:
***
You have to install: numpy, matplotlib, and scipy
***

## 1. Assignment_01_Part_01.ipynb - Stationary problem
   
In this part, we investigate four bandit algorithms, including the greedy method with non-optimistic initial values, the epsilon-greedy method, the greedy method with optimistic starting values, and the gradient bandit algorithm. 

Each algorithm is run for 2000 time steps with 1000 different simulations.

## 2. Assignment_01_Part_02.ipynb - Non-Stationary problem

In this part, we consider a bandit problem consisting of 10 arms with non-stationary environments that change the rewards gradually, abruptly, or a combination of both. 

There are four types of changes considered, including drift in means, mean-reverting change, permuting means, and a hard reset in all action values. 

All algorithms are run over 1000 simulations of 2000 time steps. In the simulations, we use the same 10 seeds to keep the same random processes happening in 10 arms. 
