# Order confirmation options appear in English on the Turkish page
<!-- standardized-defect-report -->

| Field | Value |
| --- | --- |
| Defect ID | DEF-YS-001 |
| Status | Documented |
| Type | UI/UX |
| Severity | Not recorded |
| Priority | Not recorded |
| Reproducibility | Not recorded |
| Platform | Web |
| Evidence | Included in the report |

[Back to portfolio](../../README.md) · [Türkçe sürüm](../../Turkish-Reports/yemeksepeti-web-defects/order-confirmation-page-interface-issue.md)

## Preconditions

The user must have a Yemeksepeti account.

## Area

Order confirmation

## Steps to Reproduce

1. Go to https://www.yemeksepeti.com.
2. Select a restaurant.
3. Click a product.
4. Complete all required selections.
5. Click "Sepete Ekle" (add to cart).
6. Click "Sepeti Onayla" (confirm cart).

## Evidence

![](../../Turkish-Reports/yemeksepeti-web-defects/images/siparis_onay.png)

## Expected Result

The order confirmation options should be in Turkish: "Kapıya bırak", "Varınca beni ara", and "Zili çal".

## Actual Result

The options appear in English as "Leave it at the door", "Call me upon arrival", and "Ring the doorbell".

## Test Environment

*Device:* Intel i9-10850K - NVIDIA GEforce RTX 3070 - 16gb RAM

*OS Version:* Windows 11 23H2 Build 22631.3810

*Display Resolution:* 1920x 1080

*Browser:* Firefox 127.0.2 (64-bit)

*Issue Reproduction Time:* 01.07.2024 , 15:34

## Impact

Not formally assessed in the original test session.

## Workaround

No workaround was documented during the original test session.
