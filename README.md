# Topological-Sorting-Application
I made this project as a way of practicing using different data structures in Java. Topological sorting is basically a linear ordering of vertices for Directed Acyclic Graphs. It is usually used in scheduling jobs and prerequisites of courses. In this application, nodes of the graph are represented by islands and edges are represented by one-way bridges. You are allowed to only move forward between directly reachable islands until you get stuck on an island where you can’t move any further; the goal is to find that island that has the maximum number of paths leading to it (and other islands that you have an equal probability to get stuck on) using Topological Sorting.
-The code doesn't require any special installments for it to run properly.
-The used graph must be acyclic, otherwise the program will not return the required results.
-You will be asked to enter 3 integers space separated in a single line
Then 2 integers space separated in each line for a number of times equal to the number of graph edges.
