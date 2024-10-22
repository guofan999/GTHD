# Game Theory-Based Harmonious Decision-Making (GTHD) Algorithm

## Overview
Blended traffic, comprising autonomous buses (ABs) and human-driven vehicles (HDVs), is becoming increasingly common. However, the lane change decision-making for ABs remains challenging due to complex interactions with heterogeneous HDVs. This repository contains the implementation of a game theory-based harmonious decision-making (GTHD) algorithm that addresses these challenges.

## Key Features
- **Game Theory Framework**: Utilizes a game theoretic model considering the nuances of HDV driving styles.
- **Driving Style Estimation**: Employs clustering of historical data for initial driving style estimation, refined in real-time through Bayesian estimation.

## Technical Details
The GTHD algorithm leverages:
- Predictions of the opposing vehicle’s motion.
- Information from preplanned trajectories.
- A modified game theoretic model that adapts self-preferences based on opponent behavior.

## Getting Started
### Prerequisites
To perform testing, you will need two PCs. One should have 51SimOne installed, which can be downloaded from 51SimOne's official website：https://www.51sim.com/products/simone. The second PC should be running Ubuntu with the following installed: ROS (Robot Operating System), CMake, Anaconda3, C++, and the appropriate NVIDIA drivers. These setups will enable you to effectively test and run the simulations.

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/guofan999/GTHD.git
2. Clone the repository:
   ```bash
   cd repository
3. Create a new Anaconda environment:
   ```bash
   conda create -n gthd_env python=3.9
4. Activate the environment:
   ```bash
   conda activate gthd_env
5. Install the required packages:
   ```bash
   pip install -r requirements.txt
6. Install the ros:
   
### Provided Tools
Here are some essential tools provided to support your research and development efforts. These tools include localization functions, data logging capabilities, map parsing utilities, and hardware-in-the-loop (HIL) simulation tools. These resources will help you efficiently test and validate the performance of autonomous driving algorithms, ensuring adaptability and robustness in various real-world scenarios.

### Data
We have provided necessary sample data to assist you in getting started with your work. If you require additional data or have specific data requests, please feel free to contact us at fanguo@tju.edu.cn. We will be happy to assist you with any further data needs.

### Others
If you have any questions, please feel free to reach out to us. We welcome collaboration and discussion. The code is continuously being updated, and we are working on a more complete version, which will be uploaded to GitHub soon.

