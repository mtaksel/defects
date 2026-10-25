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

## Browse by language

| Report language | Reports | Collection |
| --- | ---: | --- |
| English | 5 | [Browse English reports](./English-Reports/) |
| Turkish | 29 | [Browse Turkish reports](./Turkish-Reports/) |
| **Total** | **34** | |

## Testing scope

| Product | Language | Platform | Report collection |
| --- | --- | --- | --- |
| Hepsiburada | Turkish | Mobile Web | [View reports](./Turkish-Reports/hepsiburada-mobile-web-defects/) |
| LinkedIn | Turkish | Web | [View reports](./Turkish-Reports/linkedin-web-defects/) |
| Mindset | Turkish | Web | [View reports](./Turkish-Reports/mindset-web-defects/) |
| Pupilica | Turkish | Web | [View reports](./Turkish-Reports/pupilica-web-defects/) |
| Supervive | English | PC Game | [View reports](./English-Reports/supervive-game-defects/) |
| Turkcell Geleceği Yazanlar | Turkish | Web | [View reports](./Turkish-Reports/turkcell-gelecegi-yazanlar-web-defects/) |
| World of Warcraft: Cataclysm Classic | English | PC Game | [View reports](./English-Reports/world-of-warcraft-cataclysm-classic-game-defects/) |
| Yemeksepeti | Turkish | Web | [View reports](./Turkish-Reports/yemeksepeti-web-defects/) |

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

- [Payment options panel cannot be closed](./Turkish-Reports/hepsiburada-mobile-web-defects/payment-options-panel-cannot-be-closed.md)
- [Unable to return to the product page after the login redirect](./Turkish-Reports/hepsiburada-mobile-web-defects/cannot-return-to-product-page-after-login-redirect.md)
- [Campaign information panel cannot be closed](./Turkish-Reports/hepsiburada-mobile-web-defects/campaign-information-panel-cannot-be-closed.md)
- [Review publishing criteria page has no exit option](./Turkish-Reports/hepsiburada-mobile-web-defects/review-publishing-criteria-page-has-no-exit-option.md)

**UI/UX**

- [Product description text is not readable](./Turkish-Reports/hepsiburada-mobile-web-defects/product-description-text-is-not-readable.md)
- [Product return conditions text is not readable](./Turkish-Reports/hepsiburada-mobile-web-defects/product-return-conditions-text-is-not-readable.md)

### Web

#### LinkedIn — 1 report

**Functional**

- [Unable to display additional congratulation templates](./Turkish-Reports/linkedin-web-defects/cannot-view-additional-congratulation-templates.md)

#### Mindset — 6 reports

**Functional**

- [Navigation search button is inactive](./Turkish-Reports/mindset-web-defects/navigation-search-button-is-inactive.md)
- [Duplicate search bar on the training page](./Turkish-Reports/mindset-web-defects/duplicate-search-bar-on-training-page.md)
- [Training search does not filter the grid view](./Turkish-Reports/mindset-web-defects/training-search-does-not-filter-grid-view.md)
- [Short programs collapse button does not work](./Turkish-Reports/mindset-web-defects/short-programs-collapse-button-does-not-work.md)
- [Training search does not filter the list view](./Turkish-Reports/mindset-web-defects/training-search-does-not-filter-list-view.md)

**UI/UX**

- [Short programs section is not centered](./Turkish-Reports/mindset-web-defects/short-programs-section-is-not-centered.md)

#### Pupilica — 9 reports

**Functional**

- [Homepage slideshow does not advance automatically](./Turkish-Reports/pupilica-web-defects/homepage-slideshow-does-not-advance-automatically.md)
- [Training list is sorted incorrectly from A to Z](./Turkish-Reports/pupilica-web-defects/training-list-sorted-incorrectly-a-to-z.md)
- [Training list is sorted incorrectly from Z to A](./Turkish-Reports/pupilica-web-defects/training-list-sorted-incorrectly-z-to-a.md)
- [LinkedIn profile link is missing from an instructor card](./Turkish-Reports/pupilica-web-defects/instructor-card-is-missing-linkedin-link.md)
- [Instructor LinkedIn link redirects incorrectly](./Turkish-Reports/pupilica-web-defects/instructor-linkedin-link-redirects-incorrectly.md)
- [Skills filter contains an unnamed option](./Turkish-Reports/pupilica-web-defects/skills-filter-contains-unnamed-option.md)
- [Event type filter is unresponsive](./Turkish-Reports/pupilica-web-defects/event-type-filter-is-unresponsive.md)

**UI/UX**

- [Instructor cards have inconsistent proportions](./Turkish-Reports/pupilica-web-defects/instructor-cards-have-inconsistent-proportions.md)
- [About page layout defect](./Turkish-Reports/pupilica-web-defects/about-page-layout-defect.md)

#### Turkcell Geleceği Yazanlar — 5 reports

**Functional**

- [Facebook registration and login issue](./Turkish-Reports/turkcell-gelecegi-yazanlar-web-defects/facebook-registration-and-login-issue.md)
- [Google registration and login issue](./Turkish-Reports/turkcell-gelecegi-yazanlar-web-defects/google-registration-and-login-issue.md)
- [Job posting start-date filters do not work](./Turkish-Reports/turkcell-gelecegi-yazanlar-web-defects/job-posting-start-date-filters-do-not-work.md)
- [Twitter registration and login issue](./Turkish-Reports/turkcell-gelecegi-yazanlar-web-defects/twitter-registration-and-login-issue.md)
- [Registration form issue](./Turkish-Reports/turkcell-gelecegi-yazanlar-web-defects/registration-form-issue.md)

#### Yemeksepeti — 2 reports

**UI/UX**

- [Order confirmation page interface issue](./Turkish-Reports/yemeksepeti-web-defects/order-confirmation-page-interface-issue.md)
- [Order payment page interface issue](./Turkish-Reports/yemeksepeti-web-defects/order-payment-page-interface-issue.md)

### PC Games

#### Supervive — 4 reports

**Localization**

- [Language inconsistency in the character selection interface](./English-Reports/supervive-game-defects/Localization-Bug/language-inconsistency-in-character-selection-interface.md)
- [Inconsistent language display in game map themes](./English-Reports/supervive-game-defects/Localization-Bug/map-theme-language-inconsistency.md)

**UI/UX**

- [Character unlock message does not fit on screen](./English-Reports/supervive-game-defects/UI-UX-Bug/character-unlock-message-inconsistency.md)
- [Map theme description capitalization inconsistency](./English-Reports/supervive-game-defects/UI-UX-Bug/map-theme-description-capitalization-inconsistency.md)

#### World of Warcraft: Cataclysm Classic — 1 report

**Crash / Blocking**

- [Crash while claiming the “Those Bears Up There” daily quest reward](./English-Reports/world-of-warcraft-cataclysm-classic-game-defects/Crash-Blocking%20Bug/those-bears-up-there-daily-quest-defect.md)

## Featured reports

- [Language inconsistency in the Supervive character selection interface](./English-Reports/supervive-game-defects/Localization-Bug/language-inconsistency-in-character-selection-interface.md)
- [Hepsiburada payment options panel cannot be closed](./Turkish-Reports/hepsiburada-mobile-web-defects/payment-options-panel-cannot-be-closed.md)
- [Supervive game defect collection](./English-Reports/supervive-game-defects/)
- [World of Warcraft: Cataclysm Classic defect collection](./English-Reports/world-of-warcraft-cataclysm-classic-game-defects/)

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
