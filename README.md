# proje1
[22, 27, 16, 2, 18, 6]

[ 22, 27 , 16, 2, 18, 6] .... 1

[ 16, 22, 27 , 2, 18, 6]

[ 2, 16, 22, 27 , 18, 6]

[ 2, 16, 18, 22, 27 , 6] .... n-1

[ 2, 6, 16, 18, 22, 27 ] .... n
Büyük O Notasyonu 
n!= n*(n+1)/2= (n^2+n)/2 => O(n^2)

tüm sayıların zaten sıralanmış olduğu durum, O(n)

ortalama durum: O(n^2)

en kötü durum: O(n^2)

18 için hangi dava?
Dizinin ortasında olduğu için 18 ortalama durum kapsamındadır.

İlk 4 Ekleme Sıralama adımları
[7,3,5,8,2,9,4,15,6]

[[ 3,7 ,5,8,2,9,4,15,6]

[ 3,5,7 ,8,2,9,4,15,6]

[ 3,5,7,8 ,2,9,4,15,6]

[ 3,5,7,2,8 ,9,4,15,6]

Seçim Sıralama Projesi
[ 22 ,27,16,2,18,6]

[2, 27 ,16,22,18,6] Bu durumda 2 en küçük olduğuna göre ikinci sayıdan kontrol etmeye başlayacağız.

[2,6, 16 ,22,18,27] Sırada bir değişiklik yok çünkü bir sonraki sayı zaten doğru yerde.

[2,6,16, 22 ,18,27]

[2,6,16,18, 22 ,27]

[2,6,16,18,22, 27 ]

Büyük O Notasyonu - en kötü durum
n, listenin büyüklüğünü göstersin,

1. adımda bütün değerler kontrol edilmelidir. (n)

ardışık her adımda çek miktarı 1 azaldı. (n-1,n-2,n-3.......1)

bu durum, toplam çek miktarının n olduğu anlamına gelir!

n!= n*(n-1)/2= (n^2-n)/2 n^2 burada baskın,

yani O(n^2)

Zaman komp.
en kötü, ortalama ve en iyi durum: O(n^2)

İlk 4 Seçim Sıralama adımları
[7,3,5,8,2,9,4,15,6]

[ 7 ,3,5,8,2,9,4,15,6]

[2, 3 ,5,8,7,9,4,15,6]

[2,3, 5 ,8,7,9,4,15,6]

[2,3,4, 8 ,7,9,5,15,6]
