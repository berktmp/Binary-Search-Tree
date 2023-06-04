# Binary-Search-Tree
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] => Binary Search Tree

1. We take the first element, 7, as the root.

2. The second element, 5, becomes the left child of the root because it is smaller than the root.
3. The third element, 1, becomes the left child of 5 because it is smaller than 5.
4. The fourth element, 8, becomes the right child of the root because it is greater than the root.
5. The fifth element, 3, becomes the right child of 1 because it is greater than 1 but smaller than 5.
6. The sixth element, 6, becomes the right child of 5 because it is greater than 5 but smaller than 7.
7. The seventh element, 0, becomes the left child of 1 because it is smaller than 1.
8. The eighth element, 9, becomes the right child of 8 because it is greater than both the root and 8.
9. The ninth element, 4, becomes the right child of 3 because it is greater than 3 but smaller than 5.
10. The tenth element, 2, becomes the left child of 3 because it is greater than 1 but smaller than 3.~
```
           7  
          / \
         5   8
        / \   \
       1   6   9 
      / \   
     0   3  
        / \
       2   4  
```
