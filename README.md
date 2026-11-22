# The Third Caption

_not 2d_

An independent evolving exhibition about art, AI, making, credit, and what a label cannot settle.

## Explore

- [Open the landing page source](public/index.html)
- [Visit the Study Wall source](public/gallery/index.html): twelve numbered original SVG studies, available to open or save individually.
- [Read the technical release receipt](RELEASE-RECEIPT.md)

## Preview status

The pages currently declare `noindex,nofollow`. The public source is present in this repository; a successful Cloudflare build, live endpoint response, device checks, and custom-domain DNS/HTTPS are not verified in the release receipt. A public source commit does not confirm that the preview is live.

The site is served from static files in `public/`; `wrangler.toml` points Cloudflare Workers Static Assets at that directory.
