# Eğitimler sayfasında Grid Görünümde Arama Çubuğunun Eğitimleri Filtrelememesi Sorunu
<!-- standardized-defect-report -->

| Field | Value |
| --- | --- |
| Defect ID | DEF-MS-003 |
| Status | Documented |
| Type | Functional |
| Severity | Not recorded |
| Priority | Not recorded |
| Reproducibility | Not recorded |
| Platform | Web |
| Evidence | Included in the report |

[Back to Software Defect Portfolio](../README.md)

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

## Impact

Not formally assessed in the original test session.

## Workaround

No workaround was documented during the original test session.
