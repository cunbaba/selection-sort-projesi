# SELECTION SORT PROJESİ

## Insertion Sort
1. [22,27,16,2,18,6] elimizdeki elemanların seçimli sıralaması.
Dizindeki en küçük rakamı buluyoruz. Burada en küçük rakam 2. En baştaki rakam ile yer değiştiriyoruz. Sıralama;
2. [2,27,16,22,18,6]
Şimdi ikinci en küçük rakamı buluyoruz. O da 6. İkinci rakam ile yer değiştiriyoruz. Yani 27 ile. Sıralama;
3. [2,6,16,22,18,27]
Üçüncü en küçük elemanı üçüncü sırada olduğu için olduğu gibi bırakıyoruz.
Dördüncü küçük elemanı dördüncü sıradaki elemanla yer değiştiriyoruz. Yani 22 ile 18. Sıralama;
4. [2,6,16,18,22,27]
Son yaptığımız işlem ile elemanlarımız sıralanmış oldu.

## Big-O Gösterimi
n elemanlı dizimizde her işlemden sonra eleman sayısı 1 eksileceğinden yukarıdaki sıralama;<br>
n+(n-1)+(n-2)+(n-3)+1 şeklinde olur.<br>
Big-O Notation formülü de n*(n+1)/2 olur. Burada dominant olanı aldığımızdan;<br>
Big-O Notation O(n^2) olur.

## 18 Sayısının Time Complexity'si hangi case kapsamına girer?
18 sayısı sıralama neticesinde ortada yer aldığından Time Complexity;<br>
Average Case kapsamına girer.

## [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a Göre İlk 4 adımı
1. adım: En küçük eleman olan 2 ile en baştaki 7 yer değiştirir.
[2,3,5,8,7,9,4,15,6]
2. adım: İkinci en küçük eleman olan 3 olduğu için yer değiştirme işlemine gerek kalmıyor.
[2,3,5,8,7,9,4,15,6]
3. adım: Üçüncü en küçük rakam olan 4 ile Üçüncü sıradaki 5 yer değiştirir.
[2,3,4,8,7,9,5,15,6]
4. adım: Dördüncü en küçük rakam olan 5 ile dördüncü rakam olan 8 yer değiştirir.
[2,3,4,5,7,9,8,15,6]

https://patika.dev

