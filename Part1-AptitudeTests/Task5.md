##### Calculating the number of comparisons to make when finding out the smallest number among:

a) 3 numbers

Ans: 2 comparisons

b) 6 numbers

Ans: 5 comparisons

c) n numbers

Ans: n-1 comparisons (n>=1) 

Explanation:

If n = 1, we don't need to compare. i.e 0 comparisons <br>
If n = 2, we need to compare the two numbers only once i.e 1 comparison <br>
For greater values of n, we can create a variable `smallest` and update it on each comparision. We can easily see that the pattern leads to n-1 comparisons.