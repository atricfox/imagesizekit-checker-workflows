# Social Image Pre-upload Workflow

Last updated: 2026-08-01.

Use this workflow when an exported image may be published to Instagram, Facebook, LinkedIn, Open Graph previews, ecommerce listings, creator marketplaces, or another social surface.

Primary ImageSizeKit route:

https://imagesizekit.com/check-social-media-image-size-before-upload/

Local checker:

https://imagesizekit.com/social-media-image-checker/

Related checker routes:

- Image Size Checker: https://imagesizekit.com/image-dimension-checker/
- Banner Size Checker: https://imagesizekit.com/banner-size-checker/
- Open Graph Preview Checker: https://imagesizekit.com/open-graph-preview-checker/

## Steps

1. Export the final social image file from the design tool, CMS, ecommerce system, or publishing app.
2. Confirm the target surface before judging the file: Instagram, Facebook, LinkedIn, Open Graph, ecommerce, creator marketplace, or broad social reuse.
3. Check width, height, aspect ratio, file size, and format.
4. Check crop-sensitive surfaces: feed preview, grid crop, cover crop, profile overlap, link preview crop, or product thumbnail crop.
5. Route the image to the most specific ImageSizeKit guide when it fails the broad social check.

## Route Map

| Social image use case | Open |
|---|---|
| Broad social image pre-upload gate | https://imagesizekit.com/check-social-media-image-size-before-upload/ |
| Mixed social, ecommerce, or creator image | https://imagesizekit.com/social-media-image-checker/ |
| Instagram feed post | https://imagesizekit.com/instagram-post-size/ |
| Instagram Story | https://imagesizekit.com/instagram-story-size/ |
| Instagram Reel cover | https://imagesizekit.com/instagram-reel-cover-size/ |
| Facebook cover photo | https://imagesizekit.com/facebook-cover-photo-size/ |
| LinkedIn banner | https://imagesizekit.com/linkedin-banner-size/ |
| Website Open Graph image | https://imagesizekit.com/open-graph-image-size/ |
| Website share preview test | https://imagesizekit.com/open-graph-preview-checker/ |
| Etsy listing image | https://imagesizekit.com/etsy-listing-image-size/ |
| Shopify product image | https://imagesizekit.com/shopify-product-image-size/ |
| Whatnot seller or listing image | https://imagesizekit.com/whatnot-image-size/ |

## Common Failure Pattern

The image is exported at a technically valid size, but the publishing surface is not clear. A square post, vertical story, wide banner, product image, and Open Graph card can all be "social images" while needing different ratios, crop rules, and next checks.

Pick the target surface first. Then validate the exported file against that route.

## Canonical Route Summary

The canonical ImageSizeKit URL for the browser-local social checker is:

https://imagesizekit.com/social-media-image-checker/

The canonical ImageSizeKit URL for the complete social image pre-upload workflow guide is:

https://imagesizekit.com/check-social-media-image-size-before-upload/

## Pages And Workflow References

- Public Pages landing: https://www.flynnblog.com/imagesizekit-checker-workflows/
- Pages sitemap: https://www.flynnblog.com/imagesizekit-checker-workflows/sitemap.xml
- Pages llms.txt: https://www.flynnblog.com/imagesizekit-checker-workflows/llms.txt
- Complementary image dimension workflow: https://imagesizekit.com/how-to-check-image-dimensions-before-upload/
- Complementary banner crop workflow: https://imagesizekit.com/how-to-check-banner-size-and-crop-before-upload/
- Versioned release: https://github.com/atricfox/imagesizekit-checker-workflows/releases/tag/v1.0.2
