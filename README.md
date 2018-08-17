# Python-Examples
Examples of my code in Python

## Random Forest Implementation - decision_trees_submission.py

**As noted in the placeholder file, please contact me at cwlong@okstate.edu or linkedin.com/in/chad-long-3b1543100 to see this code**

decision_trees_submission.py creates a random forest from dynamically generated decision trees to classify data as a machine learning technique. The decision trees classify based on the highest Gini impurity gain for a given attribute of the features data. These decision trees are limited in size by a depth parameter that can be toggled for accuracy. The random forest specifies a number of trees to create and selects specific attribiutes to train with for each tree. The final classification of data results from the majority vote of the random forest.

To test the effectiveness of the random forest, A parameter vaue determines the number of k-folds created as testing and training data. Specifically in the code, 10 folds of 9 training parts and 1 testing part are generated to train the forest and test its effectiveness. This forest achieved an accuracy of 0.887 on the test data, while the same code on the Kaggle Challenge data resulted in an accuracy of 0.817.

Other code for confusion matrices, accuracy, precision, recall, and vectorization is also present.

The following is a breakdown of my portions of code noted by **CHAD's CODE** comments to differentiate from the provided framework:
**90-102, 122-161, 178-199, 216-240, 257-281, 300-326, 339-368, 408-546, 557-580, 598-661, 684-686, 695-735, 744-796, 817-819, 831-871, 885-937, 983-989, 1033-1045, 1092-1105**

## Spanning Tree Protocol - Switch.py

**As noted in the placeholder file, please contact me at cwlong@okstate.edu or linkedin.com/in/chad-long-3b1543100 to see this code**

Switch.py defines the messaging behavior for a simulated switch in a simulated network using the Mininet tool. Specifically, Switch.py correctly executes a simplified and distributed Spanning Tree Protocol (STP) to find a Spanning Tree that prevents forwarding loops within a layer 2 network topology.

Please read about Spanning Trees here: https://en.wikipedia.org/wiki/Spanning_tree. 
Please read about the Spanning Tree Protocol here: https://en.wikipedia.org/wiki/Spanning_Tree_Protocol.

**I specifically wrote the code for lines 42-52, 59-86, 94-280, and 297-320 marked by "CHAD'S CODE" comments**

In this distributed algorithm, each switch sends out initial messages and processes all incoming messages to find the shortest path. Each switch in the simulated system executes this specific code making for a broad algorithm. This STP algorithm ends when all messages have been processed with no further messages being sent out based on conditions. In terms of scale, this algorithm proved to be effective on simulated Mininet networks of hundreds of switches.
