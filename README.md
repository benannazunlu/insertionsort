Insertion Sort Projesi
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
1. Adım: [22,27,16,2,18,6] 
2. Adım: [22,27,16,2,18,6]
3. Adım: [22,16,27,2,18,6] -> [16,22,27,2,18,6] 
4. Adım: [16,22,2,27,18,6] -> [16,2,22,27,18,6] -> [2,16,22,27,18,6]
5. Adım: [2,16,22,18,27,6] -> [2,16,18,22,27,6]
6. Adım: [2,16,18,22,6,27] -> [2,16,18,6,22,27]
7. Adım: [2,16,6,18,22,27] -> [2,6,16,18,22,27]

Big-O gösterimini yazınız.
O(n^2)

Time Complexity:
i. Average case: Aradığımız sayının ortada olması = [n*(n-1)]/2: n^2
ii. Worst case: Aradığımız sayının sonda olması = n^2
iii. Best case: Aradığımız sayının dizinin en başında olması. =n

Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
Verilerin ortancası bu yüzden average case olur.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
1. Adım: 7 3 5 8 2 9 4 15 6
2. Adım: 3 7 5 8 2 9 4 15 6
3. Adım: 3 5 7 8 2 9 4 15 6
4. Adım: 3 4 7 8 2 9 4 15 6
