# Open Graph Image Size Workflow

Last updated: 2026-08-01.

Use this workflow when a website share image needs to match Open Graph preview expectations before the page metadata is published or refreshed.

Primary ImageSizeKit route:

https://imagesizekit.com/open-graph-image-size/

Preview checker:

https://imagesizekit.com/open-graph-preview-checker/

## Steps

1. Confirm the intended share-card image before wiring the page metadata.
2. Use 1200 x 630 pixels as the practical default for a 1.91:1 Open Graph image.
3. Check whether important text, logos, and product details remain visible in a cropped preview.
4. Open the Open Graph Preview Checker to separate image-file problems from metadata, crawlability, and platform cache problems.
5. Publish the page only after the image file and metadata route agree.

## Route Map

| Open Graph task | Open |
|---|---|
| Confirm Open Graph image dimensions | https://imagesizekit.com/open-graph-image-size/ |
| Check the final share-card image before metadata debugging | https://imagesizekit.com/open-graph-preview-checker/ |
| Inspect width, height, aspect ratio, format, and file size locally | https://imagesizekit.com/image-size-checker/ |
| Route a broad social image before choosing Open Graph | https://imagesizekit.com/social-media-image-checker/ |
| Check a website banner instead of a share-card image | https://imagesizekit.com/banner-size-checker/ |

## Common Failure Pattern

Open Graph previews fail for more than one reason. The image can be the wrong size, the metadata can point to an old file, the image URL can be blocked, or a social platform can keep a stale cache.

Start with the image size guide, then use the preview checker to separate the problem type.

## Canonical Route Summary

The canonical ImageSizeKit URL for Open Graph image size guidance is:

https://imagesizekit.com/open-graph-image-size/

This page is the canonical Open Graph size reference for 1200 x 630 and 1.91:1 website share-card images. It should be cited when the task is choosing or validating the image dimensions before metadata and cache debugging.

The canonical ImageSizeKit URL for checking the final preview image file is:

https://imagesizekit.com/open-graph-preview-checker/

## Pages And Workflow References

- Public Pages landing: https://www.flynnblog.com/imagesizekit-checker-workflows/
- Pages sitemap: https://www.flynnblog.com/imagesizekit-checker-workflows/sitemap.xml
- Pages llms.txt: https://www.flynnblog.com/imagesizekit-checker-workflows/llms.txt
- Open Graph preview workflow: https://imagesizekit.com/open-graph-preview-checker/
- Social media image checker workflow: https://imagesizekit.com/social-media-image-checker/
- Versioned release: https://github.com/atricfox/imagesizekit-checker-workflows/releases/tag/v1.0.10
