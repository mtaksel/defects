# Training search does not filter the grid view
<!-- standardized-defect-report -->

| Field | Value |
| --- | --- |
| Defect ID | DEF-MS-003 |
| Status | Documented |
| Type | Functional |
| Severity | Not recorded |
| Priority | Not recorded |
| Reproducibility | Not recorded |
| Platform | Web |
| Evidence | Included in the report |

[Back to portfolio](../../README.md) · [Türkçe sürüm](../../Turkish-Reports/mindset-web-defects/training-search-does-not-filter-grid-view.md)

## Preconditions

Not recorded.

## Area

Training page

## Steps to Reproduce

1. Go to https://www.mindset.com.tr/.
2. Click "Eğitimler" (training) in the navigation bar.
3. Verify that the training page opens.
4. Verify that the courses are displayed in grid view.
5. Enter "iş analizi" in the training search bar.

## Evidence

![](../../Turkish-Reports/mindset-web-defects/images/e%C4%9Fitimler-grid-gorunum-arama-cubugu-tepkisizlik.gif)

## Expected Result

The grid should display filtered results matching the words entered in the training search bar.

## Actual Result

Entering text in the search bar does not filter the courses.

## Test Environment

*Device:* Intel i9-10850K - NVIDIA GEforce RTX 3070 - 16gb RAM

*OS Version:* Windows 11 23H2 Build 22631.4037

*Display Resolution:* 1920x 1080

*Browser:* Firefox 129.0.2 (64-bit)

*Issue Reproduction Time:* 28.08.2024 , 16:11

## Impact

Not formally assessed in the original test session.

## Workaround

No workaround was documented during the original test session.
