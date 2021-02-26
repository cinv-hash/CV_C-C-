*The program's purpose is to construct a doubly linked list and store it, through an input of a sorted sequence of integers.
*The program then proceeds to do binary search to return the position of the key, or either delete an exisiting key or insert the key into the list.

Program Input and Output
---
(1) A task selection integer
-if 0, perform binary search and output position of the key or -1 if the key is not found.
-if 1, perform key deletion or insertion (automatically decide), and output the updated sequence.
(2) A search key
(3) The input sequence of integers, ended with a non-integer character – we suggest using ‘s’.

Program Input and Output Example
---
Input for binary search
---
0 
46
9 14 23 37 46 58 61 79 S
---
Output
---
4


Input for deletion
---
1
11
1 2 4 7 8 9 11 15 s
Output
---
1 2 4 7 8 9 15 
