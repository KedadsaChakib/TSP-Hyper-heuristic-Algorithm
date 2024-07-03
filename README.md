# Hyper-Heuristic Solutions for the Traveling Salesman Problem (TSP)

This repository presents two hyper-heuristic solutions tailored for solving the Traveling Salesman Problem (TSP): one based on Ant Colony Optimization (ACO) and another inspired by TS-ILS (Thompson Sampling Iterated Local Search).

## ACO-Based Solution

### Overview
Our ACO-based approach optimizes execution time and solution quality through strategic pheromone updates and heuristic selection. The high-level strategy adapts ACO specifically for TSP, while the low-level heuristics combine constructive methods for initial solution building and improvement methods for iterative refinement.

### Key Features
- **High-Level Strategy**: Customizes ACO for TSP, focusing on effective pheromone updates and heuristic selection.
- **Low-Level Heuristics**: Integrates constructive and improvement methods to enhance solution effectiveness across diverse problem instances.

## TS-ILS-Based Solution

### Overview
Drawing from TS-ILS, our second approach redistributes workload between high and low levels. The high-level strategy employs a 'Ruin and Recreate' method for diversification, while the low-level strategy intensifies through improvement heuristics like local search.

### Key Features
- **High-Level Strategy**: Implements 'Ruin and Recreate' for diversification in solution exploration.
- **Low-Level Strategy**: Focuses on intensification through local search, refining solutions iteratively.

## Conclusion
By combining ACO and TS-ILS concepts, this repository offers versatile solutions to the TSP, adaptable to various problem instances. Both approaches aim to balance exploration and exploitation strategies effectively, enhancing the overall quality of solutions for the Traveling Salesman Problem.

---

For detailed implementation and usage instructions, please refer to the respective directories for each hyper-heuristic solution.

**Scientific Article:** [Link to the scientific article](https://drive.google.com/file/d/1dCpFzAqxaD0FcdJBgiACNkJDYvn4bSdu/view?usp=sharing) 



