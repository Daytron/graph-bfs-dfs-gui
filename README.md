

## Graph BFS/DFS GUI ##


### Description ###
A Python GUI application to find a node in a linked graph using breadth and depth first search with simpleguitk module. It allows the user to plot the graph first and link them together graphically. This was initially built using simplegui module for codeskulptor ([http://www.codeskulptor.org/](http://www.codeskulptor.org/)), later moved to simpleguitk module.

![Screenshot](https://raw.githubusercontent.com/Daytron/graph-bfs-dfs-gui/master/screenshots/screenshot1.png)

### Requirements: ###
- Python 2.7
- simpleguitk - [https://pypi.python.org/pypi/SimpleGUITk/1.1.3](https://pypi.python.org/pypi/SimpleGUITk/1.1.3 "Link")

### Usage ###
    python BFS_DFS_GUI.py
Console is use to monitor results while you interact in the frame window. Click on the canvas to start plotting the nodes of the graph. Once satisfied with the nodes, press *Lock in the nodes* button to lock in the nodes. Then you can now link the nodes together by clicking it. If you're happy with the graph then press *Lock in the graph* button to finalise your graph. Otherwise, press *Reset edge drawing* button to reset all edges/links/connections between nodes.
<br><br>
Enter the start and goal node either by submitting a number or letter (any case is acceptable) that corresponds to the nodes of the graph made. Then you can search the goal using breadth first search by pressing the *find BFS* button and depth first search by pressing *find DFS* button.

###Contribution###
Feel free to fork the project and apply changes on your own repo but please don't send me any pull request.

### License and Copyright ###
This package is Copyright (c) Ryan Gilera 2014 and is licensed under the MIT license. See [license](https://github.com/Daytron/graph-bfs-dfs-gui/blob/master/LICENSE) for more details.