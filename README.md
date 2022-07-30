## Proje 2 - Merge Sort

[16,21,11,8,12,22]

Dizinimizi ikiye bölüyoruz:
[16.21,11]  [8,12,22]

Elimizdeki dizinleri tekrar ikiye bölüyoruz:
[16,21]  [11]  [8,12]  [22]

Tek eleman kalana kadar kalan dizinleri de bölüyoruz:
[16]  [21]  [11]  [8]  [12]  [22]


Bölme işlemi bittikten sonra sıralama yaparak ikili olarak birleştiriyoruz:
[16,21]  [11]  [8,12]  [22]

[11,16,21] [8,12,22]

[8,11,12,16,21,22]

# Big-O Gösterimi
Fonksiyonumuz sürekli kendini çağıran recursive bir işlemdir. Her çağırmada kendini ikiye bölerek işle yapar. Big-O gösterimi O(n*(logn))'dir. Elimizdeki dizine bakarsak değerimiz O(6*(log6)) olacaktır.
