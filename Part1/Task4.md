##### Let me write a pseudo-code that is self explanatory

```
let numbers := array of 50 numbers
let sum := 0
let count_of_positives := 0

for each element x in numbers:
  
  sum := sum + x
  
  if x > 0:
    count_of_positives := count_of_positives + 1
  endif

endfor

print sum
print count_of_positives
```