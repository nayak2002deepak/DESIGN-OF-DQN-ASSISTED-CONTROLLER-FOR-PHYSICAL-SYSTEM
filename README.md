# DESIGN-OF-DQN-ASSISTED-CONTROLLER-FOR-PHYSICAL-SYSTEM

A Deep Reinforcement Learning–based control system to stabilize and optimize the behavior of a Mass-Spring-Damper system using Deep Q-Networks (DQN).

🧩 Problem Statement
Traditional controllers require accurate system models and tuning. In this project, we explore how an agent can learn to control a second-order mechanical system — specifically, a Mass-Spring-Damper — using Deep Q-Learning without predefined control laws.

🚀 Objective
Stabilize the mass to its equilibrium position.

Minimize oscillations and settling time.

Learn control policies through interaction, not pre-programmed rules.

🧠 Approach
Model the Mass-Spring-Damper system in a custom OpenAI Gym environment.

Implement a Deep Q-Network (DQN) agent to observe system state and take control actions.

Train the agent to apply optimal force at each step to stabilize the system under varying damping and stiffness.

📌 Key Features
Discrete action space: agent applies quantized force values.

Custom reward function to encourage stability and penalize oscillations.

Visualization of position, velocity, reward, and convergence.

Adaptive learning: agent generalizes over multiple physical configurations.

🛠 Technologies Used
Python

NumPy

OpenAI Gym

PyTorch / Keras (update this based on what you used)

Matplotlib

📊 Results
Agent successfully learned to dampen oscillations and stabilize the mass.

Trained policies were robust across varying damping and spring constants.

Performance improved significantly compared to random or fixed-action baselines.
Acknowledgements
This project was developed as part of my final year B.Tech thesis at NIT Allahabad, Department of Electrical Engineering.
