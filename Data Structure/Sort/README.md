Primary objectives of this program
---
1. Sort an arbitrary input list in descending order
2. Implement the bubble sort algorithm.
3. Implement the merge sort algorithm with the selection sort algorithm as its subroutine.

Program Input and Output
---
1. A task selection integer
  a. if 0, perform bubble sort
  b. if 1, perform merge sort (+selection sort)
2. An arbitrary list of non-repeated integers, end with a character ‘s’.

Program Input and Output Example
---
Example of Successful Search
---
14 27 36 9 7 11 s, 1, 27

Output
---
7 11 9 36 27 14

Example of Search Failure
---
14 27 36 9 7 11 s, 1, 8

Output
---
-1



Example of Successful Insertion
---
14 27 36 9 7 11 s, 2, 20

Output
---
7 11 9 20 36 27 14

Example of Insertion Failure
---
14 27 36 9 7 11 s, 2, 36

Output
---
-1


Example of Successful Deletion
---
14 27 36 9 7 11 s, 3, 11

Output
---
7 9 36 27 14

Example of Deletion Failure
---
14 27 36 9 7 11 s, 3, 8

Output
---
-1
