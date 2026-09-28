# Q-Learning Reinforcement Learning – CliffWalking-v1

## 📌 Project Overview

This project implements the **Q-Learning** reinforcement learning algorithm using the **CliffWalking-v1** environment from Gymnasium.

Q-Learning is an **off-policy Temporal Difference (TD) learning algorithm** that learns the optimal action-selection policy by updating Q-values based on the maximum expected future reward from the next state.

## 🎯 Objective

The main objective of this project is to understand and implement the **Q-Learning algorithm** and observe how an agent learns to navigate through the CliffWalking-v1 grid environment while avoiding the cliff and reaching the destination.

## 🌍 Environment

The project uses:

**CliffWalking-v1**

CliffWalking is a grid-world environment where the agent starts at a fixed position and must reach the goal while avoiding the cliff. Stepping into the cliff results in a large negative reward.

## 🔄 Workflow

1. Create the `CliffWalking-v1` environment.
2. Initialize the Q-table.
3. Define the epsilon-greedy action-selection strategy.
4. Set Q-Learning parameters such as learning rate and discount
