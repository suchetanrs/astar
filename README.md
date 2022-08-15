# A* path planning algorithm

# Video Demonstration
![](https://github.com/suchetanrs/astar/blob/master/README_files/animate.gif)
__This is a gif showing examples of some paths.__
__The green block is the start coordinate and the red block is the end coordinate__

# Working of the algorithm
A* is an extension of __Dijkstra's algorithm.__ It works breadth-first search. This means that it is Dijkstra's algorithm but the search is in the direction of the end co-ordinate most of the time. <br/>
This helps speeding up the search and is particularly useful when the paths are huge and have many alternatives.

# How to use the code
1. Clone this repository into your working directory
2. Run ```AstarPlot.py``` using the command ```python AstarPlot.py```
3. Enter your start-coordinates and end-coordinates. The code will shut down if the coordinates are an obstacle.
4. Your matplotlib figure with the planned path will be shown.
5. You can make your own obstacle grid by modifying the function ```make_obstacles()``` in ```draw_graph.py```