# Training list is sorted incorrectly from Z to A
<!-- standardized-defect-report -->

| Field | Value |
| --- | --- |
| Defect ID | DEF-PU-003 |
| Status | Documented |
| Type | Functional |
| Severity | Not recorded |
| Priority | Not recorded |
| Reproducibility | Not recorded |
| Platform | Web |
| Evidence | Included in the report |

[Back to portfolio](../../README.md) · [Türkçe sürüm](../../Turkish-Reports/pupilica-web-defects/training-list-sorted-incorrectly-z-to-a.md)

## Preconditions

Not recorded.

## Area

Training page

## Steps to Reproduce

1. Go to https://pupilica.com/.
2. Hover over "Eğitimler" (training) in the top navigation bar.
3. Click "Tümünü Gör" (view all).
4. Verify that the training page opens.
5. Select Z–A in the training sorting options.
6. Check whether the list is ordered from Z to A.

## Evidence

![](../../Turkish-Reports/pupilica-web-defects/images/egitimler-sayfasindaki-egitimlerin-z-a-yanlis-filtrelenmesi.gif)

## Expected Result

Names should be listed in correct reverse alphabetical order when Z–A is selected. The original expected result refers to instructor names.

## Actual Result

Some names appear out of order. Z–A sorting does not work correctly, making the desired instructor harder to find.

## Test Environment

*Device:* Intel i9-10850K - NVIDIA GEforce RTX 3070 - 16gb RAM

*OS Version:* Windows 11 23H2 Build 22631.4037

*Display Resolution:* 1920x 1080

*Browser:* Firefox 129.0.2 (64-bit)

*Issue Reproduction Time:* 06.09.2024 , 20:37

## Impact

Not formally assessed in the original test session.

## Workaround

No workaround was documented during the original test session.
