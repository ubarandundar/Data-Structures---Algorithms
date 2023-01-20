# Selection Sort Project

**Soru: [22,27,16,2,18,6] -> Insertion Sort**

**Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.**

Cevap:

Akış: İkinci eleman birinci ile kendini karşılaştırır. Eğer ikinci birinciden küçük ise yer değiştirirler, aksi takdirde sabit kalır. Sonra üçüncü eleman; kendini ikinci eleman ile, sonra da birinci eleman ile karşılaştırır. Akış bu şekilde sonlanana kadar devam eder.

`[22,27|,16,2,18,6]`

`[16,22,27|,2,18,6]`

`[2,16,22,27|,18,6]`

`[2,16,18,22,27|,6]`

`[2,6,16,18,22,27]`

---

**Soru: Big-O gösterimini yazınız.**

Cevap: Big-O=(n^2)

---

**Soru: Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.**

Cevap: 18 sayısı ortalarda olduğu için "Average Case" kapsamına girer.

---

**Soru: [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.**

Cevap:

Akış: Dizideki en küçük sayıyı bulur ve en baştaki eleman ile yer değiştirerek en başa sabitler. En baştaki eleman en küçük ise sabit kalır ve ikinci elemana geçer. Sonra dizideki ikinci en küçük sayıyı bulur ve ikinci sıraya sabitler. Akış bu şekilde sonlanana kadar devam eder.

1.step: `[2|,3,5,8,7,9,4,15,6]`

2.step: `[2,3|,5,8,7,9,4,15,6]`

3.step: `[2,3,4|,8,7,9,5,15,6]`

4.step: `[2,3,4,5|,7,9,8,15,6]`
