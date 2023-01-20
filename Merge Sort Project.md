# Merge Sort Project

**Soru: [16,21,11,8,12,22] -> Merge Sort**

**Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.**

Cevap:

Akış: Merge sort her adımda array'i parçalayarak ayırıp tek eleman kalıncaya kadar böler. Böldükten sonra sıralı bir şekilde birleştirir.
Üç solda, üç sağda olmak üzere iki parçaya ayırarak başladık.

`[16,21,11,8,12,22]`

`[16,21,11] [8,12,22]`

`[16] [21,11] [8] [12,22]` => Birleşmeden önceki son durum

`[16] [11,21] [8] [12,22]`

`[11,16,21] [8,12,22]`

`[8,11,12,16,21,22]`

---

**Soru: Big-O gösterimini yazınız.**

Cevap:

2^x=n  |  x=log(n)   

n*log(n)=O(nlogn)