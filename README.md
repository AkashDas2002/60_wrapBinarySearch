# 60_wrapBinarySearch

## Recall inverse functions and logarithms

What is meant by y = log<sub>2</sub>x? What does its graph look like?

The mathematical equation y = log<sub>2</sub>x is equivalent to the equation x = 2<sup>y</sup>. In other words, y is the unique number such that when 2 is raised to that power, the resulting number of x. Logarithms is the inverse of exponentiation.


![Image of Graph](https://www.algebra.com/cgi-bin/plot-formula.mpl?expression=+graph%28+500%2C+500%2C+-10%2C+10%2C+-10%2C+10%2C+log%282%2C%28x%29%29%29+)

## Description of recursive solution

### Statement of Problem

Given an Integer *a* and an ordered list of Integers, determine the index where *a* appears in the list or if it doesn't appear at all.

### Statement of the recursive abstraction

Given an Integer *a* and an ordered list of Integers of length at least two, the recursive abstraction can determine the index where *a* appears in an ordered list of Integers of length half of the original list.

### Parts of the solution

1. Boolean expression determining whether to use base case or recursive case
```
if (low >= high)
```
2. Base Case
```
return -1;
```
3. Recursive Cases
- leftover
- recursive abstraction
- combiner
```
Yo
```


