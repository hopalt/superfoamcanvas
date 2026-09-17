# Super Foam Canvas homepage

Static multilingual website for `https://sfc.hopalt.com`.

## Pages

- English home: `/`
- Korean home: `/ko/`
- Japanese home: `/ja/`
- English privacy policy: `/privacy/`
- Korean privacy policy: `/ko/privacy/`
- Japanese privacy policy: `/ja/privacy/`

The files are ready to be used as the root of
[`hopalt/superfoamcanvas`](https://github.com/hopalt/superfoamcanvas).

## GitHub Pages deployment

1. Copy the contents of this folder to the repository root.
2. In GitHub, open **Settings → Pages** and publish from the chosen branch root.
3. Set the custom domain to `sfc.hopalt.com` and enable **Enforce HTTPS** after the certificate is ready.
4. At the DNS provider for `hopalt.com`, create a `CNAME` record:
   - Host/name: `sfc`
   - Target/value: `hopalt.github.io`
5. Verify `https://sfc.hopalt.com`, all language links, images, and privacy pages.

GitHub recommends verifying the custom domain in the account settings before
attaching it to a Pages site. DNS and Pages settings are external deployment
steps and are not performed by these files.

## Google Play values

- Privacy policy URL: `https://sfc.hopalt.com/privacy/`
- Website: `https://sfc.hopalt.com/`
- Support email: `hopalt@gmail.com`

## Advertising disclosure

The multilingual home and privacy pages disclose the planned use of Kidoz
child-appropriate contextual advertising. They describe Kidoz's technical data
processing and link to Kidoz's current Website and SDK Privacy Policy. Review
the disclosure again whenever the SDK configuration or Kidoz policy changes.

## Icons

- Store-ready 512 × 512 PNG: `assets/icon-512.png`
- Browser favicon: `assets/favicon-32.png`
- Apple touch icon: `assets/apple-touch-icon.png`
- Full-resolution source used on the page: `assets/app-icon.png` (1024 × 1024)

No build step or external JavaScript dependency is required. The website uses
lossless WebP files generated directly from the original 1080-pixel-wide
emulator captures; it does not reuse the framed Google Play marketing images.
