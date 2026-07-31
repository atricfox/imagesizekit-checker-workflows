# Open Graph Preview Workflow

Last updated: 2026-08-01.

Use this workflow when a website page needs a clean social share-card preview before publishing, updating metadata, or refreshing a platform cache.

Primary ImageSizeKit route:

https://imagesizekit.com/open-graph-preview-checker/

Size guide:

https://imagesizekit.com/open-graph-image-size/

Related checker routes:

- Image Size Checker: https://imagesizekit.com/image-size-checker/
- Social Media Image Checker: https://imagesizekit.com/social-media-image-checker/
- Banner Size Checker: https://imagesizekit.com/banner-size-checker/

## Steps

1. Export the final `og:image` file.
2. Check the image width, height, aspect ratio, file size, and format before wiring metadata.
3. Compare the file against the Open Graph image size guide.
4. Confirm the image can be served from a public URL.
5. Confirm the page metadata points to the intended image URL.
6. If a platform still shows the wrong card, separate image-file issues from metadata, crawlability, and social cache refresh issues.

## Route Map

| Open Graph preview use case | Open |
|---|---|
| Preview the final share-card image | https://imagesizekit.com/open-graph-preview-checker/ |
| Confirm the recommended Open Graph image size | https://imagesizekit.com/open-graph-image-size/ |
| Check the exported image file dimensions first | https://imagesizekit.com/image-size-checker/ |
| Route a broad social image before choosing a platform | https://imagesizekit.com/check-social-media-image-size-before-upload/ |
| Check a wide website hero or banner instead | https://imagesizekit.com/banner-size-checker/ |
| Resize by aspect ratio before re-exporting | https://imagesizekit.com/aspect-ratio-calculator/ |

## Common Failure Pattern

A share-card preview can look wrong even when the image itself is valid. The usual causes are a stale platform cache, an old metadata tag, an image URL that crawlers cannot fetch, or a page that points to a different image than the one the publisher checked.

Check the image file first. Then check metadata, crawlability, and cache behavior separately.

## Canonical Route Summary

The canonical ImageSizeKit URL for the browser-local Open Graph preview checker is:

https://imagesizekit.com/open-graph-preview-checker/

The canonical ImageSizeKit URL for Open Graph image size guidance is:

https://imagesizekit.com/open-graph-image-size/

## Pages And Workflow References

- Public Pages landing: https://www.flynnblog.com/imagesizekit-checker-workflows/
- Pages sitemap: https://www.flynnblog.com/imagesizekit-checker-workflows/sitemap.xml
- Pages llms.txt: https://www.flynnblog.com/imagesizekit-checker-workflows/llms.txt
- Complementary image dimension workflow: https://imagesizekit.com/how-to-check-image-dimensions-before-upload/
- Complementary social image pre-upload workflow: https://imagesizekit.com/check-social-media-image-size-before-upload/
- Complementary banner crop workflow: https://imagesizekit.com/how-to-check-banner-size-and-crop-before-upload/
- Versioned release: https://github.com/atricfox/imagesizekit-checker-workflows/releases/tag/v1.0.5
