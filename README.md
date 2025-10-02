# Optimal Control

This project aims to explore and compare the different methods of solving optimal control problems.

This project will focus on apply different optimal control methods on different types of systems with the goal.

The optimal control methods implemented in this project are categorised based on how much information about the system is available as Planning Methods which require complete information on the system, Model-Based Learning which requires some information on the system, and Model-Free Learning which requires almost no information on the system.

The systems modeled in this project are also categorised based on how much information about the system is available as Deterministic systems, and Stochastic Systems.

## The Objective

The objective of this project is to implement an optimal control strategy for different classes of optimal control problems

# Table of Contents

* [Introduction to Optimal Control Problems](./Systems/README.md)
  - [Dynamical Systems](./Systems/README.md)
    + [Properties of dynamical systems](./Systems/README.md) 
    + [Challenges that may arise when modelling a dynamical system](./Systems/README.md)
    + [Types of dynamical systems](./Systems/README.md)
  - [Control Theory](./Systems/README.md)
    + [Basic terminology of control theory](./Systems/README.md)
    + [Challenges that may arise when controlling a system](./Systems/README.md)
    + [Methods of control](./Systems/README.md)
    + [Markov Decision Processes](./Systems/README.md)
  - [Optimization Problems](./Systems/README.md)
    + [Types of optimization problems](./Systems/README.md)
    + [Methods of optimization](./Systems/README.md)
    - [Optimization in Control Theory](./Systems/README.md)
* [Optimal Control Methods](./Optimal%20Control%20Methods/README.md)
  - [Analytical/ Planning Methods](./Optimal%20Control%20Methods/README.md)
    + [Variational Calculus](./Optimal%20Control%20Methods/README.md)
    + [Minimum Principle](./Optimal%20Control%20Methods/README.md)
    + [Hamilton-Jacobi-Bellman Equation](./Optimal%20Control%20Methods/README.md)
  - [Learning Methods](./Optimal%20Control%20Methods/README.md)
    + [Dynamic Programming](./Optimal%20Control%20Methods/README.md)
    + [Model-Based Reinforcemnt Learning](./Optimal%20Control%20Methods/README.md)
    + [Model-Free Reinforment Learning](./Optimal%20Control%20Methods/README.md)
* [Implementation of Solutions](#18)
  - [Case Study 1: Trajectory Optimization](#19)
    + [System Design](#20)
    + [Control Implementation](#21)
  - [Case Study 2: Adaptive Control](#22)
    + [System Design](#23)
    + [Control Implementation](#24)
  - [Case Study 3: Stochastic Control](#25)
    + [System Design](#26)
    + [Control Implementation](#27)

## Code Design
The code for this project will be written in Python with Jupyter Notebook and will be divided into the following sections:
- **Optimal Control Methods**: This section will contain the implementation of the different optimal control methods.
- **System Models**: This section will contain the implementation of the different system models.
- **Case Studies**: This section will contain the implementation of the different case studies.
- **Tests**: This section will contain the code to test each System Model, and Optimal Control Method
- **Tools**: This section will contain scripts to automate tasks in the project.


The code is tested with `Python 3.12.1` with the following packages:
```
Package    Version
---------- -------
numpy      1.26.4
pip        24.0
torch      2.3.1
```
## References
- [Model-based Reinforcement Learning: A Survey.](https://arxiv.org/pdf/2006.16712)
- [Back propagation implementation.]https://towardsdatascience.com/neural-networks-backpropagation-by-dr-lihi-gur-arie-27be67d8fdce/
- [Layer Normalization](https://arxiv.org/pdf/1607.06450)
- [Weight Normalization](https://arxiv.org/pdf/1602.07868)
- [FASTNORM](https://openreview.net/pdf?id=BkbOsNeSM)
- [Layer Normalization Implemetation](https://neuralthreads.medium.com/layer-normalization-applied-on-a-neural-network-f6ad51341726#:~:text=Second%2C%20the%20activation%20function%20for,layer%20is%20the%20Softmax%20function.&text=Fifth%2C%20For%20the%20first%20hidden,before%20the%20ReLU%20activation%20function.)
- [DDPG](https://www.davidsilver.uk/wp-content/uploads/2020/03/deterministic-policy-gradients.pdf)
- [Reinforcement Learning for Continuous Stochastic Control Problems](https://proceedings.neurips.cc/paper_files/paper/1997/file/186a157b2992e7daed3677ce8e9fe40f-Paper.pdf)
### TO DO/ Future Updates
- Complete testing for DDPG Algorithm
- Hyperparametric optimization of DDPG solution of the particle in a field problem
- Complete implementation of the MDP algorithm
- Testing the MDP algorithm
- Use the MDP algorithm to solve the the particle in a field problem
- Benchmark the performance of these algorithms


