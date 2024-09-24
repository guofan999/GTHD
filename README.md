# Game Theory-Based Harmonious Decision-Making (GTHD) Algorithm

## Overview
Blended traffic, comprising autonomous buses (ABs) and human-driven vehicles (HDVs), is becoming increasingly common. However, the lane change decision-making for ABs remains challenging due to complex interactions with heterogeneous HDVs. This repository contains the implementation of a game theory-based harmonious decision-making (GTHD) algorithm that addresses these challenges.

## Key Features
- **Game Theory Framework**: Utilizes a game theoretic model considering the nuances of HDV driving styles.
- **Driving Style Estimation**: Employs clustering of historical data for initial driving style estimation, refined in real-time through Bayesian estimation.
- **Human-like Performance**: Achieves 91.50% - 98.50% accuracy compared to human bus drivers in various conditions.

## Technical Details
The GTHD algorithm leverages:
- Predictions of the opposing vehicle’s motion.
- Information from preplanned trajectories.
- A modified game theoretic model that adapts self-preferences based on opponent behavior.

## Validation
The efficacy of the GTHD algorithm is validated using a hardware and human-in-the-loop simulator, demonstrating superior performance over several data-driven lane change models.

## Getting Started
### Prerequisites
- [List any dependencies, libraries, or software required]

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/repository.git
2. Clone the repository:
   ```bash
   cd repository
3. Create a new Anaconda environment:
   ```bash
   conda create -n gthd_env python=3.8
4. Activate the environment:
   ```bash
   conda activate gthd_env
5. Install the required packages:
   ```bash
   pip install -r requirements.txt
