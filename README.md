# Path Finding Visualizer

This is a web-based application for visualizing different path finding algorithms built with React.
It provides an interactive platform for users to create grids, place obstacles and visualize how the algorithms work to find the shortest path between the start and end points.

## Features

Add obstacles to the grid

### Visualize the path finding algorithms:

- Dijkstra
- A\*
- Breadth First Search (BFS)
- Depth First Search (DFS)
- Clear the grid and start over

## Installation

- Clone the repository to your local machine
- Install dependencies with npm install
- Run the app with npm start

## Usage

- Click on the grid cells to create obstacles, start and end points.
- Select the algorithm from the dropdown menu.
- Click the "Visualize" button to see the algorithm in action.
- Click the "Clear" button to clear the grid and start over.

## Algorithms

### Dijkstra

Dijkstra's algorithm is a weighted graph search algorithm that finds the shortest path between a start node and all other nodes in a graph. It does not work well with negative weights.

### A\*

A\* algorithm is a heuristic search algorithm that finds the shortest path between a start node and a goal node. It uses a heuristic function to estimate the distance between the current node and the goal node.

### Breadth First Search (BFS)

Breadth First Search is an algorithm for traversing or searching a graph or tree data structure. It explores all the neighbor nodes at the present depth before moving on to the nodes at the next depth level.

### Depth First Search (DFS)

Depth First Search is an algorithm for traversing or searching a graph or tree data structure. It explores as far as possible along each branch before backtracking.

## File Structure

src folder contains all the source code.
components folder contains all the React components.
algorithms folder contains the implementation of the algorithms.
styles folder contains all the CSS stylesheets.
public folder contains the index.html file and other static files.
Future Development

## Future Development

Allow users to save and load grids
Add more algorithms
Improve the UI/UX
Credits
