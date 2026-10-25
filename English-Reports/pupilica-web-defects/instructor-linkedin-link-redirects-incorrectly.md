# Instructor LinkedIn link redirects incorrectly
<!-- standardized-defect-report -->

| Field | Value |
| --- | --- |
| Defect ID | DEF-PU-004 |
| Status | Documented |
| Type | Functional |
| Severity | Not recorded |
| Priority | Not recorded |
| Reproducibility | Not recorded |
| Platform | Web |
| Evidence | Included in the report |

[Back to portfolio](../../README.md) · [Türkçe sürüm](../../Turkish-Reports/pupilica-web-defects/instructor-linkedin-link-redirects-incorrectly.md)

## Preconditions

Not recorded.

## Area

Instructors page

## Steps to Reproduce

1. Go to https://pupilica.com/.
2. Scroll to the bottom of the page.
3. Click "Eğitmenler" (instructors).
4. Verify that the Instructors page opens.
5. Scroll down and locate the instructor card for "Barış Gürkaş".
6. Click his LinkedIn button.

## Evidence

![](../../Turkish-Reports/pupilica-web-defects/images/egitmenler-sayfasi-egitmen-profilinin-yanlis-yonlendirilmesi.gif)

## Expected Result

Each instructor card should provide a clickable LinkedIn button that opens the corresponding instructor's profile.

## Actual Result

The LinkedIn button on the card for "Barış Gürkaş" opens the wrong URL, making it harder to view his professional background.

## Test Environment

*Device:* Intel i9-10850K - NVIDIA GEforce RTX 3070 - 16gb RAM

*OS Version:* Windows 11 23H2 Build 22631.4037

*Display Resolution:* 1920x 1080

*Browser:* Firefox 129.0.2 (64-bit)

*Issue Reproduction Time:* 06.09.2024 , 20:24

## Impact

Not formally assessed in the original test session.

## Workaround

No workaround was documented during the original test session.
