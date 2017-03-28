a) (i>=1) and (i<=5)

Ans: For this expression we see that in the first comparison, `i` is greater than or equal to 1. This means that it is not bounded to the right (increasing side). It goes like this: 1, 2, 3, 4, 5, 6, 7, and so on... (considering that `i` is an `integer`)
However, the second rule restricts this since we are using an `and` operator. The second rule when evaluated independently can yield values like ..., -2, -1, 0, 1, 2, 3, 4, 5.

When the results are combined by the and operator, it yields the values present in both sets. i.e. `[1,2,3,4,5]`
So, The expression is true when `i` has values:  are `1 2 3 4 5`

b) (j>=3) or (j<=7)

Ans: Here, `or` operator is used so either or both rules can be `true` to yield a `true`. That means the expression as a whole is true as long as `j>=3` or `j<=7` or both. Considering this, we see that for `j` to be >= 3, it can take the following sample values: 3, 4, 5, 6, 7, 8, 9, 10, ... so on. (considering `j` as an integer)
Clearly, there are no bounds on this expression. So, The expression is true when `j` has values:   `possible -ve most value, ... -100, ..., -2, -1, 0, 1, 2, ..., possible +ve most value`