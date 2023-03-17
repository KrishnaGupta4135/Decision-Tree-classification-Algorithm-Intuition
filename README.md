# Decision-Tree-classification-Algorithm-Intuition

# Gini Index

Gini Index or Gini impurity measures the degree or probability of a particular variable being wrongly classified when it is randomly chosen.





---


 ### But what is actually meant by ‘impurity’?
---
If all the elements belong to a single class, then it can be called pure. The degree of Gini Index varies between 0 and 1,

where,
'0' denotes that all elements belong to a certain class or there exists only one class (pure), and
'1' denotes that the elements are randomly distributed across various classes (impure).

A Gini Index of '0.5 'denotes equally distributed elements into some classes.

---

##Formula for Entropy

The formula for entropy, in order to find out the uncertainty or the high disorder, goes as follows:

E
(
S
)
=
c
∑
i
=
1
−
p
i
l
o
g
2
p
i

where,p, denotes the probability of entropy and E(S) denotes the entropy.

---

##Formula of Gini Index
The formula of the Gini Index is as follows:

G
i
n
i
=
1
−
n
∑
i
=
1
 
(
p
i
)
2
where,
‘pi’ is the probability of an object being classified to a particular class.

While building the decision tree, we would prefer to choose the attribute/feature with the least Gini Index as the root node.
