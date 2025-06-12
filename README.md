# Markov_Process_Simulation
A 2-state Continuous Time Markov Chain project: Simulate stochastic transitions using the Gillespie algorithm, compare empirical &amp; analytical probabilities, and analyze steady-state behavior. Code + theory in Python.

# 2-State Continuous Time Markov Chain Simulation

A Python implementation of a **2-state Continuous Time Markov Chain (CTMC)**, simulating stochastic transitions using the Gillespie algorithm and comparing empirical trajectories with analytical solutions.

## 📌 Overview
- **Master Equation**: Solves ∂ₜP(t) = L·P(t) for transition matrix `L`.
- **Gillespie Algorithm**: Generates stochastic state trajectories.
- **Validation**: Compares empirical `P₁(t)` from simulations with theoretical predictions.

## 🔧 Key Features
- **Analytical Solution**: Computes `P₁(t)` for given transition rates (ω⁺, ω⁻).
- **Steady-State Analysis**: Finds limₜ→∞ P(t).
- **Stochastic Simulation**: Generates trajectories with exponential waiting times.
- **Visualization**: Plots theory vs. simulation results.

## ⚙️ Dependencies
- Python 3.x
- NumPy (`pip install numpy`)
- SciPy (`pip install scipy`)
- Matplotlib (`pip install matplotlib`)
- Jupyter Notebook (optional, for interactive plots)

## 🚀 Quick Start
1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/ctmc-simulation.git
