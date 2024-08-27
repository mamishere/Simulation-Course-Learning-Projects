# Simulation Homework: Logistic Simulation in Shipping Ports

## Overview

This project focuses on simulating logistics operations in shipping ports using Arena simulation software. The primary objective is to model and analyze the process of ships entering a port, waiting for docking space, and unloading cargo at various terminals. This simulation aims to optimize port operations, reduce waiting times, and improve the utilization of port resources.

## Purpose

This simulation homework was completed as part of a course at Sharif University of Technology, under the guidance of Dr. Hassan Nayebi. The goal was to apply discrete event simulation techniques to real-world logistical problems in maritime shipping.

## Author

- Mohammad Hossein Mahmoudi

## Problem Description

The simulation models the logistics of ship operations at a port. Key components of the model include:

1. **Arrival at Anchorage**: Ships enter the anchorage area and are registered based on their type, length, cargo load, and arrival time.
2. **Waiting Queue**: Ships wait at the anchorage area until certain conditions are met, such as availability of docking space and no blockage in access channels.
3. **Travel to Terminals**: Once conditions are satisfied, ships reserve a terminal and proceed through access channels to dock.
4. **Cargo Unloading**: At the terminal, ships are unloaded based on their type and allocated resources, such as cranes.

## Modeling Approach

- **Simulation Software**: Arena
- **Modeling Technique**: Discrete Event Simulation (DES)
- The simulation is designed to track the status of ships and resources in real-time, providing insights into the performance of port operations and resource utilization.

![Modeling Approach](path/to/your/modeling_approach_image.png)

## Key Components of the Simulation

### 1. Registration and Initial Queue

- Ships are categorized into two types: Liner and Feeder.
- Liner ships can only unload at Terminal A, while Feeder ships can use both Terminal A and B, with a preference for Terminal B.
- Ships are registered upon arrival, and their details are logged.

### 2. Waiting and Docking Logic

- Ships wait at anchorage until docking conditions are met:
  - Liner ships require sufficient docking space at Terminal A.
  - Feeder ships can proceed to either Terminal A or B based on availability and priority.
- Liner ships have priority in the access channel.

### 3. Unloading at Terminals

- Ships are served based on their terminal assignment:
  - Terminal A serves both Liner and Feeder ships.
  - Terminal B serves only Feeder ships.
- The number of cranes assigned for unloading depends on the type and load of the ship.

### 4. Exit from System

- After unloading, ships release their reserved space and exit the system.
- The total time spent in the system, including waiting, docking, and unloading, is recorded.

## Data Analysis

- The simulation provides detailed reports on key metrics:
  - Waiting time at anchorage
  - Number of ships waiting
  - Time spent in the system (anchorage + terminal)
  - Utilization of cranes at each terminal

- The results are analyzed to answer critical questions about improving port operations, such as the impact of adding additional cranes to terminals.

![Data Analysis Table](path/to/your/data_analysis_image.png)

## Results and Recommendations

- Initial analysis suggests that adding a crane to Terminal A can reduce the overall waiting time for ships.
- Further tests are required to validate these findings using statistical methods.

## Conclusion

This simulation project demonstrates the use of discrete event simulation to analyze and optimize port logistics. The model helps in identifying bottlenecks and provides a framework for improving operational efficiency.

## Acknowledgements

This project was conducted as part of the coursework for the Simulation class at Sharif University of Technology, instructed by Dr. Hassan Nayebi.
