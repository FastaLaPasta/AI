# Learn2Slither: Q-Learning Snake Agent

This project, developed as part of the 42 school curriculum, features an AI agent that learns to play the classic Snake game using Q-learning.

## Overview

- **Objective:**  
  Implement a Q-learning algorithm that enables an agent to learn optimal strategies for playing Snake.

- **Key Features:**  
  - Q-learning implementation using a Q-table  
  - Separation of game logic and agent behavior  
  - Real-time decision making and iterative learning  
  - Modular structure for scalability and testing


## Setup & Installation

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/yourusername/yourrepo.git
    cd yourrepo/Learn2Slither
    ```

2. **Install Dependencies:**
    Ensure Python 3 is installed and run:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

- **Starting the Game:**  
  Run `main.py` to launch the Snake game with the Q-learning agent.

- **Agent Training:**  
  The Q-learning logic is implemented in `agent/snake_agent.py`. Monitor training progress through in-game performance and logs.

- **Game Components:**  
  The `game` folder houses the core game modules (apple spawning, board management, etc.), while `utils` contains helper functions.

## Challenges & Learnings

- Balancing exploration and exploitation in Q-learning  
- Managing game state and ensuring smooth, real-time gameplay  
- Debugging reinforcement learning algorithms in an interactive environment
