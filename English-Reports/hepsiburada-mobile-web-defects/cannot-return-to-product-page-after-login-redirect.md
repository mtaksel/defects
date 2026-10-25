# Cannot return to the product page after the login redirect
<!-- standardized-defect-report -->

| Field | Value |
| --- | --- |
| Defect ID | DEF-HB-002 |
| Status | Documented |
| Type | Functional |
| Severity | Not recorded |
| Priority | Not recorded |
| Reproducibility | Not recorded |
| Platform | Mobile Web |
| Evidence | Included in the report |

[Back to portfolio](../../README.md) · [Türkçe sürüm](../../Turkish-Reports/hepsiburada-mobile-web-defects/cannot-return-to-product-page-after-login-redirect.md)

## Preconditions

The user must not be signed in.

## Area

Product details

## Steps to Reproduce

1. Open Safari.
2. Go to https://hepsiburada.com/.
3. Search for "neoflam fika glace vakumlu cam saklama kabı bej 5 parça".
4. Open the first product in the search results.
5. Scroll down to "Satıcıya Sor" (ask the seller).
6. Click "Satıcıya Sor".
7. Select "Ürün Özellikleri" (product details) in the "Seçim Yapın" dropdown.
8. Enter details about the question.
9. Click "Soru sor" (ask a question).
10. Verify that the login page opens.
11. Click the back button at the top left of the page.
12. Observe that the homepage opens.

## Evidence

![](../../Turkish-Reports/hepsiburada-mobile-web-defects/images/saticiya-sor-butonu-sorunu.gif)

## Expected Result

After being redirected to login to ask the seller a question, the back button should return the user to the product page, preserving a continuous navigation experience.

## Actual Result

The back button redirects to the homepage instead of the product page. The user must find the product again, which disrupts navigation.

## Test Environment

*Device:* Iphone 11

*OS Version:* iOS 17.6.1

*Display Resolution:* 828x1792 px

*Browser:* Safari 17.6.1

*Issue Reproduction Time:* 06.09.2024 , 11:23

## Impact

Not formally assessed in the original test session.

## Workaround

No workaround was documented during the original test session.
