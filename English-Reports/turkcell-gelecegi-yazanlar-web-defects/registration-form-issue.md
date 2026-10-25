# Registration form exposes an internal identifier and misaligned fields
<!-- standardized-defect-report -->

| Field | Value |
| --- | --- |
| Defect ID | DEF-TG-005 |
| Status | Documented |
| Type | Functional |
| Severity | Not recorded |
| Priority | Not recorded |
| Reproducibility | Not recorded |
| Platform | Web |
| Evidence | Included in the report |

[Back to portfolio](../../README.md) · [Türkçe sürüm](../../Turkish-Reports/turkcell-gelecegi-yazanlar-web-defects/registration-form-issue.md)

## Preconditions

Not recorded.

## Area

Registration

## Steps to Reproduce

1. Go to https://gelecegiyazanlar.turkcell.com.tr/.
2. Click "Giriş Yap" (sign in).
3. Click the registration button beside "Hesabınız yok mu?" (do not have an account?).
4. Verify navigation to https://gelecegiyazanlar.turkcell.com.tr/user/register.
5. Inspect the registration form layout.

## Evidence

![](../../Turkish-Reports/turkcell-gelecegi-yazanlar-web-defects/images/anasayfa.png)

![](../../Turkish-Reports/turkcell-gelecegi-yazanlar-web-defects/images/uye-ol-butonu.png)

![](../../Turkish-Reports/turkcell-gelecegi-yazanlar-web-defects/images/kaydolma-sorunu.png)

## Expected Result

The registration form should not expose the internal "phone_num" identifier, and its input fields should be aligned correctly.

## Actual Result

The internal component identifier "phone_num" is visible in the interface, and the input fields are misaligned.

## Test Environment

*Device:* Intel i9-10850K - NVIDIA GEforce RTX 3070 - 16gb RAM

*OS Version:* Windows 11 23h2 Build 22631.3235

*Display Resolution:* 1920x 1080

*Browser:* Firefox 123.0 (64-bit)

*Issue Reproduction Time:* 04.03.2024 , 12:24

## Impact

Not formally assessed in the original test session.

## Workaround

No workaround was documented during the original test session.
