# Network-Routing-Simulation-
This project simulates intelligent message routing across a network using Dijkstra’s algorithm. Each node maintains a dynamic routing table optimized for quick lookups, enabling efficient path selection for message delivery.
ntelligent Network Routing Simulation Using Splay Trees and Dijkstra's Algorithm
This project presents a simulation of intelligent message routing across a dynamic network topology. Developed as a Data Science term project at FAST-NU, Spring 2025, the system models a distributed network using a graph-based approach, where each node maintains a local routing table and message queue.

The key objective was to explore efficient, adaptive routing techniques for minimizing latency and resource usage in real-world networking scenarios. To achieve this, the project integrates:
Dijkstra's Algorithm for computing shortest paths between nodes
Custom message-passing simulation, complete with a user-defined message generation, timestamping, and routing behavior

*Key Features:*
Graph Representation of Network: The network is represented as a weighted graph, with nodes and directed/undirected edges carrying weights that simulate latency or bandwidth cost.
Dynamic Routing Tables: Each node maintains its own routing table, updated using Dijkstra’s algorithm when network conditions change or messages are received.
Efficient Lookup with Splay Trees: To improve performance during frequent routing table updates and lookups, splay trees are used to ensure amortized logarithmic time complexity.
Message Handling Simulation: The project processes a predefined set of messages that traverse the network. Each message is routed from source to destination via the shortest path determined by the current state of the network.
Traceability & Logging: Each step of the message routing process is logged, offering detailed insights into routing decisions, path selections, and splay tree operations.

*Technologies Used:*
Python for simulation logic and data structures
NetworkX or custom graph logic (depending on implementation specifics)
Matplotlib or console-based logs for tracing message flow

*Learning Outcomes:*
Understanding of how classical algorithms (like Dijkstra's) are applied in real-time systems
Practical use of self-adjusting data structures (splay trees) in optimizing routing logic
Enhanced debugging, logging, and testing skills for complex data pipelines
Experience in simulating real-world network behaviors and interpreting routing dynamics
