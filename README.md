# Cliff-Walking SARSA Agent

An implementation of the on-policy SARSA (State-Action-Reward-State-Action) reinforcement learning algorithm to navigate the classic Cliff-Walking grid environment. Built using Python and the Gymnasium library, this project demonstrates the agent's ability to learn a safer, more conservative path across the grid compared to off-policy methods.

## 🚀 Features
* **SARSA Implementation:** Implements the on-policy SARSA update rule, dynamically updating the Q-table based on the actual actions taken by the epsilon-greedy policy.
* **Epsilon-Greedy Policy:** Balances exploration of new grid states with the exploitation of known optimal actions to maximize long-term rewards.
* **Performance Tracking:** Logs the total reward and episode length across 500 training episodes, allowing for analysis of the learning curve.
* **Human-Readable Rendering:** Includes a testing phase that visually renders the trained agent navigating the environment using the learned optimal path.

## 💻 Tech Stack
* **Language:** Python
* **Libraries:** * `gymnasium` (for the CliffWalking-v1 environment)
  * `numpy` (for zero-initialized Q-table matrix operations)
  * `random` (for stochastic action selection)

## ⚙️ Hyperparameters Used
* **Discount Factor (Gamma):** `0.99`
* **Learning Rate (Alpha):** `0.5`
* **Exploration Rate (Epsilon):** `0.1`
* **Training Episodes:** `500`
