# EV Fleet Charging Optimization under Grid Constraints

Project developed at **KTH Royal Institute of Technology** within the course *Practical Optimization of Energy Networks*.

## Overview

This project investigates the integration of **electric freight transport charging infrastructure** into a medium-voltage distribution network.

The objective is to evaluate how large EV charging loads affect network operation and to develop charging strategies that balance:

- Fleet operational requirements
- Electricity market costs
- Distribution-grid constraints
- Network losses
- Power quality and contingency requirements

The analysis is based on the **CIGRE Medium Voltage benchmark network** and considers four freight depots with different operational profiles.

## Methodology

The project is divided into five main steps:

### Step 1 – Baseline Network Analysis

- Power-flow analysis of the CIGRE MV network
- Evaluation of bus voltages and line/transformer loading
- **N-1 contingency analysis**
- Identification of critical network elements

### Step 2 – Time-Series Network Analysis

- Integration of time-varying distribution-network loads
- Selection of suitable connection points for freight depots
- Two-week hourly load-flow simulations
- Analysis of peak loading conditions
- Contingency analysis with depot loads

### Step 3 – EV Charging Infrastructure Design

- Definition of fleet characteristics and operational schedules
- Charging infrastructure sizing using **eFleetScheduler**
- Simulation of uncontrolled charging
- Evaluation of voltage and equipment-loading impacts
- Contingency analysis under EV charging conditions

### Step 4 – Market-Driven Smart Charging

- Integration of **Nord Pool Day-Ahead electricity prices**
- Optimization of EV charging schedules
- Consideration of vehicle departure times and charging requirements
- Evaluation of charging costs and grid constraints
- Comparison with uncontrolled charging

### Step 5 – Network-Loss Optimization

- Optimization of charging schedules with **network-loss minimization** as the objective
- Load-flow and contingency analysis
- Comparison between:
  - uncontrolled charging,
  - electricity-cost optimized charging,
  - network-loss optimized charging

The overall project structure combines distribution-grid analysis and optimization to study the interaction between freight electrification and network operation. 

## Repository Structure

The coding files are organized according to the project steps:

- **Steps 1–4 folder** – Contains the Jupyter Notebooks covering baseline network analysis, time-series simulations, EV charging infrastructure design, and market-driven smart charging optimization.
- **Step 5 folder** – Contains the notebooks and files related to network-loss-based charging optimization.

The **main results and figures** can be found directly inside the corresponding step folders.

A complete summary of the methodology, comparisons and main outcomes is also available in the **PDF presentation** included in the repository.

## Tools and Methods

**Python · Jupyter Notebook · pandapower · Power Flow Analysis · N-1 Contingency Analysis · EV Charging Optimization · eFleetScheduler · Nord Pool Market Data · Time-Series Analysis · Distribution Networks**

## Project Material

The repository contains:

- Jupyter Notebooks for the different project steps
- Input datasets used for network and EV simulations
- Generated figures and simulation results
- Final PDF presentation summarizing the project

## License

Copyright © 2025. All rights reserved.

This repository is made publicly available for **portfolio and academic viewing purposes only**. No permission is granted to copy, modify, distribute, or reuse the original code, analyses, models, presentations, or other materials developed by the project authors without prior written permission.

Third-party datasets, libraries, network models and other externally sourced materials remain subject to the rights, licenses and restrictions of their respective owners.

## Author

**Michelangelo Inzerilli**  
EIT InnoEnergy, KTH Royal Institute of Technology and Universitat Politècnica de Catalunya