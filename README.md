# Consensus Control of Time-Delayed Single Integrator Multi-Agent System

## Overview

This project focuses on achieving consensus control for a Time-Delayed Single Integrator Multi-Agent System. The project includes the design, simulation, and analysis of leader-following and leaderless graph structures under varying time delays. The objective is to determine the range of time delays within which the system can achieve consensus and to identify the conditions that lead to instability.

## Project Structure

1. **Introduction**
   - **Objectives:** 
     - Achieve consensus for all given leader-following and leaderless graphs by applying time delays.
     - Design simulation models for different graph structures based on a range of time delays.
     - Observe the simulation results and identify the stability range of the system.

2. **Schematic Block Diagram**
   - Schematic block diagrams for different graph structures (Leader Following Graphs 1 and 2, Leaderless Graphs 3 and 4).

3. **Theory**
   - Analysis of time delays in communication among agents and their impact on system consensus.
   - Calculation of the permissible range of time delays based on the eigenvalues of Laplacian matrices associated with the graph structures.

4. **Conclusion**
   - The system can achieve consensus only if the time delay is within a specified range. If the delay exceeds this range, the system becomes unstable.

5. **Matlab Codes, Simulink Diagrams, Simulation Results**
   - Matlab codes and Simulink diagrams for each graph structure.
   - Simulation results showing stable and unstable behavior for different time delays.

## How to Use

### 1. Hardware and Software Requirements
   - **Software:** MATLAB with Simulink
   - **Hardware:** No specific hardware is required as the project is simulation-based.

### 2. Steps to Run the Simulations
   - Open the MATLAB scripts provided for each graph structure.
   - Run the scripts to generate the state-space matrices and calculate eigenvalues.
   - Open the corresponding Simulink models and simulate the system for varying time delays.
   - Observe the system's behavior and identify the time delay range within which the system achieves consensus.

### 3. Interpreting the Results
   - The simulation results will show how the system behaves under different time delays.
   - Identify the maximum time delay before the system transitions from stable to unstable.

### 4. Modifying the System Parameters
   - You can modify the system parameters (e.g., number of agents, feedback gain) in the MATLAB scripts to observe different behaviors.
   - Re-run the simulations after making changes to verify the impact of the modifications.

## Results and Analysis
   - The project demonstrates that the system achieves consensus within a specific range of time delays, which varies for different graph structures.
   - For example:
     - **Leader Following Graph 1:** Stable for \(0 < T < 1.57\).
     - **Leader Following Graph 2:** Stable for \(0 < T < 1.57\).
     - **Leaderless Graph 3:** Stable for \(0 < T < 0.4598\).
     - **Leaderless Graph 4:** Stable for \(0 < T < 0.3925\).

## Future Work
   - Extend the analysis to non-linear systems and different types of multi-agent systems.
   - Explore the effects of other types of delays (e.g., communication delays, processing delays) on consensus.
   - Implement real-time consensus control on a hardware testbed.

## Contributors
   - **Meesala Ganesh** (Roll No: 234102505)
   - **Arya Mallick** (Roll No: 234102501)
   - Under the guidance of **Dr. Parijat Bhowmick**.

## License
   - This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

