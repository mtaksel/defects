# Event type filter is unresponsive
<!-- standardized-defect-report -->

| Field | Value |
| --- | --- |
| Defect ID | DEF-PU-008 |
| Status | Documented |
| Type | Functional |
| Severity | Not recorded |
| Priority | Not recorded |
| Reproducibility | Not recorded |
| Platform | Web |
| Evidence | Included in the report |

[Back to portfolio](../../README.md) · [Türkçe sürüm](../../Turkish-Reports/pupilica-web-defects/event-type-filter-is-unresponsive.md)

## Preconditions

Not recorded.

## Area

Events page

## Steps to Reproduce

1. Go to https://pupilica.com/.
2. Click "Etkinlikler" (events) in the navigation bar.
3. Verify that the Events page opens.
4. Select "Webinar" in the event type filter.
5. Check the filtered results.

## Evidence

![](../../Turkish-Reports/pupilica-web-defects/images/etkinlikler-sayfasindaki-etkinlik-turu-filtrelemesi-tepkisizligi.gif)

## Expected Result

Selecting a filter should update the displayed list or content to match the chosen criterion, making the applied filtering visible to the user.

## Actual Result

The selected filter has no effect. The page does not respond and the content does not update, so the user cannot see the requested results.

## Test Environment

*Device:* Intel i9-10850K - NVIDIA GEforce RTX 3070 - 16gb RAM

*OS Version:* Windows 11 23H2 Build 22631.4037

*Display Resolution:* 1920x 1080

*Browser:* Firefox 129.0.2 (64-bit)

*Issue Reproduction Time:* 07.09.2024 , 10:14

## Impact

Not formally assessed in the original test session.

## Workaround

No workaround was documented during the original test session.
