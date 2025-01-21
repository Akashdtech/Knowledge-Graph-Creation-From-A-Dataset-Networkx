# Knowledge-Graph-Creation-From-A-Dataset-Networkx
This script creates and visualizes a bipartite knowledge graph to explore the relationships between movie titles and their genres using data from a CSV file (movies.csv). The script is implemented using Python with the pandas, networkx, and matplotlib libraries.

    Data Loading: The script loads movie data from a CSV file (movies.csv) into a pandas DataFrame.
    Extracting Nodes:
        Unique movie titles are extracted as one set of nodes.
        Unique genres are extracted as another set of nodes.
    Defining Edges:
        For each movie, edges are created between the movie title and its associated genres.
    Graph Creation:
        A bipartite graph is constructed using the networkx library.
        Nodes and edges are added to the graph to represent the relationships between movies and genres.
    Visualization (Optional):
        A visualization block (commented out) is included to display the graph using a random layout with customizable node and edge properties.

Usage:

    Ensure the input CSV (movies.csv) is in the correct format, with at least title and genres columns.
    Uncomment the visualization block to view the graph.

Example Output:

The graph structure connects each movie to its associated genres, providing a clear, visual representation of genre relationships across movies.
