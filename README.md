# Hybrid Genetic Algorithm and Tabu Search for Task Scheduling in Edge-Cloud Computing

This repository contains the implementation of a hybrid optimization algorithm that combines **Genetic Algorithm (GA)** and **Tabu Search (TS)** for efficient task scheduling in a collaborative **edge-cloud computing** environment. The solution was developed as part of a master's thesis at OsloMet in 2025.

## 📌 Project Highlights

- Optimizes task-to-resource allocation using a hybrid GA–TS approach.
- Supports heterogeneous edge-cloud environments with dynamic workloads.
- Utilizes **epsilon-decay** strategy to adapt the mutation rate over time.
- Employs a **weighted multi-objective fitness function** focusing on:
  - ✅ Makespan minimization
  - ✅ Throughput maximization
  - ✅ Resource utilization

## 📁 File Included

- `Master_thesis_epsilon_decay_2025_v32.1_v18_Weighted_Sum_GA_TS_27_Mars.py`  
  The full Python script implementing the hybrid scheduling solution.

## ⚙️ Key Features

- **Epsilon Decay Mechanism**: Dynamically adjusts mutation rates to balance exploration and exploitation across generations.
- **Weighted Fitness Function**: Combines multiple performance metrics into a single score.
- **Tabu Search Integration**: Enhances local refinement and avoids revisiting previous solutions.
- **Edge-Cloud Simulation**: Models collaborative environments with heterogeneous resources and tasks.

## 🧪 Requirements

- Python 3.7+
- NumPy
- Random
- Time
- (Optional) matplotlib or pandas for post-processing or visualization

## 🚀 How to Run

```bash
python Master_thesis_epsilon_decay_2025_v32.1_v18_Weighted_Sum_GA_TS_27_Mars.py
