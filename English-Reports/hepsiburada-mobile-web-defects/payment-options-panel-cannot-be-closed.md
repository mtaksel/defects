# Payment options panel cannot be closed
<!-- standardized-defect-report -->

| Field | Value |
| --- | --- |
| Defect ID | DEF-HB-001 |
| Status | Documented |
| Type | Functional |
| Severity | Not recorded |
| Priority | Not recorded |
| Reproducibility | Not recorded |
| Platform | Mobile Web |
| Evidence | Included in the report |

[Back to portfolio](../../README.md) · [Türkçe sürüm](../../Turkish-Reports/hepsiburada-mobile-web-defects/payment-options-panel-cannot-be-closed.md)

## Preconditions

Not recorded.

## Area

Product page

## Steps to Reproduce

1. Open Safari.
2. Go to https://hepsiburada.com/.
3. Search for "Solo Bambu Tuvalet Kağıdı 40'lı".
4. Open the first product in the search results.
5. Click "Ayda 23,33 TL’den başlayan, 12 ay taksitle" (12 monthly installments starting at TRY 23.33).
6. Verify that the detailed information panel opens.

## Evidence

![](../../Turkish-Reports/hepsiburada-mobile-web-defects/images/odeme-firsatlari-sekmesi-sorunu.gif)

## Expected Result

The payment campaign panel should close when the user clicks the close (X) button, returning the user to the previous view.

## Actual Result

The close (X) button does not respond, so the user cannot exit the campaign panel.

## Test Environment

*Device:* Iphone 11

*OS Version:* iOS 17.6.1

*Display Resolution:* 828x1792 px

*Browser:* Safari 17.6.1

*Issue Reproduction Time:* 06.09.2024 , 11:05

## Impact

Not formally assessed in the original test session.

## Workaround

No workaround was documented during the original test session.
