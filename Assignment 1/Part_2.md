# Assignment 1, Part 2 : Decision Tree Learning

Produce a program which implements the Decision Tree Learning method. Limited data or lack of pruning meant the produced tree was only as accurate as the Baseline Classifier.

Using K-Fold Cross Validation with the above program lowered the average performance, likely overfitting the AI to the data.

Pruning a Decision Tree is more accurate as it reduces the features the tree has to consider, preventing overfitting.

The impurity measure for the above program is probability based which, if more class types were added, would become more and more complex. A different method could be used if:
- It could return 0 if all the instances belong to one class
- It's max result is returned when the number of instances for each class are equal (not bias)
- It produces a continuous and smooth curve between pure and impure
