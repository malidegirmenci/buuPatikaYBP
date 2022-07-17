# Insertion Sort Projesi
[22,27,16,2,18,6] -> Insertion Sort

1. Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.
3. Time Complexity: 
 * Average case: Aradığımız sayının ortada olması,
 * Worst case: Aradığımız sayının sonda olması, 
 * Best case: Aradığımız sayının dizinin en başında olması.
4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
---
# Cevaplar
---
## 1. INSERTION SORT AŞAMALARI
Temel Durum: [22,27,16,2,18,6]
A1: [22|,27,16,2,18,6]
A2: [22,27|,16,2,18,6]
A3: [16,22,27|,2,18,6]
A4: [2,16,22,27|,18,6]
A5: [2,16,18,22,27|,6]
A6: [2,6,16,18,22,27]
---
## 2. Big O Notation Gösterimi
Worst Case  : o(n^2)
Avarage Case: o(n^2)
Best CAse   : o (n)
---