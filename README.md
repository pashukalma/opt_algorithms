### Optimization Algorithms (`opt_algorithms`)

A collection of Jupyter Notebooks exploring routing, search, geospatial analysis, and metaheuristic optimization algorithms.
- Traveling Salesperson Problem (TSP) formulations and heuristics 
- Facility location or allocation using NSGA (Non-dominated Sorting Genetic Algorithm) 
- Spatial data handling, coordinates, and mapping workflows 
- Shortest-path speedup techniques via Contraction Hierarchies 
- General network and vehicle routing problem modeling 
- Foundational graph and state-space search algorithms 
- Supply-demand optimization using Ant Colony Optimization (ACO) 

#### Overview
TSP.ipynb: Models and solves the Traveling Salesperson Problem, finding the shortest closed tour that visits a set of locations once before returning to the origin.

bikeshare_data_analysis.ipynb: Analyzes bikeshare trip and station data, focusing on usage patterns, station demand, and spatial/temporal trends.

facilities_solver_nsga.ipynb: Solves a multi-objective Facility Location Problem using NSGA (Non-dominated Sorting Genetic Algorithm) to balance competing goals such as cost and coverage.

geospatial_data.ipynb: Works with geospatial datasets, handling coordinate systems, distance calculations, spatial joins, or map visualizations.

routing_contract_hierarchy.ipynb: Implements Contraction Hierarchies, a graph preprocessing technique that adds shortcut edges to accelerate shortest-path queries on road networks.

routing_problem.ipynb: Models general network or vehicle routing problems, optimizing paths or fleet assignments across a graph.

search_algorithms.ipynb: Explores foundational graph and state-space search algorithms (such as BFS, DFS, Dijkstra's, or A*) for pathfinding.

supply_demand_with_aco.ipynb: Applies Ant Colony Optimization (ACO) to match or route supply to demand nodes using pheromone-based metaheuristic search.