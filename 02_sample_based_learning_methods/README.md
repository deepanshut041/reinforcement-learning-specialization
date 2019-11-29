# Sample-based Learning Methods

By the end of this course you will be able to:

- Understand Temporal-Difference learning and Monte Carlo as two strategies for estimating value functions from sampled experience
- Understand the importance of exploration, when using sampled experience rather than dynamic programming sweeps within a model
- Understand the connections between Monte Carlo and Dynamic Programming and TD.
- Implement and apply the TD algorithm, for estimating value functions
- Implement and apply Expected Sarsa and Q-learning (two TD methods for control)
- Understand the difference between on-policy and off-policy control
- Understand planning with simulated experience (as opposed to classic planning strategies)
- Implement a model-based approach to RL, called Dyna, which uses simulated experience
- Conduct an empirical study to see the improvements in sample efficiency when using Dyna

## Week 1: Welcome to the Course

Welcome to the second course in the Reinforcement Learning Specialization: Sample-Based Learning Methods, brought to you by the University of Alberta, Onlea, and Coursera. In this pre-course module, you'll be introduced to your instructors, and get a flavour of what the course has in store for you. Make sure to introduce yourself to your classmates in the "Meet and Greet" section!

## Week 2: Monte Carlo Methods for Prediction & Control

This week you will learn how to estimate value functions and optimal policies, using only sampled experience from the environment. This module represents our first step toward incremental learning methods that learn from the agent’s own interaction with the world, rather than a model of the world. You will learn about on-policy and off-policy methods for prediction and control, using Monte Carlo methods---methods that use sampled returns. You will also be reintroduced to the exploration problem, but more generally in RL, beyond bandits.

- Graded Quiz: [Monte Carlo Methods](./Week_2/Graded_Quiz.pdf)
- Programming Assignment: [Blackjack](./Week_2/Assignment/Blackjack.ipynb)

## Week 3: Temporal Difference Learning Methods for Prediction

This week, you will learn about one of the most fundamental concepts in reinforcement learning: temporal difference (TD) learning. TD learning combines some of the features of both Monte Carlo and Dynamic Programming (DP) methods. TD methods are similar to Monte Carlo methods in that they can learn from the agent’s interaction with the world, and do not require knowledge of the model. TD methods are similar to DP methods in that they bootstrap, and thus can learn online---no waiting until the end of an episode. You will see how TD can learn more efficiently than Monte Carlo, due to bootstrapping. For this module, we first focus on TD for prediction, and discuss TD for control in the next module. This week, you will implement TD to estimate the value function for a fixed policy, in a simulated domain.

- Practice Quiz: [TD Learning(Prediction)](./Week_3/Practice_Quiz.pdf)
- Programming Assignment: [Policy Evaluation with Temporal Difference Learning](./Week_3/Assignment/C2M2-Assignment-v4.ipynb)

## Week 4: Temporal Difference Learning Methods for Control

This week, you will learn about using temporal difference learning for control, as a generalized policy iteration strategy. You will see three different algorithms based on bootstrapping and Bellman equations for control: Sarsa, Q-learning and Expected Sarsa. You will see some of the differences between the methods for on-policy and off-policy control, and that Expected Sarsa is a unified algorithm for both. You will implement Expected Sarsa and Q-learning, on Cliff World.

- Practice Quiz: [TD Learning(Control)](./Week_4/Practice_Quiz.pdf)
- Programming Assignment: [Q-Learning and Expected Sarsa](./Week_4/Assignment/C2M3_Assignment2_v6.ipynb)

## Week 5: Planning, Learning & Acting

Up until now, you might think that learning with and without a model are two distinct, and in some ways, competing strategies: planning with Dynamic Programming verses sample-based learning via TD methods. This week we unify these two strategies with the Dyna architecture. You will learn how to estimate the model from data and then use this model to generate hypothetical experience (a bit like dreaming) to dramatically improve sample efficiency compared to sample-based methods like Q-learning. In addition, you will learn how to design learning systems that are robust to inaccurate models.

- Practice Quiz: [Planning, Learning & Acting](./Week_5/Practice_Quiz.pdf)
- Programming Assignment: [Dyna-Q and Dyna-Q+](./Week_5/Assignment/Planning_Assignment-v2.ipynb)

## Course Certificate

![Certificate](./3W9VT59J6R7E.png)