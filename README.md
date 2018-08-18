# Python-Examples
Examples of my code in Python

## Random Forest Implementation

**As noted in the placeholder file, please contact me at cwlong@okstate.edu or linkedin.com/in/chad-long-3b1543100 to see this code**

This code creates a random forest from dynamically generated decision trees to classify data as a machine learning technique. The decision trees classify based on the highest Gini impurity gain for a given attribute of the features data. These decision trees are limited in size by a depth parameter that can be toggled for accuracy. The random forest specifies a number of trees to create and selects specific attribiutes to train with for each tree. The final classification of data results from the majority vote of the random forest.

To test the effectiveness of the random forest, a parameter vaue determines the number of k-folds created as testing and training data. Specifically in the code, 10 folds of 9 training parts and 1 testing part are generated to train the forest and test its effectiveness. This forest achieved an accuracy of 0.887 on the test data, while the same code on the Kaggle Challenge data resulted in an accuracy of 0.817.

Other code for confusion matrices, accuracy, precision, recall, and vectorization is also present.

## Spanning Tree Protocol

**As noted in the placeholder file, please contact me at cwlong@okstate.edu or linkedin.com/in/chad-long-3b1543100 to see this code**

This code defines the messaging behavior for a simulated switch in a simulated network using the Mininet tool. Specifically, the code correctly executes a simplified and distributed Spanning Tree Protocol (STP) to find a Spanning Tree that prevents forwarding loops within a layer 2 network topology.

Please read about Spanning Trees here: https://en.wikipedia.org/wiki/Spanning_tree. 
Please read about the Spanning Tree Protocol here: https://en.wikipedia.org/wiki/Spanning_Tree_Protocol.

In this distributed algorithm, each switch sends out initial messages and processes all incoming messages to find the shortest path. Each switch in the simulated system executes this specific code making for a broad algorithm. This STP algorithm ends when all messages have been processed with no further messages being sent out based on conditions. In terms of scale, this algorithm proved to be effective on simulated Mininet networks of hundreds of switches.

## Viterbi Algorithm

**As noted in the placeholder file, please contact me at cwlong@okstate.edu or linkedin.com/in/chad-long-3b1543100 to see this code**

This code defines a simple application of the Viterbi algorithm for determining the Morse code sequences for 5 characters. These Morse code characters have Hidden Markov Models (HMM) that define the dot and dash sequences that result in a character. The code defines all of the necessary prior, emission, and transition probabilities to make a HMM application possible.

Please read about Hidden Markov Models here: https://en.wikipedia.org/wiki/Hidden_Markov_model
Please read about the Viterbi algorithm here: https://en.wikipedia.org/wiki/Viterbi_algorithm

The code receives evidence that falls within the simplified bounds of the predefined map of probabilities. With this evidence, the Viterbi algorithm identifies all of the Morse code transitions in the Viterbi path after determining which states match the evidence with the highest probability. The last method in this code finally decodes all of the sequences while having to account for word spaces, letter transitions, and noise that muddles the Morse code sequence before decoding occurs.
