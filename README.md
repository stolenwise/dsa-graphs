# dsa-graphs

# Graph Data Structure (with DFS and BFS)

This project implements an undirected graph using JavaScript classes, with support for common graph operations, including:

- Adding and removing vertices
- Adding and removing edges
- Depth-First Search (DFS)
- Breadth-First Search (BFS)

## Files

- `graph.js`: Contains the `Node` and `Graph` classes.
- `graph.test.js`: Contains unit tests for all graph methods using Jest.

## Features

### Graph Methods

- `addVertex(vertex)`  
  Adds a single `Node` instance to the graph.

- `addVertices(vertexArray)`  
  Adds multiple `Node` instances to the graph.

- `addEdge(v1, v2)`  
  Creates a bidirectional edge between two nodes.

- `removeEdge(v1, v2)`  
  Removes the bidirectional edge between two nodes.

- `removeVertex(vertex)`  
  Removes a node from the graph and all edges pointing to it.

- `depthFirstSearch(start)`  
  Returns an array of node values visited in depth-first order.

- `breadthFirstSearch(start)`  
  Returns an array of node values visited in breadth-first order.

## Running Tests

Make sure you have [Node.js](https://nodejs.org/) installed. Then install dependencies and run the tests:

```bash
npm install
npx jest
