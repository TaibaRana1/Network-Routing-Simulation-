Intelligent Network Routing Simulation (C++)
This project is a C++ simulation of intelligent message routing across a dynamically defined network, . It demonstrates how advanced algorithms and data structures can be used to optimize communication in networked systems, mimicking real-world routing behaviors.

*Overview:*
The simulation models a network of nodes, each with its own routing table and ability to send and receive messages. To determine the most efficient communication paths, the project uses Dijkstra’s algorithm for shortest path calculations. 
This combination of graph algorithms and adaptive data structures results in a system capable of smart, fast, and flexible routing decisions in response to simulated message traffic.

*Key Features*
Graph-Based Network Modeling
The network is implemented as a weighted graph, where nodes represent routers and edges simulate communication channels with varying costs (such as latency or bandwidth).

*Dijkstra’s Algorithm for Shortest Path:*
Efficient path computation between nodes is handled using Dijkstra’s algorithm, ensuring messages follow the least-cost route.

*Splay Trees for Routing Table Optimization*
Routing tables are implemented  to prioritize frequently accessed paths, improving lookup performance over time through self-adjustment.

*Message Routing Simulation*
Messages are generated with defined sources and destinations, passed through the network, and tracked for delivery time, hop count, and routing decisions.

*Data Logging and Analysis*
Each step of the routing process is logged to allow analysis of algorithm performance, tree adjustments, and overall message flow efficiency.

*Technologies Used*
Language: C++ 

Data Structures: Graphs, Priority Queues

Algorithms: Dijkstra’s Algorithm


Learning Objectives:
Applying theoretical graph algorithms in practical network simulations




Potential Extensions:
Implementing real-time network updates (dynamic topology)

Adding congestion modeling or bandwidth constraints

Introducing alternative routing algorithms (e.g., Bellman-Ford)

Visualizing network behavior with a graphical interface
