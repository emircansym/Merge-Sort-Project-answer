1. Adım: Diziyi Bölme
İlk olarak, diziyi ikiye bölüyoruz:

Sol kısım: [16, 21, 11]
Sağ kısım: [8, 12, 22]
2. Adım: Parçaları Küçük Alt Parçalara Bölme
Bu parçalarda işlem yapabilmek için yine ikiye bölmeye devam ediyoruz:

Sol kısımdan başlayarak: [16] ve [21, 11] olarak ayırıyoruz.
Sağ kısım ise: [8] ve [12, 22] olarak ayrılıyor.
3. Adım: En Küçük Parçalara Kadar Bölme
Artık her parçayı mümkün olan en küçük birimlerine indiriyoruz:

[21, 11] kendi içinde [21] ve [11] olarak ikiye ayrılıyor.
[12, 22] ise [12] ve [22] şeklinde ayrılıyor.
4. Adım: Parçaları Tekrar Birleştirerek Sıralama
Şimdi her küçük parçayı sıralı olarak birleştirmeye başlıyoruz:

[21] ve [11] birleşip sıralanıyor: [11, 21]
[12] ve [22] birleşip sıralanıyor: [12, 22]
5. Adım: Büyük Parçaları Birleştirerek Sıralama
Bu sırada, birleştirdiğimiz parçaları büyük birimlere çıkarıyoruz:

[16] ve [11, 21] birleştirilip sıralanıyor: [11, 16, 21]
[8] ve [12, 22] birleştirilip sıralanıyor: [8, 12, 22]
6. Adım: Son Birleştirme ve Tam Sıralı Hali
Artık elimizde iki ana parça kaldı ve bu parçaları birleştiriyoruz:

[11, 16, 21] ve [8, 12, 22] sıralanarak birleşiyor: [8, 11, 12, 16, 21, 22]
Sonuç: Dizinin sıralanmış hali [8, 11, 12, 16, 21, 22] olarak karşımıza çıkıyor.

Big-O Notasyonu
Bu sıralama türü (Merge Sort), her durumda aynı performansı gösterir ve genellikle oldukça verimlidir. İşlem sayısını ifade eden Big-O notasyonu ise O(nlogn) şeklindedir.