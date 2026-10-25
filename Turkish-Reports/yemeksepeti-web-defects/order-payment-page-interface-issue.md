
<!-- standardized-defect-report -->

| Alan | Değer |
| --- | --- |
| Hata Kimliği | DEF-YS-002 |
| Durum | Raporlandı |
| Tür | UI/UX |
| Önem Derecesi | Kaydedilmedi |
| Öncelik | Kaydedilmedi |
| Tekrarlanabilirlik | Kaydedilmedi |
| Platform | Web |
| Kanıt | Raporda yer alıyor |

[Ana sayfaya dön](../../README.md) · [English version](../../English-Reports/yemeksepeti-web-defects/order-payment-page-interface-issue.md)
# Sipariş Ödeme Sayfası Arayüz Sorunu
## Ön Koşullar
-Yemeksepeti hesabının olması

## Aşama
- Sipariş Ödeme

## Senaryo
. https://www.yemeksepeti.com linkine girilir.<br>
. Bir restorant seçilir.<br>
. Bir ürüne tıklanır .<br>
. Doldurulması zorunlu bölümler işaretlenir<br>
. "Sepete Ekle" butonuna tıklanır.<br>
. "Sepeti Onayla" butonuna tıklanır.<br>

## Ekran Görüntüleri
![](images/siparis_odeme.png)

## Beklenen Sonuç
- Sayfa dili Türkçe seçilmişken diğer ödeme yöntemlerini göstermesi için "Hepsini Göster" butonu olmalı.

## Oluşan Durum
- Sayfa dili Türkçe seçilmişken diğer ödeme yöntemlerini göstermesi için "Hepsini Göster" yerine "Show all" yazılmış

## Test Ortamı
*Test cihazı:* Intel i9-10850K - NVIDIA GEforce RTX 3070 - 16gb RAM

*Test cihazı sürümü:* Windows 11 23H2 IS derlemesi 22631.3810

*Test cihazı ekran çözünürlüğü:* 1920x 1080

*Uygulamanın test edildiği browser:* Firefox 127.0.2 (64 bit)

*Sorunun Tekrarlanma Saati:* 01.07.2024 , 15:34

## Etki

İlk test oturumunda resmi bir etki değerlendirmesi yapılmadı.

## Geçici Çözüm

İlk test oturumunda geçici çözüm belgelenmedi.
