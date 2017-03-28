>Calculate the space time complexity of your solution to prior question.

**Time complexity**: O(n<sup>2</sup>), where `n` is the total number of elements in the given array.

This is because for each outer iteration from `0` to `n-1`, we iterate `n` times in the inner array.

**Space complexity**: O(n) i.e. `n` units of space each for `arr` and `common_hash`. And a single unit each for `i`, `j` etc. Thus, it is simplified to O(n).
   