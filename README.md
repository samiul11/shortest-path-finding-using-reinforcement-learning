# shortest-path-finding-using-reinforcement-learning
Path Finding is used to find the shortest path between two points in Gridworld.
It ensures that planning is done in less time and in optimized way to finish the task.

### Conditions:


1. 20x20 grid, making 100 squares
2. Hard Obstacles marked as pink
3. Soft obstacles marked as purple
3. start and end points are generated random

The squares are identified by the coordinate (x,y) where x is the column and y is the row to which the square belongs. Each square
can be empty or have an Obstacle or have an Object.
The position of the Obstacles can be changed using config.

###Algorithms
The program uses Q learning and A* search for optimization 
###Output
Program gives an output generated by OpenCV library. The output is a window of the grid and simulation of the path taken. 

###Dependencies

[Use pip to install.](https://pypi.python.org/pypi/pip)

1.  Install OpenCV for Python

	[`For Windows`](http://docs.opencv.org/3.1.0/d5/de5/tutorial_py_setup_in_windows.html)

	[`For Ubuntu`](http://www.pyimagesearch.com/2015/06/22/install-opencv-3-0-and-python-2-7-on-ubuntu/)
2. Install numpy 

	Open command prompt and type in:
	```pip install numpy```
