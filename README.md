# merge-sort-projesi
**[Patika.dev](www.patika.dev/) sitesindeki Veri Yapıları ve Algoritmalar dersleri sonu "Merge Sort Projesi"**  

  ///////////////////  SORULAR  ///////////////////

**Proje 2** 

**[16,21,11,8,12,22]** -> Merge Sort

1.  Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2.  Big-O gösterimini yazınız.

///////////////////  CEVAPLAR  ///////////////////

1. Adım: Liste elemanlarını ortadan ikiye böl.  
	[16,21,11] - [8,12,22]

2. Adım: Listeyi ikili gruplar halinde böl.  
	[16]-[21,11] - [8]-[12,22]

3. Adım: Listeyi teker eleman kalacak şekilde böl.  
	[16]-[21],[11] - [8]-[12],[22]

4. Adım: Listeyi ikişer eleman olacak şekilde birleştir. Birleştirirken sırala. Küçük rakam başta olsun.  
	[16]-[11,21] - [8]-[12,22]

5. Adım: İkili listeleri birleştir. Birleştirirken sırala. Küçük rakam başta olsun.  
	[11,16,21] - [8,12,22]

6. Adım: Var olan listeleri birleştir. Birleştirirken sırala. Küçük rakam başta olsun.  
	[8,11,12,16,21,22]

///////////////////////////////////////////  

Big-O gösterimi: O(nlogn)
