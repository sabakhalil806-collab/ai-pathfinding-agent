# AI Pathfinding Agent: Search Algorithms and Q-Learning

An experimental AI pathfinding project that compares classical search algorithms with reinforcement learning in maze environments.

The project implements Dijkstra's algorithm, A* search with different heuristics, and Q-learning. It also includes maze generation, path validation, performance benchmarking, and visualizations.

## Project Overview

Finding an efficient path through a maze is a classic problem in artificial intelligence. Different algorithms approach this problem in different ways: some search systematically for the shortest path, while reinforcement learning learns a policy through interaction with the environment.

This project explores these approaches and evaluates their behavior across different maze configurations.

## Algorithms Implemented

### 1. Dijkstra's Algorithm
- Finds shortest paths using accumulated path cost.
- Serves as a baseline for comparing search performance.

### 2. A* Search
- Uses the cost accumulated so far and a heuristic estimate of the remaining distance.
- Supports Manhattan and Euclidean distance heuristics.
- Includes weighted A* for exploring the effect of heuristic weighting.

### 3. Q-Learning
- Implements a reinforcement learning approach to maze navigation.
- Learns action values through interaction with the environment.
- Evaluates learning behavior across multiple mazes and random seeds.

## Features

- Random maze generation with configurable obstacle probabilities.
- Perfect-maze generation.
- Path correctness tests.
- Benchmarking across different maze sizes and configurations.
- Comparisons of search effort, runtime, and path optimality.
- Visualizations of algorithm behavior.
- Q-learning experiments and learned-policy visualizations.

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/sabakhalil806-collab/ai-pathfinding-agent.git
cd ai-pathfinding-agent
```



### 2. Install the dependencies

```bash
pip install -r requirements.txt
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open `path-finding.ipynb` and execute the cells in order.

Alternatively, upload the notebook to Google Colab or Kaggle and run it in a notebook environment that supports the required Python libraries.

**Note:** Full benchmark and reinforcement learning experiments may take time to execute, depending on the environment and configuration.

## Evaluation

The notebook includes experiments for comparing algorithms using metrics such as:

- Runtime
- Number of expanded nodes
- Maximum frontier size
- Path optimality
- Q-learning reward and learning behavior

The notebook generates the experimental results and visualizations. Refer to its output cells for the actual measurements from a particular run.

## Project Structure

```text
ai-pathfinding-agent/
├── path-finding.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

## Learning Outcomes

This project explores:

- Classical AI search techniques.
- Heuristic functions and informed search.
- Graph traversal and shortest-path problems.
- Reinforcement learning fundamentals.
- Experimental evaluation of AI algorithms.
- Visualization and analysis of algorithm performance.

## Future Improvements

- Implement additional search algorithms such as Greedy Best-First Search.
- Add interactive maze creation.
- Compare algorithms on larger and more complex environments.
- Improve Q-learning exploration and reward strategies.
- Develop a small interactive web application for demonstrating pathfinding.

## Author

**Saba Khalil**

GitHub: https://github.com/sabakhalil806-collab

---

This project is intended for educational and experimental purposes.
