# Shortest-path-using-OSM
"Find the shortest path on OpenStreetMap using A*, BFS, and Floyd-Warshall algorithms. Visualize routes on maps with Python and OSMnx." 
This project provides Python code for finding the shortest path on OpenStreetMap (OSM) maps using three different algorithms: A* (A Star), Breadth-First Search (BFS), and Floyd-Warshall. The code leverages the following libraries: OSMnx for working with OSM data, NetworkX for graph operations, and Plotly for map visualization.

Key Features:

Map Data Retrieval: The code fetches map data from OpenStreetMap by specifying a bounding box, including north, south, east, and west coordinates. The map data is obtained for the specified region and network type (e.g., 'drive').

Map Visualization: It includes a visualization of the obtained map graph, showing road networks within the specified bounding box.

Graph Representation: The map data is represented as a graph, with nodes and edges. Information about the nodes, edges, and edge attributes (e.g., length) is extracted from the OSM data.

Shortest Path Calculation: The code calculates the shortest path between two specified points (origin and destination) on the map using the A* algorithm. It also allows for custom heuristic functions.

Path Visualization: The resulting shortest path is plotted on the map, with the origin and destination points highlighted in different colors. The path is displayed using blue lines.

Performance Measurement: The runtime of the A* algorithm is measured and displayed, providing insight into the efficiency of the shortest path calculation.

Additional Algorithms: While the code primarily focuses on A* algorithm implementation, it mentions the possibility of implementing BFS and Floyd-Warshall algorithms, providing opportunities for future enhancements.

This GitHub project serves as a valuable resource for developers and researchers interested in working with OSM data and implementing different path-finding algorithms for map-based applications. It offers a clear demonstration of A* algorithm usage and the potential for expanding path-finding capabilities.
