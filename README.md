# Path-finding-in-a-maze-using-A-star-algorithm
A project designed to implement the A* algorithm to preprocess it,  find the path in a maze image and display the path. The A* algorithm is an algorithm used in Artificial Intelligence for pathfinding and graph traversal. It efficiently finds the shortest path from a starting point to a goal in a weighted graph, utilizing a heuristic to guide the search and optimize the exploration process.
Code explanation:
1. Opening the image.
2. Converting the image to grayscale.
3. Applying a threshold to convert the grayscale image into a binary image.
4. Applying a median filter that removes small noise or artefacts from the image.
5. Using OpenCV to find contours in the thresholded image.
6. Isolating the region of interest (ROI) by finding and filling the largest contour in the thresholded image.
7. Resizing the ROI image and implementing a function to map image coordinates to grid coordinates.
8. Creating a simple interface for selecting the starting and goal coordinates on an image.
9. Marking the start and goal locations on the resized image.
10. The Python script uses the A* algorithm to find the shortest path through a maze represented as a 2D array. Steps involved:
    1. Image processing
    2. Labelling
    3. A* Algorithm
    4. Path Finding
11. Using Matplotlib to visualise the maze along with the found path.

The maze_path pdf file above, contains the step by step execution and further explanation of the code.
