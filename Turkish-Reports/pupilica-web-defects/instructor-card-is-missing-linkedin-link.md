# Eğitmen Kartında LinkedIn Profil Bağlantısı Eksikliği
<!-- standardized-defect-report -->

| Alan | Değer |
| --- | --- |
| Hata Kimliği | DEF-PU-006 |
| Durum | Raporlandı |
| Tür | Fonksiyonel |
| Önem Derecesi | Kaydedilmedi |
| Öncelik | Kaydedilmedi |
| Tekrarlanabilirlik | Kaydedilmedi |
| Platform | Web |
| Kanıt | Raporda yer alıyor |

[Ana sayfaya dön](../../README.md) · [English version](../../English-Reports/pupilica-web-defects/instructor-card-is-missing-linkedin-link.md)

## Ön Koşullar
-

## Aşama
- Eğitmenler Sayfasi

## Senaryo
1. https://pupilica.com/ linkine girilir.
2. Sayfanın en altına kadar kaydırılır.
3. Eğitmenler butonuna tıklanır.
4. Eğitmenler sayfasında yönlendirildiği doğrulanır.
5. Sayfa aşağıya kaydırılır ve " Batuhan Özcan " isimli eğitmenin kartı doğrulanır.
## Ekran Görüntüleri
![](images/egitmenler-sayfasi-egitmen-profilinde-linkedin-butonu-olmamasi.gif)

## Beklenen Sonuç
- Her eğitmen profilinin, LinkedIn profil bağlantısı, tıklanabilir bir buton ile gösterilmeli ve kullanıcılar bu buton üzerinden ilgili eğitmenin LinkedIn sayfasına yönlendirilmelidir.

## Oluşan Durum
- " Batuhan Özcan " isimli eğitmenin kartında LinkedIn profili için tıklanabilir buton bulunmuyor. Bu eksiklik, kullanıcıların eğitmenin profesyonel geçmişini görüntülemesini zorlaştırıyor ve diğer eğitmen profillerindeki tutarlılığı bozuyor.

## Test Ortamı
*Test cihazı:* Intel i9-10850K - NVIDIA GEforce RTX 3070 - 16gb RAM

*Test cihazı sürümü:* Windows 11 23H2 IS derlemesi 22631.4037

*Test cihazı ekran çözünürlüğü:* 1920x 1080

*Uygulamanın test edildiği browser:* Firefox 129.0.2 (64 bit)

*Sorunun Tekrarlanma Saati:* 06.09.2024 , 20:14

## Etki

İlk test oturumunda resmi bir etki değerlendirmesi yapılmadı.

## Geçici Çözüm

İlk test oturumunda geçici çözüm belgelenmedi.
