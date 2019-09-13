#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) In the example the running time depends on the size of input N. Its running time grows as input size increases.

    O(N)

b) The loop variables is increased exponentially by a constant amount.
    O (N log N)


c) The function is being called recursively n times before reaching base case so its running time grows as input size increases.
    O (N)

## Exercise II

1. We walk to the middle floor of all floors and throw egg there. 

2. If it doesn't get broken, it means it will not get broken from 0 floor to the len(floors) / 2 floor (middle floor).

2. If it is broken, then it will break after being dropped on every floor above middle point.

3. Depending if egg is broken or not we are going to the middle of the middle floor --> last floor OR 
   middle of the first floor --> middle floor. 
   And repeating the process. 


Time complexity will be O(log n) because the loop variables will be divided by a constant amount (two).


