# Navigation search button is inactive
<!-- standardized-defect-report -->

| Field | Value |
| --- | --- |
| Defect ID | DEF-MS-001 |
| Status | Documented |
| Type | Functional |
| Severity | Not recorded |
| Priority | Not recorded |
| Reproducibility | Not recorded |
| Platform | Web |
| Evidence | Included in the report |

[Back to portfolio](../../README.md) · [Türkçe sürüm](../../Turkish-Reports/mindset-web-defects/navigation-search-button-is-inactive.md)

## Preconditions

Not recorded.

## Area

Homepage

## Steps to Reproduce

1. Go to https://www.mindset.com.tr/.
2. Locate the search bar below the navigation bar.
3. Enter "İş Analisti" in the search bar.
4. Click the magnifying glass icon to search.
5. Press Enter on the keyboard.

## Evidence

![](../../Turkish-Reports/mindset-web-defects/images/arama-cubugu-tepkisizlik.gif)

## Expected Result

Clicking the magnifying glass or pressing Enter should submit the entered text and open the search results page.

## Actual Result

Neither the magnifying glass nor the Enter key triggers a response for the entered text.

## Test Environment

*Device:* Intel i9-10850K - NVIDIA GEforce RTX 3070 - 16gb RAM

*OS Version:* Windows 11 23H2 Build 22631.4037

*Display Resolution:* 1920x 1080

*Browser:* Firefox 129.0.2 (64-bit)

*Issue Reproduction Time:* 26.08.2024 , 03:34

## Impact

Not formally assessed in the original test session.

## Workaround

No workaround was documented during the original test session.
