# CI2025_lab1
Multi-Dimensional Multi-Knapsack: ILS vs SA

## Iterated Local Search (ILS)
ILS is a metaheuristic that improves solutions through repeated local search with controlled perturbations to escape local optima. 
It gets stuck if not perturbed strongly enough, but it is fast and Simple to implement and tune.

Steps:

- Start with a greedy feasible solution.

- Apply local improvement (hill climbing).

- Perturb the solution (small random change).

- Improve again using local search.

- Keep the best solution found so far



## Simulated Annealing (SA)

A probabilistic algorithm inspired by the physical annealing process. Requires a good cooling schedule and may converge slowly ad needs repair to fix infeasible solutions.

Steps:

- Start from a (usually random) initial solution.

- Slightly mutate the solution.

- Accept:

Always if it's better.

Sometimes if it's worse, based on temperature.

- Gradually cool the system by reducing temperature.
