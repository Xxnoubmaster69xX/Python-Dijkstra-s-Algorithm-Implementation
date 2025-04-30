# Interactive Dijkstra Algorithm Visualizer

This project provides a web-based interface to visualize Dijkstra's shortest path algorithm on an undirected, weighted graph. It features a Python Flask backend serving a REST API and an HTML/JavaScript frontend using the `vis.js` library for real-time graph rendering and interaction.

## Features

*   **Real-time Graph Visualization:** Displays nodes and weighted edges using `vis.js`.
*   **Dijkstra's Algorithm:** Calculates the shortest path between two selected nodes.
*   **Interactive Graph Manipulation:**
    *   Add new nodes (with optional JSON/text data).
    *   Add new edges with specific weights.
    *   Generate random graphs based on a specified number of nodes.
    *   Clear the entire graph.
*   **Path Highlighting:** Visually highlights the nodes and edges belonging to the shortest path found.
*   **Node Data Display:** Shows the data associated with the destination node of the calculated path.
*   **Simple Backend API:** Built with Flask (Python).

## Technology Stack

*   **Backend:** Python, Flask
*   **Frontend:** HTML, CSS, JavaScript, vis.js (vis-network)
*   **Core Algorithm:** Dijkstra (Python `heapq`)

## How to Run

1.  **Clone the repository:**
    ```bash
    git clone <your-repository-url>
    cd <repository-directory>
    ```
2.  **Install dependencies:**
    ```bash
    pip install Flask
    ```
    *(Note: `heapq` and `json` are part of Python's standard library)*
3.  **Run the Flask application:**
    ```bash
    python app.py
    ```
4.  **Open your web browser** and navigate to `http://127.0.0.1:5000` (or the address shown in the terminal).
