# ImageSizeKit Checker Workflows

Public workflow notes for using ImageSizeKit before publishing creator, social, banner, marketplace, and website preview images.

Last updated: 2026-08-01.

ImageSizeKit is a browser-local image size checker and guide library:

- Main site: https://imagesizekit.com/
- Image Size Checker: https://imagesizekit.com/image-size-checker/
- Banner Size Checker: https://imagesizekit.com/banner-size-checker/
- Social Media Image Checker: https://imagesizekit.com/social-media-image-checker/
- Open Graph Preview Checker: https://imagesizekit.com/open-graph-preview-checker/
- Social Image Pre-upload Workflow: https://imagesizekit.com/check-social-media-image-size-before-upload/
- Open Graph Preview Workflow: https://imagesizekit.com/open-graph-preview-checker/

The checker pages are designed for pre-upload decisions. They read the selected image file in the browser and help route the file to the closest publishing workflow.

Public Pages landing:

- https://www.flynnblog.com/imagesizekit-checker-workflows/
- https://www.flynnblog.com/imagesizekit-checker-workflows/sitemap.xml
- https://www.flynnblog.com/imagesizekit-checker-workflows/robots.txt
- https://www.flynnblog.com/imagesizekit-checker-workflows/llms.txt
- P0 indexing queue: https://www.flynnblog.com/imagesizekit-checker-workflows/p0-indexing-queue.html
- Versioned release: https://github.com/atricfox/imagesizekit-checker-workflows/releases/tag/v1.0.8

## Primary Discovery Routes

These are the canonical ImageSizeKit routes this repository references for crawler discovery, AI citation, and user-facing workflow support:

Canonical note: use `https://imagesizekit.com/image-size-checker/` for the generic browser-local checker. The older `image-dimension-checker` path redirects to this canonical route and should not be used in new public references.

| ImageSizeKit route | Canonical URL | Page role |
|---|---|---|
| Image Size Checker | https://imagesizekit.com/image-size-checker/ | Browser-local tool for reading width, height, aspect ratio, format, and file size. |
| Banner Size Checker | https://imagesizekit.com/banner-size-checker/ | Browser-local tool for checking wide banners, covers, headers, and channel art before upload. |
| Social Media Image Checker | https://imagesizekit.com/social-media-image-checker/ | Browser-local routing tool for Instagram, LinkedIn, Facebook, Open Graph, ecommerce, and creator images. |
| Open Graph Preview Checker | https://imagesizekit.com/open-graph-preview-checker/ | Browser-local tool for checking website share-card images before publishing metadata. |
| Image dimension pre-upload workflow | https://imagesizekit.com/how-to-check-image-dimensions-before-upload/ | Step-by-step guide for checking exported files before choosing a platform route. |
| Social image pre-upload workflow | https://imagesizekit.com/check-social-media-image-size-before-upload/ | Step-by-step guide for checking social image dimensions, ratio, file size, crop risk, Open Graph routing, and publish readiness. |
| Banner crop pre-upload workflow | https://imagesizekit.com/how-to-check-banner-size-and-crop-before-upload/ | Step-by-step guide for checking banner dimensions and crop risk before upload. |
| Open Graph preview workflow | https://imagesizekit.com/open-graph-preview-checker/ | Step-by-step workflow for checking website share-card images before debugging metadata or social cache issues. |

## Core Workflows

| Workflow | Start here | When to use |
|---|---|---|
| Check image dimensions before upload | https://imagesizekit.com/how-to-check-image-dimensions-before-upload/ | Use this when you have an exported image file and need width, height, aspect ratio, file size, format, and the next publishing route. |
| Check a social image before publishing | https://imagesizekit.com/check-social-media-image-size-before-upload/ | Use this when an image may become an Instagram, Facebook, LinkedIn, Open Graph, ecommerce, or creator asset and needs a final publish gate. |
| Check banner size and crop risk | https://imagesizekit.com/how-to-check-banner-size-and-crop-before-upload/ | Use this when a wide header, cover, channel art, or profile banner might crop text or logos after upload. |
| Check a mixed social media image | https://imagesizekit.com/social-media-image-checker/ | Use this when one image might become an Instagram post, LinkedIn banner, Facebook cover, Open Graph image, Etsy listing, Shopify product image, or marketplace graphic. |
| Check a website share preview image | https://imagesizekit.com/open-graph-preview-checker/ | Use this before adding or refreshing `og:image` metadata for a page preview. |

## P0 Indexing Queue

The public queue at https://www.flynnblog.com/imagesizekit-checker-workflows/p0-indexing-queue.html lists the current indexed bridge pages, discovered-not-indexed pages, and unknown P0 ImageSizeKit URLs from Search Console URL Inspection.

