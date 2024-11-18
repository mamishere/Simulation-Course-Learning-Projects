# Logistic Simulation in Shipping Ports

This project utilizes **Arena simulation software** to model and analyze shipping port operations. The simulation focuses on optimizing port logistics, including ship arrivals, docking, and cargo unloading, to reduce waiting times and enhance resource utilization.

## Objectives

The primary aim is to apply **Discrete Event Simulation (DES)** techniques to maritime logistics, addressing real-world challenges in port operations. This project was completed under the supervision of **Dr. Hassan Nayebi** as part of coursework at **Sharif University of Technology**.

## Problem Scope

The simulation models key aspects of port logistics:
1. **Ship Arrival and Registration**: Logging details such as ship type, cargo load, and arrival time.
2. **Anchorage Waiting Queue**: Managing docking space availability and access channel clearance.
3. **Docking and Unloading**: Allocating terminals and cranes based on ship type and cargo.
4. **System Exit**: Measuring total time spent in the system and releasing resources.

## Methodology

- **Software**: Arena  
- **Technique**: Discrete Event Simulation (DES)  

The model tracks real-time status of ships and resources, offering insights into performance metrics and bottlenecks.

## Simulation Components

1. **Registration and Queue Management**:
   - Ships are categorized as **Liner** or **Feeder**.
   - Liner ships dock exclusively at **Terminal A**, while Feeder ships can use both **Terminal A** and **Terminal B**, prioritizing the latter.
   
2. **Docking Logic**:
   - Ships wait in anchorage until docking conditions are met.
   - Liner ships have priority in access channels.

3. **Cargo Unloading**:
   - Cranes are assigned based on ship type and load.
   - Terminal A serves both ship types, while Terminal B exclusively serves Feeder ships.

4. **Exit**:
   - Ships release docking space and exit after unloading.
   - Key metrics, such as time spent in the system, are recorded.

## Data Analysis and Results

Key metrics analyzed include:
- **Waiting time** at anchorage  
- **System time** (total time from arrival to exit)  
- **Cranes utilization** at terminals  

### Key Findings:
- Adding one crane to **Terminal A** significantly reduces waiting times for ships.
- Further analysis with statistical validation is recommended to confirm these results.

## Conclusion

This project highlights the potential of **Discrete Event Simulation** in optimizing port logistics, identifying bottlenecks, and improving operational efficiency. It serves as a framework for strategic decision-making in maritime logistics.
