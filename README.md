# Numerical Approaches to Fundamental Physics Problems

This repository contains computational models addressing two fundamental physics problems: the Traveling Salesperson Problem (TSP) and the Tacoma Narrows Bridge disaster modeling. Both implementations use numerical methods to explore optimization techniques and dynamical systems.

## Overview

The repository includes algorithms, simulations, and visualizations for:

1. **The Traveling Salesperson Problem (TSP)**
   - Implementation of the Simulated Annealing algorithm to find optimal paths
   - Analysis of convergence rates and parameter optimization
   - Visualization of paths across US state capitals

2. **Tacoma Narrows Bridge Disaster Model**
   - Numerical modeling of bridge oscillations using coupled differential equations
   - Comparison of Taylor and Cromer methods for solving ODEs
   - Analysis of resonant frequencies and the effects of driving forces
   - Heat maps and time trajectories for visualizing system behavior

## Getting Started

### Prerequisites
- `numpy`
- `matplotlib`
- `pandas`
- `scipy`

### Running the Notebooks

The Jupyter notebooks in the `notebooks/` directory contain complete analyses with explanations and visualisations:

```
jupyter notebook notebooks/tsp_analysis.ipynb
jupyter notebook notebooks/tacoma_bridge_analysis.ipynb
```

## Repository Structure

- `data/`: Contains necessary data files (maps, coordinates)
- `src/`: Source code organized by problem domain
- `notebooks/`: Jupyter notebooks with complete analyses
- `images/`: Figures used in the notebooks and documentation

## Results

### Traveling Salesperson Problem

The simulated annealing algorithm found a minimum path for 30 US cities of 2182.34 units. The algorithm implements a temperature schedule to gradually cool the system, increasing the likelihood of finding the global minimum.

### Tacoma Bridge Model

The model investigated the relationship between torsional angle θ and vertical displacement Y over time, finding the resonant frequency of the bridge model to be between 0.13 and 0.16 Hz, which is at maximum a 35% difference from the literature value of 0.2 Hz.

## License

This project is licensed under the MIT License.

## Acknowledgments

- This project was created as part of a computational physics assignment in an undergraduate physics course at King's College London.
- Map and coordinate data sourced from open datasets
