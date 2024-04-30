# Ant Colony Optimization for Traveling Salesman Problem

This repository contains Python code implementing an Ant Colony Optimization (ACO) algorithm for solving the Traveling Salesman Problem (TSP).

## Overview

The Traveling Salesman Problem (TSP) is a classic optimization problem where the goal is to find the shortest possible route that visits each city exactly once and returns to the origin city. Ant Colony Optimization (ACO) is a metaheuristic algorithm inspired by the foraging behavior of ants that can be used to solve combinatorial optimization problems like the TSP.

This code implements an ACO algorithm to find near-optimal solutions for the TSP by simulating the foraging behavior of ants. It includes classes for representing cities and ants, as well as functions for initializing pheromone levels, generating ant colonies, updating pheromones, and running the algorithm.

## Usage

To use the code:

1. Ensure you have Python installed on your system.
2. Clone this repository to your local machine.
3. Install the required dependencies listed in `requirements.txt`.
4. Run the `main.py` script to execute the ACO algorithm and find the optimal tour for the given set of cities.

## File Structure

The repository contains the following files:

- `main.py`: Main script to run the ACO algorithm.
- `ant_colony.py`: Python module containing the implementation of the ACO algorithm.
- `city.py`: Python module defining the `City` class to represent cities.
- `ant.py`: Python module defining the `Ant` class to represent ants.
- `data.csv`: CSV file containing data about the cities (name, latitude, longitude).
- `requirements.txt`: Text file listing the required Python packages and their versions.

## Dependencies

The code requires the following Python packages:

- `numpy`: Library for numerical computing.
- `matplotlib`: Library for creating visualizations and plots.
- `seaborn`: Data visualization library based on Matplotlib, providing a high-level interface for drawing attractive statistical graphics.
- `opencv-python`: OpenCV library for computer vision tasks.
- `scikit-image`: Image processing library.

You can install these dependencies using pip:

```bash
pip install -r requirements.txt
