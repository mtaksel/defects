# Navigasyon Menu Altındaki Arama Çubuğunda Bulunan Arama Butonunun Pasif Olması Sorunu
<!-- standardized-defect-report -->

| Alan | Değer |
| --- | --- |
| Hata Kimliği | DEF-MS-001 |
| Durum | Raporlandı |
| Tür | Fonksiyonel |
| Önem Derecesi | Kaydedilmedi |
| Öncelik | Kaydedilmedi |
| Tekrarlanabilirlik | Kaydedilmedi |
| Platform | Web |
| Kanıt | Raporda yer alıyor |

[Ana sayfaya dön](../../README.md) · [English version](../../English-Reports/mindset-web-defects/navigation-search-button-is-inactive.md)

## Ön Koşullar
-

## Aşama
- Ana Sayfa

## Senaryo
1. https://www.mindset.com.tr/ linkine girilir.
2. Navigasyon Bar'ın altındaki Arama Çubuğu görüntülenir.
3. Arama Çubuğuna "İş Analisti" metini girilir.
4) Arama yapması için Büyüteç ikonuna tıklanır.
5) Klavyeden Enter tuşuna basılır.

## Ekran Görüntüleri
![](images/arama-cubugu-tepkisizlik.gif)

## Beklenen Sonuç
- Arama çubuğuna girilen metinin Büyüteç butonuna ya da Enter tuşuna basılarak arama sonuçlarını gösteren sayfaya yönlendirmeli.

## Oluşan Durum
- Arama çubuğuna girilen metin Büyüteç butonuna ve Enter tuşuna basıldığında tepkisiz kalıyor.

## Test Ortamı
*Test cihazı:* Intel i9-10850K - NVIDIA GEforce RTX 3070 - 16gb RAM

*Test cihazı sürümü:* Windows 11 23H2 IS derlemesi 22631.4037

*Test cihazı ekran çözünürlüğü:* 1920x 1080

*Uygulamanın test edildiği browser:* Firefox 129.0.2 (64 bit)

*Sorunun Tekrarlanma Saati:* 26.08.2024 , 03:34

## Etki

İlk test oturumunda resmi bir etki değerlendirmesi yapılmadı.

## Geçici Çözüm

İlk test oturumunda geçici çözüm belgelenmedi.
