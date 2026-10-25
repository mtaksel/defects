# Oyun haritası temalarında dil tutarsızlığı
<!-- standardized-defect-report -->

| Alan | Değer |
| --- | --- |
| Hata Kimliği | DEF-SV-002 |
| Durum | Raporlandı |
| Tür | Yerelleştirme |
| Önem Derecesi | Orta |
| Öncelik | Kaydedilmedi |
| Tekrarlanabilirlik | Kaydedilmedi |
| Platform | PC Oyunu |
| Kanıt | Raporda yer alıyor |

[Ana sayfaya dön](../../../README.md) · [English version](../../../English-Reports/supervive-game-defects/Localization-Bug/map-theme-language-inconsistency.md)

## Açıklama

Supervive oyununda farklı temalar bulunuyor. Görüntülenen oyun modları veya temalar karışık dillerde sunuluyor; biri Türkçe, diğeri İngilizce görünüyor.

## Ön Koşullar

Dil ayarı: Türkçe.

## Yeniden Oluşturma Adımları

1. Steam istemcisini başlatın.
2. Supervive oyununu başlatın.
3. Eşleşme aramak için sıraya girin.
4. Oyunun bir eşleşme bulmasını bekleyin.
5. Karakter seçimi ekranına gidin.
6. Oyunun başlamasını bekleyin.

## Kanıtlar

![](../../../English-Reports/supervive-game-defects/media/map-theme-language-inconsistency-1.png)

## Beklenen Sonuç

Tüm oyun modları ve temalar, oyuncunun seçtiği dil tercihine göre aynı dilde (Türkçe veya İngilizce) görüntülenmelidir.

## Gerçekleşen Sonuç

Bir tema İngilizce, diğeri Türkçe görüntüleniyor. Bu durum oyunun kullanıcı arayüzünde tutarsızlık oluşturuyor.

## Önem Derecesi

Seviye: Orta.

## Test Ortamı

*Cihaz: Intel i9-10850K - NVIDIA GeForce RTX 3070 - 16GB RAM

*İşletim sistemi sürümü: Windows 11 23H2, Derleme 22631.4037

*Ekran çözünürlüğü: 1920x1080

*Platform ayrıntıları: PC

*Steam istemci sürümü: 1726604483

*Supervive sürümü: release0.15.snf-100829-shipping

*Hatanın tekrarlandığı tarih ve saat: 19.10.2024, 23:15

## Etki

İlk test oturumunda resmi bir etki değerlendirmesi yapılmadı.

## Geçici Çözüm

İlk test oturumunda geçici çözüm belgelenmedi.
