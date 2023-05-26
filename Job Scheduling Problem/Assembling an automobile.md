The assembling of a car at an automobile assembly plant plant can be divided into various steps:
1. Construct the frame.
2. Install engine, power train components, gas tank.
3. Install brakes, wheels, tires.
4. Install dashboard, floor, seats.
5. Install electrical lines.
6. Install gas lines.
7. Install brake lines.
8. Attach body panels to frame.
9. Paint body

Some of these processes can be done at the same time, while others must wait until the preceding tasks are complete. Following table gives an overview of the order of the tasks and how long it takes to carry each one out:
| Task | Immediately Preceding Tasks | Time Needed to Perform Task |
| :-------: | :-------: | :----------------: |
|   1       |           |     7 hours        |
|   2       |   1       |     6 hours        |
|   3       |   1       |     3 hours        |
|   4       |   2       |     6 hours        |
|   5       |   2, 3    |     3 hours        |
|   6       |   4       |     1 hours        |
|   7       |   2, 3    |     1 hours        |
|   8       |   4, 5    |     2 hours        |
|   9       |   6,7,8   |     5 hours        |



Let $\mathbb{T}$ be the set of all tasks, and consider the partial order relation defined on $\mathbb{T}$ as follows: For all tasks $x$ and $y$ in $\mathbb{T}$,
$$x \preceq y \iff x = y \quad \vee \quad  x \enspace \text{precedes} \enspace y.$$

If the Hasse diagram of this relation is turned sideways, it has the appearance shown below:


What is the minimum time required to assemble a car? You can determine this by
working from left to right across the diagram, noting for each task (say, just above the box
representing that task) the minimum time needed to complete that task starting from the
beginning of the assembly process. For instance, you can put a 7 above the box for task 1
because task 1 requires 7 hours. Task 2 requires completion of task 1 (7 hours) plus 6 hours
for itself, so the minimum time required to complete task 2, starting at the beginning of
the assembly process, is 716 5 13 hours. So you can put a 13 above the box for task 2.
Similarly, you can put a 10 above the box for task 3 because 713 5 10. Now consider
what number you should write above the box for task 5. The minimum times to complete
tasks 2 and 3, starting from the beginning of the assembly process, are 13 and 10 hours
respectively. Since both tasks must be completed before task 5 can be started, the minimum time to complete task 5, starting from the beginning, is the time needed for task 5
itself (3 hours) plus the maximum of the times to complete tasks 2 and 3 (13 hours), and
this equals 3113 5 16 hours. Thus you should place the number 16 above the box for task
5. The same reasoning leads you to place a 14 above the box for task 7. Similarly, you can
place a 19 above the box for task 4, a 20 above the box for task 6, a 21 above the box for
task 8, and a 26 above the box for task 9, as shown below.
