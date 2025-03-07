# Project2_Planning
# Path Planning using Dijkstra & BFS

## Overview  
This project implements **Dijkstra’s Algorithm** and **Breadth-First Search (BFS)** to find the shortest path for a **point robot** (radius = 0, clearance = 2 mm) on a **180 mm × 50 mm** map with obstacles.

## Dependencies  
Install required libraries using:  
pip install numpy opencv-python matplotlib

yaml
Copy
Edit

## How to Run  
1. Run the script in Google Colab or locally using:  
python path_planning.py

markdown
Copy
Edit
2. Enter **start and goal coordinates** in mm (origin at bottom-left).  
3. Choose algorithm:  
   - `1` for Dijkstra  
   - `2` for BFS  

## Output  
- **Visualization**: Node exploration + optimal path.  
- **Output video**: `output.mp4`  
- **Terminal output**: Total explored nodes & path cost.

## Example Input  
Enter start node (x y): 10 10
Enter goal node (x y): 150 40
Choose Algorithm (1-Dijkstra, 2-BFS): 1

pgsql
Copy
Edit

## Notes  
- BFS treats all moves equally, while Dijkstra finds the lowest-cost path.  
- Visualization starts **after** the path is found.  

## Author  
Project 02: Path Planning  
