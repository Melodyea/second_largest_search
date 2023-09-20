# second_largest_search

Given as input an unsorted array of n distinct numbers, where n is the power of 2.

Identify the second-largest number in the array using the fastest algorithm.

Step 1: find the largest number through pariwise comparison

```bash
a  b  c  d  e  f  g  h
\  /  \  /  \  /  \  /
 a     d     e     g
  \   /       \   /
    a           e
     \         /
          e
```

Step 2: find the largest number in the list of numbers that has been compared with the largest number.
(if e is the largest number, the second largest number must be in a, or g, or f
