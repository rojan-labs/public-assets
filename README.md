# public-assets

Public media host for Rojan's content system (`general-social-media`). Buffer and Metricool
require publicly reachable URLs for images/videos — this repo exists so local files can be
committed and served via `raw.githubusercontent.com` instead of needing a separate CDN.

## Layout
- `images/` — image assets (png, jpg, webp)
- `videos/` — video assets (mp4, mov)

## Usage
1. Drop the file into `images/` or `videos/`, named `YYYY-MM-DD-slug.ext`.
2. Commit and push to `main`.
3. Use the raw URL: `https://raw.githubusercontent.com/rojan-labs/public-assets/main/<path>`

Videos over ~50MB should go through Git LFS or an external host instead — GitHub raw URLs are not
meant for large media.
