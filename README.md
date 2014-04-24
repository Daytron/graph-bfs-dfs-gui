

## Graph Node Search using BFS and DFS algorithms ##


### Description ###
A Python GUI application to search for a node in a linked graph using breadth or depth first search with simpleguitk module. It allows the user to plot the graph on a canvas and link them together graphically. This was initially built using simplegui module for codeskulptor ([http://www.codeskulptor.org/](http://www.codeskulptor.org/)), but later moved to simpleguitk module.

![Screenshot](https://raw.githubusercontent.com/Daytron/graph-bfs-dfs-gui/master/screenshots/screenshot1.png)

### Requirements: ###
- Python 2.7
- simpleguitk - [https://pypi.python.org/pypi/SimpleGUITk/1.1.3](https://pypi.python.org/pypi/SimpleGUITk/1.1.3 "Link")

### Usage ###
    python BFS_DFS_GUI.py
Console is used to monitor results while you interact in the frame window. Click on the canvas, to start plotting the graph nodes on the canvas. If you're satisfied with the nodes, press *Lock in the nodes* button to lock-in the nodes. You can now link the nodes together by clicking it, one node at a time. If you're happy with your graph, then press *Lock in the graph* button to finalise your graph. Otherwise, press *Reset edge drawing* button to reset all edges/links/connections between the nodes.
<br><br>
Enter a start and goal node, either by submitting a number or letter (any case is acceptable) that corresponds to the nodes of the graph made. You can then initiate the node search using breadth first search by pressing the *find BFS* button or depth first search by pressing *find DFS* button.

###Contribution###
Feel free to fork the project and apply changes on your own repo but please no pull request.

### License and Copyright ###
This package is Copyright (c) Ryan Gilera 2014 and is licensed under the MIT license. See [license](https://github.com/Daytron/graph-bfs-dfs-gui/blob/master/LICENSE) for more details.