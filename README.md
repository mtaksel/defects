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
