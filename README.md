# A Numerical Approach to Fundamental Physical Problems: Travelling Salesperson Problem and the Tacoma Bridge Disaster
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=Jupyter)](tsp-tacoma.ipynb)

This repository contains a Jupyter notebook that explores computational approaches to solve two fundamental problems in physics and engineering:

1. **The Travelling Salesperson Problem (TSP)** - Using simulated annealing to find optimal paths
2. **The Tacoma Narrows Bridge Disaster Model** - Simulating resonance and oscillation phenomena

## Overview

The notebook demonstrates how numerical methods can be applied to complex physical problems. It includes detailed mathematical explanations, algorithm implementations, and visualisations of the results.

## Contents

### 1. The Travelling Salesperson Problem (TSP)

- Implementation of a simulated annealing algorithm to solve the TSP
- Visualisation of path optimisation across U.S. capital cities
- Analysis of temperature schedules and convergence rates
- Exploration of parameter optimisation for finding global minima
- Comparison of different cooling rates (α values)

### 2. The Tacoma Narrows Bridge Disaster Model

- Mathematical modelling of bridge oscillations using coupled differential equations
- Comparison of Taylor and Cromer methods for solving differential equations
- Analyse the effects of driving forces on bridge stability
- Visualisation of time trajectories for different frequency values
- Identification of resonant frequencies through heat maps
- Comparison of simulation results with historical data

## Requirements

The notebook requires the following Python packages:
- NumPy
- Matplotlib
- Random
- JSON
- Copy
- IPython

## Usage

1. Clone this repository
2. Ensure you have Jupyter Notebook or JupyterLab installed
3. Install the required dependencies
4. Open the notebook in Jupyter

```bash
jupyter notebook tsp-tacoma.ipynb
```
Alternatively, use any workspace that has .ipynb capabilities.

## Key Results

- **Travelling Salesperson Problem**: The simulated annealing algorithm successfully finds a minimum path distance of 2182.34 for 30 U.S. cities.
- **Tacoma Narrows Bridge Model**: The resonant frequency of the model was found to be between 0.13 and 0.16 Hz, which is reasonably close to the literature value of 0.2 Hz.

## Visualisation Examples

The notebook contains numerous visualisations including:
- Optimised travel paths overlaid on a U.S. map
- Temperature-distance graphs showing convergence properties
- Time series plots of bridge oscillations
- Phase space trajectories showing chaotic behavior
- 3D heat maps of torsional angles vs. frequency and time

## Limitations and Future Work

The notebook discusses limitations of both models:
- For TSP: The stochastic nature of simulated annealing means the global minimum isn't guaranteed
- For Tacoma Bridge: The 2D model simplifies the complex 3D dynamics and aeroelastic flutter

Future work could include:
- Implementing asymmetric TSP for more realistic travel scenarios
- Developing more sophisticated 3D models of bridge dynamics
- Incorporating material properties and structural elements

## License

MIT License

## Acknowledgements

This work references multiple academic sources included in the notebook's references section.
