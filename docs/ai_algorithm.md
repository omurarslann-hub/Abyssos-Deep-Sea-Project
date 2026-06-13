# AI Otonom Keşif Algoritması (Core-A)

## Karar Mekanizması
Cihaz, "Keşif" ve "Enerji Koruma" modları arasında dinamik olarak geçiş yapar.

## Algoritma Mantığı
- *Anomali Tespiti:* Sensörlerden gelen veriler, makine öğrenmesi modelleriyle "standart okyanus tabanı" verisinden ayrıştırılır. Eğer standart dışı (yeni bir canlı, jeolojik yapı, batık) bir sinyal alınırsa, sistem "Yüksek Öncelikli Kayıt" moduna geçer.
- *Enerji Yönetimi:* Batarya seviyesi %20'nin altına düşerse, cihaz "pasif sürüklenme" moduna geçer ve sadece en düşük enerji harcayan sensörleri açık tutar.
- *Navigasyon:* Cihaz, çevredeki manyetik alan dalgalanmalarını ve akustik yankıları kullanarak kendi konumunu (SLAM) oluşturur.

## Hedef
İnsan müdahalesi olmadan 6 ay boyunca, kendi kendine yeten bir keşif süreci.
