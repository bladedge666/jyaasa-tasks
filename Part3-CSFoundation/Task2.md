>Write an algorithm or pseudo-code to find common elements in an array

Here is the simplest algorithm I came up with (naive approach), using brute force:

```
arr := [arr of elements]
common_hash := {empty_hash}
n = length(arr)
for i := 0 to n - 1:
  comm_index := [empty_arr]
  
  for j := 0 to n - 1:
    if arr[i] equals arr[j]:
      comm_index.append(i)
    endif
    common_hash[i] = comm_index
  endfor

endfor

```

To retrieve a `value` (position of occurence) for `key`, we can do something like `common_hash[1]` which gives out the indices for occurences of the same element 1.

In this approach, I use a hashmap to store keys and values corresponding to the `element` and the `indices` where it reoccurs. For example, for an array that looks like `[1,2,3,4,1]`, `common_hash` would look like `{1: [0, 4]}`

This can be optimized as well by changing the second loop as: `for j := i to n - 1:`