# Eğitimler sayfasında Grid Görünümde Arama Çubuğunun Eğitimleri Filtrelememesi Sorunu
<!-- standardized-defect-report -->

| Alan | Değer |
| --- | --- |
| Hata Kimliği | DEF-MS-003 |
| Durum | Raporlandı |
| Tür | Fonksiyonel |
| Önem Derecesi | Kaydedilmedi |
| Öncelik | Kaydedilmedi |
| Tekrarlanabilirlik | Kaydedilmedi |
| Platform | Web |
| Kanıt | Raporda yer alıyor |

[Ana sayfaya dön](../../README.md) · [English version](../../English-Reports/mindset-web-defects/training-search-does-not-filter-grid-view.md)

## Ön Koşullar
-

## Aşama
- Eğitimler Sayfası

## Senaryo
1. https://www.mindset.com.tr/ linkine girilir.
2. Navigasyon Bar'daki Eğitimler seçeneğine tıklanır
3. Kullanıcının Eğitimler sayfasında olduğu doğrulanır
4. Eğitim listelemenin Grid Görünümde olduğu doğrulanır
5. Eğitim Arama Çubuğuna "iş analizi" yazılır.
## Ekran Görüntüleri
![](images/eğitimler-grid-gorunum-arama-cubugu-tepkisizlik.gif)

## Beklenen Sonuç
- Eğitim Arama Çubuğuna girilen metinin içinde geçen kelimeleri Grid görünümde arama sonucu olarak filtrelemeli ve ekrana getirmelidir.

## Oluşan Durum
- Eğitim Arama Çubuğuna metin girildiğinde herhangi bir filtreleme gerçekleşmiyor.

## Test Ortamı
*Test cihazı:* Intel i9-10850K - NVIDIA GEforce RTX 3070 - 16gb RAM

*Test cihazı sürümü:* Windows 11 23H2 IS derlemesi 22631.4037

*Test cihazı ekran çözünürlüğü:* 1920x 1080

*Uygulamanın test edildiği browser:* Firefox 129.0.2 (64 bit)

*Sorunun Tekrarlanma Saati:* 28.08.2024 , 16:11

## Etki

İlk test oturumunda resmi bir etki değerlendirmesi yapılmadı.

## Geçici Çözüm

İlk test oturumunda geçici çözüm belgelenmedi.
