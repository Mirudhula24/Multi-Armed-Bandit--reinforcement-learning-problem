# Multi-Armed-Bandit--reinforcement-learning-problem
Multi-Armed Bandit (MAB)

The Multi-Armed Bandit (MAB) problem is a fundamental framework in Reinforcement Learning that models decision-making under uncertainty.
In this setting, an agent repeatedly chooses one action from a fixed set of actions (called arms) and receives a reward based on the chosen action. The reward distributions are initially unknown and must be learned through interaction.

The objective of a MAB algorithm is to maximize cumulative reward over time by balancing:

Exploration: Trying different actions to learn their reward distributions.
Exploitation: Selecting the action that is currently believed to yield the highest reward.

Unlike full Markov Decision Processes (MDPs), the MAB problem has:

No state transitions
No delayed rewards
Immediate feedback after each action

In practical applications, each arm represents a possible choice such as a product recommendation, advertisement, or pricing option, and the reward represents profit, click-through rate, or user engagement.

Common MAB strategies include:

Random Policy (pure exploration)
Greedy Strategy (pure exploitation)

ε-Greedy Strategy (controlled exploration–exploitation trade-off)

The Multi-Armed Bandit framework is widely used in recommendation systems, online advertising, clinical trials, and adaptive resource allocation, making it a core concept in Deep Reinforcement Learning foundations.
