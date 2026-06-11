# Open Graph Image Dimension Checker

> Check a share image against Open Graph and Twitter card rules.

**Live demo:** https://0xelitesystem.github.io/open-graph-image-dimension-checker/

Single HTML file. Runs in the browser with no build step, no server, no tracking, and no data leaving the page.

## What it does

- Takes a width and height, or reads them from an image you drop in, with no upload
- Reports aspect ratio and megapixels alongside the raw size
- Checks Open Graph minimum and recommended sizes and the 1.91 to 1 ratio
- Checks the Twitter large-image 2 to 1 ratio and size bounds, with pass or check per rule

## What it is not

- Not a file-size or format validator. It works from pixel dimensions
- Not an uploader. Dropped images are read locally and never sent anywhere

## Use it

Open the hosted page: https://0xelitesystem.github.io/open-graph-image-dimension-checker/

Or download `index.html` and open it in any browser. It works offline.

## Privacy

Everything runs client-side. No analytics, no cookies, no network calls, no local storage.

## Related

- [open-graph-preview-tester](https://github.com/0xelitesystem/open-graph-preview-tester)
- [meta-og-tag-generator](https://github.com/0xelitesystem/meta-og-tag-generator)
- [image-seo-and-alt-text-reference](https://github.com/0xelitesystem/image-seo-and-alt-text-reference)

## License

MIT, copyright 0xelitesystem 2026.
