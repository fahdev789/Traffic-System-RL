🚦 Reinforcement Learning for Traffic Signal Control 🚗
Project Overview 🧠
This project uses Reinforcement Learning (RL) to optimize the control of traffic signals at intersections. We employ the Gensyn RL Environment to simulate real-time traffic conditions and train an RL agent that dynamically controls the traffic lights to improve traffic flow, reduce congestion, and minimize environmental impact.

The RL agent learns to decide when to turn each lane’s traffic signal Green based on the number of cars in each lane, with the goal of reducing wait times and enhancing traffic efficiency.

Gensyn RL Environment 🔧
This project utilizes Gensyn as the RL framework to model and control the traffic signal system. Gensyn's RL environment is designed to handle complex simulation problems, like traffic management, where multiple agents interact with each other and the environment.

Custom Traffic Simulation: A 4-lane intersection environment is created where each lane has a traffic queue. The RL agent’s job is to optimize the traffic flow by controlling when each lane's light turns Green or Red.

Dynamic Training: Using Gensyn's RL, the agent learns from the environment by observing the state of each lane (queue size) and taking actions (turning the light Green or Red). Rewards are given for clearing cars from the queue, and penalties are given for congestion.

Real-World Application: The goal is to apply this model to real-world traffic systems to reduce congestion, optimize traffic flow, and lower carbon emissions.

Features 🚀
Real-Time Adaptation: Traffic signals learn to adapt based on current traffic conditions, making them more efficient than fixed-timed signals.

Energy and Emission Savings: Optimized traffic flow reduces vehicle idling, improving air quality.

Scalable: The system can be extended to handle multiple intersections and complex road networks.

Interactive Simulation: Allows testing of different traffic scenarios and visualizes the behavior of the traffic light system in real-time.

