# 60_wrapBinarySearch

### 1. What does a logarithm mean?

Given a logarithm of Y = log (base 2) X:

The above logarithm means that Y is some number such that 2 raised to said number gives you X.

### 2. How does its graph look like?

The graph on a Cartesian plane can be visualized in the following way:

0. Take any parabola with the vertex at the origin.
1. Rotate it 90 degrees clockwise.
2. Remove the portion under the x-axis.

### Recursive solution

0. The problem: Given an ordered ArrayList, find the location of a given value.
1. Recursive abstraction: If I am expected to return the occurrence of a value in an ArrayList, the recursive abstraction will return the occurrence of the value by looking at the half of the ArrayList that has the value in it.
2. The 6 parts:
  0. Define the problem: Stated above.
  1. Binary decision: Whether the given part of the ArrayList only have one element.
  2. Solution to Base case: There is only one element. Either the element we seek is here or it is not.
  3. Solution to Recursive case: depends on the below things.
  4. Recursive abstraction: Stated above.
  5. Leftover processing:
