# Nim
Reinforcement Learning AI for Nim Game
## Overview
To build a self-learning AI for the game of Nim using reinforcement learning (specifically Q-learning), you need to complete the implementation of the NimAI class. Below is an outline of the steps you'll take, focusing on how to add the necessary components to the project and how they relate to the reinforcement learning concepts you need to implement.
## Key Concepts for Q-Learning
* **State**: The current configuration of piles in Nim, represented as a list (e.g., [1, 1, 3, 5]).
* **Action**: A tuple (i, j) representing removing j objects from pile i.
* **Q-value**: A numerical value associated with a specific state-action pair, stored in self.q. Over time, the AI will update these Q-values to reflect the quality of actions in different states.
* **Learning Rate (alpha)**: A parameter to control how much new information is considered in updating the Q-values.
* **Exploration Rate (epsilon)**: A parameter for the epsilon-greedy strategy that controls how often the AI explores by taking random actions versus exploiting known Q-values.
## Specification
For more information about the project specifications, please refer to the [Harvard CS50AI](https://cs50.harvard.edu/ai/) website.
Please avoid directly copying the source code as it is provided for reference purposes only. 

