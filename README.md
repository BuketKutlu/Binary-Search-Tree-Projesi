# Binary-Search-Tree-Projesi
Patika.dev - Veri Yapıları ve Algoritmalar - Binary Search Tree Projesi


Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

Cevap:

Dizinin en başındaki eleman root olarak seçilir. Bu dizideki root 7 olacaktır.

1. Adım: 5 elemanı, 7'den küçük olduğu için 7'nin soluna gelir.
2. Adım: 1 elemanı, 7'den küçük olduğu için 7'nin soluna gelir. Daha sonra 5 elemanından küçük olduğu için yeni bir bağ ile sol tarafa yerleştirilir.
3. Adım: 8 elemanı, 7'den büyük olduğu için 7'nin sağına geçer.
4. Adım: 3 elemanı, 7'den küçük olduğu için sola, 5 elemanından küçük olduğu için sola, 1'den ise büyük olduğu yeni bir bağ ile sağa gelir.
5. Adım: 6 elemanı, 7'den küçük olduğu sola, 5'den büyük olduğu için yeni bir bağ ile sağ tarafa geçer.
6. Adım: 0 elemanı, 7'den küçük olduğu için sola, sırasıyla 1'e kadar gelir. 1'den küçük olduğu için sol tarafa yerleştirilir.
7. Adım: 9 elemanı, 7'den büyük olduğu için sağa, 8'den büyük olduğu için sağına geçer.
8. Adım: 4 elemanı, 7'den küçük olduğu için sola gelerek 3 elemanının sağına gelir.
9. Adım: 2 elemanı, 7'den küçük olduğu için sola ve sırasıyla takip ederek 3 elemanının soluna yerleştirilir.

![cevabın görsel hali](BinarySearch.png)

[Patika.dev Adresim](https://app.patika.dev/buketktl)


www.patika.dev
