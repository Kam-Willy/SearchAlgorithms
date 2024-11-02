Maze-Solving Algorithms in Python

A Python project implementing and visualizing several classic maze-solving algorithms. This project includes BFS, DFS, Greedy Best-First Search (GBFS), Greedy Depth-First Search (GDFS), A*, 
Dijkstra's, and Johnson's algorithms. Each algorithm is evaluated for performance and efficiency, with a visual comparison of their paths on randomly generated mazes.

Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Algorithms Implemented](#algorithms-implemented)
- [Installation](#installation)
- [Usage](#usage)
- [Example Output](#example-output)
- [License](#license)

Project Overview

This project showcases various search algorithms to solve randomly generated mazes. Each algorithm's progress is visualized, allowing you to see how different approaches find paths in unique ways.
The algorithms are evaluated on both accuracy and time taken, providing insights into their strengths and weaknesses.

Features

- **Maze Generation:** Randomly generates mazes with adjustable size.
- **Algorithm Visualization:** Visualizes each algorithm’s solution path in the maze.
- **Performance Comparison:** Measures and compares the performance of each algorithm.
- **Progress Tracking:** Shows algorithm progress using `tqdm` for time evaluation.

Algorithms Implemented

The following algorithms are implemented from scratch:
- **Depth-First Search (DFS)**
- **Breadth-First Search (BFS)**
- **Greedy Best-First Search (GBFS)**
- **Greedy Depth-First Search (GDFS)**
- **A\* Search**
- **Dijkstra's Algorithm**
- **Johnson's Algorithm**

## Installation

To run this project, clone the repository and install the necessary dependencies.

```bash
# Clone the repository
git clone https://github.com/yourusername/maze-solving-algorithms.git
cd maze-solving-algorithms

# Install dependencies
pip install -r requirements.txt
```

## Usage

To run the simulation, simply execute the `main.py` file. You can adjust parameters such as maze size and the number of simulations.

```bash
python main.py
```

## Example Output

The project generates visualizations of each algorithm’s path through the maze and plots of their performance:

- **Path Visualization**: Shows each algorithm’s solution path on a sample maze.
- **Performance Comparison**: Bar chart comparing average time taken by each algorithm.

Example image:

![Example Path Visualization](example_image.png)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

--- 

Add any further customization or details specific to your project, such as acknowledgments or links to related resources!
