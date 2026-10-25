# Software Defect Portfolio

> A curated collection of reproducible software defect reports covering web, mobile web, and PC game testing.

[![Manual Testing](https://img.shields.io/badge/Testing-Manual-2563EB?style=flat-square)](#testing-scope)
[![Web Testing](https://img.shields.io/badge/Platform-Web-0EA5E9?style=flat-square)](#testing-scope)
[![Mobile Web](https://img.shields.io/badge/Platform-Mobile_Web-8B5CF6?style=flat-square)](#testing-scope)
[![Game Testing](https://img.shields.io/badge/Testing-Games-E11D48?style=flat-square)](#testing-scope)
[![Bug Reports](https://img.shields.io/badge/Documentation-Bug_Reports-16A34A?style=flat-square)](#reporting-standard)

## About this repository

This repository demonstrates my approach to exploratory testing, defect discovery, reproducible bug reporting, and evidence-based QA documentation. Each report is written to help developers and product teams understand the problem, reproduce it efficiently, assess its impact, and verify a future fix.

The reports include examples from real web, mobile web, and PC game test sessions. Product names are used only to identify the tested environment; this repository is an independent QA portfolio and is not affiliated with the listed companies.

## Testing scope

| Product | Platform | Report collection |
| --- | --- | --- |
| Hepsiburada | Mobile Web | [View reports](./hepsiburada-mobile-web-defects/) |
| LinkedIn | Web | [View reports](./linkedin-web-defects/) |
| Mindset | Web | [View reports](./mindset-web-defects/) |
| Pupilica | Web | [View reports](./pupilica-web-defects/) |
| Supervive | PC Game | [View reports](./supervive-game-defects/) |
| Turkcell Geleceği Yazanlar | Web | [View reports](./turkcell-gelecegi-yazanlar-web-defects/) |
| World of Warcraft: Cataclysm Classic | PC Game | [View reports](./world-of-warcraft-cataclysm-classic-game-defects/) |
| Yemeksepeti | Web | [View reports](./yemeksepeti-web-defects/) |

## Defect catalog

The portfolio currently contains **34 documented defects**. Reports are grouped below by platform, product, and defect type so reviewers can quickly navigate to relevant examples.

| Platform | Functional | UI/UX | Localization | Crash / Blocking | Total |
| --- | ---: | ---: | ---: | ---: | ---: |
| Web | 18 | 5 | 0 | 0 | 23 |
| Mobile Web | 4 | 2 | 0 | 0 | 6 |
| PC Game | 0 | 2 | 2 | 1 | 5 |
| **Total** | **22** | **9** | **2** | **1** | **34** |

### Mobile Web

#### Hepsiburada — 6 reports

**Functional**

- [Payment options panel cannot be closed](./hepsiburada-mobile-web-defects/odeme-firsatlari-sekmesinin-kapanmama-sorunu.md)
- [Unable to return to the product page after the login redirect](./hepsiburada-mobile-web-defects/saticiya-soru-sorduktan-sonra-login-sayfasindan-urun-sayfasına-geri-donememe-sorunu.md)
- [Campaign information panel cannot be closed](./hepsiburada-mobile-web-defects/urune-ait-kampanya-bilgi-butonuna-tiklandiginda-acilan-sayfanin-kapanmama-sorunu.md)
- [Review publishing criteria page has no exit option](./hepsiburada-mobile-web-defects/yorumlari-yayinlama-kriterleri-sayfasi-sorunu.md)

**UI/UX**

- [Product description text is not readable](./hepsiburada-mobile-web-defects/urun-aciklamasi-metini-okunabilir-degil.md)
- [Product return conditions text is not readable](./hepsiburada-mobile-web-defects/urun-iade-kosullari-metini-okunabilir-degil.md)

### Web

#### LinkedIn — 1 report

**Functional**

- [Unable to display additional congratulation templates](./linkedin-web-defects/defects.md)

#### Mindset — 6 reports

**Functional**

- [Navigation search button is inactive](./mindset-web-defects/arama-cubugundaki-arama-butonu-sorunu.md)
- [Duplicate search bar on the training page](./mindset-web-defects/fazladan-arama-cubugu-sorunu.md)
- [Training search does not filter the grid view](./mindset-web-defects/grid-gorunumde-egitim-filtreleme-sorunu.md)
- [Short programs collapse button does not work](./mindset-web-defects/kisa-programlar-bolumu-kucultme-butonu-sorunu.md)
- [Training search does not filter the list view](./mindset-web-defects/list-gorunumde-egitim-filtreleme-sorunu.md)

**UI/UX**

- [Short programs section is not centered](./mindset-web-defects/kisa-programlar-bolumu-ui-sorunu.md)

#### Pupilica — 9 reports

**Functional**

- [Homepage slideshow does not advance automatically](./pupilica-web-defects/anasayfa-slideshow-sorunu.md)
- [Training list is sorted incorrectly from A to Z](./pupilica-web-defects/egitimler-A-Z-filtreleme-sorunu.md)
- [Training list is sorted incorrectly from Z to A](./pupilica-web-defects/egitimler-Z-A-filtreleme-sorunu.md)
- [LinkedIn profile link is missing from an instructor card](./pupilica-web-defects/egitmen-sayfasinda-eksik-linkedin-butonu.md)
- [Instructor LinkedIn link redirects incorrectly](./pupilica-web-defects/egitmenler-sayfasinda-egitmen-kartindaki-linkedin-butonunun-yanlis-yonlendirmesi.md)
- [Skills filter contains an unnamed option](./pupilica-web-defects/etkinlikler-sayfasindaki-beceriler-filtreleme-sorunu.md)
- [Event type filter is unresponsive](./pupilica-web-defects/etkinlikler-sayfasindaki-etkinlik-turu-filtrelemesinin-tepkisizligi.md)

**UI/UX**

- [Instructor cards have inconsistent proportions](./pupilica-web-defects/egitmenler-sayfasindaki-tasarim-hatasi.md)
- [About page layout defect](./pupilica-web-defects/hakkimizda-sayfasi-tasarim-sorunu.md)

#### Turkcell Geleceği Yazanlar — 5 reports

**Functional**

- [Facebook registration and login issue](./turkcell-gelecegi-yazanlar-web-defects/Facebook-ile-kayit-olma-ve-giris-sorunu.md)
- [Google registration and login issue](./turkcell-gelecegi-yazanlar-web-defects/Google-hesabıyla-kayit-olma-ve-giris-sorunu.md)
- [Job posting start-date filters do not work](./turkcell-gelecegi-yazanlar-web-defects/is-ilanları-ilan-baslangic-tarihi.md)
- [Twitter registration and login issue](./turkcell-gelecegi-yazanlar-web-defects/Twitter-ile-kayit-olma-ve-giris-sorunu.md)
- [Registration form issue](./turkcell-gelecegi-yazanlar-web-defects/Uye-olma-formu-sorunu.md)

#### Yemeksepeti — 2 reports

**UI/UX**

- [Order confirmation page interface issue](./yemeksepeti-web-defects/siparis-onaylama-sayfasinda-arayuz-sorunu.md)
- [Order payment page interface issue](./yemeksepeti-web-defects/sipariş-odeme-sayfasında-arayuz-sorunu.md)

### PC Games

#### Supervive — 4 reports

**Localization**

- [Language inconsistency in the character selection interface](./supervive-game-defects/Localization-Bug/language-inconsistency-in-character-selection-interface.md)
- [Inconsistent language display in game map themes](./supervive-game-defects/Localization-Bug/map-theme-language-inconsistency.md)

**UI/UX**

- [Character unlock message does not fit on screen](./supervive-game-defects/UI-UX-Bug/character-unlock-message-inconsistency.md)
- [Map theme description capitalization inconsistency](./supervive-game-defects/UI-UX-Bug/map-theme-description-capitalization-inconsistency.md)

#### World of Warcraft: Cataclysm Classic — 1 report

**Crash / Blocking**

- [Crash while claiming the “Those Bears Up There” daily quest reward](./world-of-warcraft-cataclysm-classic-game-defects/Crash-Blocking%20Bug/those-bears-up-there-daily-quest-defect.md)

## Featured reports

- [Language inconsistency in the Supervive character selection interface](./supervive-game-defects/Localization-Bug/language-inconsistency-in-character-selection-interface.md)
- [Hepsiburada payment options panel cannot be closed](./hepsiburada-mobile-web-defects/odeme-firsatlari-sekmesinin-kapanmama-sorunu.md)
- [Supervive game defect collection](./supervive-game-defects/)
- [World of Warcraft: Cataclysm Classic defect collection](./world-of-warcraft-cataclysm-classic-game-defects/)

## Reporting standard

Each new report follows a consistent, developer-friendly structure:

1. Clear, observable title
2. Defect metadata: ID, status, type, severity, priority, and reproducibility
3. Complete test environment and build information
4. Preconditions and test data
5. Minimal numbered reproduction steps
6. Expected and actual results
7. User or business impact
8. Screenshot, GIF, or video evidence
9. Workaround and additional notes when relevant

Use the [bug report template](./BUG_REPORT_TEMPLATE.md) for new reports.

## Severity guide

| Severity | Definition | Example impact |
| --- | --- | --- |
| Critical | Blocks a core flow, causes data loss, or makes the product unusable | Crash, payment failure, lost progress |
| High | Major functionality fails and no reasonable workaround exists | Login or checkout flow blocked |
| Medium | Functionality is impaired, but a workaround or alternate path exists | A panel cannot be closed normally |
| Low | Cosmetic, wording, alignment, or minor usability issue | Localization or visual inconsistency |

> Severity describes technical and user impact. Priority describes how urgently the issue should be addressed and may depend on business context.

## Skills demonstrated

- Exploratory and scenario-based testing
- Reproduction and isolation of defects
- Severity and impact assessment
- Web, mobile web, and game testing
- Environment and build documentation
- Visual evidence collection
- Clear communication for developers and stakeholders

## Author

**Mehmet Turgut Aksel** — QA & Test Automation Engineer

- [GitHub Profile](https://github.com/mtaksel)
- [Portfolio](https://mtaksel.github.io/my-portfolio/)
- [LinkedIn](https://www.linkedin.com/in/mehmeturgutaksel/)
