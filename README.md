# PROJE 2 - Merge-Sort-Projesi
Patika ile merge sort projesi yapıldı.

## **[16,21,11,8,12,22]** -> Merge Sort
### Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
* [16,21,11]            [8,12,22]
* [16,21]    [11]       [8,12]  [22]
* [16][21][11]          [8][12][22] 

// Tüm elemanlar tek index olana kadar parçalama işlemi yaptık.Bundan sonraki aşama da ise küçükten büyüğe sıralamak için tekrar birleştirme yapılacak.

* [16,21][11]            [8,12][22]

// Burada ise soldaki değerler daha küçük olduğu için birbiri içinde kıyaslama yapılıp,sıralanacak.

* [11,16,21]            [8,12,22]
* [8,11,12,16,21,22]
### Big-O gösterimini yazınız.
* 2^x =logn
 x=logn
 O(nlogn)
