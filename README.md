# Graph-theory
Notes on Graph theory

**Introduction to Graph Theory**

**Slide 1: Title Slide**
- Welcome to the Presentation on Graph Theory

**Slide 2: What is Graph Theory?**
- Graph Theory is a branch of mathematics that deals with the study of graphs.
- A graph is a mathematical representation of a set of objects (vertices/nodes) connected by links (edges/arcs).
- Widely applicable in various fields such as computer science, social networks, transportation systems, and more.

**Slide 3: Basic Definitions**
- Vertex/Node: Representing the elements in a graph.
- Edge/Arc: Connecting the vertices, representing relationships between elements.
- Undirected Graph: Edges have no direction.
- Directed Graph (Digraph): Edges have a direction.
- Weighted Graph: Assigning values (weights) to edges, representing costs or distances.

**Slide 4: Types of Graphs**
1. Undirected Graph:
   - Each edge (u, v) is represented as (u <-> v).
   - No direction between connected nodes.
   - Example: Friendship networks.

2. Directed Graph (Digraph):
   - Each edge (u, v) is represented as (u -> v).
   - Arrows indicate the direction of relationships.
   - Example: Internet web pages with hyperlinks.

3. Weighted Graph:
   - Each edge (u, v) has an associated weight (w).
   - Represents costs, distances, or any other value.
   - Example: Road networks with different travel times.

**Slide 5: Applications of Graph Theory**
1. Social Networks:
   - Analyzing connections and patterns in friend networks.
   - Identifying influential individuals.

2. Computer Networks:
   - Analyzing data flow and communication between devices.
   - Finding the shortest path for data transmission.

3. Transportation Systems:
   - Analyzing routes and connections between cities.
   - Optimizing travel paths and costs.

4. Game Theory:
   - Analyzing strategies and decision-making processes.

5. Bioinformatics:
   - Analyzing molecular structures and interactions.

**Slide 6: Representing Graphs**
1. Adjacency Matrix:
   - A two-dimensional array indicating connections between vertices.
   - Suitable for small graphs.

2. Adjacency List:
   - A collection of linked lists representing the edges of each vertex.
   - Efficient for sparse graphs.

**Slide 7: Graph Traversal**
1. Depth-First Search (DFS):
   - Explore as far as possible along each branch before backtracking.
   - Uses a stack or recursion.
   - Used for topological sorting, finding connected components.

2. Breadth-First Search (BFS):
   - Explore all the neighbors at the present depth before moving to the next level.
   - Uses a queue.
   - Used for shortest path algorithms.

**Slide 8: Shortest Path Algorithms**
1. Dijkstra's Algorithm:
   - Finds the shortest path from a single source vertex to all other vertices.
   - Requires non-negative edge weights.

2. Bellman-Ford Algorithm:
   - Finds the shortest path from a single source vertex to all other vertices.
   - Can handle negative edge weights but detects negative cycles.

**Slide 9: Eulerian and Hamiltonian Graphs**
1. Eulerian Graph:
   - A graph that contains an Eulerian cycle (a cycle that visits every edge exactly once).
   - Eulerian cycles have even degrees for all vertices.

2. Hamiltonian Graph:
   - A graph that contains a Hamiltonian cycle (a cycle that visits every vertex exactly once).

**Slide 10: Conclusion**
- Graph theory is a powerful mathematical tool with wide applications in various fields.
- Understanding graphs and their properties helps solve real-world problems efficiently.
- Embrace the beauty and complexity of graph theory in your academic and professional pursuits.

**Slide 11: Q&A**
- Thank you for your attention! Now, I'm happy to answer any questions you may have.
