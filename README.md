# Treasure-Hunt-Grid-World
A grid world treasure hunt environment based reinforcement learning application trained using SARSA and n-step double q learning

A treasure hunt environment of 5*4 grids (20 states) having positive and negative rewards and an end goal, navigated by 4 actions (up, down, left, right) 

<img src="https://github.com/user-attachments/assets/d61854fc-4973-4b61-8bf2-6fe639fcf67a" alt="Sample Image" width="400" />

Trained with random hyperparameters using SARSA and n-step double q-learning approach. Tested using greedy-approach on the updated Q-table. Implemented hyperparameter tuning using Optuna to find ideal learning rate(alpha), discount factor(gamma), exploration factor(epsilon), exploration factor decay rate(epsilon decay rate), no.of training episodes, maximum timesteps in an episode, minimum epsilon value. 

**Results:**
For SARSA, without optimisation initital rewards collected was +54 points.
After hyperparameter optimisation, it increased to +594.

For N-Step Double Q-Learning without optimisation initial rewards collected was +348.
After hyperparameter optimisation it increased to 694 with n=4.
