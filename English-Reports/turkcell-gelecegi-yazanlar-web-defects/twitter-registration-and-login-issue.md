# Twitter registration and login return an unexpected error
<!-- standardized-defect-report -->

| Field | Value |
| --- | --- |
| Defect ID | DEF-TG-004 |
| Status | Documented |
| Type | Functional |
| Severity | Not recorded |
| Priority | Not recorded |
| Reproducibility | Not recorded |
| Platform | Web |
| Evidence | Included in the report |

[Back to portfolio](../../README.md) · [Türkçe sürüm](../../Turkish-Reports/turkcell-gelecegi-yazanlar-web-defects/twitter-registration-and-login-issue.md)

## Preconditions

The Twitter account must be signed in within the browser.

## Area

Login / registration

## Steps to Reproduce

1. Go to https://gelecegiyazanlar.turkcell.com.tr/.
2. Click "Giriş Yap" (sign in).
3. Select Twitter below the text offering sign-in through other accounts.
4. If the Twitter account is signed in, continue; otherwise, complete the Twitter sign-in form.
5. Enter the two-factor authentication code after signing in.
6. Check whether https://gelecegiyazanlar.turkcell.com.tr/benim-sayfam opens.

## Evidence

![](../../Turkish-Reports/turkcell-gelecegi-yazanlar-web-defects/images/anasayfa.png)

![](../../Turkish-Reports/turkcell-gelecegi-yazanlar-web-defects/images/twitter-giris.png)

![](../../Turkish-Reports/turkcell-gelecegi-yazanlar-web-defects/images/twitter-uyari.png)

![](../../Turkish-Reports/turkcell-gelecegi-yazanlar-web-defects/images/twitter-hata-kodu.png)

## Expected Result

Twitter sign-in should authenticate the user and redirect to https://gelecegiyazanlar.turkcell.com.tr/benim-sayfam.

## Actual Result

Clicking Twitter sign-in opens a white page with "The website encountered an unexpected error. Please try again later." The user is not signed in. Registration has the same issue.

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
