# Review publishing criteria page has no exit option
<!-- standardized-defect-report -->

| Field | Value |
| --- | --- |
| Defect ID | DEF-HB-006 |
| Status | Documented |
| Type | Functional |
| Severity | Not recorded |
| Priority | Not recorded |
| Reproducibility | Not recorded |
| Platform | Mobile Web |
| Evidence | Included in the report |

[Back to portfolio](../../README.md) · [Türkçe sürüm](../../Turkish-Reports/hepsiburada-mobile-web-defects/review-publishing-criteria-page-has-no-exit-option.md)

## Preconditions

The user must not be signed in.

## Area

Product details

## Steps to Reproduce

1. Open Safari.
2. Go to https://hepsiburada.com/.
3. Search for "neoflam fika glace vakumlu cam saklama kabı bej 5 parça".
4. Open the first product in the search results.
5. Verify that the product page opens.
6. Click "Yorum Yapma Kriterleri" (review criteria) below "Değerlendir" (review).
7. View the review criteria text.
8. Enter details about the topic, as recorded in the original scenario.

## Evidence

![](../../Turkish-Reports/hepsiburada-mobile-web-defects/images/yorumlari-yaninlama-kriterleri.gif)

## Expected Result

The screen opened from the review flow should offer a visible, functional exit or cancel button so the user can close it and return to the previous page.

## Actual Result

The screen offers no exit or cancel option. The user cannot leave the screen through its controls, which creates a confusing, trapped navigation experience.

## Test Environment

*Device:* Iphone 11

*OS Version:* iOS 17.6.1

*Display Resolution:* 828x1792 px

*Browser:* Safari 17.6.1

*Issue Reproduction Time:* 07.09.2024 , 11:34

## Impact

Not formally assessed in the original test session.

## Workaround

No workaround was documented during the original test session.
