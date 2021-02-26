Primary objectives of this program
---
1. Implement a binary search tree and four operators: search, insertion, deletion and enumeration.
2. Implement a stack class to assist the implementation of enumeration.

Program Input and Output
---
1. An arbitrary sequence of non-repeated integer keys, ended with ‘s’. These keys will be used to construct the initial tree.
2. An integer indicating which operation to perform on the current tree.
  a. 1 indicates searching for a key.
  b. 2 indicates inserting a key.
  c. 3 indicates deleting a key.
3. A key, x, associated with the operator
  a. if the task is search, then x can be arbitrary and won’t be processed inside the program.
  b. if the task is insertion, then x is the key to insert.
  c. if the task is deletion, then x is the key to delete.

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

