# Product return conditions text is not readable
<!-- standardized-defect-report -->

| Field | Value |
| --- | --- |
| Defect ID | DEF-HB-005 |
| Status | Documented |
| Type | UI/UX |
| Severity | Not recorded |
| Priority | Not recorded |
| Reproducibility | Not recorded |
| Platform | Mobile Web |
| Evidence | Included in the report |

[Back to portfolio](../../README.md) · [Türkçe sürüm](../../Turkish-Reports/hepsiburada-mobile-web-defects/product-return-conditions-text-is-not-readable.md)

## Preconditions

Not recorded.

## Area

Product details

## Steps to Reproduce

1. Open Safari.
2. Go to https://hepsiburada.com/.
3. Search for "Misbahçe Ozonlu Kantaron Yağı 50 ml".
4. Open the first product in the search results.
5. Scroll down to the product details.
6. Click the link in "Ürünlerinizi 14 gün içerisinde iade edebilirsiniz. Detaylı bilgi için tıklayın." (returns within 14 days; click for details).
7. Verify that the return conditions page opens.

## Evidence

![](../../Turkish-Reports/hepsiburada-mobile-web-defects/images/iade-kosullari-image.jpg)

## Expected Result

Return conditions should be easy to read and understand, with suitable font size, colors, background contrast, and layout across devices and browsers.

## Actual Result

The first word of the return conditions is partially clipped at the edge of the screen. This alignment issue prevents the text from being read completely.

## Test Environment

*Device:* Iphone 11

*OS Version:* iOS 17.6.1

*Display Resolution:* 828x1792 px

*Browser:* Safari 17.6.1

*Issue Reproduction Time:* 06.09.2024 , 21:52

## Impact

Not formally assessed in the original test session.

## Workaround

No workaround was documented during the original test session.
