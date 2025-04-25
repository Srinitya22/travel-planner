# Travel-planner
A Python project that aims to help travellers plan optimal travel routes between different locations using graph algorithms.This applicatioon will be able to calculate the shortest path between two locations,considering factors like distance,travel time and cost.
## Features
- Graph representation of locations using cities names as nodes and paths and the connecting roads or transportation routes as edges.
- Adds edges between nodes with attributes[distance,travel time,cost ,mode of transport].
- Dijkstra's algorithm for shortest path.
- Uses networkX and Matplotlib to visualize the graph.
- Users can input their budget in various currencies(USD,Euros,Rupees,Pounds,Yen)
## How to Use
 1. Run the code
 2. Choose your start and end locations
 3. Input your budget,currency and maximum travel time.
## Output 
- The best route
- Total cost (converted to your currency)
- Total travel time
- Warnings if the route exceeds your budget or time
- The suggested mode of transport
- A graph visualization will appear showing the route map.