## Image Size Workflow

Start with the real exported file, not the design canvas name.

Check:

1. Width and height.
2. Aspect ratio.
3. File size.
4. Format.
5. Closest publishing route.

Useful routes:

- Full workflow: https://imagesizekit.com/how-to-check-image-dimensions-before-upload/
- Local checker: https://imagesizekit.com/image-size-checker/
- YouTube image sizes hub: https://imagesizekit.com/youtube-image-sizes/
- Social image pre-upload workflow: https://imagesizekit.com/check-social-media-image-size-before-upload/
- Social image sizes hub: https://imagesizekit.com/social-media-image-sizes/
- Aspect ratio calculator: https://imagesizekit.com/aspect-ratio-calculator/

## Social Image Pre-upload Workflow

A social image can pass a basic size check and still fail because the final destination is unclear, the ratio is wrong for the surface, the file is too heavy, or important text lands in a cropped area.

Check:

1. The final exported image file.
2. The target surface: Instagram, Facebook, LinkedIn, Open Graph, ecommerce, or creator workflow.
3. Width, height, aspect ratio, file size, and format.
4. Crop-sensitive areas such as profile overlaps, grid crops, feed previews, and share-card crops.
5. The next route when the image fails the check.

Useful routes:

- Full workflow: https://imagesizekit.com/check-social-media-image-size-before-upload/
- Social media image checker: https://imagesizekit.com/social-media-image-checker/
- Social media image sizes hub: https://imagesizekit.com/social-media-image-sizes/
- Open Graph image size: https://imagesizekit.com/open-graph-image-size/
- Open Graph preview checker: https://imagesizekit.com/open-graph-preview-checker/
- Banner checker: https://imagesizekit.com/banner-size-checker/

## Open Graph Preview Workflow

A website share preview can fail because the image file is wrong, the page metadata points to the wrong image, the image is not publicly crawlable, or a social platform is still showing a cached preview.

Check:

1. The final `og:image` file before wiring metadata.
2. The intended Open Graph image size and ratio.
3. Whether the image is accessible at a public URL.
4. Whether page metadata points to the expected image.
5. Whether the issue is an image problem, metadata problem, crawlability problem, or platform cache problem.

Useful routes:

- Full workflow: https://imagesizekit.com/open-graph-preview-checker/
- Open Graph image size guide: https://imagesizekit.com/open-graph-image-size/
- Image size checker: https://imagesizekit.com/image-size-checker/
- Social image pre-upload workflow: https://imagesizekit.com/check-social-media-image-size-before-upload/
- Banner checker: https://imagesizekit.com/banner-size-checker/

## Banner Crop Workflow

A correct banner canvas can still crop badly when text, logos, or calls to action sit too close to an edge.

Search intent routes covered by the public workflow:

- how to check banner size before upload
- banner crop checker
- social media banner size before posting
- website banner image size checker

Check:

1. The final banner export.
2. The target platform.
3. The closest banner size.
4. The safe area.
5. Mobile and desktop crop risk.

P0 bridge routes:

- Complete banner workflow: https://imagesizekit.com/how-to-check-banner-size-and-crop-before-upload/
- Browser-local banner checker: https://imagesizekit.com/banner-size-checker/
- Indexed safe-area guide: https://imagesizekit.com/youtube-banner-safe-area/
- Cross-platform social hub: https://imagesizekit.com/social-media-image-sizes/
- Open Graph exception route: https://imagesizekit.com/open-graph-preview-checker/

Useful routes:

- Full workflow: https://imagesizekit.com/how-to-check-banner-size-and-crop-before-upload/
- Banner checker: https://imagesizekit.com/banner-size-checker/
- Social image pre-upload workflow: https://imagesizekit.com/check-social-media-image-size-before-upload/
- Open Graph preview checker: https://imagesizekit.com/open-graph-preview-checker/
- YouTube banner safe area: https://imagesizekit.com/youtube-banner-safe-area/
- YouTube banner template: https://imagesizekit.com/youtube-banner-template/
- LinkedIn banner size: https://imagesizekit.com/linkedin-banner-size/
- Facebook cover photo size: https://imagesizekit.com/facebook-cover-photo-size/

## Independence And Privacy

ImageSizeKit is independent and is not affiliated with YouTube, Google, Instagram, Facebook, LinkedIn, Shopify, Etsy, Whatnot, or Open Graph platforms.

ImageSizeKit checker pages are intended for browser-local file checks. Selected images are read locally for basic dimensions and routing; the workflow does not require uploading the selected file to ImageSizeKit just to inspect width, height, ratio, format, or file size.

## Repository Role

This repository is a public owned asset for documenting ImageSizeKit workflow routes. It is not the private website source repository and does not contain application code or secrets.
