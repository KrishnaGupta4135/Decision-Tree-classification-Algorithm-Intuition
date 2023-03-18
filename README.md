# Decision-Tree-classification-Algorithm-Intuition


Decision Tree is the most powerful and popular tool for classification and prediction. A Decision tree is a flowchart-like tree structure, where each internal node denotes a test on an attribute, each branch represents an outcome of the test, and each leaf node (terminal node) holds a class label.

## Construction of Decision Tree: 
A tree can be “learned” by splitting the source set into subsets based on an attribute value test. This process is repeated on each derived subset in a recursive manner called recursive partitioning. The recursion is completed when the subset at a node all has the same value of the target variable, or when splitting no longer adds value to the predictions. The construction of a decision tree classifier does not require any domain knowledge or parameter setting, and therefore is appropriate for exploratory knowledge discovery. Decision trees can handle high-dimensional data. In general decision tree, classifier has good accuracy. Decision tree induction is a typical inductive approach to learn knowledge on classification.

## Gini Index
Gini Index or Gini impurity measures the degree or probability of a particular variable being wrongly classified when it is randomly chosen.

## But what is actually meant by ‘impurity’?

If all the elements belong to a single class, then it can be called pure. The degree of Gini Index varies between 0 and 1,

where, '0' denotes that all elements belong to a certain class or there exists only one class (pure), and '1' denotes that the elements are randomly distributed across various classes (impure).

A Gini Index of '0.5 'denotes equally distributed elements into some classes.



# Entropy and Information Gain

### Formula for Entropy

The formula for entropy, in order to find out the uncertainty or the high disorder, goes as follows:

E ( S ) = c ∑ i = 1 − p i ( l o g 2 p i )

where,p, denotes the probability of entropy and E(S) denotes the entropy.

### Information Gain formula

Information Gain formula = 1 – Entropy



### Formula of Gini Index

The formula of the Gini Index is as follows:

G i n i = 1 − n ∑ i=1 ( p i )^ 2

where, ‘pi’ is the probability of an object being classified to a particular class.

While building the decision tree, we would prefer to choose the attribute/feature with the least Gini Index as the root node.
Information Gain formula



