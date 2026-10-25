# "Satıcıya Sor" Butonuna Tıklayıp Login Sayfasında Yönlendirdikten Sonra Ürün Sayfasına Geri Dönme Sorunu
<!-- standardized-defect-report -->

| Field | Value |
| --- | --- |
| Defect ID | DEF-HB-002 |
| Status | Documented |
| Type | Functional |
| Severity | Not recorded |
| Priority | Not recorded |
| Reproducibility | Not recorded |
| Platform | Mobile Web |
| Evidence | Included in the report |

[Back to Software Defect Portfolio](../README.md)

## Ön Koşullar
- Üye girişi yapılmamış olmalı

## Aşama
- Ürün Özellikleri

## Senaryo
1. Safari açılır.
2. https://hepsiburada.com/ linkine girilir.
3. Arama çubuğuna "neoflam fika glace vakumlu cam saklama kabı bej 5 parça" girilir.
4. Arama sonucundan çıkan ilk ürüne tıklanır.
5. "Satıcıya Sor" butonu kısmına kadar sayfa aşağıya kaydırılır.
6. "Satıcıya Sor" butonu tıklanır.
7. "Seçim Yapın" Dropdown Menüden Ürün Özellikleri seçilir.
8. Konu ile ilgili detay metini girilir.
9. "Soru sor" butonuna tıklanır.
10. Login olma sayfasına yönlendirildiği doğrulanır.
11. Sayfanın sol üst tarafındaki Geriye Dönme butonuna tıklanır.
12. Anasayfaya yönelendirildiği doğrulanır.
## Ekran Görüntüleri
![](images/saticiya-sor-butonu-sorunu.gif)

## Beklenen Sonuç
- Kullanıcı, "Satıcıya Sor" butonuna tıklayıp soru sormak için giriş yapmaya yönlendirildiğinde, geri dönme butonuna bastığında ürün sayfasına geri dönmelidir. Bu, kullanıcı deneyimini kesintisiz tutmak için önemli bir navigasyon fonksiyonudur.

## Oluşan Durum
- Kullanıcı, geri dönme butonuna bastığında ürün sayfasına geri dönmek yerine ana sayfaya yönlendiriliyor. Bu, kullanıcıların tekrar ürünü bulmasını zorlaştırıyor ve kullanıcı deneyimini olumsuz etkiliyor.

## Test Ortamı
*Test cihazı:* Iphone 11

*Test cihazı sürümü:* iOS 17.6.1

*Test cihazı ekran çözünürlüğü:* 828x1792 px

*Uygulamanın test edildiği browser:* Safari 17.6.1 

*Sorunun Tekrarlanma Saati:* 06.09.2024 , 11:23

## Impact

Not formally assessed in the original test session.

## Workaround

No workaround was documented during the original test session.
