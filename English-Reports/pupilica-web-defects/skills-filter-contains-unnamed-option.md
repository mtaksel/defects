# Skills filter contains an unnamed option
<!-- standardized-defect-report -->

| Field | Value |
| --- | --- |
| Defect ID | DEF-PU-007 |
| Status | Documented |
| Type | Functional |
| Severity | Not recorded |
| Priority | Not recorded |
| Reproducibility | Not recorded |
| Platform | Web |
| Evidence | Included in the report |

[Back to portfolio](../../README.md) · [Türkçe sürüm](../../Turkish-Reports/pupilica-web-defects/skills-filter-contains-unnamed-option.md)

## Preconditions

Not recorded.

## Area

Events page

## Steps to Reproduce

1. Go to https://pupilica.com/.
2. Click "Etkinlikler" (events) in the navigation bar.
3. Verify that the Events page opens.
4. Locate the unnamed option in the skills filter.

## Evidence

![](../../Turkish-Reports/pupilica-web-defects/images/etkinlikler-sayfasi-beceriler-filtrelemesi-sorunu.gif)

## Expected Result

Every filter option should have a meaningful label or heading that clearly explains what it filters. No option should be unnamed.

## Actual Result

The skills filter contains an unnamed option, leaving users unable to understand what it filters and reducing usability.

## Test Environment

*Device:* Intel i9-10850K - NVIDIA GEforce RTX 3070 - 16gb RAM

*OS Version:* Windows 11 23H2 Build 22631.4037

*Display Resolution:* 1920x 1080

*Browser:* Firefox 129.0.2 (64-bit)

*Issue Reproduction Time:* 07.09.2024 , 10:00

## Impact

Not formally assessed in the original test session.

## Workaround

No workaround was documented during the original test session.
