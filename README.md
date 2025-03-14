# Project2_Planning
# Path Planning using BFS

## Overview  
This project implements **Breadth-First Search (BFS)** to find the shortest path for a **point robot** (radius = 0, clearance = 2 mm) on a **180 mm × 50 mm** map with obstacles.

## Dependencies  
Install required libraries using:  
pip install numpy opencv-python matplotlib

## How to Run  
1. Run the script in Google Colab or locally using:  
python BFS_Manas_Desai.py

2. Enter **start and goal coordinates** in mm (origin at bottom-left).  

## Output  
- **Visualization**: Node exploration + optimal path.  
- **Output video**: `output.mp4`  
- **Terminal output**: Total explored nodes and the found path.

## Example Input  
Enter start node (x y): 10 10
Enter goal node (x y): 150 40

## Notes  
- BFS treats all moves equally, while Dijkstra finds the lowest-cost path.  
- Visualization starts **after** the path is found.  

## Author  
Project 02: Path Planning  
