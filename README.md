# CI2024_lab2

To solve the TSP problem, I used two algorithms. The first one is simulated annealing with an initial temperature of 10,000, a cooling rate of 0.995, and a minimum temperature of 1. This algorithm provides a globally optimal solution only for the first set of cities (Vanuatu). The second algorithm I used combines a "2-opt" function for local optimization of the set, a scramble mutation to perform gene mutation, and a nearest neighbor to generate the initial population. This hybrid solution consistently provides a globally optimal solution, although it takes a significant amount of time for the China set. The following are the test results.

VANUATU

Simulated Annealing
Distance of best tour: 1345.5449564733112

Hybrid Implementation
Distance of best tour: 1345.5449564733112

ITALY

Simulated Annealing
Distance of best tour: 7642.632926389612

Hybrid Implementation
Distance of best tour: 4172.762613916409

RUSSIA
Simulated Annealing
Distance of best tour: 150696.8353151428

Hybrid Implementation
Distance of best tour: 32772.614876239066

US
Simulated Annealing
Distance of best tour: 335942.6514039016

Hybrid Implementation
Distance of best tour: 38365.85862833056
