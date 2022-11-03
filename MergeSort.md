# Merge Sort Projesi
-----

[16,21,11,8,12,22] -> Merge Sort

1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.

------
## 1.Adım: Yukarıdaki dizinin merge sort türüne göre aşamalarını yazınız.


| Adimlar | Bölme ve Birleştirme |
| :--- | :---: | 
| Adim 1 | [16,21,11] - [8,12,22] | 
| Adim 2 | [16] [21,11] - [8] [12,22] |
| Adim 3 | [16] [11,21] - [8] [12,22] |
| Adim 4 | [16] [11] [21] [8] [12] [22] |
| Adim 5 | [11,16] [21]   [8,12] [22] |
| Adim 6 | [11,16,21] - [8,12,22] |
| Adim 7 | [8,11,12,16,21,22] |
------

## 2.Adım: Big-O gösterimini yazınız.

* *O(nlogn)*

[Patika.dev](https://www.patika.dev/tr) 