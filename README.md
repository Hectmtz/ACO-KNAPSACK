
## Problem introduction
The aim of this project was to solve the basic binary knapsack optimization task. The idea behind it was to use one of swarm intelligence algorithms, namely the ant colony optimization (ACO) in its basic form (AS – ant system).
The discrete knapsack is a well-known optimization problem. Its name was derived from the problem of maximization of items’ choice so that their total value is the highest with respect to capacity constraints.

## Problem solution
The ACO algorithm is one of the swarm intelligence algorithms. They rely on cooperation of independent agents that research and alter the solution space. This cooperation, under conditions brought on by the algorithm, leads to finding the optimal solution by emergence.
In the ACO algorithm a colony of artificial ants is spawned. Each ant creates its own solution in several steps. The probability of specific object’s selection is given by its value, remaining knapsack capacity and a variable called pheromone which is deposited on objects that form single ant’s solution. By introducing an evaporation system which in every iteration lessens the amount of pheromone, the final optimal solution is formed.

