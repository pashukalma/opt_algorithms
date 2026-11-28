### RL Algorithms (`opt_algorithms`)

(RL) Simulate and train a centralized Reinforcement Learning (RL) policy for autonomous mobile network coordination using the mobile-env and stable-baselines3 libraries.
- RL_autonomous_mobile.ipynb: Workflow using mobile-env to optimize base station (BS) and user equipment (UE) connections for Quality of Experience (QoE), contrasting a centralized Stable-Baselines3 PPO agent against a multi-agent Ray RLlib setup.

(RL) Transitions from stateless decision-making under uncertainty (Multi-Armed Bandits) to sequential decision-making in stateful environments (Advantage Actor-Critic on CartPole-v1).
- RL_concepts.ipynb: Multi-Armed Bandits (MAB) & Exploration-Exploitation, and  Advantage Actor-Critic (A2C) Algorithm on CartPole-v1. 

### LDemand Allocation
Implement and analyze bio-inspired and heuristic optimization strategies for the Drone Delivery Optimization Problem. 
- location_allocation_problem.ipynb
- drone_delivery_solver.ipynb

### Optimization Algorithms (`opt_algorithms`)

Exploring routing, search, geospatial analysis, and metaheuristic optimization algorithms.
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