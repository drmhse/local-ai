# Local AI Field Guide

A self-contained HTML slide deck about running open models locally: model formats, quantization, runtimes, hardware, chat templates, RAG, agents, and a practical first stack.

## Open locally

Open `index.html` directly in a browser:

```sh
open index.html
```

No build step or dev server is required.

## Files

- `index.html` - the complete slide deck, styles, metadata, and navigation script.
- `bg.svg` - responsive background artwork used behind non-cover slides.
- `cover.png` - original full-resolution cover artwork.
- `assets/cover-*.jpg` - compressed responsive cover and social-card images.
- `logo.png` - source logo used for favicon and app icons.
- `assets/icons/` - favicon, Apple touch icon, and web app icons generated from `logo.png`.
- `cute_puppy.svg` - source puppy artwork retained for reference.

## Social previews

The deck includes Open Graph, Twitter card, and JSON-LD metadata. The social preview image is:

```text
assets/cover-og.jpg
```

Before publishing to a custom domain, update the root-relative metadata URLs in `index.html` to absolute production URLs, especially:

- `link[rel="canonical"]`
- `og:url`
- `og:image`
- `og:image:secure_url`
- `twitter:image`
- JSON-LD `image`

## Navigation

- Use the top selector to jump between slides.
- Use keyboard arrows, space, Page Up/Down, Home, and End.
- On desktop/tablet, previous and next controls sit on the left and right edges.
- On mobile, previous and next controls sit together at the bottom center.
