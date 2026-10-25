# Karakter seçimi arayüzünde dil tutarsızlığı
<!-- standardized-defect-report -->

| Alan | Değer |
| --- | --- |
| Hata Kimliği | DEF-SV-001 |
| Durum | Raporlandı |
| Tür | Yerelleştirme |
| Önem Derecesi | Orta |
| Öncelik | Kaydedilmedi |
| Tekrarlanabilirlik | Kaydedilmedi |
| Platform | PC Oyunu |
| Kanıt | Raporda yer alıyor |

[Ana sayfaya dön](../../../README.md) · [English version](../../../English-Reports/supervive-game-defects/Localization-Bug/language-inconsistency-in-character-selection-interface.md)

## Açıklama

Oyunun dili Türkçe olarak ayarlandığında karakter seçimi arayüzü İngilizce görüntülenmeye devam ediyor. Bu durum kullanıcı deneyiminde dil tutarsızlığı oluşturuyor.

## Ön Koşullar

Dil ayarı: Türkçe.

## Yeniden Oluşturma Adımları

1. Steam istemcisini başlatın.
2. Supervive oyununu başlatın.
3. Eşleşme aramak için sıraya girin.
4. Oyunun bir eşleşme bulmasını bekleyin.
5. Karakter seçimi ekranına gidin.

## Kanıtlar

![](../../../English-Reports/supervive-game-defects/media/language-inconsistency-in-character-selection-interface-media.jpg)

## Beklenen Sonuç

Karakter seçimi arayüzü Türkçe görüntülenmelidir.

## Gerçekleşen Sonuç

Türkçe dil ayarı seçili olmasına rağmen karakter seçimi arayüzü İngilizce görüntüleniyor.

## Önem Derecesi

Seviye: Orta.

## Test Ortamı

*Cihaz: Intel i9-10850K - NVIDIA GeForce RTX 3070 - 16GB RAM

*İşletim sistemi sürümü: Windows 11 23H2, Derleme 22631.4037

*Ekran çözünürlüğü: 1920x1080

*Platform ayrıntıları: PC

*Steam istemci sürümü: 1726604483

*Supervive sürümü: release0.15.snf-100829-shipping

*Hatanın tekrarlandığı tarih ve saat: 19.10.2024, 23:01

## Etki

İlk test oturumunda resmi bir etki değerlendirmesi yapılmadı.

## Geçici Çözüm

İlk test oturumunda geçici çözüm belgelenmedi.
