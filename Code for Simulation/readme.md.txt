# Quantum Spin Chain Simulation  

This project simulates a **Time crystal behavior in quantum spin chain system** using **QuSpin** and **SciPy**. The code performs **time evolution**, **Hamiltonian construction**, and **observables measurement** in a **6-spin system** with spin interactions. The goal is to analyze spin dynamics and expectation values of Spin magnetization over time to simulate time crystal behavior.

## **Features**
- **Defines a quantum spin chain** of length `L = 6`.
- Constructs **Hamiltonians** with `XX`, `YY`, and `ZZ` interactions.
- Implements **unitary time evolution** using matrix exponentiation.
- Computes **spin expectation values** for central spin as well as satellite spin.
- Plots **$|(-1)^n S_z,0|$** vs. period number on a logarithmic scale.

## **Dependencies**
Ensure you have the following Python packages installed:
```bash
pip install numpy scipy matplotlib quspin
