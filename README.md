# Hasse Diagram and an Apllication of Partial Ordrer Relations
This repository contains a Python program to draw the Hasse Diagram of a partial order relation and a markdown file discussing a Job Scheduling Problem.

## Job Scheduling Problem
The markdown file `Assembling an Automobile.md` explains the problem of finding the minimum time required to assemble a car at an automobile assembly plant. It shows how to model the assembly process as a partially ordered set and how to construct a Hasse diagram to represent the order of the tasks and their durations. It also shows how to find the critical path and the optimal assembly sequence that minimizes the total assembly time.

## Hasse Diagram Python Program
The Python program `Hasse Diagram with python.py` uses the `networkx`, `matplotlib`, and `pydot` libraries to draw a Hasse diagram for a partial order relation. It takes as input ordered pairs of the relation and then checks if the relation is partial order relation. If the relation is partial order relation, then it draws the Hasse Diagram of the relation.

You can also find a jupyter notebook file `Hasse Diagram with python.ipynb` that contains the same code as the Python program.

### How to Run
To run the Python program or the jupyter notebook file, you need to have Python 3 and and the following modules installed:
- networkx
- matplotlib
- pydot
- graphviz

You can install them using `pip`:

`pip install networkx`

`pip install matplotlib`

`pip install pydot`

`pip install pydot`

You also need to have Graphviz software installed on your system. You can download it from [Graphviz](https://graphviz.org/download/ "Go to Graphviz Official Website")


Then, you can run the program from the command line as follows:

`python hasse_diagram.py`

Or you can open the jupyter notebook file in your preferred editor and run it from there.

The program will prompt you to enter all ordered pairs separated by spaces. For example:

`Enter all ordered pairs separated by spaces: (1,1) (1,2) (2,2) (2,3) (3,3)`

The program will check if the relation is partial order. If it is, Hasse diagram for the relation will be drawn on the screen. If the relation is not partial order, then the program will prompt the user again to enter the ordered pairs.
