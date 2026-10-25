# Training list is sorted incorrectly from A to Z
<!-- standardized-defect-report -->

| Field | Value |
| --- | --- |
| Defect ID | DEF-PU-002 |
| Status | Documented |
| Type | Functional |
| Severity | Not recorded |
| Priority | Not recorded |
| Reproducibility | Not recorded |
| Platform | Web |
| Evidence | Included in the report |

[Back to portfolio](../../README.md) · [Türkçe sürüm](../../Turkish-Reports/pupilica-web-defects/training-list-sorted-incorrectly-a-to-z.md)

## Preconditions

Not recorded.

## Area

Training page

## Steps to Reproduce

1. Go to https://pupilica.com/.
2. Hover over "Eğitimler" (training) in the top navigation bar.
3. Click "Tümünü Gör" (view all).
4. Verify that the training page opens.
5. Select A–Z in the training sorting options.
6. Check whether the list is ordered from A to Z.

## Evidence

![](../../Turkish-Reports/pupilica-web-defects/images/egitimler-sayfasindaki-egitimlerin-a-z-yanlis-filtrelenmesi.gif)

## Expected Result

Names should be listed in correct alphabetical order when A–Z is selected. The original expected result refers to instructor names.

## Actual Result

Some names appear out of order. A–Z sorting does not work correctly, making the desired instructor harder to find.

## Test Environment

*Device:* Intel i9-10850K - NVIDIA GEforce RTX 3070 - 16gb RAM

*OS Version:* Windows 11 23H2 Build 22631.4037

*Display Resolution:* 1920x 1080

*Browser:* Firefox 129.0.2 (64-bit)

*Issue Reproduction Time:* 06.09.2024 , 20:34

## Impact

Not formally assessed in the original test session.

## Workaround

No workaround was documented during the original test session.
