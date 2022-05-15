Proje 2
[16,21,11,8,12,22] -> Merge Sort

1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
	Liste 2 ye bölünür
	[16,21,11] [8,12,22] ikiye bölme işlemi tekrarlanır
	[16] [21,11] [8] [12,22] 2 eleman kalmış listeler sıralı hale getirilir
	[16] [11,21] [8] [12,22] bütün listeler sıralı olduğu için listeler birleştirlir
	[11,16,21] [8,12,22] tekrar birleştirilme işlemi yapılır
	[8,11,12,16,21,22]
2.Big-O gösterimini yazınız.
	average case: O(nlog(n))
	best case:    O(nlog(n))
	worst case:   O(nlog(n))