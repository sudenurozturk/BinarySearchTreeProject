# BinarySearchTreeProject
## Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.
```
Öncelikle 7 root kabul edilir.
*    7
*      7           5, 7'den küçük olduğu için soluna yerleştirilir.
     /
    5

*      7           1, 7 ve 5'ten küçük olduğu için ikisinin de soluna yerleştirilir.
     /
    5
   /
  1

*      7           8, 7'den büyük olduğu için sağına eklenir.
     / \
    5   8
   /
  1

*      7
     / \
    5   8
   / \
  1   3

*      7
     / \
    5   8
   / \ 
  1   6
     /
    3

*      7
     / \
    5   8
   / \ 
  1   6
 /   /
0   3

*      7
     / \
    5   8
   / \   \
  1   6   9
 /   /
0   3

*      7
     / \
    5   8
   / \   \
  1   6   9
 /   /
0   3
   /
  4

*     7
    / \
   5   8
  / \   \
 1   6   9
/   /
0   3
   / \
  2   4




```

