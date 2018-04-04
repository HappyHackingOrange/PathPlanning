# PathPlanning
MATLAB implementation of pathfinding algorithms for UGVs



Instruction:

1. Include those folders in path:
- Astar
- rvctools  (contains D* algorithm)
2. Make terrain_generation current directory in MATLAB
3. Run terrain_generation_and_d_star.m.  It will go through a number of iterations until it generates a reasonably good map. It might take some time.  Keep those windows open for the last script file.
4. Type command A_Star1. It’ll run A_Star1.m from the path and generates other obstacle map that plans a path using A* search algorithm.  You’ll see a small blue circle move across the map.  Wait for it to finish so that it’ll create a variable that contains coordinates of the A* path.
5.  Run path_plotting_and_stat_info.m.  It will plot D* and A* paths on the 3d terrain map and contour map at same time, and print summary of results.  The red line is D* path, and the blue line is A* path.
