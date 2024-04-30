# Metaheuristic Optimization for Traveling Salesman Problem

This repository contains Python code implementing metaheuristic optimization algorithms for solving the Traveling Salesman Problem (TSP).

## Overview

The Traveling Salesman Problem (TSP) is a classic optimization problem where the goal is to find the shortest possible route that visits each city exactly once and returns to the origin city. Metaheuristic optimization algorithms are a class of algorithms that efficiently explore large solution spaces to find near-optimal solutions for combinatorial optimization problems like the TSP.

### Genetic Algorithm (GA)

Genetic Algorithms (GAs) are evolutionary algorithms inspired by the process of natural selection and genetics. They are commonly used to find near-optimal solutions to optimization and search problems. The GA implemented in this repository simulates the process of natural selection and evolution to find near-optimal solutions for the TSP.

### Ant Colony Optimization (ACO)

Ant Colony Optimization (ACO) is a metaheuristic algorithm inspired by the foraging behavior of ants. It utilizes artificial ants to explore the solution space and deposit pheromones on the paths they traverse. The ACO algorithm implemented in this repository mimics the foraging behavior of ants to find near-optimal solutions for the TSP.

## Usage

To use the code:

1. Ensure you have Python installed on your system.
2. Clone this repository to your local machine.
3. Install the required dependencies listed in `requirements.txt`.
4. Explore the provided algorithms by running the respective scripts (`main_ga.py` for Genetic Algorithm and `main_aco.py` for Ant Colony Optimization).
5. Customize the algorithms or integrate them into your projects as needed.

## File Structure

The repository contains the following files:

- `GeneticAlgorithm.ipynb`: Python module containing the implementation of the Genetic Algorithm.
- `AntColony.ipynb`: Python module containing the implementation of the Ant Colony Optimization algorithm.
- `data.csv`: CSV file containing data about the cities (name, latitude, longitude).

## Dependencies

The code requires the following Python packages:

- `numpy`
- `matplotlib`
- `opencv-python`
- `scikit-image`

You can install these dependencies using pip:

```bash
pip install -r requirements.txt
