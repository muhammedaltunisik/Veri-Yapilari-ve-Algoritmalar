# Insertion Sort Projesi
-----

[22,27,16,2,18,6] -> Insertion Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.
3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

## 1.Adım: Verilerin insertion sort türüne göre aşamalari
---
* Dizinin adimlari
```
1. [22,27,16,2,18,6]
2. [16,22,27,2,18,6]
3. [2,16,22,27,18,6]
4. [2,16,18,22,27,6]
5. [2,6,16,18,22,27]
```

## 2.Adım: Big-O gösterimi
----
O(n^2)

## 3.Adım: Time Complexity
------
Worst Case:
```
[27,22,18,16,6,2]
```
Best Case:
```
[2,6,16,18,22,27]
```
Average Case:
```
[18,6,2,16,22,27]
```

## 4.Adım: 18 sayisinin girdiği kapsam
* 18 sayısı dizinin ortadaki elemanı olduğu için avarege case durumuna girer.
-----------

## [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
```
1. [3,7,5,8,2,9,4,15,6]
2. [3,5,7,8,2,9,4,15,6]
3. [3,5,7,8,2,9,4,15,6]
4. [2,3,5,7,8,9,4,15,6]
```

[Patika.dev](https://www.patika.dev/tr) 