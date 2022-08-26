# PatikaVeriYapilariInsertionSortProjesi
www.patika.dev
Insertion Sort Projesi

A-)[22,27,16,2,18,6]

1.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Cevap:
1.adım: [22,27,16,2,18,6]
2.adım: [22,16,27,2,18,6]--->[16,22,27,2,18,6]
3.adım: [16,22,2,27,18,6]--->[16,2,22,27,18,6]--->[2,16,22,27,18,6]
4.adım: [2,16,22,18,27,6]--->[2,16,18,22,27,6]
5.adım: [2,16,18,22,6,27]--->[2,16,18,6,22,27]--->[2,16,6,18,22,27]--->[2,6,16,18,22,27]

2.Big-O gösterimini yazınız.
Cevap:
Big-O(n^2)

3.Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Cevap:
Worst Case:   O(n^2)
Average Case: O(n^2)
Best Case:    O(n)

4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
Cevap:
Average Case kapsamına girer.

B-)[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
Cevap:
1.adım: [3,7,5,8,2,9,4,15,6]
2.adım: [3,5,7,8,2,9,4,15,6]
3.adım: [3,5,7,2,8,9,4,15,6]--->[3,5,2,7,8,9,4,15,6]--->[3,2,5,7,8,9,4,15,6]--->[2,3,5,7,8,9,4,15,6]
4.adım: [2,3,5,7,8,4,9,15,6]--->[2,3,5,7,4,8,9,15,6]--->[2,3,5,4,7,8,9,15,6]--->[2,3,4,5,7,8,9,15,6]
