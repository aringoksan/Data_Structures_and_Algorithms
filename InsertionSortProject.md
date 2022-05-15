[22,27,16,2,18,6] -> Insertion Sort
 
1. Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
	Listenin ilk elemanı olan 22 yi alıp, listenin elemanlarını tek tek ilerlenir ve kendisinden küçük bir elemanla karşılaşılması durumunda,küçük eleman listenin başına alınır.
	Yani 16 sayısı 22 sayısından küçük olduğu için 16 sayısı listenin başına alınır.
	Yeni liste şu şekildedir. [16,22,27,2,18,6] Listenin belirli bir kısmı sıralı durumda.
	Sıralı olmayan kısımdan devam edilir. 2 sayısı alınır ve listenin sıralı kısmında uygun konuma yerleştirilir.
	Yeni liste şu şekildedir. [2,16,22,27,18,6]
	Bu işlem tüm liste sıralı olana kadar devam eder ve sıralı liste elde edilir. [2,6,16,18,22,27]
2. Big-O gösterimini yazınız.
	average case: O(n^2)
	best case:    O(n)
	worst case:   O(n^2)
3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4. 18 ortada bulunduğu için average case kapsamındadır.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1) [3,7,5,8,2,9,4,15,6] 7 3 ile karşılaştırılır ve 3 küçük olduğu için sola alınır.
2) [3,5,7,8,2,9,4,15,6] 5 listenin sıralı kısmında ([3,7]) uygun konuma yerleştirilir.
3) [3,5,7,8,2,9,4,15,6] 8 listenin sıralı kısmında ([3,5,7)]uygun konuma yerleştirilir.
4) [2,3,5,7,8,9,4,15,6]	2 listenin sıralı kısmında ([3,5,7,8)]uygun konuma yerleştirilir.
