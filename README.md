# Python-Examples
Examples of my code in Python

## Spanning Tree Protocol - Switch.py

**As noted in the placeholder file, please contact me at cwlong@okstate.edu or linkedin.com/in/chad-long-3b1543100 to see this code**

Switch.py defines the messaging behavior for a simulated switch in a simulated network using the Mininet tool. Specifically, Switch.py correctly executes a simplified and distributed Spanning Tree Protocol (STP) to find a Spanning Tree that prevents forwarding loops within a layer 2 network topology.

Please read about Spanning Trees here: https://en.wikipedia.org/wiki/Spanning_tree. 
Please read about the Spanning Tree Protocol here: https://en.wikipedia.org/wiki/Spanning_Tree_Protocol.

**I specifically wrote the code for lines 42-52, 59-86, 94-280, and 297-320 marked by "CHAD'S CODE" comments**

In this distributed algorithm, each switch sends out initial messages and processes all incoming messages to find the shortest path. Each switch in the simulated system executes this specific code making for a broad algorithm. This STP algorithm ends when all messages have been processed with no further messages being sent out based on conditions. In terms of scale, this algorithm proved to be effective on simulated Mininet networks of hundreds of switches.
