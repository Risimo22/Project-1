Project 1  - Insertion Sort
[22,27,16,2,18,6] -> Insertion Sort

Stages:

1-Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2-Big-O gösterimini yazınız.
3-Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4-Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
5-[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

Solves:
1-

22-27,16,2,18,6

22,27-16,2,18,6

16,22,27-2,18,6

2,16,22,27-18,6

2,16,18,22,27-6

2,6,16,18,22,27

2-
Avarage case: O(nn)=O(n^2) 

Best case: O(n) 

Worst Case: O(nn)=O(n^2)

3-
Average case: Aranılan sayının ortada olması
Worst case: Aranılan sayının sonda olması
Best case: Aranılan sayının en başta olması

4-
Dizinin sıralı hali: 2,6,16,18,22,27
18 orta değerlerden bir tanesi olduğu için average case kapsamına girer.

5-

7-3,5,8,2,9,4,15,6

3,7-5,8,2,9,4,15,6

3,5,7-8,2,9,4,15,6

3,5,7,8-2,9,4,15,6
