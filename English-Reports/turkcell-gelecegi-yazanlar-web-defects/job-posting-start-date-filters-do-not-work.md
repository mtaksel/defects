# Job posting start-date filters return a server error
<!-- standardized-defect-report -->

| Field | Value |
| --- | --- |
| Defect ID | DEF-TG-003 |
| Status | Documented |
| Type | Functional |
| Severity | Not recorded |
| Priority | Not recorded |
| Reproducibility | Not recorded |
| Platform | Web |
| Evidence | Included in the report |

[Back to portfolio](../../README.md) · [Türkçe sürüm](../../Turkish-Reports/turkcell-gelecegi-yazanlar-web-defects/job-posting-start-date-filters-do-not-work.md)

## Preconditions

Not recorded.

## Area

Job posting filtering

## Steps to Reproduce

1. Go to https://gelecegiyazanlar.turkcell.com.tr/.
2. Click "İş İlanları" (job postings).
3. Under "İLAN BAŞLANGIÇ TARİHİ" (posting start date), try "Bugünün İlanları", "Son 3 Günün İlanları", "Son 1 Haftanın İlanları", and "Son 1 Yılın Ilanları" (today, last 3 days, last week, last year).
4. Check whether matching postings are displayed or a no-postings message appears.

## Evidence

![](../../Turkish-Reports/turkcell-gelecegi-yazanlar-web-defects/images/is-ilani-anasayfa.png)

![](../../Turkish-Reports/turkcell-gelecegi-yazanlar-web-defects/images/%C4%B0s-%C4%B0lanlari-filtreleme.png)

![](../../Turkish-Reports/turkcell-gelecegi-yazanlar-web-defects/images/Is-ilani-sorunu.png)

## Expected Result

Job postings should be filtered by the selected date range. If no postings match, an appropriate message should appear.

## Actual Result

Clicking a filter returns HTTP 500 with "The website encountered an unexpected error. Please try again later."

## Test Environment

*Device:* Intel i9-10850K - NVIDIA GEforce RTX 3070 - 16gb RAM

*OS Version:* Windows 11 23h2 Build 22631.3235

*Display Resolution:* 1920x 1080

*Browser:* Firefox 123.0 (64-bit)

*Issue Reproduction Time:* 07.03.2024 , 105:46

## Impact

Not formally assessed in the original test session.

## Workaround

No workaround was documented during the original test session.
