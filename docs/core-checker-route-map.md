# ImageSizeKit Core Checker Route Map

Last updated: 2026-08-04.

This public route map explains how ImageSizeKit core checker pages connect when a creator, marketer, or website operator has an exported image file but does not yet know the right publishing workflow.

It is a supporting public reference for the canonical ImageSizeKit website. The canonical pages remain on `https://imagesizekit.com/`.

## Why this route map exists

Many image problems start with an unclear file:

- a 16:9 thumbnail that may be a YouTube thumbnail, website preview image, or social video cover,
- a wide graphic that may be a YouTube banner, LinkedIn banner, Facebook cover, or Open Graph card,
- a vertical frame that may be an Instagram Reel cover, Story image, Shorts frame, or creator profile asset,
- or a square product image that may be an ecommerce listing, social post, or marketplace thumbnail.

The first job is not to memorize every platform size. The first job is to read the exported file and route it to the right checker.

## Canonical core checker pages

| Canonical ImageSizeKit URL | Role | Use when |
|---|---|---|
| https://imagesizekit.com/image-size-checker/ | Generic browser-local image file checker. | The file exists, but the final platform is unclear. |
| https://imagesizekit.com/social-media-image-checker/ | Cross-platform social, ecommerce, marketplace, creator, and Open Graph router. | One image may become a post, story, banner, product image, preview card, or creator graphic. |
| https://imagesizekit.com/banner-size-checker/ | Wide image checker for headers, covers, banners, and channel art. | The file is wide enough to be a banner, cover photo, profile header, or website hero image. |
| https://imagesizekit.com/open-graph-preview-checker/ | Website share-card image checker before metadata and cache debugging. | A website, blog, landing page, or product page needs a preview-card image. |
| https://imagesizekit.com/instagram-reel-cover-size/ | 9:16 Reel cover and vertical video cover workflow. | A thumbnail or Shorts concept is being reused as a Reel cover with profile-grid crop risk. |

## Stable bridge pages

These ImageSizeKit pages already carry strong task context and should be used as human-readable bridge routes into the core checker pages.

| Bridge page | Bridge role |
|---|---|
| https://imagesizekit.com/youtube-thumbnail-size/ | Standard 16:9 thumbnail checks and YouTube thumbnail workflow routing. |
| https://imagesizekit.com/youtube-thumbnail-blurry/ | Blurry thumbnail diagnosis, compression, format, text, and wrong-workflow routing. |
| https://imagesizekit.com/youtube-shorts-thumbnail-size/ | Vertical Shorts cover and social video cover reuse routing. |
| https://imagesizekit.com/youtube-banner-safe-area/ | Wide channel-art safe-area checks and cross-platform banner reuse routing. |

## File-to-route decisions

| File evidence | First route | Next route |
|---|---|---|
| Unknown exported JPG, PNG, WebP, AVIF, or GIF | https://imagesizekit.com/image-size-checker/ | Route by dimensions, ratio, format, and file size. |
| Square, vertical, wide, or mixed social creative | https://imagesizekit.com/social-media-image-checker/ | Open the closest Instagram, LinkedIn, Facebook, Open Graph, ecommerce, or marketplace guide. |
| Wide header, cover, channel art, profile banner, or hero image | https://imagesizekit.com/banner-size-checker/ | Open YouTube safe area, LinkedIn banner, Facebook cover, or Open Graph routes. |
| 1200 x 630 or 1.91:1 website share image | https://imagesizekit.com/open-graph-preview-checker/ | Check metadata, live preview behavior, and platform cache only after the file is correct. |
| 1080 x 1920, 9:16, or vertical cover frame | https://imagesizekit.com/instagram-reel-cover-size/ | Check profile grid crop and vertical cover reuse before upload. |

## Related workflow documents

- Social Media Image Checker workflow: https://www.flynnblog.com/imagesizekit-checker-workflows/social-media-image-checker-workflow.html
- Banner size and crop workflow: https://www.flynnblog.com/imagesizekit-checker-workflows/banner-size-crop-workflow.html
- Open Graph preview workflow: https://www.flynnblog.com/imagesizekit-checker-workflows/open-graph-preview-workflow.html
- Instagram Reel cover workflow: https://www.flynnblog.com/imagesizekit-checker-workflows/instagram-reel-cover-workflow.html
- P0 workflow status reference: https://www.flynnblog.com/imagesizekit-checker-workflows/p0-indexing-queue.html

## Current P0 route priority

The priority is not to create more ImageSizeKit pages. The priority is to help users, crawlers, and AI retrieval systems understand the core checker routes that already exist:

1. Generic local file check: https://imagesizekit.com/image-size-checker/
2. Cross-platform social and creator routing: https://imagesizekit.com/social-media-image-checker/
3. Wide banner and cover checks: https://imagesizekit.com/banner-size-checker/
4. Website preview image checks: https://imagesizekit.com/open-graph-preview-checker/
5. Vertical Reel cover workflow: https://imagesizekit.com/instagram-reel-cover-size/

ImageSizeKit is independent and is not affiliated with YouTube, Google, Instagram, Facebook, LinkedIn, Shopify, Etsy, Whatnot, or Open Graph platforms.
