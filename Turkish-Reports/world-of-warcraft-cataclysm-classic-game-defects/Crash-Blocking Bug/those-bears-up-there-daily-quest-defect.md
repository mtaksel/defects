# Those Bears Up There günlük görevinin ödülleri alınırken oyun donuyor
<!-- standardized-defect-report -->

| Alan | Değer |
| --- | --- |
| Hata Kimliği | DEF-WOW-001 |
| Durum | Raporlandı |
| Tür | Çökme / Engelleyici |
| Önem Derecesi | Kaydedilmedi |
| Öncelik | Kaydedilmedi |
| Tekrarlanabilirlik | Kaydedilmedi |
| Platform | PC Oyunu |
| Kanıt | Raporda yer alıyor |

[Ana sayfaya dön](../../../README.md) · [English version](../../../English-Reports/world-of-warcraft-cataclysm-classic-game-defects/Crash-Blocking%20Bug/those-bears-up-there-daily-quest-defect.md)

## Açıklama

Görev tamamlandıktan sonra oyuncu ödülleri almak için düğmeye tıkladığında oyun donuyor.

## Ön Koşullar

85. seviye bir karaktere ve satın alınmış World of Warcraft oyun süresine sahip olunmalıdır.

## Yeniden Oluşturma Adımları

1. World of Warcraft oyununu açın ve karakterinizle giriş yapın.
2. “Those Bears Up There” günlük görevini kabul edin.
3. Gerekli tüm nesneleri toplayarak görevi tamamlayın.
4. Görev ödüllerini almayı deneyin.

## Kanıtlar

[![İzlemek için tıklayın](../../../English-Reports/world-of-warcraft-cataclysm-classic-game-defects/media/media1.jpeg)](https://www.youtube.com/watch?v=PnsAQlRa4ng)

[![İzlemek için tıklayın](../../../English-Reports/world-of-warcraft-cataclysm-classic-game-defects/media/media2.jpeg)](https://www.youtube.com/watch?v=_s-t96ZAKjo)

İlk video ödül alınırken yaşanan donmayı; ikinci video yeniden girişten sonra karakterin düşerek hasar almasını gösterir.

## Beklenen Sonuç

Görev tamamlandıktan sonra oyuncu ödülleri alma düğmesine tıkladığında ödüller başarıyla alınmalıdır.

## Gerçekleşen Sonuç

Ödülleri alma düğmesine tıklandığında oyun donuyor ve kısa süre sonra “You have been disconnected from the server.” mesajı görüntüleniyor. Oyuna yeniden girildiğinde karakter, bağlantının koptuğu yerden biraz uzakta havada başlıyor; yere düşüp düşme hasarı alıyor.

## Test Ortamı

*Cihaz: Intel i9-10850K - NVIDIA GeForce RTX 3070 - 16GB RAM

*İşletim sistemi sürümü: Windows 11 23H2, Derleme 22631.4037

*Ekran çözünürlüğü: 1920x1080

*Battle.net istemci sürümü: 2.29.0 (64-bit)

*World of Warcraft Cataclysm Classic sürümü: 4.4.0 - 24 Eylül 2024 düzeltme yaması (64-bit)

*Hatanın tekrarlandığı tarih ve saat: 29.09.2024, 23:27

## Etki

İlk test oturumunda resmi bir etki değerlendirmesi yapılmadı.

## Geçici Çözüm

İlk test oturumunda geçici çözüm belgelenmedi.
