Project: Scheduling with Graph Theory
Overview
This project focuses on implementing a scheduling system using Graph Theory. The system reads constraint tables from text files, constructs a directed acyclic graph (DAG), verifies its properties, and calculates key scheduling metrics.

Features
Graph Construction: Parses a constraint table and builds a directed graph.
Graph Validation: Ensures the graph has no cycles and no negative edges.
Scheduling Computations:
Computes ranks of tasks using topological sorting.
Determines earliest and latest start dates.
Calculates float times for task flexibility.
Identifies critical paths in the project schedule.
Interactive Testing: Supports testing multiple constraint tables without restarting the program.
Usage
Run the program.
Enter the filename of a constraint table (or type "exit" to quit).
View the generated graph and scheduling computations.
Repeat the process with different input files.
Requirements
Python 3.x
Libraries: networkx, numpy
Execution
bash
Copier
Modifier
python scheduling.py
This project helps analyze task dependencies and optimize project schedules efficiently.
