# PatikaDev
Veri Yapıları
Insertion Sort Ödevi

[22,27,16,2,18,6] -> Insertion Sort
1)Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
[22,27,16,2,18,6] 
[2,27,16,22,18,6] 
[2,6,16,22,18,27] 
[2,6,16,18,22,27]

2) Big-O gösterimini yazınız.
n + (n-1) + (n-2) + (n-3) +........+ 1

n(n+1)/2 => (n^2+n)/2 (wors case)
Big O Notation'ı O(n^2)'dir.

3) Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Average Case = O(n^2) Worst Case = O(n^2) Best Case = O(n)

4) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
18 sayısı ortada olduğu için Average case kapsamına girer.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
[7,3,5,8,2,9,4,15,6]

[2,3,5,8,7,9,4,15,6]

[2,3,4,8,7,9,5,15,6]

[2,3,4,5,7,9,8,15,6]

[2,3,4,5,6,9,8,15,7]

[2,3,4,5,6,7,8,15,9]

[2,3,4,5,6,7,8,9,15]
