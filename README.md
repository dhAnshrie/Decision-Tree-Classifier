# Introduction to Decision Tree algorithm
A Decision Tree algorithm is one of the most popular machine learning algorithms. It uses a tree like structure and their possible combinations to solve a particular problem. It belongs to the class of supervised learning algorithms where it can be used for both classification and regression purposes.

A decision tree is a structure that includes a root node, branches, and leaf nodes. Each internal node denotes a test on an attribute, each branch denotes the outcome of a test, and each leaf node holds a class label. The topmost node in the tree is the root node.

We make some assumptions while implementing the Decision-Tree algorithm. These are listed below:-

At the beginning, the whole training set is considered as the root.
Feature values need to be categorical. If the values are continuous then they are discretized prior to building the model.
Records are distributed recursively on the basis of attribute values.
Order to placing attributes as root or internal node of the tree is done by using some statistical approach.

## Decision Tree algorithm terminology 
In a Decision Tree algorithm, there is a tree like structure in which each internal node represents a test on an attribute, each branch represents the outcome of the test, and each leaf node represents a class label. The paths from the root node to leaf node represent classification rules.

We can see that there is some terminology involved in Decision Tree algorithm. The terms involved in Decision Tree algorithm are as follows:-

### Root Node
It represents the entire population or sample. This further gets divided into two or more homogeneous sets.
### Splitting
It is a process of dividing a node into two or more sub-nodes.
### Decision Node
When a sub-node splits into further sub-nodes, then it is called a decision node.
### Leaf/Terminal Node
Nodes that do not split are called Leaf or Terminal nodes.
### Pruning
When we remove sub-nodes of a decision node, this process is called pruning. It is the opposite process of splitting.
### Branch/Sub-Tree
A sub-section of an entire tree is called a branch or sub-tree.
### Parent and Child Node
A node, which is divided into sub-nodes is called the parent node of sub-nodes where sub-nodes are the children of a parent node.
