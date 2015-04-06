This code implements Prim's minimum spanning tree algorithm for graphs. It reports the overall cost of a minimum spanning tree (which may be negative) and, optionally, the structure of the MST as well as the execution time. This implementation features heaps and sets (i.e., hash tables) in order to speed up min-cost searches and edge-vertex lookups. 
The input file should describe an undirected graph with integer edge costs and have the following format:
[number_of_nodes] [number_of_edges]
[one_node_of_edge_1] [other_node_of_edge_1] [edge_1_cost]
[one_node_of_edge_2] [other_node_of_edge_2] [edge_2_cost]
...
For example, the third line of the file is "2 3 -8874", indicating that there is an edge connecting vertex #2 and vertex #3 that has cost -8874. 
