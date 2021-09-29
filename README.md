# Tugas DFS dan BFS
![tree](https://user-images.githubusercontent.com/86350332/135272198-8451d0a4-a689-488f-80fd-5957faf72d89.png)

DFS
Lines 2-11: The illustrated graph is represented using an adjacency list - an easy way to do it in Python is to use a dictionary data structure. Each vertex has a list of its adjacent nodes stored.

Line 11: visited is a set that is used to keep track of visited nodes.

Line 21: The dfs function is called and is passed the visited set, the graph in the form of a dictionary, and A, which is the starting node.

Lines 13-18: dfs follows the algorithm described above: It first checks if the current node is unvisited - if yes, it is appended in the visited set. Then for each neighbor of the current node, the dfs function is invoked again. The base case is invoked when all the nodes are visited. The function then returns.
