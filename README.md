# Logistic Simulation in Shipping Ports

<p align="justify">
This project utilizes <strong>Arena simulation software</strong> to model and analyze shipping port operations. The simulation focuses on optimizing port logistics, including ship arrivals, docking, and cargo unloading, to reduce waiting times and enhance resource utilization.
</p>

## Objectives

<p align="justify">
The primary aim is to apply <strong>Discrete Event Simulation (DES)</strong> techniques to maritime logistics, addressing real-world challenges in port operations. This project was completed under the supervision of <strong>Dr. Hassannayebi</strong> as part of coursework at <strong>Sharif University of Technology</strong>.
</p>

## Problem Scope

<p align="justify">
The simulation models key aspects of port logistics:
</p>

1. <p align="justify"><strong>Ship Arrival and Registration</strong>: Logging details such as ship type, cargo load, and arrival time.</p>
2. <p align="justify"><strong>Anchorage Waiting Queue</strong>: Managing docking space availability and access channel clearance.</p>
3. <p align="justify"><strong>Docking and Unloading</strong>: Allocating terminals and cranes based on ship type and cargo.</p>
4. <p align="justify"><strong>System Exit</strong>: Measuring total time spent in the system and releasing resources.</p>

## Methodology

<p align="justify">
- <strong>Software</strong>: Arena  
- <strong>Technique</strong>: Discrete Event Simulation (DES)  
</p>

<p align="justify">
The model tracks real-time status of ships and resources, offering insights into performance metrics and bottlenecks.
</p>

## Simulation Components

1. <p align="justify"><strong>Registration and Queue Management</strong>:  
   Ships are categorized as <strong>Liner</strong> or <strong>Feeder</strong>. Liner ships dock exclusively at <strong>Terminal A</strong>, while Feeder ships can use both <strong>Terminal A</strong> and <strong>Terminal B</strong>, prioritizing the latter.</p>

2. <p align="justify"><strong>Docking Logic</strong>:  
   Ships wait in anchorage until docking conditions are met. Liner ships have priority in access channels.</p>

3. <p align="justify"><strong>Cargo Unloading</strong>:  
   Cranes are assigned based on ship type and load. Terminal A serves both ship types, while Terminal B exclusively serves Feeder ships.</p>

4. <p align="justify"><strong>Exit</strong>:  
   Ships release docking space and exit after unloading. Key metrics, such as time spent in the system, are recorded.</p>

## Data Analysis and Results

<p align="justify">
Key metrics analyzed include:
</p>

- **Waiting time** at anchorage  
- **System time** (total time from arrival to exit)  
- **Cranes utilization** at terminals  

### Key Findings:
<p align="justify">
- Adding one crane to <strong>Terminal A</strong> significantly reduces waiting times for ships.  
- Further analysis with statistical validation is recommended to confirm these results.
</p>

## Conclusion

<p align="justify">
This project highlights the potential of <strong>Discrete Event Simulation</strong> in optimizing port logistics, identifying bottlenecks, and improving operational efficiency. It serves as a framework for strategic decision-making in maritime logistics.
</p>
