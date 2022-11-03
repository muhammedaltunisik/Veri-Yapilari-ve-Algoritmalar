# Binary Search Tree Projesi
-----

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

------

## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

* Kök 7 olarak belirlenmiştir.
* Ağaç 7 ile başlayacak küçükler sol tarafa büyükler sağ tarafa yerleştirilecektir.

```
                7
```
```
                7
               /
              5
```
```
                7
               /
              5
             /
            1
```
```
                7
               / \
              5   8
             /
            1
             \
              3
```
```
                7
               / \
              5   8
             / \   \
            1   6   9
           / \
          0   3
```
```
                7
               / \
              5   8
             / \   \
            1   6   9
           / \
          0   3
               \
                4
```
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

[Patika.dev](https://www.patika.dev/tr) 