# Fundamentals of Reinforcement Learning

This course introduces you to the fundamentals of Reinforcement Learning. When you finish this course, you will:

- Formalize problems as Markov Decision Processes 
- Understand basic exploration methods and the exploration/exploitation tradeoff
- Understand value functions, as a general-purpose tool for optimal decision-making
- Know how to implement dynamic programming as an efficient solution approach to an industrial control problem

## Week 1: The K-Armed Bandit Problem

For the first week of this course, you will learn how to understand the exploration-exploitation trade-off in sequential decision-making, implement incremental algorithms for estimating action-values, and compare the strengths and weaknesses to different algorithms for exploration. For this week’s graded assessment, you will implement and test an epsilon-greedy agent.

- Practice Quiz: [Exploration-Exploitation](./Week_1/Practice_Quiz.pdf)
- Programming Assignment: [Bandits and Exploration/Exploitation](./Week_1/Assignment/Assignment1-v2.ipynb)

## Week 2: Markov Decision Processes

When you’re presented with a problem in industry, the first and most important step is to translate that problem into a Markov Decision Process (MDP). The quality of your solution depends heavily on how well you do this translation. This week, you will learn the definition of MDPs, you will understand goal-directed behavior and how this can be obtained from maximizing scalar rewards, and you will also understand the difference between episodic and continuing tasks. For this week’s graded assessment, you will create three example tasks of your own that fit into the MDP framework.

- Graded Quiz: [MDPs](./Week_2/Graded_Quiz.pdf)

## Week 3: Value Functions & Bellman Equations

Once the problem is formulated as an MDP, finding the optimal policy is more efficient when using value functions. This week, you will learn the definition of policies and value functions, as well as Bellman equations, which is the key technology that all of our algorithms will use.

- Practice Quiz: [Value Functions and Bellman Equations](./Week_3/Practice_Quiz.pdf)
- Graded Quiz: [Value Functions and Bellman Equations](./Week_3/Graded_Quiz.pdf)

## Week 4: Dynamic Programming

This week, you will learn how to compute value functions and optimal policies, assuming you have the MDP model. You will implement dynamic programming to compute value functions and optimal policies and understand the utility of dynamic programming for industrial applications and problems. Further, you will learn about Generalized Policy Iteration as a common template for constructing algorithms that maximize reward. For this week’s graded assessment, you will implement an efficient dynamic programming agent in a simulated industrial control problem.

- Practice Quiz: [Dynamic Programming](./Week_4/Practice_Quiz.pdf)
- Programming Assignment: [Optimal Policies with Dynamic Programming](./Week_4/Assignment/C1M4_Assignment2-v3.ipynb)

## Course Certificate

![Certificate](./3W9VT59J6R7E.png)