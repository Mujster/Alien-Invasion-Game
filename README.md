# Alien-Invasion-Game

## Graph Representation

- A graph structure to represent cities.
- Each node represents a city.
- Cities are connected by edges with distances predefined.
- Some nodes randomly assigned military bases.

## City Initialization

- Allocate civilians to each city at the initialization stage.

## Alien Spawning

- Random start node is chosen and a destination node (Alexandria).
- Implemented BFS algorithm to allocate alien population.
- Randomly assigns alien population quotas to nodes on the selected path.

## City Defense

- Utilize available resources to defend cities:
  - Military bases
  - Weapon stockpiles
  - Civilian populations for evacuation

## Resource Management

- Efficiently allocates limited resources to defend cities and counter the alien threat.

## Strategy Optimization

- Optimize city defense sequence based on:
  - Minimizing weapons used
  - Maximizing civilians saved
  - Considering distances and available resources

## Heuristic Function

- Designed a heuristic function considering multiple factors such as:
  - Military bases
  - Weapons
  - Civilians
  - Aliens
  - Distances
- Prioritize cities based on factors mentioned above to design an optimal city-to-city path.

## Priority Assignment

- Cities where aliens have already attacked take higher priority for defense.

## Source and Final Nodes

- A source node for troop deployment.
- The final node for the last battle, representing the stronghold of the aliens (Alexandria).

