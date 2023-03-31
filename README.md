# algoritma

## Proje 1
- [22,27,16,2,18,6] -> Insertion Sort
Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

- Aşama 1
[2,27,16,22,18,6] ----> [2,6,16,22,18,27] ----> [2,6,16,18,22,27]

- Big-O gösterimi
 O(n^2)        
- Cevap
 Dizi sıralandıktan sonra 18 sayısı average case kapsamına girer

 ## Proje2
 -  [16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

## Aşama 1
-        [16,21,11] --- [8,12,22]   
- [16,21] - [11] ----- [8,12] - [22] 
- [16] [21] [11] --------[8] [12] [22]
- [16,21] [11] ----------- [8,12] [22]
- [11,16,21] -------------- [8,12,22]
- [8,11,12,16,21,22]

## Big-O gösterimi
- O(logn)

## Proje3
- [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

## Cevap
-                (5)
-           (4)          (6)
-         (3)-(7)      (2)-(8)
-       (2)    (9)    (1)
-                   (0)   
