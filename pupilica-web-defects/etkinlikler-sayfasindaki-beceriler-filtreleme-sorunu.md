# Etkinlikler Sayfasındaki Beceriler Filtrelemesindeki İsimsiz Filtreleme Seçeneği
<!-- standardized-defect-report -->

| Field | Value |
| --- | --- |
| Defect ID | DEF-PU-007 |
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
- Etkinlikler Sayfası

## Senaryo
1. https://pupilica.com/ linkine girilir.
2. Navigasyon Bardan Etkinlikler seçeneğine tıklanır.
3. Etkinlikler Sayfasina yönlendirildiği doğrulanır
4. Beceri filtrelemesindeki isimsiz filtreleme seçeneği görüntülenir.
## Ekran Görüntüleri
![](images/etkinlikler-sayfasi-beceriler-filtrelemesi-sorunu.gif) 

## Beklenen Sonuç
- Tüm filtreleme seçeneklerinin, kullanıcılara neyi filtreleyeceklerini açıkça belirten bir etiket ya da başlığa sahip olması gerekir. Her filtre seçeneği anlamlı ve kullanımı kolay olmalı, isimsiz seçenek olmamalıdır.

## Oluşan Durum
- Filtreleme seçenekleri arasında isimsiz bir seçenek bulunuyor, bu da kullanıcıların neyi filtrelediklerini anlayamamasına neden oluyor. Bu durum, kullanıcı deneyimini olumsuz etkileyebilir ve işlevselliği azaltabilir.

## Test Ortamı
*Test cihazı:* Intel i9-10850K - NVIDIA GEforce RTX 3070 - 16gb RAM

*Test cihazı sürümü:* Windows 11 23H2 IS derlemesi 22631.4037

*Test cihazı ekran çözünürlüğü:* 1920x 1080

*Uygulamanın test edildiği browser:* Firefox 129.0.2 (64 bit)

*Sorunun Tekrarlanma Saati:* 07.09.2024 , 10:00

## Impact

Not formally assessed in the original test session.

## Workaround

No workaround was documented during the original test session.
