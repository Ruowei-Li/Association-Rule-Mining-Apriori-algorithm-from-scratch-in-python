# Association Rule Mining : Apriori algorithm from scratch in python

This is an implementation of a Apriori algorithm (in python using Jupyter notebook).

It takes the following parameters:
* minsup - minimum support
* minconf - minimum confidence
* minlift - minimum lift
* the name of file of transactions (supermarket.csv -- whose format is comma separated value). Each line within the data file represents a transaction, where items are separated by commas. Imagine you are going to a grocery store, your transaction at the check-out counter would be one of the lines.


It will produce all association rules which can be mined from the transaction file which satisfy the minimum support, lift, and confidence requirements. The rules should be output sorted first by the number of items that they contain (in ascending order), then by the lift value, confidence, and support (all three in descending order).

Example:
```
A -> B 4, 0.9, 0.8
A, C -> B 3.8, 0.8, 0.7
A, D -> B 3.6, 0.8, 0.6
```
