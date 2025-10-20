# Pirate Intelligent Agent  
**CS-370: Current/Emerging Trends in Computer Science**

## Project Overview
This project focused on developing an intelligent reinforcement learning (RL) agent capable of navigating a maze environment to find treasure efficiently. The agent, represented as a pirate, was trained using a **Deep Q-Learning (DQN)** approach to optimize its decision-making process over multiple episodes. The goal was to enable the agent to learn from experience — balancing exploration and exploitation — until it could consistently reach the goal state.

## Work Completed
The project was built from a partially provided codebase.  

### **Provided Code**
I was given:
- `TreasureMaze.py` — the environment defining maze layout, rewards, and rules for movement.
- `GameExperience.py` — a memory buffer managing experience replay for the DQN model.
- Supporting configuration and utility functions for simulation and visualization.

### **My Contributions**
I implemented and refined:
- The **Deep Q-Learning algorithm**, including:
  - The neural network model architecture (`Sequential` with dense and activation layers).
  - The training loop with epsilon-greedy action selection, reward updates, and experience replay.
  - Epsilon decay to balance exploration and exploitation over time.
- GPU acceleration and environment optimization under **WSL2 with TensorFlow**.
- Visualization improvements and result tracking using `matplotlib`.
- Documentation and testing to verify successful model convergence.

## Connecting Learning to the Field of Computer Science

### **What Computer Scientists Do and Why It Matters**
Computer scientists design intelligent systems, algorithms, and tools that solve real-world problems through automation, data analysis, and optimization. This project demonstrates how machine learning and reinforcement learning can teach an artificial agent to make strategic decisions — a foundational concept used in robotics, autonomous vehicles, and recommendation systems. The ability to simulate learning and decision-making in software helps drive innovation across industries.

### **How I Approach a Problem as a Computer Scientist**
I approach problems by:
1. **Understanding the environment and goal** — defining state, actions, and rewards (in this case, the maze and treasure).
2. **Designing modular, testable code** — separating environment logic, experience management, and learning algorithms.
3. **Applying experimentation and iteration** — adjusting hyperparameters, monitoring performance, and debugging logically.
4. **Leveraging computation tools** — such as GPU acceleration and deep learning frameworks to increase efficiency.

This systematic and analytical approach reflects the core mindset of a computer scientist — to break complex challenges into solvable components using data-driven logic.

### **Ethical Responsibilities to the End User and Organization**
As a computer scientist, ethical responsibility extends beyond technical correctness. When developing intelligent systems:
- **Transparency and accountability** are essential — ensuring that decision-making logic is explainable and fair.
- **User safety and privacy** must be prioritized — especially when AI systems interact with personal or sensitive data.
- **Bias mitigation** is critical — training data and algorithms must be monitored to prevent unintended discrimination or harm.

In this project, although the RL agent operates in a simulated maze, the underlying principles mirror real-world AI ethics — emphasizing responsible innovation that benefits both users and organizations.

---

## Technologies Used
- **Python 3.10**
- **TensorFlow 2.20 / Keras**
- **NumPy, Matplotlib**
- **WSL2 + Ubuntu 22.04 (CUDA 12.9, cuDNN 8.9.7)**
- **VS Code + Jupyter Notebooks**

---

## Author
**Diego Caputi**  
Southern New Hampshire University  
[GitHub Profile](https://github.com/DCaputi001)

---

